# README - Página Tributo ao LeBron James

## 📖 Sobre o Projeto

Este projeto é uma página web desenvolvida em **HTML5** e **CSS3** dedicada ao jogador de basquete LeBron James, conhecido como **King James**.

A página apresenta:

* Uma introdução sobre quem é LeBron James
* Sua história e primeiros anos
* Conquistas e legado
* Inspiração para o futuro

O objetivo do projeto é praticar conceitos de estruturação de páginas web e estilização moderna utilizando apenas HTML e CSS.

---

## 🚀 Tecnologias Utilizadas

* HTML
* CSS
  
---

## 🎨 Design da Página

O site utiliza um visual moderno com tema inspirado nas cores associadas ao LeBron James:

* 🟣 Roxo
* 🟡 Dourado
* ⚫ Preto

### Recursos visuais aplicados:

* Gradientes
* Hover effects
* Sombras
* Responsividade básica
* Imagens ilustrativas
* Cards estilizados

---

## 📂 Estrutura do Projeto

```bash
📁 projeto-lebron
 ├── index.html
 └── README.md
```

---

## 🧠 Explicação do Código

### 1. Estrutura HTML

O HTML organiza o conteúdo da página em:

* `<header>` → Banner principal e título
* `<section>` → Informações sobre LeBron
* `<footer>` → Mensagem final inspiradora

Cada seção possui:

* Uma imagem
* Um título (`h2`)
* Um parágrafo descritivo

---

### 2. Estilização CSS

O CSS foi utilizado para criar:

### ✅ Variáveis de Cor

```css
:root {
   --black: #080808;
   --gold: #C9A84C;
   --purple: #7C3AED;
}
```

Essas variáveis facilitam a manutenção e organização das cores.

---

### ✅ Layout Centralizado

```css
main {
   max-width: 900px;
   margin: 0 auto;
}
```

O conteúdo fica centralizado na tela.

---

### ✅ Efeitos Visuais

#### Hover nas seções:

```css
section:hover {
   border-color: var(--purple);
}
```

#### Zoom nas imagens:

```css
section img:hover {
   transform: scale(1.02);
}
```

Esses efeitos deixam a página mais interativa.

---

### ✅ Gradiente nos Títulos

```css
background: linear-gradient(...)
```

Os títulos possuem um efeito de cor degradê dourado e roxo.

---

## 📱 Responsividade

A página possui adaptação básica para diferentes tamanhos de tela através da meta tag:

```html
<meta name="viewport" content="width=device-width, initial-scale=1.0">
```

---

## ▶️ Como Executar o Projeto

1. Baixe ou clone este repositório:

```bash
git clone https://github.com/seu-usuario/seu-repositorio.git
```

2. Abra o arquivo:

```bash
index.html
```

em qualquer navegador.

---

## 📸 Prévia do Projeto

O site contém:

* Banner principal
* Seções informativas
* Imagens estilizadas
* Rodapé motivacional

---

## 📚 Objetivos de Aprendizado

Este projeto foi criado para praticar:

* Estruturação HTML
* Estilização com CSS
* Uso de variáveis CSS
* Flexibilidade visual
* Design moderno
* Organização de código

---

## 👑 Inspiração

Projeto inspirado na trajetória de LeBron James, um dos maiores jogadores da história do basquete.

---

## 📄 Licença

Este projeto é apenas para fins educacionais.
