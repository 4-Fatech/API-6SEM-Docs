<h4 align="center"> 
	<img alt="Logo Fatech" title="#Fatech" src="https://github.com/4-Fatech/API-6SEM-Front/blob/main/public/logo.png" />
</h4>
<p align="center">
 <a href="#-sobre-o-projeto">Sobre</a> •
 <a href="#-Padronização de commit's">Padronização de commit's</a> •
 <a href="#-Estratégia de Branches">Estratégia de Branches</a> •
 <a href="#-Modelo Entidade Relacionamento">MER</a> •
  <a href="#-Deploy">Deploy</a> •
 <a href="#-Vídeo Sprint 1">Sprint 1</a> • 
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
No repositório do frontend, atualmente existem 2 branchs no projeto, sendo elas a main e a dev.

A branch dev é dedicada ao desenvolvimento do projeto, que, ao longo da sprint são criadas as issues e a partir delas os PR's (pull requests) em que cada pull request é criado uma branch nova para a resolução da issue e assim que é solucionada é mergeada na branch dev.
Ao final da sprint a branch dev é mergeada com a main e por fim é criado a tag da sprint, para termos um melhor controle do código durante o processo.
A ação de merge com a main só pode ser feito após um review, afim de evitar o comprometimento da branch.

<h3><a href="https://github.com/4-Fatech/API-6SEM-Back">API-6SEM-Back</a></h3>
No repositório do backend, atualmente existem 3 branchs no projeto, sendo elas a main, deploy-render e a dev.

A branch deploy render é uma ramificação da branch dev, ela foi criada com o intuito de viabilizar o upload do projeto no render, possibilitando o build automatico da aplicação.

A branch dev é dedicada ao desenvolvimento do projeto, que, ao longo da sprint são criadas as issues e a partir delas os PR's (pull requests) em que cada pull request é criado uma branch nova para a resolução da issue e assim que é solucionada é mergeada na branch dev.
Ao final da sprint a branch dev é mergeada com a main e por fim é criado a tag da sprint, para termos um melhor controle do código durante o processo.
A ação de merge com a main só pode ser feito após um review, afim de evitar o comprometimento da branch.

<h3><a href="https://github.com/4-Fatech/API-6SEM-AI">API-6SEM-AI</a></h3>
No repositório da IA, atualmente existem 2 branchs no projeto, sendo elas a main e a dev.

A branch dev é dedicada ao desenvolvimento do projeto, que, ao longo da sprint são criadas as issues e a partir delas os PR's (pull requests) em que cada pull request é criado uma branch nova para a resolução da issue e assim que é solucionada é mergeada na branch dev.
Ao final da sprint a branch dev é mergeada com a main e por fim é criado a tag da sprint, para termos um melhor controle do código durante o processo.
A ação de merge com a main só pode ser feito após um review, afim de evitar o comprometimento da branch.

## 🎨 Layout - Mockups

O layout da aplicação está disponível no Figma:

<a href="https://www.figma.com/file/npSn8yHa7ta2qVyJdPwHPE/API-6%C2%BA?type=design&node-id=0-1&mode=design">
  <img alt="Link do Figma" src="https://img.shields.io/badge/Acessar%20Layout%20-Figma-%2304D361">
</a>

---

## 📊 Modelo Entidade Relacionamento

## ✅ Deploy
<h3><a href="https://github.com/4-Fatech/API-6SEM-Front">API-6SEM-Front</a></h3>
Atualmente o frontend pode ser consultado online a partir do site: https://api-6semestre-front.onrender.com/

<h3><a href="https://github.com/4-Fatech/API-6SEM-Back">API-6SEM-Back</a></h3>
Atualmente o backend pode ser consultado online a partir do site: https://api-6sem-back.onrender.com/
E também as **rotas** do backend estão documentadas em: https://api-6sem-back.onrender.com/swagger-ui/index.html

## 🎥 Vídeos das Sprints
 - [Sprint 1](https://github.com/4-Fatech/API-6SEM-Docs/tree/main/Sprint%201#v%C3%ADdeo-da-sprint-1)

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
