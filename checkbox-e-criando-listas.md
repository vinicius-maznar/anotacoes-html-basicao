# 📝 Criar uma lista com **"checkbox"** 

## 🧙‍♀️ **Transformando em Lista:**

- Use várias tags `<input type="checkbox>` para criar uma lista de opções em seu formulário.

- Cada `<input type="checkbox>` deve ter um atributo `name` igual, indicando que eles fazem parte do mesmo grupo.

- Atribua valores diferentes ao atributo `value` de cada `<input type="checkbox>`, representando as opções da lista.

## ✉➡ **Envio da lista criada ao servidor:**

- A tag formulário deve ter o conter o seguinte atributo <form method="post"> para que o servidor possa receber os dados selecionados como uma lista contendo varios itens.

## 👩‍🏫 **Exemplo:**

- Criar uma lista em HTML com nomes de frutas utilizando a tag <input type="checkbox">:

```html
<form method="post">
  <input type="checkbox" name="frutas" value="maca"> Maçã
  <input type="checkbox" name="frutas" value="banana"> Banana
  <input type="checkbox" name="frutas" value="laranja"> Laranja
</form>
```
