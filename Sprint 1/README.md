
# 📃 DoR(Definition of Ready):

## 🗒️ Backlog Sprint 1 
| Rank | Prioridade | User Story | Estimativa |Sprint | Requisito do Parceiro |
|--- |--- |--- |--- |--- | --- |
| 1 | Alta | Como gerente, quero que use uma inteligência artificial que utilize a câmera na entrada da redzone para fazer a contagem de pessoas que saíram e entraram dela, para não precisar fazer uma contagem manual. | 80 | 1 | RF8 |
| 2 | Alta | Como gerente, desejo ter a capacidade de visualizar os registros de acesso à redzone, a fim de identificar precisamente os horários de entrada e saída dos usuários, possibilitando um monitoramento eficaz das atividades. | 60 | 1 |RF6 |
| 3 | Alta |Como gerente, desejo visualizar em tempo real a quantidade de pessoas na redzone, para poder monitorar efetivamente a presença de indivíduos nessa área específica. | 15 | 1 | RF8 |
| 4 | Alta |Como gerente, desejo uma interface de busca que utilize a data como filtro e apresente os resultados em uma tabela, incluindo os horários de entrada e saída na redzone, para facilitar futuras análises de dados. | 10 | 1 | RF6 |


RF6 - Desenvolver um CRUD (Criar, Ler, Alterar e Deletar) de Redzone.

RF8 - Utilizar a câmera da entrada para contabilizar as pessoas que entraram e saíram da Redzone.


## 📋  User Stories, Critérios de Aceitação e Use Case

#### US #1:  Como gerente, quero que use uma inteligência artificial que utilize a câmera na entrada da redzone para fazer a contagem de pessoas que saíram e entraram dela, para não precisar fazer uma contagem manual.

#### Critérios de aceitação:

- A inteligência artificial deve ser capaz de contar as pessoas que entram e saem com base nas imagens da câmera da entrada da redzone.

- Os registros de entrada e saída de pessoas devem ser salvos no banco de dados.


#### Use Case: 

Pré-condições:
- O sistema de contagem automática de pessoas está configurado e funcionando corretamente.
- A câmera na entrada da redzone está conectada e operacional.

Fluxo Principal:
- A inteligência artificial utiliza a câmera na entrada da redzone para detectar e contar as pessoas que entram e
e saíram.
- A contagem é registrada pelo sistema e atualizada em tempo real.
- O Gerente monitora a contagem de pessoas na redzone por meio de uma interface dedicada.

Fluxo Alternativo:
- Se houver uma interrupção na conexão da câmera ou no funcionamento da inteligência artificial:
- O sistema exibe uma mensagem de erro indicando o problema.
- O Gerente é notificado sobre a falha e toma as medidas necessárias para resolver o problema.


#### US #2: Como gerente, desejo ter a capacidade de visualizar os registros de acesso à redzone, a fim de identificar precisamente os horários de entrada e saída dos usuários, possibilitando um monitoramento eficaz das atividades.

#### Critérios de aceitação:

- A visualização dos registros deve ser clara e organizada, expondo as seguintes informações; data e horária das entradas e saídas da redzone.

#### Use Case: 

Pré-condições:
- Os registros de acesso à redzone estão armazenados no sistema.
- O sistema de visualização de registros está operacional.

Fluxo Principal:
- O Gerente acessa a interface de visualização da redzone.
- O sistema recupera os registros de acesso armazenados no banco de dados.
- Os registros são apresentados ao Gerente em uma interface amigável, mostrando os horários de entrada e saída dos usuários.

Fluxo Alternativo:
- Se não houver registros de acesso disponíveis para a data especificada:
- O sistema exibe uma mensagem indicando a falta de registros.



#### US #3: Como gerente, desejo visualizar em tempo real a quantidade de pessoas na redzone, para poder monitorar efetivamente a presença de indivíduos nessa área específica. 

#### Critérios de aceitação:

- A visualização em tempo real deve ser precisa e atualizada continuamente conforme as pessoas entram e saem da redzone.

#### Use Case: 

Pré-condições:
- O sistema de contagem automática de pessoas na redzone está operacional.

Fluxo Principal:
- O Gerente acessa a interface de visualização da redzone.
- O sistema exibe dinamicamente a quantidade atual de pessoas na redzone, atualizando em tempo real.
- O Gerente monitora a quantidade de pessoas na redzone conforme necessário.

Fluxo Alternativo:
- Se houver uma falha na contagem automática de pessoas:
- O sistema exibe uma mensagem de erro indicando a falha.



#### US #4: Como gerente, desejo uma interface de busca que utilize a data como filtro e apresente os resultados em uma tabela, incluindo os horários de entrada e saída na redzone, para facilitar futuras análises de dados.

#### Critérios de aceitação:

- A interface de busca deve permitir ao gerente filtrar os registros de acesso à redzone por data específica.
- Os resultados da busca devem ser apresentados de forma clara e organizada em uma tabela, incluindo informações como horários de entrada e saída.

#### Use Case: 

Pré-condições:
- Os registros de acesso à redzone estão armazenados no sistema.

Fluxo Principal:
- O Gerente acessa a interface de busca para análise de dados.
- O Gerente insere os critérios de busca desejados, como datas específicas.
- O sistema filtra os registros de acesso à redzone com base nos critérios de busca inseridos.
- Os registros filtrados são apresentados ao Gerente em uma tabela formatada.

Fluxo Alternativo:
- Se não houver registros correspondentes aos critérios de busca inseridos:
- O sistema exibe uma mensagem indicando a ausência de registros para os critérios especificados.
- Se não houver registros de acesso disponíveis para a data especificada:
- O Gerente é informado de que não há registros para a data selecionada.



## 📝 Modelo do Banco de Dados
O modelo de banco de dados utilizado e desenvolvido nessa sprint foi:

![alt text](Img/Modelo_logico.png)


## 🎨 Mockups
![alt text](Img/Mockups.jpg)

## 💾 Dados
O dataset utilizado para o treinamento da IA é o YOLO-V8. Para acessar a documentação completa deste dataset, você pode visitar o repositório oficial no GitHub: [Documentação](https://github.com/autogyro/yolo-V8)

## Vídeo da Sprint 1

***Por favor, para o carregamento das gifs espere alguns segundos.***
- Monitoramento do fluxo de pessoas em tempo real - IA
![IA (1)](https://github.com/4-Fatech/API-6SEM-Docs/assets/89141910/9b718fcf-1af9-4d37-ba17-5a8953aeda4c)

- Visualização do fluxo de pessoas em tempo real - Frontend
![historico (1)](https://github.com/4-Fatech/API-6SEM-Docs/assets/89141910/240324d8-b81a-4fde-a98e-9f834c69bec6)

- 📂 Pasta completa dos materiais desenvolvidos na sprint 1 - [Link](https://drive.google.com/drive/folders/1Z6rl5nGkvD1bf-cNF6al9NBHzDnzO9gJ)

