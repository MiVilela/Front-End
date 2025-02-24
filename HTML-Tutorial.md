# Introdução ao HTML

HTML é uma linguagem de marcação padrão para criar páginas da WEB. Significa Hyper Text Markup Linguage.

## 🏗️ Estrutura Básica de um Documento HTML  
```html
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Meu Site</title>
</head>
<body>
    <h1>Olá, mundo!</h1>
    <p>Este é um parágrafo em HTML.</p>
</body>
</html>
```

🔹 Principais Tags do HTML

!DOCTYPE html - Define que o documento é HTML5
html - elemento raiz
title - especifica o titulo da página (mostrado na barra de título do navegador)
body - corpo do documento, contêiner para todo o conteúdo visível.
h1 - elemento define um grande título
p - elemento define um parágrafo

## Elemento HTML

É definido por uma tag inicial, o conteúdo e uma tag final.
Alguns elementos HTML não possuem conteúdo, por exemplo o < br >, ele serve somente para quebrar a linha e não possui uma tag final.

## Cabeçalhos HTML

Os titulos HTML são definidos por h1 a h6.

h1 = define o titulo mais importante
h6 = define o titulo menos importante

## Paragrafo

Utilizamos a tag < p > para definir um paragrafo.

## Links

Definimos um link com a tag < a >

```html
<a href="www.google.com">Link<a>
```
O atributo href serve para especificar o link.

## Imagens

Imagens são definidas com a tag <img>.
Os atributos:
- src = origem do arquivo.
- alt = texto alternativo.
- width e height - tamanho da imagem.
  
````html
<img src="w3schools.jpg" alt="W3Schools.com" width="104" height="142">
````

## Atributos

Agora vamos falar um pouco sobre os atributos HTML, eles fornecem informações adicionar sobre elementos.
São sempre especificados na tag inicial. 
Geralmente vem em pares nome/valor como: nome="valor".

**href** - atributo especifica URL;
**src** - especifica o caminho para a imagem ser exibida;
Podemos especificar a imagem no src utilizando uma URL Absoluta, seria uma imagem externa que está hospedada em outro site.
URL relativa, link para uma imagem hospedada dentro do site atual.
**width** - largura;
**height** - altura;
**alt** - especifica um texto alternativo para uma imagem, se a imagem não for exibida este texto que aparece na tela;
**style** - adicionar estilos a um elemento, cor, fonte, tamanho, etc;
**lang** - declara o idiota da página Web;
**title** - define algumas informações extras sobre um elemento. Será exibido como uma dica de ferramenta quando você passar o mouse sobre o elemento.

OBS: Sempre utilizar atributos com letra minúscula.
