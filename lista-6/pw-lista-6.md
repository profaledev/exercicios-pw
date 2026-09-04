# Exercicio - 1 🌟 Atividade Prática – Página de Galeria Interativa 🎨📷

## 📚 Objetivo

Criar uma **galeria de imagens** usando **HTML e CSS puro**, aplicando:

* **Box Model**: `margin`, `padding`, `border`, `width`, `height`, `box-sizing`.
* **Display**: `block`, `inline-block`.
* **Float**: para organizar colunas e imagens lado a lado.

## 🔥 Desafio

1. **Estrutura da página**:

   * `<header>`: Título da galeria e menu horizontal (`Home | Sobre | Contato`).
   * `<section>`: Galeria de imagens dividida em **três colunas**, cada imagem com **legenda**.
   * `<aside>`: Barra lateral com **informações extras** ou **categorias de imagens**.
   * `<footer>`: Créditos e links de redes sociais.

2. **Box Model e Estética**:

   * Cada **imagem** deve estar dentro de uma **caixa** (`div`) com `padding`, `border` e `margin`.
   * Adicione **sombras** e **bordas arredondadas**.
   * Use cores de fundo diferentes para a galeria e a barra lateral.

3. **Float e Display**:

   * As imagens na galeria devem **flutuar lado a lado** (`float: left`) dentro de cada coluna.
   * As colunas devem usar `width` proporcional (ex.: 30% cada) com `margin` entre elas.
   * O `<aside>` deve usar `float: right` para ficar ao lado da galeria.
   * Limpe floats após as seções para evitar sobreposição.

4. **Interatividade visual**:

   * Adicione **hover effects**: aumentar a imagem, mudar a borda ou adicionar sombra.
   * Faça com que o texto da legenda apareça sobre a imagem ao passar o mouse, usando **positioning** (`relative`/`absolute`).

<!-- ## 💡 Dicas de Código

```css
.gallery-column {
  float: left;
  width: 30%;
  margin: 1.66%;
}

.gallery-item {
  margin-bottom: 20px;
  padding: 5px;
  border: 2px solid #ccc;
  border-radius: 8px;
  box-sizing: border-box;
  transition: transform 0.3s, box-shadow 0.3s;
}

.gallery-item:hover {
  transform: scale(1.05);
  box-shadow: 0 5px 15px rgba(0,0,0,0.3);
}

.clearfix::after {
  content: "";
  display: block;
  clear: both;
}

aside {
  float: right;
  width: 25%;
  padding: 10px;
  background-color: #f2f2f2;
  box-sizing: border-box;
}
``` -->

## 🏁 Elaboração

* Arquivos **HTML e CSS** separados.
* **Galeria com pelo menos 9 imagens** e **3 colunas**.
* Uso correto de **box model, float e display**.
* Adição de **interatividade visual** com hover.
* Barra lateral funcional com informações ou links.
* Layout organizado, proporcional e esteticamente agradável.





