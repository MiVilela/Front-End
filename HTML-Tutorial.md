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

🔹 Principais Tags do HTML

<!DOCTYPE html> - Define que o documento é HTML5
<html> - elemento raiz
<title> - especifica o titulo da página (mostrado na barra de título do navegador)
<body> - corpo do documento, contêiner para todo o conteúdo visível.
<h1> - elemento define um grande título
<p> - elemento define um parágrafo

## Elemento HTML

É definido por uma tag inicial, o conteúdo e uma tag final.
Alguns elementos HTML não possuem conteúdo, por exemplo o <br>, ele serve somente para quebrar a linha e não possui uma tag final.

## Cabeçalhos HTML

Os titulos HTML são definidos por h1 a h6.

h1 = define o titulo mais importante
h6 = define o titulo menos importante

## Paragrafo

Utilizamos a tag <p> para definir um paragrafo.

## Links

Definimos um link com a tag <a>
<a href="www.google.com">Link<a>

O atributo href serve para especificar o link.

## Imagens

Imagens são definidas com a tag <img>.
Os atributos:
- src = origem do arquivo.
- alt = texto alternativo.
- width e height - tamanho da imagem.

<img src="w3schools.jpg" alt="W3Schools.com" width="104" height="142">

