# 📜 Listas em HTML

Listas são usadas para organizar informações de forma estruturada. Existem 3 tipos principais:

## 🔹 Listas Não Ordenadas (`<ul>`)
- Marcadores (padrão: bolinhas 🔵)
- Exemplo:
  ```html
  <ul>
    <li>HTML</li>
    <li>CSS</li>
    <li>JavaScript</li>
  </ul>
  ```
## 🎨 Personalizando os Marcadores (list-style-type)
- Podemos mudar o estilo do marcador padrão usando CSS!
- 🔵 Tipos de marcador:
  - disc (padrão) ➝ ● Item
  - circle ➝ ○ Item
  - square ➝ ■ Item
  - none (sem marcador) ➝ Item

- Exemplo:
  ```html
  <ul style="list-style-type: square;">
    <li>Item A</li>
    <li>Item B</li>
    <li>Item C</li>
  </ul>
  ```
  
## 🔢 Listas Ordenadas (`<ol>`)
- Itens numerados (1, 2, 3...)
- Exemplo:
  ```html
  <ol>
    <li>Acordar</li>
    <li>Tomar café</li>
    <li>Codar!</li>
  </ol>
  ```

## 🎨 Atributo Type para listas ordenadas
- O atributo type define o tipo do marcador da lista ordenada.
  - type="1" ➝ Serão numerados com números, padrão.
  - type="A" ➝ Serão numerados com letras maiúsculas.
  - type="a" ➝ Serão numerados com letras minúsculas.
  - type="I" ➝ Serão numerados com números romanos maiúsculos.
  - type="i" ➝ Serão numerados com números romanos minúsculos.
  - Exemplo:
  ```html
  <ol type="A">
    <li>Coffee</li>
    <li>Tea</li>
    <li>Milk</li>
  </ol>
  ```

## 📑 Listas de Definição (`<dl>`)
- Tipo “termo e descrição”
- Exemplo:
  ```html
  <dl>
    <dt>HTML</dt>
    <dd>Linguagem de marcação</dd>
    <dt>CSS</dt>
    <dd>Folhas de estilo</dd>
  </dl>
  ```
