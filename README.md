

# Estudo de HTML (Site Curiosidades)
Site com finalidade educativa, utilizando apenas tags HTML.

### Referência
Abaixo estão todas as tags do HTML. Embora a documentação seja de fácil acesso em diversos sites como o [MDN](https://developer.mozilla.org/) e o [W3C](https://www.w3schools.com/), elas serão incluídas aqui para facilitar o acesso e ajudar no estudo.

---

### Tags
As principais tags serão melhor exploradas com mais informações: descrição, atributos e exemplos.

---

### [Tags básicas]
**`<!DOCTYPE>`**

 Define o tipo do documento. Todo documento HTML precisa iniciar com esta declaração(não é uma tag). Ela informa ao browser o tipo de documento esperado. Esta declaração é válida para HTML5, versões antigas como HTML 4 e HTML tem um formato diferente. 
 
#### Exemplo
```html
<!DOCTYPE html>
<html>
  <head>
    <title>
    </title>
	</head>
  <body>
  </body>
</html>
```
---
**`<html>`**
 
Define um documento HTML. 

**`<head>`**
	
Contém meta-dados e informações para o documento.

**`<title>`**
	
Define um título para o documento.

**`<body>`**
	
Define o um corpo para o documento.

**`<h1>`** to **`<h6>`**

Define os cabeçálhos para o HTML.

**`<p>`**
	
Define um parágrafo.

**`<br>`**

Insere uma quebra de linha.

**`<hr>`**
	
Define uma mudança temática no conteúdo.

**`<!--...-->`**
	
Define um comentário.

### Tags de formatação

**`<acronym>`**

*Não suportada pelo HTML5. Use `<abbr>` instead.*
Define uma sigla.

**`<abbr>`**

Define uma abreviação ou uma sigla.

**`<address>`**

Define informações de contato do autor ou dono do documento ou artigo.

**`<b>`**

Define o texto em negrito.

**`<bdi>`**

Isola uma parte do texto que pode ser formatada em uma direção diferente do outro texto fora dele.

**`<bdo>`**

Substitui a direção atual do texto.

**`<big>`**

*Não suportada no HTML5. Use CSS ao invés desta tag.*

**`<blockquote>`**

Define uma seção que é cidata em outra fonte.

**`<center>`**

*Não suportada no HTML5. Use CSS ao invés desta tag.*
Define texto centralizado.

**`<cite>`**

Define o título de uma obra.

**`<code>`**

Define uma pedaço de código de computador.

**`<del>`**

Define um texto que foi deletado do documento.

**`<dfn>`**

Especifica um termo que será definido dentro do conteúdo da página.

**`<em>`**

Define um texto enfatizado.

**`<font>`**

*Não suportada no HTML5. Use CSS ao invés desta tag.*
Define fonte, cor e tamanho do texto.

**`<i>`**

Define uma parte do texto com voz ou entonação alternativa.

**`<ins>`**

Define um texto novo que foi inserido.

**`<kbd>`**

Define uma entrada do teclado.

**`<mark>`**

Define um texto marcado/destacado.

**`<meter>`**

Define uma medida escalar dentro de um intervalo conhecido (um medidor)

**`<pre>`**

Define texto pre-formatado.

**`<progress>`**

Representa o progresso de uma tarefa.

**`<q>`**

Define uma citação curta.

**`<rp>`**

Define o que mostrar ao browser que não suporta *ruby anotations*.

**`<rt>`**

Define uma explicação/pronúncia de caracteres.  (para a tipografia do Leste Asiático).

**`<ruby>`**

Define uma *ruby annotation* (para a tipografia do Leste Asiático)

**`<s>`**

Define um texto que não está mais correto.

**`<samp>`**

Define uma amostra  de uma saída de um programa de computador.

**`<small>`**

Define um texto pequeno.

**`<strike>`**

*Não mais suportado no HTML5. Use `<del>` or `<s>` instead.*
Define um texto riscado/apagado do conteúdo.

**`<strong>`**

Define um texto importante

**`<sub>`**

Define um texto subscrito.

**`<sup>`**

Define um texto sobrescrito.

**`<template>`**

Define um container para conteúdo que deve ser escondido quando a página carrega.

**`<time>`**

Define uma hora ou data específica.

**`<tt>`**

*Não suportada no HTML5. Use CSS ao invés dela.*
Define um texto *teletype*.

**`<u>`**

Define um texto não relacionado e estilizado de forma diferente do texto normal.

**`<var>`**

Define uma variável.

**`<wbr>`**

Define uma possível quebra de linha.

### Formulários e entrada de dados

---

### Frames

---

### Imagens

**`<img>`**

Define uma imagem

**`<map>`**

Define um *image-map* do lado do cliente

**`<area>`**

Define uma área dentro de um *image-map*

**`<canvas>`**

Usado para desenhar gráficos, *on the fly*, via script (normalmente JavaScript)

**`<figcaption>`**

Define uma *caption* para o elemento  **`<figure>`**.

**`<figure>`**

Especifica um conteúdo independente.

**`<picture>`**

Define um container com multiplos recursos de imagens.

**`<svg>`**

Define um container para gráficos SVG.

---

### Audio / Vídeo

---

### Links

---

**`<a>`**
Define um hyperlink.

**`<link>`**

Define uma relação entre o documento e um recurso externo (o mais usado é o link para *style sheets*)

**`<nav>`**

Define links de navegação.

---

### Listas

---

### Tabelas

---

### Estilo e Semântica

**`<style>`**

Define informações de estilo para um documento.

**`<div>`**

Define uma seção em um documento.

**`<span>`**

Define uma seção em um documento.

**`<header>`**

Define um cabeçalho para um documento ou seção.

**`<footer>`**

Defiine um rodapé para um documento ou seção.

**`<main>`**

Especifica o conteúdo principal do documento.

**`<section>`**

Define uma seção em um documento.

**`<article>`**

Define um artigo.

**`<aside>`**

Define um conteúdo secundário para o conteúdo principal da página.

**`<details>`**

Define detalhes adicionais que o usuário pode ver ou esconder.

**`<dialog>`**

Define uma caixa de diálogo ou janela.

**`<summary>`** 

Define um cabeçalho visível para o elemento **`<details>`**.

**`<data>`**
Adiciona uma tradução legível para máquinas a um determinado conteúdo.

---

### Meta informação

**`<head>`**

Define informações sobre o documento.

**`<meta>`**

Define metadados sobre o documento HTML.

**`<base>`**

Especifica a base URL/target ara todas URLs relativas do documento.

**`<basefont>`**

Não suportada pelo HTML5. Use CSS ao invés desta tag.  
Especifica os padrões de cor, tamanho e fonte de todos os textos em um documento.

---

### Programação

**`<script>`**

Define um script *client-side*.

**`<noscript>`**

Define um conteúdo alternado para usuários que não tem suporte a scripts *client-side*.

**`<applet>`**

Não mais suportado em HTML5. Use **`<embed>`** or **`<object>`** ao invés dela.
Define um *applet* embutido.

**`<embed>`**

Define um container para uma aplicação externa (não HTML).

**`<object>`**

Define um objeto embutido.

**`<param>`**

Define um parâmetro para um objeto.

