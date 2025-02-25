# 💡Links em HTML

Links HTML são hiperlinks. Você pode clicar em um link e pular para outro documento.

A tag < a > define um hyperlink. Ela tem a seguinte sintaxe:

```html
<a href="url">link text</a>
```

O atributo mais importante seria o href, que serve para especificar o link.

O texto do link é a parte que ficará visível para o leitor. Clicar no texto enviará o leitor para o link especificado.

Por padrão, os links aparecerão da seguinte forma em todos os navegadores:

- Um link não visitado é sublinhado e azul
- Um link visitado é sublinhado e roxo
- Um link ativo é sublinhado e vermelho

Por padrão, a página vinculada será exibida na janela atual do navegador. Para alterar isso, você deve especificar outro alvo para o link.

O atributo **target** especifica onde abrir o documento vinculado.

Pode ter um dos seguintes valores:

- **_self** - Padrão. Abre o documento na mesma janela/guia em que foi clicado;
- **_blank** - Abre o documento em uma nova janela ou aba;
- **_parent** - Abre o documento no quadro pai;
- **_top** - Abre o documento no corpo inteiro da janela.

```html
<a href="https://www.w3schools.com/" target="_blank">Visit W3Schools!</a>
```

## Use uma imagem como link

Para colocar um link em uma imagem, basta colocar a tag img dentro da tag a. Segue exemplo:

```html
<!DOCTYPE html>
<html>
<body>

<h2>Imagem é um link</h2>

<p>Esta imagem é um link, clique nela.</p>

<a href="default.asp"><img src="smiley.gif" alt="HTML tutorial" style="width:42px;height:42px;"></a>

</body>
</html>
```

## Link para um endereço de email

Use **mailto:** dentro do href para criar um link que abre o programa de e-mail do usuário (para permitir que ele envie um novo e-mail):

```html
<a href="mailto:someone@example.com">Isto é um e-mail.</a>
```

## Botão com um link

Para usar um botão HTML como um link, você precisa adicionar algum código JavaScript.
Permite que você especifique o que acontece em certos eventos, como o clique de um botão:

```html
<button onclick="document.location='default.asp'">HTML Tutorial</button>
```

## 
