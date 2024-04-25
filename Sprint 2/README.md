
# 📃 DoR(Definition of Ready):

## 🗒️ Backlog Sprint 2 
| Rank | Prioridade | User Story | Estimativa |Sprint | Requisito do Parceiro |
|--- |--- |--- |--- |--- |--- |
| 1 | Média | Como gerente geral, quero poder criar um departamento no sistema, fornecendo informações como nome, responsável e redzones atreladas a esse departamento, para cadastrar as novas redzones. | 15 | 2 |RF7 |
| 2 | Média | Como gerente geral, quero uma página inicial que me permita acessar facilmente todas os departamentos monitorados, incluindo métricas importantes como capacidade atual e alertas ativos, para facilitar o gerenciamento. | 15 | 2 | RF7 |
| 3 | Média | Como gerente geral, quero poder criar uma nova redzone no sistema ela tem que estar atrelada ao departamento que sou responsável, fornecendo informações como nome, responsável, câmera e capacidade máxima, para cadastrar as novas redzones.| 15 | 2 | RF6 |
| 4 | Média | Como gerente geral, quero uma página inicial que me permita acessar facilmente todas as informações como métricas importantes como capacidade atual, alertas ativos e responsável pela redzone, para facilitar o gerenciamento. | 15 | 2 | RF6 |
| 5 | Média |Como gerente, desejo uma ferramenta que permita filtrar (por período desejado) os dados de acesso para comparação, para analisar tendências e identificar variações significativas. | 15 | 2 | RF3 |
| 6 | Média | Como gerente geral, quero poder alterar os dados de um determinado departamento no sistema, para poder cadastrar e corrigir dados já existentes. | 10 | 2 | RF7 |
| 7 | Média | Como gerente geral, quero poder alterar os dados de uma determinada redzone no sistema, para poder cadastrar e corrigir dados já existentes. | 10 | 2 | RF6 |
| 8 | Média | Como gerente geral, quero poder cadastrar um novo usuário no sistema, fornecendo seu nome, e-mail, matrícula da empresa e tipo de usuário, (guarda, gerente de área), para garantir que a equipe de segurança esteja completa e atualizada. | 10 | 2 | RF5 |
| 9 | Média | Como gerente geral, desejo uma funcionalidade que me permita visualizar todos os usuários do sistema, sendo os gerentes de área e guardas, para ter uma visão geral da equipe de segurança. | 10 | 2 | RF5 |
| 10 | Média | Como gerente geral, quero poder alterar do usuário, para lidar com mudanças dos dados da equipe. | 10 | 2 | RF5 |
| 11 | Média | Como gerente geral, quero poder desativar um determinado departamento, para garantir a segurança e integridade das áreas monitoradas. | 5 | 2 | RF7|
| 12 | Média | Como gerente geral, quero poder desativar uma determinada redzone, para garantir a segurança e integridade das áreas monitoradas. | 5 | 2 | RF6 |
| 13 | Média | Como gerente geral, quero poder desativar um usuário, para impedir o acesso quando necessário. | 5 | 2 | RF5 |


RF3 - Filtros de período para análise dos dados.

RF5 - Desenvolver um CRUD (Criar, Ler, Alterar e Deletar) de Usuários.

RF6 - Desenvolver um CRUD (Criar, Ler, Alterar e Deletar) de Redzone.

RF7 - Desenvolver um CRUD (Criar, Ler, Alterar e Deletar) de Departamento.

### Critérios de aceitação

Rank 1 :

- Ao criar um departamento, é essencial que o usuário tenha campos disponíveis para preencher, tais como o nome do departamento e o nome do responsável é o sistema deve ser capaz de armazenar esses dados.

Rank 2 :

- Deve exibir todos os departamentos monitorados, incluindo as informações importantes como capacidade atual e alertas ativos.
- As informações exibidas na página inicial devem ser atualizadas automaticamente conforme ocorrem mudanças nos departamentos.

Rank 3 :

- Ao criar uma nova redzone, deve conter todos os campos sendo eles; nome, responsável, câmera e capacidade máxima.
- A redzone criada deve ser automaticamente atrelada ao departamento.
- Cada redzone tem que possuir sua própria câmera para poder fazer o log de fluxo.

Rank 4 :

- Deve exibir todos das redzone, nome, responsável, câmera e capacidade máxima.
- As informações devem ser atualizadas em tempo real para refletir a situação mais recente das redzones.

Rank 5 :

- As informações devem ser atualizadas em tempo real para refletir a situação mais recente das redzones.
- O sistema deve permitir a seleção da redzone.
- Deve ser possível escolher o período desejado, com uma data de início e uma data de fim para a seleção.

Rank 6 :

- Poder modificar informações como nome, responsável do departamento existente.
- Após a alteração dos dados, as informações atualizadas devem ser refletidas imediatamente no sistema.

Rank 7 :

- O gerente geral pode modificar informações como nome, responsável e capacidade máxima de uma redzone existente.
- Após a alteração dos dados, as informações atualizadas devem ser refletidas imediatamente no sistema.

Rank 8 :
- O sistema deve possuir os campos citados anteriormente.
- Ficar disponível no sistema para poder ser selecionado. Se for um guarda, será alocado na redzone; se for um gerente de área no departamento.

Rank 9 :
- Deve exibir todos os usuários, incluindo as informações como nome, e-mail, matricula da empresa e tipo de usuário (gerente de área ou guarda).
- As informações exibidas na página inicial devem ser atualizadas automaticamente conforme ocorrem mudanças nos usuários.

Rank 10 :
- Pode modificar informações como nome, e-mail, matrícula da empresa e tipo de usuário.
- Após a alteração dos dados, as informações atualizadas devem ser refletidas imediatamente no sistema.

Rank 11 :
- O departamento desativado deve ser claramente identificado no sistema como inativa.
- Ao desativar o departamento, todas as atividades de monitoramento e acesso devem ser interrompidas para garantir a segurança e integridade da área.

Rank 12 :
- Quando a redzone é desativada deve ser claramente identificado no sistema como inativa.
- Ao desativar a redzone, todas as atividades de monitoramento e acesso da redzone devem ser interrompidas para garantir a segurança e integridade da área.

Rank 13 :
- O usuário desativado deve ser claramente identificado no sistema como inativa.
- Ao desativar o usuário, o acesso dele do sistema deve ser contado.


## 📝  Modelo do Banco de Dados

![alt text](Img/Modelo_logico.png)


## 🎨 Mockups

O layout da aplicação está disponível no Figma:

<a href="https://www.figma.com/file/npSn8yHa7ta2qVyJdPwHPE/API-6%C2%BA?type=design&node-id=0-1&mode=design">
  <img alt="Link do Figma" src="https://img.shields.io/badge/Acessar%20Layout%20-Figma-%2304D361">
</a>

## 💾 Dados
O dataset utilizado para o treinamento da IA é o YOLO-V8. Para acessar a documentação completa deste dataset, você pode visitar o repositório oficial no GitHub: [Documentação](https://github.com/autogyro/yolo-V8)










