# Dominus Finance 💰

> Controle financeiro pessoal — PWA instalável, 100% offline, zero dependências de backend.

![Dominus Finance](https://img.shields.io/badge/PWA-Installable-FF1F3D?style=flat-square)
![License](https://img.shields.io/badge/License-MIT-1A1A1A?style=flat-square)

---

## ✨ Funcionalidades

- **Dashboard** com saldo total, receitas, despesas e últimas transações
- **Meta financeira** com barra de progresso dinâmica
- **Adicionar transações** (receita ou despesa) com categoria e data automática
- **Filtro por mês** e **busca por descrição**
- **Excluir transações** individualmente
- **Dados persistidos** no `localStorage` (sobrevivem ao fechar o navegador)
- **PWA instalável** — funciona como app no Android/iOS

---

## 🎨 Design

| Elemento   | Valor        |
|------------|-------------|
| Fundo      | `#0D0D0D`   |
| Cards      | `#1A1A1A`   |
| Destaque   | `#FF1F3D`   |
| Texto      | `#F5F5F5`   |
| Fonte display | Bebas Neue |
| Fonte body    | DM Sans    |

---

## 📁 Estrutura

```
dominus-finance/
├── index.html        ← App completo (HTML + CSS + JS)
├── manifest.json     ← Configuração PWA
├── service-worker.js ← Cache offline
├── icon-192.png      ← Ícone PWA (adicionar manualmente)
├── icon-512.png      ← Ícone PWA (adicionar manualmente)
└── README.md
```

---

## 🚀 Deploy (Vercel)

1. Suba a pasta no GitHub
2. Acesse [vercel.com](https://vercel.com) e importe o repositório
3. Clique em **Deploy** — sem configuração necessária

---

## 📱 Instalar no Celular

1. Abra o site no Chrome (Android) ou Safari (iOS)
2. Toque no menu `⋮` → **"Adicionar à tela inicial"**
3. Pronto — o app aparece como ícone na home!

> **Nota:** Adicione os ícones `icon-192.png` e `icon-512.png` à pasta raiz para que o ícone apareça corretamente. Você pode gerá-los em [favicon.io](https://favicon.io).

---

## 🛠️ Tecnologias

- HTML5 + JavaScript (vanilla, sem frameworks)
- [TailwindCSS](https://tailwindcss.com) via CDN
- [Bebas Neue](https://fonts.google.com/specimen/Bebas+Neue) + [DM Sans](https://fonts.google.com/specimen/DM+Sans) (Google Fonts)
- Service Worker API (PWA)
- localStorage (persistência)

---

MIT License — feito com ❤️
