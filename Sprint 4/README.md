
# 📃 DoR(Definition of Ready):

## 🗒️ Backlog Sprint 4
| Rank | Prioridade | User Story | Estimativa |Sprint | Requisito do Parceiro |
|--- |--- |--- |--- |--- |--- |
| 1 | Alta | Como gerente, quero que use uma inteligência artificial que utilize a câmera na entrada da redzones para fazer a contagem de pessoas que saíram e entraram dela, para não precisar fazer uma contagem manual.  | 80 | 1 | RF8 |
| 22 | Alta | Como gerente, quero um manual do usuário detalhado e fácil de entender, que forneça orientações passo a passo sobre como utilizar todas as funcionalidades do sistema, para que eu possa utilizar o sistema de forma eficaz e sem problemas. | 40 | 4 | RNF1 | 
| 23 | Média | Como gerente geral, quero um dashboard que compile e exiba métricas importantes de todos os departamentos, incluindo capacidade atual, número de alertas ativos e média de permanência das pessoas, para facilitar a análise e tomada de decisões estratégicas em relação à segurança e gestão de recursos. | 20 | 4 | RF2 |
| 24 | Média |Como gerente área, quero um dashboard que compile e exiba métricas importantes de todos as redzones que são do meu departamento, incluindo capacidade atual, número de alertas ativos e média de permanência das pessoas, para facilitar a análise e tomada de decisões estratégicas. | 20 | 4 | RF2 |
| 25 | Baixa | Como gerente geral, quero um guia de instalação detalhado e claro, para facilitar a implantação do sistema. | 20 | 4 | RNF3 |


Obs: User Story Rank 1 de volta para aplicação de melhorias apontadas do sprint review.

RF2 - Desenvolver um Dashboard de indicadores por períodos.

RF8 - Utilizar a câmera da entrada para contabilizar as pessoas que entraram e saíram da Redzone. 

RNF1 - Manual do Usuário.

RNF3 - Guia de instalação; Front - Back - IA.


## 📋  User Stories, Critérios de Aceitação e Tasks

### **US #1:** Como gerente, quero que use uma inteligência artificial que utilize a câmera na entrada da redzones para fazer a contagem de pessoas que saíram e entraram dela, para não precisar fazer uma contagem manual. 

### **Critérios de aceitação:**

### **Cenário 1 – Fluxo Principal de Contagem de Pessoas** 

<small>
  
**DADO QUE :**<br>
- O sistema de contagem automática de pessoas está configurado e funcionando corretamente<br>
- A câmera na entrada da redzone está conectada e operacional<br>

**QUANDO :**<br>
- A inteligência artificial utilizar a câmera para detectar e contar as pessoas que entram e saem <br>

**ENTÃO :**<br>
- A contagem será registrada pelo sistema e atualizada em tempo real<br>
- O Gerente poderá monitorar a contagem de pessoas na redzone por meio de uma interface dedicada

</small>

### **Cenário 2 – Contagem Simultânea de Entradas e Saídas**

<small>

**DADO QUE :**<br>
- O sistema de contagem automática de pessoas está configurado e funcionando corretamente<br>
- A câmera na entrada da redzone está conectada e operacional<br>

**QUANDO :**<br>
- A inteligência artificial detectar múltiplas pessoas entrando e saindo simultaneamente pela entrada da redzone<br>

**ENTÃO :**<br>
- sistema será capaz de registrar a entrada e saída de cada pessoa de forma precisa e em tempo real<br>
- O Gerente poderá visualizar um relatório atualizado do número total de entradas e saídas pela interface dedicada<br>

</small>


### **Cenário 3 – Situação de Quase Entrada na Redzone**

<small>

**DADO QUE :**<br>
- O sistema de contagem automática de pessoas está configurado e funcionando corretamente<br>
- A câmera na entrada da redzone está conectada e operacional<br>

**QUANDO :**<br>
- Uma pessoa passar perto da entrada da redzone sem realmente entrar nela<br>

**ENTÃO :**<br>
- O sistema não registrará essa pessoa como uma entrada na redzone<br>
- O contador de entradas permanecerá inalterado, garantindo a precisão da contagem<br>

</small>

### Tasks:

<small>

- Criar vídeos para testar contagem simultânea de entradas e saídas na redzone (Caso necessário buscar formas de resolver essa situação)
- Criar vídeos para testar a situação de quase entrada na redzones. (Caso necessário buscar formas de resolver essa situação)
- Medir acurácia média por cenário apresentado e fazer um gráfico com elas para facilitar a visualização.

</small>

### **US #22:** Como gerente, quero um manual do usuário detalhado e fácil de entender, que forneça orientações passo a passo sobre como utilizar todas as funcionalidades do sistema, para que eu possa utilizar o sistema de forma eficaz e sem problemas.

### **Critérios de aceitação:**


### **Cenário – Disponibilidade, Clareza e Conteúdo do Manual do Usuário** 

<small>

**DADO QUE :**<br>
- Um manual do usuário foi criado e está disponível para os usuários do GitHub

**QUANDO :**<br>
- Quando o usuário procurar pelo manual.

**ENTÃO :**<br>
- O manual será disponibilizado em formato PDF contendo: 
  - Capa
  - Objetivo do manual com uma visão do projeto
  - Níveis de acesso do sistema
  - Hierarquia das redzones
  - Funcionalidades principais do sistema
  - Explicação das dashboards
- As instruções serão claras e fáceis de entender, sem falar muito técnicas.
- O manual incluirá capturas de tela e exemplos práticos para ilustrar os passos

</small>

### Tasks:

<small>

- Desenvolva um manual do usuário completo em pdf que seja fácil de entender.

</small>

### **US #23:Como gerente geral, quero um dashboard que compile e exiba métricas importantes de todos os departamentos, incluindo capacidade atual, número de alertas ativos e média de permanência das pessoas, para facilitar a análise e tomada de decisões estratégicas em relação à segurança e gestão de recursos.** 

### **Critérios de aceitação:**


### **Cenário 1 – Fluxo Principal: Exibição e Interatividade do Dashboard de Métricas** 

<small>

**DADO QUE :**<br>
- O sistema possui redzones cadastradas e associadas ao departamento
- Existem dados registrados nas redzones para as métricas a serem exibidas no dashboard

**QUANDO :**<br>
- O usuário acessa o sistema e navega até a página do dashboard de métricas

**ENTÃO :**<br>
- O sistema exibe as métricas gerais, incluindo:
  - Capacidade atual de todas as redzones do departamento
  - Número total de alertas ativos em todas as redzones do departamento
  - Média de permanência das pessoas em todas as redzones do departamento
- O usuário poderá interagir com os dados, incluindo:
  - Ampliar ou reduzir o período de análise
  - Filtrar métricas específicas
  - Visualizar detalhes adicionais
- O dashboard será atualizado automaticamente conforme os dados são recebidos do sistema

</small>

### **Cenário 2 – Ausência de Departamentos Cadastrados** 

<small>

**DADO QUE :**<br>
- O sistema não possui nenhum departamento cadastrado

**QUANDO :**<br>
- O usuário acessa o sistema e navega até a página do dashboard de métricas

**ENTÃO :**<br>
- O sistema exibe uma mensagem informando que não existem departamentos no sistema

</small>


### **Cenário 3 – Ausência de Redzones Cadastradas** 

<small>

**DADO QUE :**<br>
- Sistema possui departamentos cadastrados, mas não possui nenhuma redzone cadastrada

**QUANDO :**<br>
- O usuário acessa o sistema e navega até a página do dashboard de métricas

**ENTÃO :**<br>
- O sistema exibe uma mensagem informando que não existem redzones no sistema

</small>


### **Cenário 4 – Ausência de Dados no Período Selecionado** 

<small>

**DADO QUE :**<br>
- O sistema possui departamentos e redzones cadastrados, mas não há registros de logs no período selecionado

**QUANDO :**<br>
- O usuário acessa o sistema e navega até a página do dashboard de métricas

**ENTÃO :**<br>
- O sistema mostra uma mensagem indicando que não há registros disponíveis no período selecionado

</small>

### Tasks:

<small>

- Desenvolver a lógica necessária no backend para devolver as métricas (Citadas na user story) na dashboard do departamento
- Produzir a dashboard do departamento no frontend com gráficos atrativos de sua preferência, mas assegurando que todas as métricas sejam utilizadas de maneira significativa. (As métricas estão citadas na user story)
- Criar página de not found

</small>


### **US #24:Como gerente área, quero um dashboard que compile e exiba métricas importantes de todos as redzones que são do meu departamento, incluindo capacidade atual, número de alertas ativos e média de permanência das pessoas, para facilitar a análise e tomada de decisões estratégicas.** 

### **Critérios de aceitação:**

### **Cenário 1 – Fluxo Principal: Exibição e Interatividade do Dashboard de Métricas** 

<small>

**DADO QUE :**<br>
- Existem dados registrados nas redzones para as métricas a serem exibidas no dashboard

**QUANDO :**<br>
- Usuário acessa o sistema e navega até o dashboard de sua redzone 

**ENTÃO :**<br>
- O sistema exibe as métricas gerais das redzones incluindo:
  - Capacidade atual de cada redzone
  - Número total de alertas ativos em todas as redzone
  - Média de permanência das pessoas dessa redzone 
- O usuário pode interagir com os dados, como:
   Ampliar ou reduzir o período de análise
  - Filtrar métricas específicas
  - Visualizar detalhes adicionais por redzone
- O dashboard será atualizado automaticamente conforme os dados são recebidos do sistema

</small>


### **Cenário 2 – Ausência de Dados no Período Selecionado** 

<small>

**DADO QUE :**<br>
- Sistema esteja funcional, mas não há registros de logs no período selecionado

**QUANDO :**<br>
- Usuário acessa o sistema e navega até o dashboard de métricas de sua redzone 

**ENTÃO :**<br>
- O sistema mostra uma mensagem indicando que não há registros disponíveis no período selecionado

</small>

### Tasks:

<small>

- Desenvolver no backend a lógica necessária para poder disponibilizar as métricas das redzones para a criação da dashboard. (Métricas citadas na user story)
- Criar no frontend a dashboard da redzone com base nos dados nas métricas disponibilizado na user story. (Assim como o de departamento possui a liberdade para escolher os gráficos utilizados de sua preferência)
- Inserir tooltip nos títulos dos cards do dashboard

</small>

### **US #25:Como gerente geral, quero um guia de instalação detalhado e claro, para facilitar a implantação do sistema.** 

### **Critérios de aceitação:**

### **Cenário – Guia de Instalação para Frontend, Backend e IA** 

<small>

**DADO QUE :**<br>
- Tanto o Frontend, quanto o Backend e a IA possuem no seu respectivo Readme.md 
- O guia de instalação inclui pré-requisitos e instruções desde a instalação até a execução do sistema
- As instruções são simples e explicam cada comando de forma clara
- Os usuários podem copiar os comandos diretamente do guia para facilitar a execução

**QUANDO :**<br>
- O gerente geral acessa os repositórios do Frontend, Backend e IA para consultar os guias de instalação

**ENTÃO :**<br>
- Os guias de instalação estarão bem visíveis e organizados nos Readme.md correspondentes
- Todos os pré-requisitos estarão claramente listados para utilização do sistema
- O passo a passo completo permitirá a instalação e execução do sistema sem dificuldades adicionais
- Os comandos serão apresentados de maneira que os usuários possam copiá-los facilmente

</small>

### Tasks:

<small>

- Desenvolva um guia de instalação completo com comandos necessários para a execução e expor os mesmos no readme.

</small>



## 📝  Modelo do Banco de Dados

![alt text](Img/Modelo_logico.png)


## 🎨 Mockups

O layout da aplicação está disponível no Figma:

<a href="https://www.figma.com/file/npSn8yHa7ta2qVyJdPwHPE/API-6%C2%BA?type=design&node-id=0-1&mode=design">
  <img alt="Link do Figma" src="https://img.shields.io/badge/Acessar%20Layout%20-Figma-%2304D361">
</a>

## 💾 Dados
Nessa sprint, focamos em melhorar o desempenho e a fluidez do nosso sistema de inteligência artificial. Para alcançar esse objetivo, decidimos treinar um novo modelo de dados que pudesse aprimorar a precisão da contagem.

Utilizamos o dataset fornecido pelo [RoboFlow](https://universe.roboflow.com/leo-ueno/people-detection-o4rdr/dataset/8), que nos permitiu treinar nosso modelo com uma diversidade de exemplos e situações. O treinamento foi realizado utilizando a biblioteca [YOLOv8](https://github.com/autogyro/yolo-V8), uma das ferramentas mais eficazes para detecção de objetos em tempo real.

Os resultados iniciais foram bastante promissores, com uma precisão de apuração variando entre 74%. Este nível de precisão está bem acima do mínimo necessário para contabilizar corretamente a circulação, que é de 50%.

Para otimizar o desempenho do sistema, implementamos uma estratégia onde a leitura dos dados é feita a cada três frames, contabilizando apenas um. Essa abordagem reduz a carga de processamento sem comprometer significativamente a precisão da contagem,

Além disso, incluímos uma validação no sistema para evitar contagens negativas, garantindo que a contagem seja sempre precisa e confiável. Essa validação é crucial para manter a integridade dos dados e fornecer informações úteis para análise posterior.

## Video da Sprint 4

***Por favor, para o carregamento das gifs espere alguns segundos.***
Sistema de Login e Niveis de Usuarios
!niveis de usuario


# IA e Melhoramentos Resultados:

- Cenário 1 – Fluxo Principal de Contagem de Pessoas
![fluxo_principal_img](https://github.com/4-Fatech/API-6SEM-Docs/assets/88494278/9a767021-6f56-428e-9adb-5a7e8516d84a)
)


![fluxo_principal_video](https://drive.google.com/drive/folders/1tFMV5c7uYjI2JN7TYvv7vFVjLRuIpBhf?usp=drive_link)

- Cenário 2 – Contagem Simultânea de Entradas e Saídas
![contagem_simultanea_img](https://github.com/4-Fatech/API-6SEM-Docs/assets/88494278/0b21ecd9-7a75-45a1-8831-dfa40562701e)
)

![contagem_simultanea_video](https://drive.google.com/drive/folders/1tFMV5c7uYjI2JN7TYvv7vFVjLRuIpBhf?usp=drive_link)

- Cenário 3 – Situação de Quase Entrada na Redzone
![situacao_de_quase_img](https://github.com/4-Fatech/API-6SEM-Docs/assets/88494278/a54e9657-ec5a-4381-b6c5-fbcca1f3755d)
)

![fluxo_principal_video](https://drive.google.com/drive/folders/1tFMV5c7uYjI2JN7TYvv7vFVjLRuIpBhf?usp=drive_link)

 - Resultados em Gráfico: 


- As métricas do treinamento realizado: 
![alt text](Img/results.png)


- Cenários com diferentes distâncias requisito pela Sprint Review: 
![1_5](https://github.com/4-Fatech/API-6SEM-Docs/assets/88494278/0ca8c34d-437f-4ff5-85e1-c27739092656)
)

- Media de Acurácia dos cenários desta Quarta Sprint:
![1_3](https://github.com/4-Fatech/API-6SEM-Docs/assets/88494278/74054659-95bc-4a72-ae83-f0456b535d98)
)
















