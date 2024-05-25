
# 📃 DoR(Definition of Ready):

## 🗒️ Backlog Sprint 3
| Rank | Prioridade | User Story | Estimativa |Sprint | Requisito do Parceiro |
|--- |--- |--- |--- |--- |--- |
| 1 | Alta | Como gerente, quero que use uma inteligência artificial que utilize a câmera na entrada da redzones para fazer a contagem de pessoas que saíram e entraram dela, para não precisar fazer uma contagem manual.  | 80 | 1 | RF8 |
| 19 | Média | Como gerente geral, necessito de uma função de exportação de dados que me permita baixar relatórios de um departamento específico, com informações detalhadas sobre as datas e horários de entrada e saída na redzones durante o período selecionado para realizar análises externas mais detalhadas e precisa | 20 | 3 | RF4 |
| 20 | Média | Como Gerente Geral, quero um login que gerencie o acesso de usuários com diferentes níveis de permissão, incluindo guardas, gerentes de área e outros gerentes gerai, para que cada usuário tenha acesso apenas as partes do sistema relevantes para suas responsabilidades, mantendo assim a segurança e a integridade dos dados da empresa. | 20 | 3 | RF9 |
| 21 | Baixa |Como gerente, quero poder recuperar minha senha através de um processo seguro e confiável, para caso eu a esqueça no futuro. | 10 | 3 | RF9 |

Obs: User Story Rank 1 de volta para aplicação de melhorias apontadas do sprint review.

RF4 - Geração de relatórios para compartilhamento.

RF8 - Utilizar a câmera da entrada para contabilizar as pessoas que entraram e saíram da Redzone.

RF9 - Criar três níveis (Usuário de visualização, Gerente Por 
Departamento e Gerente geral) de acesso para o projeto.


## 📋  User Stories, Critérios de Aceitação e Tasks

### **US #1:** Como gerente, quero que use uma inteligência artificial que utilize a câmera na entrada da redzones para fazer a contagem de pessoas que saíram e entraram dela, para não precisar fazer uma contagem manual. 


### **Critérios de aceitação:**

**Cenário 1 – Fluxo Principal de Contagem de Pessoas**

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

**Cenário 2 – Condições de luz**

<small>

**DADO QUE :** <br>
- O sistema de contagem automática de pessoas está configurado e funcionando corretamente <br>
- A câmera na entrada da redzone está conectada e operacional <br>

**QUANDO :** <br>
- A luminosidade ambiente mudar, seja devido à luz natural durante o dia ou à iluminação artificial à noite<br>

**ENTÃO :** <br>
- O sistema deve ainda ser capas de detectar a circulação de pessoas mesmo com essa alteração <br>
- A contagem de pessoas na redzone continuará a ser registrada e atualizada em tempo real<br>

</small>

**Cenário 3 – Variação de Distâncias:**

<small>

**DADO QUE :** <br>
- O sistema de contagem automática de pessoas está configurado e funcionando corretamente<br>
- A câmera na entrada da redzone está conectada e operacional<br>
- E as pessoas podem estar em distâncias variadas da câmera ao entrarem na redzone, incluindo diferentes locais de instalação da câmera<br>

**QUANDO :** <br>
- Uma pessoa se aproximar da câmera e entrar na redzone, independentemente da proximidade ou distância em relação à câmera<br>

**ENTÃO :**<br>
- O sistema deverá ser capaz de detectar e contar com precisão todas as pessoas quem entraem na redzone<br>
- A contagem total de pessoas na redzone será precisa e atualizada conforme necessário, considerando as diferentes posições de instalação da câmera.<br>

</small>


### **Tasks :**
<small>

- Treinar e implementar otimizações na IA para tornar mais eficiente e leve.
- Encontrar o equilíbrio entre qualidade da imagem e desempenho da IA.
- Definir os melhores critérios para determinar se a pessoa vai ser contabilizada.
- Criar vídeos com a câmera em distancias diferentes para testar a IA e registar o desempenho nessas variações.
- Criar vídeos com Iluminação diferentes para testar a IA e registar as variações.

</small>


### **US #19:** Como gerente geral, necessito de uma função de exportação de dados que me permita baixar relatórios de um departamento específico, com informações detalhadas sobre as datas e horários de entrada e saída na redzones durante o período selecionado para realizar análises externas mais detalhadas e precisa 

### **Critérios de aceitação:**

**Cenário 1 – Acesso ao Departamento e Geração de Relatório**

<small>

**DADO QUE :**<br> 
- Há pelo menos uma redzone e um departamento cadastrados no sistema<br> 
- O usuário deseja gerar um relatório para um departamento específico<br> 

**QUANDO :**<br> 
- O usuário acessa o departamento desejado<br> 
- Seleciona o período desejado para o relatório<br> 


**ENTÃO :**<br>  
- O sistema retorna os logs de todas as redzones associadas àquele departamento e disponibiliza métodos de exportação<br>  
- O usuário escolhe o método de exportação preferido
- O sistema realiza o download do relatório

</small>


**Cenário 2 – Sem Departamentos Cadastrados**

<small>

**DADO QUE :**<br> 
- Não há departamentos cadastrados no sistema<br>

**QUANDO :**<br>  
- O usuário tenta acessar um departamento para gerar um relatório<br> 

**ENTÃO :**<br>   
- O sistema exibe uma mensagem informando que não existem departamentos no sistema

</small>

**Cenário 3 – Sem Registros de Logs**

<small>

**DADO QUE :**<br> 
- Há pelo menos uma redzone e um departamento cadastrados no sistema<br> 

**QUANDO :**<br>  
- O usuário deseja gerar um relatório para um departamento específico<br> 
- Seleciona o período desejado para o relatório<br>  
- E não há registros de logs no período selecionado<br> 

**ENTÃO :**<br> 
- O sistema mostra uma mensagem indicando que não há registros disponíveis<br> 

</small>


### **Tasks :**
<small>

- Desenvolver a lógica necessária para poder estruturar os logs do departamento a serem exportados.
- Adicionar no front a opção para gerar relatório do relatório do departamento.
- Retirar do rodapé do site informações com Fecebook, LinkedIn e Instagram da empresa Altave.
- Adicionar Loading na página de registro do departamento

</small>

#### **US #20:** Como Gerente Geral, quero um login que gerencie o acesso de usuários com diferentes níveis de permissão, incluindo guardas, gerentes de área e outros gerentes gerai, para que cada usuário tenha acesso apenas as partes do sistema relevantes para suas responsabilidades, mantendo assim a segurança e a integridade dos dados da empresa.

#### **Critérios de aceitação:**

**Cenário 1 – Login com Credenciais Corretas**

<small>

**DADO QUE :**<br> 
- O sistema está disponível, operacional e o usuário esteja cadastrado no sistema<br> 

**QUANDO :**<br>  
- O usuário acessa a página de login do sistema<br> 
- Insere as credenciais corretas (e-mail e senha)<br> 

**ENTÃO :**<br> 
- o sistema verifica as credenciais<br> 
- Autêntica o usuário com sucesso<br> 

</small>

**Cenário 2 – Login com Credenciais Incorretas**

<small>

**DADO QUE :**<br>
- O sistema está disponível e operacional<br> 

**QUANDO :**<br>
- O usuário acessa a página de login do sistema<br> 
- Insere um e-mail ou senha incorreto<br> 

**ENTÃO :**<br>
- O sistema verifica as credenciais<br> 
- Exibe uma mensagem de erro indicando que a senha e o email não são correspondentes está incorreto<br> 
- E Solicita que o usuário tente novamente<br> 


</small>

### Tasks:

<small>

- Desenvolver o sistema de login no backend com base os materiais do professor Mineda 
- Fazer os níveis de permissão para que cada usuário tenha acesso apenas as partes do sistema relevantes para suas responsabilidades.
- Implementar no frontend o sistema de login que foi desenvolvido no backend
- Resolver o problema relacionado a reloader que estão ocorrendo no Frontend do Render 
- Mapear os tipos de usuário para termos mais compreensíveis para os usuários finais
- Criar a tela de perfil dos usuários para o usuário pode visualizar os seus dados é alterá-los caso necessário 
- Criar tela para o gerente de área poder visualizar todas as redzones cadastradas no do departamento que ele é responsável 

</small>

#### **US #21:** Como gerente, quero poder recuperar minha senha através de um processo seguro e confiável, para caso eu a esqueça no futuro. 

### **Critérios de aceitação:**

**Cenário 1 – Recuperação de Senha com Sucesso**

<small>

**DADO QUE :**<br>
- O sistema está operacional<br>
- O usuário possui uma conta registrada no sistema<br>

**QUANDO :**<br>
- O usuário acessa a página de recuperação de senha do sistema<br>
- Insere o e-mail associado à sua conta<br>
- Solicita o envio do e-mail de recuperação<br>
- Recebe o e-mail com o código de validação<br>
- Insere o código de validação no campo correspondente<br>
- E o código inserido está correto<br>

**ENTÃO :**<br>
- O sistema valida o código<br>
- Redireciona o usuário para a tela de alteração de senha<br>
- O usuário insere a nova senha duas vezes para confirmação<br>
- O sistema salva a nova senha criptografada<br>

</small>

**Cenário 2 – E-Mail Não Cadastrado**

<small>

**DADO QUE :**<br>
- O sistema está operacional<br>

**QUANDO :**<br>
- O usuário acessa a página de recuperação de senha do sistema<br>
- Insere o e-mail que não foi cadastrado <br>

**ENTÃO :**<br>
- O sistema devolve uma mensagem indicando que não há esse e-mail cadastrado no sistema<br> 

</small>


**Cenário 3 – Código de Validação Incorreto**

<small>


**DADO QUE :**<br>
- O sistema está operacional<br>
- O usuário possui uma conta registrada no sistema<br>

**QUANDO :**<br>
- O usuário acessa a página de recuperação de senha do sistema<br>
- Insere o e-mail associado à sua conta<br>
- Solicita o envio do e-mail de recuperação<br>
- Recebe o e-mail com o código de validação<br>
- Insere um código de validação incorreto no campo correspondente<br>

**ENTÃO :**<br>
- O sistema exibe uma mensagem de erro indicando que o código está incorreto<br>
- O usuário pode tentar novamente<br>

</small>


**Cenário 4 – Tempo de Expiração do Código**

<small>

**DADO QUE :**<br>
- O sistema está operacional<br>
- O usuário possui uma conta registrada no sistema<br>

**QUANDO :**<br>
- O usuário acessa a página de recuperação de senha do sistema<br>
- Insere o e-mail associado à sua conta<br>
- Solicita o envio do e-mail de recuperação<br>
- E-mail com o código de validação é enviado<br>
- O usuário não insere o código dentro do tempo de expiração<br>

**ENTÃO :**<br>
- O sistema redireciona o usuário para a tela de login<br>

</small>



### Tasks:

<small>

- Desenvolver um processo no backend seguro e confiável para que os usuários possam recuperar suas senhas caso as esqueçam.
- Implementar a interface no frontend para a recuperação de senha. 

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

Resultados em Gráfico: 

![alt text](Img/results.png)












