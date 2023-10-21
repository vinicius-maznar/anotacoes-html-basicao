# 🏗 Estrutura Básica do HTML

## ⁉ **Definição:**

- HTML (Hypertext Markup Language) é uma linguagem de marcação usada para criar a estrutura e o conteúdo de páginas web. A estrutura básica do HTML é composta por elementos que definem a organização e a apresentação do conteúdo na web.

## 📚 **Estrutura Geral:**

1. **`<!DOCTYPE html>`:** Esta declaração define a versão do HTML utilizada (como HTML5) e é a primeira linha em um documento HTML.

2. **`<html>`:** O elemento raiz que envolve todo o conteúdo da página.

3. **`<head>`:** A seção do cabeçalho da página, que contém informações sobre o documento, como metadados, títulos e links para estilos e scripts.

4. **`<meta>`:** Elementos usados para fornecer informações sobre a codificação de caracteres, palavras-chave, descrições e outras metainformações.

5. **`<title>`:** Define o título da página exibido na barra de título do navegador.

6. **`<link>` e `<script>`:** São usados para vincular arquivos externos de CSS e JavaScript para estilizar e adicionar funcionalidades à página.

7. **`<body>`:** A seção principal da página que contém o conteúdo visível para os visitantes.

8. **Elementos de Conteúdo:** Incluem títulos (`<h1>` a `<h6`>), parágrafos (`<p>`), listas (`<ul>`, `<ol>`, `<li>`), links (`<a>`), imagens (`<img>`), entre outros.

## 🔑 **Pontos-chave:**

- O HTML é uma linguagem de marcação que usa tags (elementos) para definir a estrutura e a apresentação do conteúdo da página.

- A estrutura básica começa com uma declaração `<!DOCTYPE>` seguida pela raiz `<html>`, cabeçalho `<head>` e corpo `<body>`.

- O cabeçalho `<head>` contém informações sobre o documento, enquanto o corpo `<body>` contém o conteúdo visível na página.

- Elementos de conteúdo, como parágrafos e listas, são usados para criar o conteúdo da página.

- Tags podem conter atributos para fornecer informações adicionais, como imagens de origem, links e classes para estilização.

## 👩‍🏫 **Exemplo:**

📌

```html
<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <title>Minha Página HTML</title>
    <link rel="stylesheet" href="styles.css">
    <script src="script.js"></script>
</head>
<body>
    <h1>Título Principal</h1>
    <p>Este é um parágrafo.</p>
    <ul>
        <li>Item 1</li>
        <li>Item 2</li>
    </ul>
    <img src="imagem.jpg" alt="Minha Imagem">
    <a href="https://www.exemplo.com">Visitar Exemplo</a>
</body>
</html>
```
📌
