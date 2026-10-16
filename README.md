# ArtesanaLÊ Torteria & Cia — Clone Completo

Este diretório contém a cópia 100% autônoma, independente e funcional do site:
`https://artesanale-torta-ateli.base44.app/`

---

## 📁 Estrutura dos Arquivos

```text
artesanale-clone/
├── index.html        # Página principal completa com todos os textos, cardápio e interações
├── style.css         # Folha de estilos compilada com design tokens, tipografia e cores
├── images/           # Todas as imagens em alta resolução baixadas localmente
│   ├── hero.jpg
│   ├── caprese.jpg
│   ├── mousse.jpg
│   ├── tortelete.jpg
│   ├── lasanha.jpg
│   ├── atelier.jpg
│   ├── flatlay.jpg
│   └── logo.png
└── README.md         # Instruções de uso e personalização
```

---

## 🚀 Como Executar Localmente

### Opção 1: Direto no Navegador
Basta dar um duplo clique no arquivo `index.html` para abrir diretamente no seu navegador (Chrome, Safari, Edge, Firefox).

### Opção 2: Servidor Local (Recomendado)
Para testar como se estivesse em produção:
```bash
# Com Python 3:
python3 -m http.server 8080

# Ou com Node.js:
npx serve .
```
Em seguida, acesse no navegador: `http://localhost:8080`

---

## 🌐 Como Publicar / Hospedar Gratuitamente

Você pode hospedar essa pasta em qualquer provedor de páginas estáticas:

1. **Vercel:**
   - Arraste a pasta `artesanale-clone` no dashboard da Vercel ou instale o CLI (`npm i -g vercel && vercel`).
2. **Netlify:**
   - Basta arrastar e soltar a pasta `artesanale-clone` em [app.netlify.com/drop](https://app.netlify.com/drop).
3. **GitHub Pages:**
   - Suba para um repositório no GitHub e ative o GitHub Pages nas configurações.
4. **Qualquer Hospedagem Tradicional (cPanel, Hostinger, Locaweb, etc.):**
   - Envie os arquivos para a pasta `public_html`.

---

## ✏️ Como Personalizar

* **WhatsApp / Telefone:**
  No arquivo `index.html`, procure por `5519991975629` e substitua pelo seu número com DDD (ex: `5511999999999`).
* **Itens do Cardápio:**
  No final do `index.html`, localize o array `menuData` no `<script>` e adicione, remova ou altere as categorias e itens de acordo com o seu negócio.
* **Fotos dos Produtos:**
  Basta substituir os arquivos dentro da pasta `images/` mantendo os mesmos nomes, ou alterar os caminhos `src="images/..."` no `index.html`.
* **Avaliações do Google:**
  No script do `index.html`, edite a lista `testimonials`.
