
# 📃 DoR(Definition of Ready):

## 🗒️ Backlog Sprint 3
| Rank | Prioridade | User Story | Estimativa |Sprint | Requisito do Parceiro |
|--- |--- |--- |--- |--- |--- |
| 1 | Média | Como gerente geral, quero um dashboard que compile e exiba métricas importantes de todos os departamentos, incluindo capacidade atual, número de alertas ativos e média de permanência das pessoas, para facilitar a análise e tomada de decisões estratégicas em relação à segurança e gestão de recursos. | 20 | 3 | RF2 |
| 2 | Média |Como gerente área, quero um dashboard que compile e exiba métricas importantes de todos as redzones que são do meu departamento, incluindo capacidade atual, número de alertas ativos e média de permanência das pessoas, para facilitar a análise e tomada de decisões estratégicas. | 20 | 3 | RF2 |
| 3 | Média | Como gerente geral, necessito de uma função de exportação de dados que me permita baixar relatórios de um departamento específico, com informações detalhadas sobre as datas e horários de entrada e saída na redzone durante o período selecionado para realizar análises externas mais detalhadas e precisa |15 | 3 | RF4 |
| 4 | Média | Como Gerente Geral, quero um login que gerencie o acesso de usuários com diferentes níveis de permissão, incluindo guardas, gerentes de área e outros gerentes gerai, para que cada usuário tenha acesso apenas as partes do sistema relevantes para suas responsabilidades, mantendo assim a segurança e a integridade dos dados da empresa. | 5 | 3 | RF9 |
| 5 | Baixa |Como gerente, quero poder recuperar minha senha através de um processo seguro e confiável, para caso eu a esqueça no futuro. | 5 | 3 | RF9 |

RF2 - Desenvolver um Dashboard de indicadores por períodos

RF4 - Geração de relatórios para compartilhamento.

RF9 - Criar três níveis (Usuário de visualização, Gerente Por 
Departamento e Gerente geral) de acesso para o projeto.

### Critérios de aceitação

Rank 1 :
- Exibir a capacidade atual de todas as redzones do departamento.
- Mostrar o número total de alertas ativos em todas as redzones do departamento.
- Expor a média de permanência das pessoas em todas as redzones do departamento.
- As dashboard devem ser atualizadas automaticamente conforme os dados são recebidos do sistema.

Rank 2 :
- O dashboard deve exibir a capacidade atual da redzone selecionada.
- Expor o número total de alertas ativos da redzone.
- Calcular e exibir a média de permanência da redzone.
- Deve ser atualizadas automaticamente conforme os dados são recebidos do sistema.

Rank 3 :
- A função de exportação de dados deve estar claramente visível e acessível na interface do sistema para o gerente geral.
- O gerente geral deve poder selecionar o departamento específico para o qual deseja gerar o relatório de entrada e saída na redzone.
- Deve ser possível escolher um intervalo de datas para o relatório, permitindo ao gerente geral analisar dados em períodos específicos.

Rank 4 :
- Apenas usuários autenticados devem ter permissão para acessar as URLs, todas são nativamente protegidas, em outras palavras, somente depois de fazer o login que podem ter acesso às rotas.
- Nesse sistema, só haverá três tipos de usuário diferentes: Guarda, que pode somente ter acesso à sua redzone; Gerente de área, que tem acesso ao departamento em que ele se encontra e às redzones que estão atreladas a ele; e o Gerente geral, que tem acesso a todos os departamentos e todas as redzones.
- As senhas dos usuários devem ser armazenadas de forma segura, com criptografia no banco de dados.

Rank 5 :
- Um e-mail deve ser enviado ao usuário com o código para iniciar o processo de recuperação de senha.
- Esse codigo não pode ser salvo no banco de dados, e depois de alguns minutos ele não pode ser mais valido.
- A nova senha do usuário deve ser armazenada de forma criptografada no banco de dados.



## 📝  Modelo do Banco de Dados

![alt text](Img/Modelo_logico.png)


## 🎨 Mockups

O layout da aplicação está disponível no Figma:

<a href="https://www.figma.com/file/npSn8yHa7ta2qVyJdPwHPE/API-6%C2%BA?type=design&node-id=0-1&mode=design">
  <img alt="Link do Figma" src="https://img.shields.io/badge/Acessar%20Layout%20-Figma-%2304D361">
</a>

## 💾 Dados
O dataset utilizado para o treinamento da IA é o YOLO-V8. Para acessar a documentação completa deste dataset, você pode visitar o repositório oficial no GitHub: [Documentação](https://github.com/autogyro/yolo-V8)










