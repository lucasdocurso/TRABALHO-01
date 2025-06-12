# 🥗 LMF Hortifruti

Site responsivo de hortifrúti feito com HTML5, CSS3 (Flexbox) e JavaScript leve — sem frameworks. Apresenta produtos, contato e animações sutis.

---

## 🔧 Tecnologias
- HTML5
- CSS3 (Flexbox, media queries, custom scroll e animações)

---

## 📁 Estrutura do Projeto

├─ index.html ← Home (banner, descrição)

├─ produtos.html ← Catálogo de produtos (grid/carrossel)

├─ contato.html ← Sobre + formulário de contato

├─ css/
│ └─ produtosstyle.css

├─ js/
│ └─ menu-toggle.js
└─ img/
└─ img1.png, img2.png


---

## 🚀 Funcionalidades Principais
- Cabeçalho fixo com logo e menu responsivo (desktop/mobile)
- Carrossel horizontal de produtos responsivo e visual
- Cards com imagens, nome, preço, estoque e hover interativo
- Botões CTA estilizados com hover
- Animações (ex: efeito *pulse* em títulos)
- Acessibilidade: `aria-expanded`, `tabindex`, navegação por teclado

---

## 📱 Responsividade
- **Mobile (≤600px):** cards em largura total
- **Tablet (≤900px):** 2 colunas com `flex-wrap`
- **Desktop:** 3 colunas sem scroll lateral

---

## 🛠️ Como Rodar
1. Clone o repositório:
   ```bash
   git clone https://github.com/usuario/lmf-hortifruti.git
