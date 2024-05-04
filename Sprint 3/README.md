
# 📃 DoR(Definition of Ready):

## 🗒️ Backlog Sprint 3
| Rank | Prioridade | User Story | Estimativa |Sprint | Requisito do Parceiro |
|--- |--- |--- |--- |--- |--- |
| 19 | Média | Como gerente geral, quero um dashboard que compile e exiba métricas importantes de todos os departamentos, incluindo capacidade atual, número de alertas ativos e média de permanência das pessoas, para facilitar a análise e tomada de decisões estratégicas em relação à segurança e gestão de recursos. | 20 | 3 | RF2 |
| 20 | Média |Como gerente área, quero um dashboard que compile e exiba métricas importantes de todos as redzones que são do meu departamento, incluindo capacidade atual, número de alertas ativos e média de permanência das pessoas, para facilitar a análise e tomada de decisões estratégicas. | 20 | 3 | RF2 |
| 21 | Média | Como gerente geral, necessito de uma função de exportação de dados que me permita baixar relatórios de um departamento específico, com informações detalhadas sobre as datas e horários de entrada e saída na redzone durante o período selecionado para realizar análises externas mais detalhadas e precisa. | 15 | 3 | RF4 |
| 22 | Média | Como Gerente Geral, quero um login que gerencie o acesso de usuários com diferentes níveis de permissão, incluindo guardas, gerentes de área e outros gerentes gerai, para que cada usuário tenha acesso apenas as partes do sistema relevantes para suas responsabilidades, mantendo assim a segurança e a integridade dos dados da empresa. | 15 | 3 | RF9 |
| 23 | Baixa |Como gerente, quero poder recuperar minha senha através de um processo seguro e confiável, para caso eu a esqueça no futuro. | 5 | 3 | RF9 |

RF2 - Desenvolver um Dashboard de indicadores por períodos

RF4 - Geração de relatórios para compartilhamento.

RF9 - Criar três níveis (Usuário de visualização, Gerente Por 
Departamento e Gerente geral) de acesso para o projeto.

## 📋  User Stories, Critérios de Aceitação e Use Case

#### US #19: Como gerente geral, quero um dashboard que compile e exiba métricas importantes de todos os departamentos, incluindo capacidade atual, número de alertas ativos e média de permanência das pessoas, para facilitar a análise e tomada de decisões estratégicas em relação à segurança e gestão de recursos.

#### Critérios de aceitação:

- Exibir a capacidade atual de todas as redzones do departamento.
- Mostrar o número total de alertas ativos em todas as redzones do departamento.
- Expor a média de permanência das pessoas em todas as redzones do departamento.
- As dashboard devem ser atualizadas automaticamente conforme os dados são recebidos do sistema.

#### Use Case: 

Pré-condições:
- O sistema possui redzones cadastradas e associadas ao departamento do gerente de área.
- Existem dados registrados nas redzones para as métricas a serem exibidas no dashboard.

Fluxo Principal:
- O usuário acessa o sistema e navega até a página do dashboard de métricas.
- O sistema exibe as métricas gerais, incluindo capacidade atual, número de alertas ativos
- O usuário pode interagir com os dados, como ampliar ou reduzir o período de análise, filtrar métricas específicas ou visualizar detalhes adicionais.

Fluxo Alternativo:
- Se não houver departamento cadastrado:
- O sistema exibe uma mensagem informando que não existem departamento no sistema.
- Se não houver redzone cadastrada:
- O sistema exibe uma mensagem informando que não existem redzones no sistema.
- Se não houver registros de logs no período selecionado:
- O sistema mostra uma mensagem indicando que não há registros disponíveis.


#### US #20: Como gerente área, quero um dashboard que compile e exiba métricas importantes de todos as redzones que são do meu departamento, incluindo capacidade atual, número de alertas ativos e média de permanência das pessoas, para facilitar a análise e tomada de decisões estratégicas.

#### Critérios de aceitação:

- O dashboard deve exibir a capacidade atual da redzone selecionada.
- Expor o número total de alertas ativos da redzone.
- Calcular e exibir a média de permanência da redzone.
- Deve ser atualizadas automaticamente conforme os dados são recebidos do sistema.

#### Use Case: 

Pré-condições:
- Possuir uma redzone cadastrada no sistema.
- Existem dados registrados nas redzones para as métricas a serem exibidas no dashboard.

Fluxo Principal:
- O usuário acessa o sistema e navega até a página de gerenciamento da redzone.
- O sistema exibe as métricas gerais, incluindo capacidade atual, número de alertas ativos
- O usuário pode interagir com os dados, como ampliar ou reduzir o período de análise, filtrar métricas específicas ou visualizar detalhes adicionais. 

Fluxo Alternativo:
- Se não houver registros de logs no período selecionado:
- O sistema mostra uma mensagem indicando que não há registros disponíveis.

#### US #21: Como gerente geral, necessito de uma função de exportação de dados que me permita baixar relatórios de um departamento específico, com informações detalhadas sobre as datas e horários de entrada e saída na redzone durante o período selecionado para realizar análises externas mais detalhadas e precisa.

#### Critérios de aceitação:

- A função de exportação de dados deve estar claramente visível e acessível na interface do sistema para o gerente geral.
- O gerente geral deve poder selecionar o departamento específico para o qual deseja gerar o relatório de entrada e saída na redzone.
- Os relatórios devem ser exportados em formatos comuns e compatíveis, como Excel e Csv, para facilitar a análise externa.
- Deve ser possível escolher um intervalo de datas para o relatório, permitindo ao gerente geral analisar dados em períodos específicos.

#### Use Case: 

Pré-condições:
- Deve haver pelo menos uma redzone e um departamento cadastrados no sistema.

Fluxo Principal:
- O usuário acessa o departamento para o qual deseja gerar o relatório.
- Seleciona o período desejado para o relatório.
- Clica em "Pesquisar".
- O sistema retorna os logs de todas as redzones associadas àquele departamento e disponibiliza métodos de exportação.
- O usuário escolhe o método de exportação preferido.
- O sistema realiza o download do relatório.

Fluxo Alternativo:
- Se não houver departamentos cadastrados:
- O sistema exibe uma mensagem informando que não existem departamentos no sistema.
- Se não houver registros de logs no período selecionado:
- O sistema mostra uma mensagem indicando que não há registros disponíveis.


#### US #22: Como Gerente Geral, quero um login que gerencie o acesso de usuários com diferentes níveis de permissão, incluindo guardas, gerentes de área e outros gerentes gerai, para que cada usuário tenha acesso apenas as partes do sistema relevantes para suas responsabilidades, mantendo assim a segurança e a integridade dos dados da empresa.

#### Critérios de aceitação:

- Apenas usuários autenticados devem ter permissão para acessar as URLs, todas são nativamente protegidas, em outras palavras, somente depois de fazer o login que podem ter acesso às rotas.
- Nesse sistema, só haverá três tipos de usuário diferentes: Guarda, que pode somente ter acesso à sua redzone; Gerente de área, que tem acesso ao departamento em que ele se encontra e às redzones que estão atreladas a ele; e o Gerente geral, que tem acesso a todos os departamentos e todas as redzones.
- As senhas dos usuários devem ser armazenadas de forma segura, com criptografia no banco de dados.

#### Cenários:

Gerente Geral
- O Gerente Geral realiza o login no sistema usando suas credenciais de usuário e senha.
- Após a autenticação, ele é redirecionado para a página inicial, onde encontra uma lista de todos os departamentos do sistema.
- Na página inicial, ele pode selecionar um departamento específico da lista.
- Ele tem a opção de gerar um relatório abrangente para o departamento selecionado, clicando na função "Gerar Relatório do Departamento".
- Além disso, o Gerente Geral pode acessar uma redzone específica dentro do departamento, clicando nela na lista.
- Ao selecionar uma redzone específica, ele pode visualizar os dados coletados nessa área.
- Ele também tem a capacidade de gerar um relatório específico para essa redzone, clicando na função “Gerar Relatório da Redzone”.

Gerente de Área
- O Gerente de Área acessa o sistema utilizando suas credenciais de usuário e senha.
- Após a autenticação, ele é direcionado para a página do departamento que ele é responsável, onde visualiza uma lista das redzones do departamento esta sob sua responsabilidade.
- Nele, ele pode optar por gerar um relatório abrangente do departamento, clicando na função "Gerar Relatório do Departamento".
- Além disso, ele tem a capacidade de acessar uma redzone específica da lista, clicando nela.
- Ao selecionar uma redzone específica, ele pode visualizar os dados coletados nessa redzone.
- Ele também tem a opção de gerar um relatório específico para essa redzone, clicando na função "Gerar Relatório da Redzone".
 
Guarda
- O Guarda acessa o sistema usando suas credenciais de usuário e senha.
- Após a autenticação bem-sucedida, é imediatamente redirecionado para a página da redzone que ele e responsável.
- Nela o Guarda pode visualizar todos os dados coletados na redzone atribuída a ele.
- Tendo a opção de gerar um relatório detalhado daquela redzone, clicando na função "Gerar Relatório da Redzone".


#### Use Case: 

Pré-condições:
- O sistema está disponível e operacional. 

Fluxo Principal:
- Acessa a página de login do sistema.
- O sistema solicita as credenciais de autenticação (e-mail e senha).
- Insere as credenciais do usuário.
- O sistema verifica as credenciais e autêntica o usuário se as credenciais estiverem corretas.

Fluxo Alternativo:
- Se as credenciais email ou senha estiverem incorretas:
- O sistema exibe uma mensagem de erro correspondendo a qual delas está incorreta é solicita que o usuário tente novamente.



#### US #23: Como gerente, quero poder recuperar minha senha através de um processo seguro e confiável, para caso eu a esqueça no futuro.

#### Critérios de aceitação:

- Um e-mail deve ser enviado ao usuário com o código para iniciar o processo de recuperação de senha.
- Esse codigo não pode ser salvo no banco de dados, e depois de alguns minutos ele não pode ser mais valido.
- A nova senha do usuário deve ser armazenada de forma criptografada no banco de dados.

#### Use Case: 

Pré-condições:
- O sistema está operacional.
- O Gerente possui uma conta registrada no sistema.

Fluxo Principal:
- O usuário acessa a página de recuperação de senha do sistema.
- O sistema solicita o e-mail associado à conta do usuário.
- O usuário insere o e-mail associado à sua conta.
- O usuário solicita o envio do e-mail de recuperação.
- O usuário acessa o email, nele tem o codigo para a validação.
- O usuário digita ele no campo.
- O sistema valida o codigo e se for valido e mandado para tela de alterar a senha.
- O usuario coloca a senha duas vezes para a confirmação.
- O sistema salva a nova senha criptografada.

Fluxo Alternativo:
- Se o codigo estiver errado:
- O sistema mostra uma mensagem e o usuário pode tentar novamente.
- Se passar do tempo de inspiração do codigo:
- O usuário é mando para a tela de login .


## 📝  Modelo do Banco de Dados

![alt text](Img/Modelo_logico.png)


## 🎨 Mockups

O layout da aplicação está disponível no Figma:

<a href="https://www.figma.com/file/npSn8yHa7ta2qVyJdPwHPE/API-6%C2%BA?type=design&node-id=0-1&mode=design">
  <img alt="Link do Figma" src="https://img.shields.io/badge/Acessar%20Layout%20-Figma-%2304D361">
</a>

## 💾 Dados
O dataset utilizado para o treinamento da IA é o YOLO-V8. Para acessar a documentação completa deste dataset, você pode visitar o repositório oficial no GitHub: [Documentação](https://github.com/autogyro/yolo-V8)










