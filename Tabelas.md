# 🗓️📝 Tabelas em HTML 

As tabelas HTML permitem que os desenvolvedores web organizem os dados em linhas e colunas.

- table → Define a tabela
- tr → Linha da tabela
- td → Célula comum
- th → Célula de cabeçalho (negrito e centralizado)
- Atributo border → Adiciona bordas
- CSS pode ser usado para estilizar

Exemplo básico:

```html
<table border="1">
  <tr>
    <th>Nome</th>
    <th>Idade</th>
  </tr>
  <tr>
    <td>Ana</td>
    <td>25</td>
  </tr>
</table>
```

<table border="1">
  <tr>
    <th>Nome</th>
    <th>Idade</th>
  </tr>
  <tr>
    <td>Ana</td>
    <td>25</td>
  </tr>
</table>

## Bordas

- Atributo border (HTML antigo) → Define a borda (não recomendado)
- CSS border → Melhor forma de estilizar
- border-collapse: collapse; → Junta as bordas das células
- border-spacing → Define o espaço entre as células
- border-radius → As bordas ganham cantos arredondados
- border-style → Define o estilo da borda:
  - solid (sólido)
  - dashed (tracejado)
  - dotted (pontilhado)
  - double (dupla)
  - groove, ridge, inset, outset (efeitos 3D)
- border-color → Define a cor da borda (nomes de cores ou códigos HEX/RGB)

```html
<table style="border: 2px solid black; border-collapse: collapse;">
  <tr>
    <td style="border: 2px dashed red;">A</td>
    <td style="border: 2px dotted blue;">B</td>
  </tr>
</table>
```

## Tamanhos

- width → Define a largura da tabela ou das células
- height → Define a altura
- % ou px podem ser usados

```html
<table style="width: 100%;">
  <tr>
    <td style="width: 50%;">Metade</td>
    <td style="width: 50%;">Metade</td>
  </tr>
</table>
```

## Header (Cabeçalho)

- <th> → Cria células de cabeçalho
- Texto fica negrito e centralizado por padrão
- Atributo scope pode indicar se o cabeçalho vale para linha (row) ou coluna (col)

```html
<table border="1">
  <tr>
    <th scope="col">Nome</th>
    <th scope="col">Idade</th>
  </tr>
  <tr>
    <td>Ana</td>
    <td>25</td>
  </tr>
</table>
```

## Espaçamento e Preenchimento em Tabelas HTML

- padding → Espaço interno dentro das células (afasta o conteúdo da borda).
- border-spacing → Espaço entre as células (quando border-collapse: separate;).
- border-collapse: collapse; → Junta as bordas das células, removendo o border-spacing.

```html
<table style="border: 1px solid black; border-collapse: collapse; border-spacing: 10px;">
  <tr>
    <td style="padding: 10px; border: 1px solid black;">Texto</td>
    <td style="padding: 20px; border: 1px solid black;">Outro</td>
  </tr>
</table>
```

## Colspan e Rowspan

- colspan → Mescla colunas (faz uma célula ocupar mais de uma coluna).
- rowspan → Mescla linhas (faz uma célula ocupar mais de uma linha).
- Exemplo, a célula do cabeçalho ocupa duas colunas:

```html
<table border="1">
  <tr>
    <th colspan="2">Nome e Idade</th>
  </tr>
  <tr>
    <td>Ana</td>
    <td>25</td>
  </tr>
</table>
```

- Exemplo, A célula "Ana" ocupa duas linhas:

```html
<table border="1">
  <tr>
    <td rowspan="2">Ana</td>
    <td>25</td>
  </tr>
  <tr>
    <td>Estudante</td>
  </tr>
</table>
```
