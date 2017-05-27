---
layout: default
---

## [](#header-2)Setup

1. Inicie o Sublime Text. Ele abrirá em uma nova janeja escura.
2. Em seu Desktop, crie uma pasta chamada **'landing'**. Arraste essa pasta para a janela do Sublime (conforme exemplo do instrutor)
3. Na Barra Lateral do Sublime, siga os seguintes passos
	- Clique com o botão direito "New File"
	- Salve como **"index.html"**
	- Repita o mesmo processo e crie o arquivo **style.css**
	- Em seguida clique com o botão direito "New Folder" e crie uma pasta chamada **img**
4. Por fim abra a pasta landing que você criou e clique duas vezes sobre **index.html** para abri o arquivo no navegador

## [](#header-2)Adicionando o HTML

1. Antes, salve estas imagens em sua pasta **img**

![](https://assets-cdn.github.com/images/icons/emoji/octocat.png) ![](https://assets-cdn.github.com/images/icons/emoji/octocat.png) ![](https://assets-cdn.github.com/images/icons/emoji/octocat.png) 

2. Copie e cole este código HTML

```html
<html>
  <head>
    <meta charset="utf-8">
    <title>Meu Super Aplicativo</title>
  </head>
  <body>
    <h1>Meu Super Aplicativo</h1>
    <p>Esta é a linha mais importante e que todos leem..</p>
    <p>
      <a href="#">Baixe Agora</a>
    </p>

    <img src="images/briefcase.png" alt="descrição" width="100">
    <h2>Rápido</h2>
    <p>Um aplicativo rápido, <strong>muito rápido</strong></p>

    <img src="images/diamond.png" alt="descrição" width="100">
    <h2>Simples</h2>
    <p>Um aplicativo simples, <strong>muito simple</strong></p>

    <img src="images/heart.png" alt="descrição" width="100">
    <h2>Incrível</h2>
    <p>Um aplicativo incrível, <strong>muito incrível</strong></p>

    <img src="images/laptop.png" alt="descrição" width="100">
    <h2>Lindo</h2>
    <p>Um aplicativo lindo, <strong>muito lindo</strong></p>

    <p>Está é uma landing ©Makers Americana</p>
  </body>
</html>
```
### [](#header-3)Extra - Onde encontrar bons icones:
- [Icon Store](https://iconstore.co/)
- [Noun Project](https://thenounproject.com/)
- [Nucleo App](https://nucleoapp.com/premium-icons/)

Fique ligado também nas novidades em: [Product Hunt](https://www.producthunt.com/search?q=icons)

## [](#header-2) Adicionando CSS, Fontes e Cores

1. Faça o link da folha de estilos CSS(style.css) na seção **head** do HTML

```html
<head>
  <link href='style.css' rel='stylesheet'>
</head>
```
2. Após fazer o link copie e cole o código abaixo em seu **style.css**

```css
/* style.css */
body{
  background: rgb(245,245,245);
  color: green;
  font-size: 25px;
  font-family: Helvetica;
}
h1{
  font-family: Courier;
  color: red;
  font-weight: lighter;
  font-size: 10px;
}
h2 {
  font-family: Courier;
  color: pink;
  font-weight: lighter;
  font-size: 8px;
}
a {
  color: yellow;
}
a:hover {
  text-decoration: none;
  color: purple;
}
```
### [](#header-3)Extra - Onde encontrar boas fontes e paletas de cores:
- [Google Fonts](http://fonts.google.com) (para fontes)
- [Colorzilla](http://www.colorzilla.com/chrome/) para pegar cores de outros sites

Você também pode achar cores interessantes no [Coolors](https://coolors.co/) ou [Color Hunt](http://colorhunt.co/)

## [](#header-2)Envolvendo seu código com DIV's

1. Envolva as diferentes seções do site com DIV

```html
<html>
  <head>
    <meta charset="utf-8">
    <title>Meu Super Aplicativo</title>
  </head>
  <body>
    <div>
    	<h1>Meu Super Aplicativo</h1>
    	<p>Esta é a linha mais importante e que todos leem..</p>
    	<p>
      		<a href="#">Baixe Agora</a>
    	</p>
    </div>
    <div>
    	<img src="images/briefcase.png" alt="descrição" width="100">
    	<h2>Rápido</h2>
    	<p>Um aplicativo rápido, <strong>muito rápido</strong></p>
    </div>
    <div>
    	<img src="images/diamond.png" alt="descrição" width="100">
    	<h2>Simples</h2>
    	<p>Um aplicativo simples, <strong>muito simple</strong></p>
    </div>
    <div>
    	<img src="images/heart.png" alt="descrição" width="100">
    	<h2>Incrível</h2>
    	<p>Um aplicativo incrível, <strong>muito incrível</strong></p>
    </div>
    <div>
    	<img src="images/laptop.png" alt="descrição" width="100">
    	<h2>Lindo</h2>
    	<p>Um aplicativo lindo, <strong>muito lindo</strong></p>
    </div>
    <div>
    	<p>Está é uma landing ©Makers Americana</p>
    </div>
  </body>
 </html>
```

## [](#header-2)Adicionando Classes e Id's

1. Nomeie seu banner e footer com ID's como: **<div id="banner">** e **<div id="footer">**

2. Nomeie suas funcionalidades com Classes como: **<div class="card">**

3. E então adicione este belo código CSS

```css
#banner{
  text-align: center;
  background-image: url("https://unsplash.it/1300/600?random");
  background-size: cover;
  padding: 150px;
  color: white;
  text-shadow: 1px 1px 5px black;
}
#banner h1 {
  color: white;
  font-size: 50px;
}
#banner p {
  color: white;
  opacity: 0.8;
  font-size: 30px;
  font-weight: lighter;
}
#footer{
  padding: 30px;
  background: rgb(30, 30, 30);
  color: lightgrey;
}
.card{
  padding: 50px;
  font-weight: lighter;
}
```
### [](#header-3)Extra - Onde encontrar boas imagens grátis:
- [Pexels](http://www.pexels.com)

6. FONTAWESOME

In your head, it's in your head!

<head>
  <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/font-awesome/4.4.0/css/font-awesome.min.css">
</head>
And then in the footer

<ul>
  <li><a href="#"><i class="fa fa-youtube"></i></a></li>
  <li><a href="#"><i class="fa fa-facebook"></i></a></li>
  <li><a href="#"><i class="fa fa-twitter"></i></a></li>
  <li><a href="#"><i class="fa fa-github"></i></a></li>
</ul>
With a bit of CSS style

#footer a {
  color: lightgrey;
  font-size: 15px;
}
#footer a:hover {
  color: white;
}

## [](#header-2)Adicionando BOOTSTRAP

1. Faça o link da stylesheet do Bootstrap no head section de seu HTML antes do link para o **style.css**

<head>
  <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.2.0/css/bootstrap.min.css">
  <link href='style.css' rel='stylesheet'>
</head>

2. Brinque com as classes do bootstrap: class="btn btn-primary" e class="list-inline" aplicando a chamada de ação e os icones do footer

## [](#header-2)Utilizando o GRID do Bootstrap

1. Utilize a estrutura abaixo e inclua os cards das funcionalidades do seu produto dentro das div's
<div class="container">
  <div class="row">
    <div class="col-xs-12 col-sm-6 col-md-3">
      <!-- div class="card" -->
    </div>
    <div class="col-xs-12 col-sm-6 col-md-3">
      <!-- div class="card" -->
    </div>
    <div class="col-xs-12 col-sm-6 col-md-3">
      <!-- div class="card" -->
    </div>
    <div class="col-xs-12 col-sm-6 col-md-3">
      <!-- div class="card" -->
    </div>
  </div>
</div>
