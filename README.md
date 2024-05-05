<h4 align="center"> 
	<img alt="Logo Fatech" title="#Fatech" src="https://github.com/4-Fatech/API-6SEM-Front/blob/main/public/logo.png" />
</h4>
<p align="center">
	<a href="#-sobre-o-projeto">Sobre</a> •
	<a href="#-Padronização-de-commit's">Padronização de commit's</a> •
	<a href="#-Estratégia-de-Branches">Estratégia de Branches</a> •
	<a href="#-Modelo-Entidade-Relacionamento">MER</a> •
	<a href="#-Deploy">Deploy</a> •
	<a href="#-Vídeos-das-Sprints">Vídeos</a> • 
	<a href="#-Autores">Autores</a>
</p>

## 💻 Sobre o projeto

🚀 Este repositório foi criado para armazenar a documentação do API do sexto semestre, no que diz as sprints e estratégias adotadas.

---

## ⚙️ Padronização de commit's

Para melhor entendimento do andamento do projeto e organização, optamos por implementar um padrão nos commits. Sendo este:

1. ```fix```: um commit do tipo fix soluciona um problema na sua base de código.
2. ```feature```: um commit do tipo feature inclui um novo recurso na sua base de código.
3. ```docs```: um commit do tipo docs inclui uma nova documentação na sua base de código.

<h3>Exemplos</h3>
- Mensagem de commit com descrição

```feature: permitir que o objeto de configuração fornecido estenda outras configurações```

- Mensagem de commit com ! para chamar a atenção para quebra a compatibilidade
  
```feature!: envia email para o cliente quando o produto é enviado```

- Mensagem de commit com escopo e ! para chamar a atenção para quebra a compatibilidade

```feature(api)!: envia email para o cliente quando o produto é enviado```

- Mensagem de commit com escopo

```feature(lang): adiciona tradução para português brasileiro```

---

## 🌲 Estratégia de Branches
No projeto, estamos utilizando a estratégia de versionamento através de branches.

<h3><a href="https://github.com/4-Fatech/API-6SEM-Front">API-6SEM-Front</a></h3>
No repositório do frontend, existem duas ramificações(branches) que dividem o projeto: a main, que contém o conteúdo funcional, e a dev, que abriga o projeto em desenvolvimento.

A branch dev é dedicada ao desenvolvimento do projeto. Durante a sprint, são criadas issues, desempenhando o papel de sugestão, rastreamento ou tarefas relacionadas ao projeto. A partir dessas issues, são criadas branches para desenvolver as soluções. Em seguida, são abertos os PRs (pull requests), cuja função é integrar as novas funcionalidades ao projeto. Cada PR é associado a uma branch específica, onde a solução da issue é desenvolvida. Uma vez que a solução é completa, ela é mergeada na branch dev.

Ao final da sprint, a branch dev é mergeada com a main e, por fim, é criada a tag da sprint para melhor controle do código durante o processo. A ação de merge com a main só pode ser realizada após uma revisão, a fim de evitar comprometer a branch.

<h3><a href="https://github.com/4-Fatech/API-6SEM-Back">API-6SEM-Back</a></h3>
A branch deploy-render foi criada a partir da branch dev com o objetivo de facilitar o processo de enviar o projeto para uma plataforma chamada Render. Isso permite que a aplicação seja automaticamente preparada para uso.

A branch dev é usada para trabalhar no desenvolvimento do projeto. Durante um período de trabalho chamado sprint, são identificados problemas ou melhorias que precisam ser feitas, chamados de issues. A partir dessas issues, são propostas soluções, chamadas de pull requests (PRs). Cada PR é como uma proposta de mudança no projeto e é feito em uma nova ramificação (branch) que é criada especificamente para resolver esse problema. Quando a solução é desenvolvida e considerada pronta, ela é integrada de volta à branch dev.

Ao final da sprint, todas as mudanças feitas na branch dev são reunidas e integradas à branch principal, main. Isso é feito para garantir que todas as novas funcionalidades e correções de bugs estejam presentes na versão principal do projeto. Além disso, é criada uma "etiqueta" para identificar as mudanças feitas durante essa sprint, o que facilita o acompanhamento do progresso do projeto.

<h3><a href="https://github.com/4-Fatech/API-6SEM-AI">API-6SEM-AI</a></h3>
No repositório da IA, atualmente existem duas ramificações (ou branches) no projeto: a main e a dev.

A branch dev é reservada para o desenvolvimento contínuo do projeto. Durante um período de trabalho conhecido como sprint, são identificados problemas ou melhorias necessárias, chamados de issues. A partir dessas issues, são propostas soluções, chamadas de pull requests (PRs). Para cada PR, é criada uma nova ramificação (branch) específica para resolver o problema em questão. Assim que a solução é implementada e considerada pronta, ela é integrada de volta à branch dev.

Ao final da sprint, todas as alterações feitas na branch dev são consolidadas e integradas à branch principal, main. Isso é feito para garantir que todas as novas funcionalidades e correções de bugs estejam presentes na versão principal do projeto. Além disso, é criada uma "etiqueta" para identificar as mudanças feitas durante essa sprint, o que facilita o acompanhamento do progresso do projeto.

## 🎨 Layout - Mockups

O layout da aplicação está disponível no Figma:

<a href="https://www.figma.com/file/npSn8yHa7ta2qVyJdPwHPE/API-6%C2%BA?type=design&node-id=0-1&mode=design">
  <img alt="Link do Figma" src="https://img.shields.io/badge/Acessar%20Layout%20-Figma-%2304D361">
</a>

---

## 📊 Modelo Entidade Relacionamento

Nosso banco de dados para a aplicação foi idealizado desta maneira:

![mer](https://github.com/4-Fatech/API-6SEM-Docs/assets/89141910/d75d59ca-b66e-4e7d-bfc8-65d0365aebac)

---

## 💾 Dados
O dataset utilizado para o treinamento da IA é o YOLO-V8. Para acessar a documentação completa deste dataset, você pode visitar o repositório oficial no GitHub: [Documentação](https://github.com/autogyro/yolo-V8)

---

## ✅ Deploy
<h3><a href="https://github.com/4-Fatech/API-6SEM-Front">API-6SEM-Front</a></h3>
Atualmente o frontend pode ser consultado online a partir do site: https://api-6semestre-front.onrender.com/

<h3><a href="https://github.com/4-Fatech/API-6SEM-Back">API-6SEM-Back</a></h3>
Atualmente o backend pode ser consultado online a partir do site: https://api-6sem-back.onrender.com/
E também as **rotas** do backend estão documentadas em: https://api-6sem-back.onrender.com/swagger-ui/index.html

## 🎥 Vídeos das Sprints
 - [Sprint 1](https://drive.google.com/drive/folders/1Z6rl5nGkvD1bf-cNF6al9NBHzDnzO9gJ) | [Documentação](https://github.com/4-Fatech/API-6SEM-Docs/tree/main/Sprint%201#-dordefinition-of-ready)
 - [Sprint 2](https://drive.google.com/drive/folders/1B8nYwbInOF46-7qFyKalrwvfCMf-SMRP) | [Documentação](https://github.com/4-Fatech/API-6SEM-Docs/blob/main/Sprint%202/README.md#-dordefinition-of-ready)

## 🦸 Autores
<div style="display: flex; justify-content: center;align-items: center;">
 <img src="https://github.com/New-Tomorrow.png" width="100px"></img>
 <img src="https://github.com/Antonio-Barbosa.png" width="100px"></img>
 <img src="https://github.com/brunadias3.png" width="100px"></img>
 <img src="https://github.com/dsslleagion.png" width="100px"></img>
 <img src="https://github.com/Evertonrwr.png" width="100px"></img>
 <img src="https://github.com/Gabriel-Coutinho0.png" width="100px"></img>
</div>

[![Linkedin Badge](https://img.shields.io/badge/-AndréRibeiro-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/andre-ramos-ribeiro-320621226/)](https://www.linkedin.com/in/andre-ramos-ribeiro-320621226/)
[![Linkedin Badge](https://img.shields.io/badge/-AntônioMarcelo-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/antonio-marcelo-9a5b68181)](https://www.linkedin.com/in/antonio-marcelo-9a5b68181)
[![Linkedin Badge](https://img.shields.io/badge/-BrunaDias-blue?style=flat-square&logo=Linkedin&logoColor=white&link=www.linkedin.com/in/brunadias3)](https://www.linkedin.com/in/brunadias3)
[![Linkedin Badge](https://img.shields.io/badge/-DionísioLeão-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/dionisio-samuel-dos-santos-le%C3%A3o-616848226/)](https://www.linkedin.com/in/dionisio-samuel-dos-santos-le%C3%A3o-616848226/)
[![Linkedin Badge](https://img.shields.io/badge/-EvertonRicardo-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/everton-rocha-1a456b20b)](https://www.linkedin.com/in/everton-rocha-1a456b20b)
[![Linkedin Badge](https://img.shields.io/badge/-GabrielCoutinho-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/gabriel-silva-b778a31aa)](https://www.linkedin.com/in/gabriel-silva-b778a31aa)

---
