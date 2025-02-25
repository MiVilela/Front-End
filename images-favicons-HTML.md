# 🖼️🖌️ Imagens em HTML

A tag img é utilizada para incorporar uma imagem na página web.

A tag tem dois atributos obrigatórios:

- src - Especifica o caminho para a imagem;
- alt - Especifica um texto alternativo para a imagem.

Sintaxe:

```HTML
<img src="url" alt="alternatetext">
```

Também podemos definir o tamanho da imagem em largura e altura com o atributo style, width e leight. Podemos usar o width e leight separados do atributo style ou junto com ele. Veja exemplos:

```html
<img src="img_girl.jpg" alt="Girl in a jacket" style="width:500px;height:600px;">

<img src="img_girl.jpg" alt="Girl in a jacket" width="500" height="600">
```

Mesmo podendo utilizar a largura e altura direto, sem o style, recomendamos utilizar com o atributo, ele impede que folhas de estilos alterem o tamanho das imagens.

Podemos utilizar imagens de pastas local ou imagens externas, utilizando o link delas.

HTML permite incorporar GIFs na página web.

### Imagem de fundo

Uma imagem de fundo pode ser especificada para quase qualquer elemento HTML.

Para adicionar uma imagem de fundo em um elemento HTML, use o style e a background-image.
Exemplo:

```html
<p style="background-image: url('img_girl.jpg');">
```

Se a imagem de fundo for menor que o elemento, a imagem se repetirá, horizontal e verticalmente, até chegar ao final do elemento:

Para evitar que a imagem de fundo se repita, defina a background-repeat como no-repeat.

Exemplo:
```html
<style>
body {
  background-image: url('example_img_girl.jpg');
  background-repeat: no-repeat;
}
</style>
```


## Favicon em HTML

Um favicon é uma pequena imagem exibida ao lado do título da página na aba do navegador.

Você pode usar qualquer imagem que quiser como seu favicon. Você também pode criar seu próprio favicon em sites como https://www.favicon.cc

Para adicionar um favicon ao seu site, salve sua imagem favicon no diretório raiz do seu servidor web ou crie uma pasta no diretório raiz chamada images e salve sua imagem favicon nessa pasta. Um nome comum para uma imagem favicon é "favicon.ico".

Em seguida, adicione um < link > ao seu arquivo "index.html", depois do < title >, como este:

```html
<!DOCTYPE html>
<html>
<head>
  <title>My Page Title</title>
  <link rel="icon" type="image/x-icon" href="/images/favicon.ico">
</head>
<body>

<h1>This is a Heading</h1>
<p>This is a paragraph.</p>

</body>
</html>
```
