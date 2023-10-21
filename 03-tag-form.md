# 🔰⚠ Tag `<form>` em HTML

## 🛠 **Funcionalidade:**

- A tag `<form>` é usada para criar um formulário em uma página web. Ela define uma seção na página onde os usuários podem inserir e enviar dados para serem processados pelo servidor.

## 🧩 **Principais Atributos:**

- `action`: Define o URL para o qual os dados do formulário serão enviados quando o usuário o submeter. Esse URL é geralmente uma página no servidor que processará os dados.
- `method`: Especifica o método de envio dos dados. Os valores comuns são "GET" (anexa os dados à URL) e "POST" (envia os dados no corpo da solicitação).

## 🔌 **Elementos Relacionados:**

- Dentro de um formulário, você pode usar vários elementos, incluindo:
  - `<input>`: Para criar campos de entrada de texto, senhas, caixas de seleção, botões de opção, entre outros.
  - `<textarea>`: Para criar áreas de texto multi-linhas.
  - `<select>`: Para criar menus suspensos.
  - `<button>`: Para criar botões de envio e redefinição do formulário, entre outros.

## 👩‍🏫 **Exemplo Básico:**

📌

```html
<form action="/processar-dados" method="POST">
  <label for="nome">Nome:</label>
  <input type="text" id="nome" name="nome" required>

  <label for="email">Email:</label>
  <input type="email" id="email" name="email" required>

  <button type="submit">Enviar</button>
</form>
```

📌
