# 🧺 Lavandaria Adelino Pressing

Landing page profissional para uma lavandaria localizada em **Panguila, Sector 3 (Luanda, Angola)**.  
O site apresenta os serviços, tabela de preços atualizada, processo de atendimento, formulário de orçamento com integração WhatsApp e um design elegante e responsivo.

![Preview do site](https://via.placeholder.com/1200x630?text=Lavandaria+Adelino+Pressing)

---

## 📌 Índice

- [Sobre o projeto](#sobre-o-projeto)
- [Tecnologias utilizadas](#tecnologias-utilizadas)
- [Funcionalidades](#funcionalidades)
- [Estrutura do projeto](#estrutura-do-projeto)
- [Como usar](#como-usar)
- [Personalização](#personalização)
- [Deploy](#deploy)
- [Licença](#licença)
- [Contacto](#contacto)

---

## 📖 Sobre o projeto

A **Lavandaria Adelino Pressing** é um estabelecimento especializado em lavagem a seco, pressing, engomagem e tratamento de tecidos delicados.  
Este site foi desenvolvido para:

- Apresentar os serviços e preços de forma clara e transparente.
- Permitir que os clientes solicitem orçamentos diretamente pelo WhatsApp.
- Reforçar a identidade visual da marca com um design moderno e acolhedor.

O projeto é **100% estático** e pode ser hospedado em qualquer serviço de hosting (Vercel, Netlify, GitHub Pages, etc.).

---

## 🚀 Tecnologias utilizadas

| Tecnologia | Descrição |
| :--- | :--- |
| **HTML5** | Estrutura semântica da página |
| **CSS3** | Estilização com variáveis, grid, flexbox e animações |
| **JavaScript (ES6)** | Comportamento interativo (loader, scroll, formulário, QR Code) |
| **[GSAP](https://greensock.com/gsap/)** | Animações suaves e efeitos de entrada |
| **[ScrollTrigger](https://greensock.com/scrolltrigger/)** | Animações controladas pelo scroll |
| **[QRCode.js](https://davidshimjs.github.io/qrcodejs/)** | Geração de QR Code para acesso rápido ao site |
| **Google Fonts** | DM Sans + Playfair Display |

---

## ✨ Funcionalidades

- ✅ **Loader animado** com barra de progresso.
- ✅ **Navegação fixa** com efeito de transparência ao scroll.
- ✅ **Hero section** com animação de tecido em canvas.
- ✅ **Marquee** com palavras‑chave dos serviços.
- ✅ **Tabela de preços** com 28 itens e informações adicionais (prazos, urgência, avisos).
- ✅ **Formulário de orçamento** com:
  - Seleção de serviços (checkboxes com preços).
  - Cálculo automático do total estimado.
  - Geração de mensagem personalizada para WhatsApp.
- ✅ **QR Code** no rodapé para acesso direto pelo telemóvel.
- ✅ **Cursor personalizado** (para desktop) com efeito de hover.
- ✅ **Design totalmente responsivo** (mobile, tablet, desktop).
- ✅ **Animações com GSAP** em todos os elementos principais.

---

## 📁 Estrutura do projeto

```
/
├── index.html          # Página principal (todo o código HTML, CSS e JS)
├── README.md           # Este ficheiro
└── (sem outras pastas, pois é uma página única)
```

O projeto é **monolítico** – todo o CSS e JavaScript estão inline no `index.html` para facilitar a hospedagem e o versionamento.

---

## 🔧 Como usar

### Pré‑requisitos
Apenas um navegador moderno (Chrome, Firefox, Edge, Safari).

### Instalação local

1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/lavandaria-adelino.git
   ```

2. Abra o ficheiro `index.html` no seu navegador:
   - Duplo clique no ficheiro, ou
   - Use uma extensão como **Live Server** no VS Code.

### Personalização rápida

- **Alterar número de WhatsApp**:  
  No `<a href="https://wa.me/244923456789"` e na função `sendToWhatsApp()` (variável `waNumber`).
- **Alterar cores**:  
  Edite as variáveis CSS no bloco `:root`.
- **Adicionar/remover serviços**:  
  Atualize a tabela de preços (`#pricing`) e os checkboxes do formulário.
- **Alterar textos e imagens**:  
  Edite diretamente no HTML.

---

## 🌐 Deploy

O site pode ser publicado gratuitamente em:

- **[Vercel](https://vercel.com/)** – recomendado (já está publicado em `https://lavandaria-adelino.vercel.app/`).
- **[Netlify](https://www.netlify.com/)**
- **[GitHub Pages](https://pages.github.com/)**

Basta fazer o upload do `index.html` ou ligar o repositório à plataforma.

---

## 📄 Licença

Este projeto está sob a licença **MIT**.  
Sinta‑se à vontade para usar, modificar e distribuir, desde que mantenha os créditos.

---

## 📞 Contacto

- **WhatsApp**: [+244 948 640 434](https://wa.me/244948640434)
- **Endereço**: Rua da Lavandaria, N° 123, Luanda – Angola
- **Site**: [https://lavandaria-adelino.vercel.app/](https://lavandaria-adelino.vercel.app/)

---

Desenvolvido com ❤️ para a **Lavandaria Adelino Pressing**.
