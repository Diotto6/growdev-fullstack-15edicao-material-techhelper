## Revisão sobre css

CSS Inline: O CSS inline é uma maneira de adicionar estilos diretamente em um elemento HTML usando o atributo "style". Por exemplo, para definir a cor do texto para vermelho em um parágrafo, você pode usar o seguinte código HTML:

```html
<p style="color: red;">Texto vermelho</p>
CSS utilizando a tag <style> no HTML: Você pode incluir CSS diretamente no HTML usando a tag <style>. Dentro dessa tag, você pode escrever as regras de estilo CSS para aplicar a elementos específicos. Por exemplo:
```

```html
<style>
  p {
    color: blue;
  }
</style>
```

CSS utilizando arquivo externo: O CSS também pode ser definido em um arquivo externo com a extensão .css. Você pode criar um arquivo CSS separado e, em seguida, referenciá-lo no HTML usando a tag `html<link>` no elemento `html<head>`. Por exemplo:

htmlCopy code

```html
<head>
  <link rel="stylesheet" href="styles.css" />
</head>
```

Comentários no CSS: Para adicionar comentários em CSS, você pode usar a sintaxe /_ comentário _/. Por exemplo:

```css
/_ Este é um comentário CSS _/
```

Definindo cores aos elementos: Existem várias maneiras de definir cores em CSS:

Por nome: Você pode usar nomes de cores pré-definidos, como red, blue, green, etc.
Código hexadecimal: Você pode usar um código hexadecimal de seis dígitos para definir uma cor. Por exemplo, #FF0000 representa a cor vermelha.
RGB: Você pode usar a sintaxe rgb(red, green, blue) para definir uma cor. Os valores de red, green e blue variam de 0 a 255.
Backgrounds: Você pode definir a cor de fundo e uma imagem de fundo para um elemento usando propriedades de CSS:

Cor de fundo: Use a propriedade background-color para definir a cor de fundo de um elemento.
Imagem de fundo: Use a propriedade background-image para definir uma imagem de fundo para um elemento.
Estilos de bordas: Você pode definir diferentes estilos de borda para um elemento usando a propriedade border em CSS. Alguns estilos comuns incluem solid (linha sólida), dashed (linha tracejada), dotted (linha pontilhada), entre outros.

Tamanhos (height e width): As propriedades height e width são usadas para definir as dimensões de um elemento em CSS. Por exemplo:

```css
div {
  height: 100px;
  width: 200px;
}
```

Medidas no CSS: Existem várias unidades de medidas disponíveis em CSS:

px (pixels): Unidade de medida fixa. Por exemplo, 10px.
em: Unidade de medida relativa ao tamanho da fonte do elemento pai. Por exemplo, 1.5em é 1,5 vezes o tamanho da fonte do elemento pai.
rem: Unidade de medida relativa ao tamanho da fonte do elemento raiz (normalmente o `html<html>`). Por exemplo, 2rem é o dobro do tamanho da fonte do elemento raiz.
vh (viewport height): Unidade de medida relativa à altura da viewport, onde 1vh corresponde a 1% da altura do viewport.

vmin e vmax: Unidades de medida relativas à altura (vmin) ou largura (vmax) do viewport, dependendo de qual dimensão for menor ou maior.
Box Model: O Box Model é um conceito fundamental do CSS que define como os elementos HTML são renderizados em relação ao seu conteúdo, preenchimento, bordas e margens. O modelo é composto pelas seguintes partes:

content: É a área onde o conteúdo do elemento é exibido.
padding: É a área de preenchimento entre o conteúdo e a borda. Pode ser definido usando a propriedade padding.
border: É a borda ao redor do conteúdo e do preenchimento. Pode ser definido usando a propriedade border.
margin: É a área de margem ao redor do elemento. Pode ser definido usando a propriedade margin.
Estilos e famílias de fontes: Você pode definir o estilo e a família de fontes em CSS usando a propriedade font. Por exemplo:

```css
p {
  font-family: Arial, sans-serif;
  font-size: 16px;
  font-weight: bold;
  font-style: italic;
}
```

Estilização de links: Você pode estilizar links em CSS usando as pseudoclasses :link, :visited, :hover, :active. Por exemplo:

```css
a:link {
  color: blue;
}
a:hover {
  color: red;
}
```

Estilização de listas: As listas podem ser estilizadas em CSS usando a propriedade list-style. Por exemplo:

```css
ul {
  list-style-type: disc;
}

ol {
  list-style-type: decimal;
}
```

Essas são apenas algumas das funcionalidades básicas do CSS. O CSS é uma linguagem poderosa para estilizar e controlar a aparência dos elementos HTML em uma página da web.

Exemplo de CSS Inline:

```html
<p style="color: red; font-size: 20px;">Texto vermelho com tamanho de fonte de 20 pixels.</p>
Exemplo de CSS utilizando a tag <style> no HTML:
htmlCopy code
<head>
  <style>
    p {
      color: blue;
      font-weight: bold;
    }
  </style>
</head>
<body>
  <p>Este é um parágrafo com texto azul e em negrito.</p>
</body>
```

Exemplo de CSS utilizando arquivo externo:
HTML (index.html):

```html
<head>
  <link rel="stylesheet" href="styles.css" />
</head>
<body>
  <p>Este é um parágrafo com estilo definido em um arquivo CSS externo.</p>
</body>
```

CSS (styles.css):

```css
p {
  color: green;
  font-style: italic;
}
```

Exemplo de adição de comentários no CSS:

```css
/_ Este é um comentário CSS _/
p {
/_ Esta é uma regra de estilo para parágrafos _/
color: red;
}
```

Exemplo de definição de cores aos elementos:

```css
p {
color: blue; /_ Define a cor do texto para azul _/
background-color: #FF0000; /_ Define a cor de fundo para vermelho usando código hexadecimal _/
}
```

Exemplo de backgrounds (cor e imagem):

```css
body {
background-color: yellow; /_ Define a cor de fundo do corpo para amarelo _/
background-image: url("imagem.jpg"); /_ Define uma imagem de fundo para o corpo _/
}
```

Exemplo de estilos de bordas:

```css
p {
border: 1px solid black; /_ Define uma borda sólida de 1 pixel em volta do parágrafo _/
}
```

Exemplo de tamanhos (height e width):

```css
div {
height: 200px; /_ Define a altura do elemento div para 200 pixels _/
width: 300px; /_ Define a largura do elemento div para 300 pixels _/
}
```

Exemplo de medidas no CSS:

```css
p {
font-size: 1.2em; /_ Define o tamanho da fonte do parágrafo como 1.2 vezes o tamanho da fonte do elemento pai _/
margin-bottom: 20px; /_ Define a margem inferior do parágrafo como 20 pixels _/
}
```

Exemplo de box model:

```css
div {
  width: 200px;
  padding: 20px;
  border: 1px solid black;
  margin: 10px;
}
```

Exemplo de estilos e famílias de fontes:

```css
h1 {
  font-family: Arial, sans-serif; /* Define a família de fontes do título como Arial ou qualquer fonte sans-serif disponível */
  font-size: 24px; /* Define o tamanho da fonte do título como 24 pixels */
  font-weight: bold; /* Define o peso da fonte do título como negrito */
}
```

Exemplo de estilização de links:

```css
a:link {
  color: blue; /* Define a cor do link antes de ser visitado como azul */
}
```
