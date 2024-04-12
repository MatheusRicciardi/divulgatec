# divulgatec

Site de divulgação de eventos de tecnologia

# Tags HTML Utilizadas no Documento

- `<!DOCTYPE html>`: Declaração do tipo de documento.
- `<html>`: Tag raiz que envolve todo o conteúdo HTML.
- `<head>`: Cabeçalho do documento que contém metadados e links para arquivos externos.
  - `<meta>`: Tags meta para configuração do documento.
  - `<link>`: Tag para vincular um arquivo CSS externo.
  - `<title>`: Define o título da página.
- `<body>`: Contém todo o conteúdo visível da página.
- `<header>`: Cabeçalho da página.
  - `<a>`: Link de âncora.
  - `<nav>`: Contêiner para links de navegação.
  - `<ul>`: Lista não ordenada.
  - `<li>`: Item de lista.
- `<main>`: Contém o conteúdo principal da página.
- `<section>`: Define uma seção na página.
  - `class`: Atributo de classe para estilização.
  - `id`: Atributo de identificação único.
- `<div>`: Divisão genérica ou contêiner.
- `<center>`: Tag desatualizada para centralizar conteúdo (é melhor usar CSS para isso).
- `<strong>`: Texto forte ou enfatizado.
- `<h1>`, `<h2>`, `<h3>`: Títulos de cabeçalho.
- `<p>`: Parágrafo.
- `<img>`: Imagem.
- `<table>`: Tabela.
  - `<tr>`: Linha de tabela.
  - `<td>`: Célula de tabela.
  - `<ol>`: Lista ordenada dentro de uma célula da tabela.
- `<a>`: Link de âncora.
  - `href`: Atributo de URL do link.
  - `target="_blank"`: Atributo para abrir o link em uma nova aba/janela.
- `<br>`: Quebra de linha.
- `<hr>`: Linha horizontal.
- `<footer>`: Rodapé da página.

# Propriedades CSS Utilizadas no Arquivo

## Seletor Universal

- `*`: Resetando `padding` e `margin` em todos os elementos.

- **IDs (`#`)**:

  - Um ID é um seletor único usado para identificar um elemento específico em uma página HTML. IDs são usados quando você tem um único elemento que precisa ser estilizado ou manipulado via JavaScript.

- **Classes (`.`)**:
  - Uma classe é um seletor reutilizável usado para estilizar múltiplos elementos. Classes são ideais para estilizar elementos que compartilham as mesmas características ou comportamentos.

## .item-lista-cabecalhoa

Este seletor é utilizado para estilizar os itens da lista no cabeçalho.

- `:active`:
  - Estilização quando o item está ativo.
- `:hover`:
  - Estilização quando o cursor está sobre o item.

### Propriedades e Valores:

- `align-items`: `center`

  - Centraliza os itens ao longo do eixo transversal em um contêiner flex.

- `background-color`: `white`

  - Define a cor de fundo como branco.

- `background-image`: `url(../img/background2.png)`

  - Define uma imagem de fundo para o elemento.

- `background-position`: `center`, `top`

  - Centraliza a posição da imagem de fundo.

- `background-repeat`: `no-repeat`

  - Evita que a imagem de fundo se repita.

- `background-size`: `cover`

  - Ajusta a imagem de fundo para cobrir todo o elemento sem distorção.

- `border-radius`: `1.5rem`

  - Arredonda os cantos do elemento.

- `color`: `black`

  - Define a cor do texto como preto.

- `display`: `block`, `flex`, `inline-block`

  - Controla como o elemento é exibido.

- `flex`: `1`

  - Define o fator de flexibilidade para o elemento em um contêiner flex.

- `flex-direction`: `column`

  - Define a direção do eixo principal em um contêiner flex como vertical.

- `font-family`: `montserrat, sans-serif`

  - Define a fonte utilizada para o texto.

- `font-size`: `62.5%`

  - Define o tamanho da fonte como 62.5% do tamanho padrão do navegador.

- `font-weight`: `600`

  - Define o peso da fonte como semibold.

- `gap`: `2.5rem`

  - Define o espaçamento entre os itens de um contêiner flex.

- `height`: `auto`, `72vh`

  - Define a altura do elemento.

- `justify-content`: `space-between`

  - Distribui o espaço restante entre os itens em um contêiner flex.

- `left`: `0`

  - Define a posição à esquerda do elemento.

- `line-height`: `1`

  - Define a altura da linha do texto.

- `list-style`: `none`

  - Remove os marcadores de lista padrão.

- `margin`: `0`, `auto`, `0 auto`, `1rem`, `1rem 0`

  - Define as margens do elemento.

- `margin-top`: `1rem`

  - Define a margem superior do elemento.

- `max-width`: `100rem`

  - Define a largura máxima do elemento.

- `min-height`: `100vh`

  - Define a altura mínima do elemento.

- `padding`: `0`

  - Define o preenchimento interno do elemento.

- `position`: `sticky`

  - Define a posição do elemento como fixa, relativa ao contêiner.

- `text-decoration`: `none`

  - Remove a decoração de texto, como sublinhado.

- `text-transform`: `none`

  - Transformação de texto para maiúsculas.

- `top`: `0`

  - Define a posição superior do elemento.

- `width`: `10rem`

  - Define a largura do elemento.

- `z-index`: `9999`
  - Define a ordem de empilhamento do elemento.
