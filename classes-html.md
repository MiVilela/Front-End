# Atributo `Class`

O atributo `class` em HTML é usado para atribuir uma ou mais classes a um elemento, permitindo que ele seja estilizado com CSS ou manipulado com JavaScript.

Facilita a aplicação de estilos em vários elementos sem precisar usar `id` ou `style` diretamente.

Segue um exemplo:

```html
<!DOCTYPE html>
<html lang="pt">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Exemplo de Class</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <h1 class="titulo">Olá, Mundo!</h1>
    <p class="destaque">Este é um parágrafo com destaque.</p>
    <p class="destaque negrito">Este é um parágrafo destacado e em negrito.</p>
</body>
</html>
```
```css
.titulo {
    color: blue;
    text-align: center;
}

.destaque {
    color: red;
}

.negrito {
    font-weight: bold;
}
```

Observação: o nome da classe diferencia maiúsculas de minúsculas!

