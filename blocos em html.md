# Blocos e elementos embutidos em HTML

## Tipos de Exibição
Cada elemento HTML tem um valor de exibição padrão, sendo os mais comuns:
- **Block (bloco)**
- **Inline (em linha)**

## Elementos de Nível de Bloco
- Sempre começam em uma **nova linha**.
- Ocupam **toda a largura disponível**.
- Exemplos comuns:
  - `<p>` (parágrafo)
  - `<div>` (divisão/seção)
 
## Elementos de bloco em HTML:
`<address>, <article>, <aside>, <blockquote>, <canvas>, <dd>, <div>, <dl>, <dt>, <fieldset>, <figcaption>, <figure>, <footer>, <form>, <h1> - <h6>, <header>, <hr>, <li>, <main>, <nav>, <noscript>, <ol>, <p>, <pre>, <section>, <table>, <tfoot>, <ul>, <video>`

## Elementos em Linha
- Não começam em uma nova linha.
- Ocupam apenas a largura necessária.
- Exemplos comuns:
- `<span>` (marca parte de um texto)

Exemplo:
```html
<span>Hello World</span>
```

## Elementos inline em HTML:
`<a>, <abbr>, <acronym>, <b>, <bdo>, <big>, <br>, <button>, <cite>, <code>, <dfn>, <em>, <i>, <img>, <input>, <kbd>, <label>, <map>, <object>, <output>, <q>, <samp>, <script>, <select>, <small>, <span>, <strong>, <sub>, <sup>, <textarea>, <time>, <tt>, <var>`

🗒️ Nota: Um elemento inline não pode conter um elemento de bloco!

## O Elemento `<div>`

- Contêiner para outros elementos HTML.
- Não possui atributos obrigatórios, mas style, class e id são comuns.
- Usado com CSS para estilização.

Exemplo:

```html
<div style="background-color:black;color:white;padding:20px;">
  <h2>London</h2>
  <p>London is the capital city of England.</p>
</div>
```

## O Elemento `<span>`

- Contêiner embutido usado para marcar partes do texto.
- Sem atributos obrigatórios, mas style, class e id são comuns.

# 📌 Resumo do Capítulo

✅ Elementos de nível de bloco: começam em uma nova linha e ocupam toda a largura disponível.

✅ Elementos inline: não começam em uma nova linha e ocupam apenas a largura necessária.

✅ Elemento `<div>`: elemento de bloco usado como contêiner para outros elementos HTML.

✅ Elemento `<span>`: elemento inline usado para destacar partes de um texto.
