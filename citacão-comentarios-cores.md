# Citações, comentários e cores em HTML

## 👩‍🏫 Citação em HTML

A tag blockquote é usado para citações longas, geralmente destacadas em um parágrafo separado. E a seção é citada normalmente de outra fonte.

Obs: Os navegadores costumam recusar o blockquote.

Exemplo:
```HTML
p>Here is a quote from WWF's website:</p>
<blockquote cite="http://www.worldwildlife.org/who/index.html">
For 60 years, WWF has worked to help people and nature thrive. As the world's leading conservation organization, WWF works in nearly 100 countries.
</blockquote>
```

A tag q é usado para definir uma citação curta dentro do texto, é inserido aspas ao redor da citação.

```HTML
<p>Einstein disse: <q>A imaginação é mais importante que o conhecimento.</q></p>
```

A tag abbr é usada para abreviações e siglas, podendo mostrar o significado completo ao passar o mouse.

```html
<p><abbr title="HyperText Markup Language">HTML</abbr> é a linguagem da web.</p>
```

A tag address é usada para informações de contato, como endereço, e-mail ou telefone. 
Geralmente é renderizado em itálico, e os navegadores sempre adicionarão uma quebra de linha antes e depois da tag.

```html
<address>
  Rua das Flores, 123<br>
  Cidade Exemplo, EX 45678<br>
  E-mail: contato@exemplo.com
</address>
```

A tag cite é usada para citar o nome de uma obra, como livros, filmes ou músicas.

```HTML
<p>O livro <cite>1984</cite> foi escrito por George Orwell.</p>
```

A tag bdo é usada para mudar a direção do texto (ex: da direita para a esquerda).

```html
<p><bdo dir="rtl">Este texto será exibido da direita para a esquerda.</bdo></p>
```

## 🗒️ Comentários

Você pode adicionar um comentário em seu código, utilizando a seguinte sintaxe:

```HTML
<!-- Write your comments here -->
```

Os comentários podem ser utilizados para ocultar conteúdo do código.

## 🖌️ Cores em HTML

As cores HTML são especificadas com nomes de cores predefinidos ou com valores RGB, HEX, HSL, RGBA ou HSLA.

Podemos mudar a cor de fundo, cor do texto, cor da borda dos elementos.

### Cores em RGB e RGBA

Um valor de cor RGB representa fontes de luz VERMELHA, VERDE e AZUL.
Um valor de cor RGBA é uma extensão de RGB com um canal Alfa (opacidade).

A sintaxe da cor RGB e RGBA é: 

```html
rgb(red, green, blue)

rgba(red, green, blue, alfa)
```

Cada parâmetro (vermelho, verde e azul) define a intensidade da cor com um valor entre 0 e 255.

Isso significa que há 256 x 256 x 256 = 16777216 cores possíveis!

Por exemplo, rgb(255, 0, 0) é exibido como vermelho, porque o vermelho está definido como seu valor mais alto (255), e os outros dois (verde e azul) estão definidos como 0.

Outro exemplo, rgb(0, 255, 0) é exibido como verde, porque o verde está definido como seu valor mais alto (255), e os outros dois (vermelho e azul) estão definidos como 0.

Para exibir preto, defina todos os parâmetros de cor como 0, assim: rgb(0, 0, 0).
Para exibir branco, defina todos os parâmetros de cor como 255, assim: rgb(255, 255, 255).

Tons de cinza são definidos por valores iguais nos três parâmetros, por exemplo, rgb(180, 180, 180), rgb(60, 60, 60).

Os valores de cor RGBA são uma extensão dos valores de cor RGB com um canal Alfa, que especifica a opacidade de uma cor.

O parâmetro alfa é um número entre 0,0 (totalmente transparente) e 1,0 (nada transparente).

### Cores em HEX

Uma cor hexadecimal é especificada com: #RRGGBB, onde os inteiros hexadecimais RR (vermelho), GG (verde) e BB (azul) especificam os componentes da cor.

Os valores hexadecimais estão entre 00 e ff (o mesmo que o decimal 0-255).
Por exemplo, #ff0000 é exibido como vermelho, porque o vermelho está definido como seu valor mais alto (ff), e os outros dois (verde e azul) estão definidos como 00.

Para exibir preto, defina todos os parâmetros de cor como 00, assim: #000000.
Para exibir branco, defina todos os parâmetros de cor como ff, assim: #ffffff.

Os tons de cinza são exibidos por valores iguais em todos os parâmetros, por exemplo, #f8f8f8, #404040.

### Cores em HSL e HSLA

HSL significa matiz, saturação e luminosidade.
Os valores de cor HSLA são uma extensão do HSL com um canal Alfa (opacidade).

A sintaxe é: 
hsl(matiz, saturação, luminosidade)

Matiz é um grau na roda de cores de 0 a 360. 0 é vermelho, 120 é verde e 240 é azul.

Saturação é um valor percentual. 0% significa um tom de cinza e 100% é a cor completa. 100% é cor pura, sem tons de cinza. 50% é 50% cinza, mas você ainda pode ver a cor. 0% é completamente cinza; você não consegue mais ver a cor.
 
Luminosidade também é um valor percentual. 0% é preto e 100% é branco. 0% significa nenhuma luz (preto), 50% significa 50% de luz (nem escuro nem claro) e 100% significa luminosidade total (branco).

Os valores de cor HSLA são uma extensão dos valores de cor HSL, com um canal Alfa, que especifica a opacidade de uma cor.
hsla( matiz, saturação , luminosidade, alfa )

O parâmetro alfa é um número entre 0,0 (totalmente transparente) e 1,0 (nada transparente).
