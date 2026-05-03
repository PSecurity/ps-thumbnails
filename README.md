# 🎨 ps.editor v2.0 – Thumbnail Engine para TikTok & Redes

![version](https://img.shields.io/badge/version-2.0-purple?style=flat-square)
![platform](https://img.shields.io/badge/platform-Android%20%7C%20Termux%20%7C%20Kali%20%7C%20Web-green?style=flat-square)
![license](https://img.shields.io/badge/license-MIT-blue?style=flat-square)

> **Criado por Peek Security** – *"Fala rapaziada, suavidade?"*

Engine de renderização de thumbnails diretamente no navegador.
Sem Photoshop, sem apps pesados. **Apenas HTML, CSS e JavaScript puro.**

---

## 🔥 Destaques

- ✅ **Proporção 9:16** – exatamente o padrão **TikTok HD** (720x1280)
- ✅ **Editor em tempo real** – todas as informações atualizam instantaneamente
- ✅ **Temas dinâmicos** – Roxo, Verde, Vermelho, Azul (troca com 1 clique)
- ✅ **Fundo estilo Hacker** – grid e gradiente que acompanham o tema
- ✅ **Responsivo** – funciona no celular (rolagem horizontal) e no PC (lado a lado)
- ✅ **Download em HD** – gera PNG com qualidade 2x ou 3x
- ✅ **Leve e 100% offline** – roda localmente, sem depender de servidor

---

## 📱 Onde rodar?

- **Termux** (Android)
- **Kali Linux / Nethunter**
- **Qualquer navegador** (PC ou celular)
- **Servidor local** (Python, Apache, etc.)

---

## 🚀 Como usar

1. **Clone o repositório**

   ```bash
   git clone https://github.com/PSecurity/ps-thumbnails.git
   cd ps-thumbnails
   ```

2. Abra o arquivo index.html no navegador
   - No Termux: `python3 -m http.server 8080` e acesse `http://localhost:8080`
3. Edite os campos – todos os textos da thumbnail alteram em tempo real
4. Clique em "BAIXAR THUMBNAIL (PNG)" – a imagem será salva na sua pasta de downloads

---

## 🌐 Acesso Online

**Quer usar sem instalar nada?** Acesse direto no navegador:

🔗 **[ps.editor v2.0 – Live Demo](https://psecurity.github.io/ps-thumbnails/)**

Basta clicar e começar a criar suas thumbnails! 🎨

---

## 🎛️ O que você pode editar?

| Campo | Descrição |
|-------|-----------|
| URL Imagem Demo | Imagem de fundo (hacker asset) |
| Logo Parte 1 e 2 | Texto do cabeçalho |
| Tag Superior Dir. | Texto no canto superior direito |
| Etiqueta Título | Pequeno selo acima do título |
| Título Linha 1,2,3 | Bloco principal da thumb |
| Subtítulo Impacto | Texto verde em destaque |
| Badge 1 e 2 | Selos laterais |
| Terminal (Header, Comando, Logs, Status) | Bloco estilo terminal |
| Bullet 1 a 4 | Itens com ícones |
| Aviso Rodapé e CTA | Textos do rodapé |

---

## 🎨 Temas disponíveis

Clique nos botões circulares coloridos no topo do painel:

- 🟣 Roxo (padrão – Peek Security)
- 🟢 Verde (estilo Matrix)
- 🔴 Vermelho (alerta total)
- 🔵 Azul (modo noturno/blue team)

O fundo da página muda automaticamente junto com o tema!

---

## 🖥️ Layout responsivo

- Desktop (≥1500px) – editor e thumbnail lado a lado, mesma altura (1280px)
- Tablet / Telas médias (740px – 1499px) – blocos empilhados, cada um com 720px de largura
- Mobile (<740px) – rolagem horizontal para manter a thumb exata (sem distorção)

---

## 🧰 Personalização avançada

Quer mudar o tamanho da thumbnail?
Edite as variáveis CSS no início do index.html:

```css
.wrapper, #thumbnail {
  width: 720px;   /* altere aqui */
  height: 1280px; /* e aqui */
}
```

⚠️ Ajuste também as posições internas (.t-l1, .terminal, etc.) se mudar a proporção.

---

## 📦 Estrutura do projeto

```
ps-thumbnails/
├── index.html       # Ferramenta completa (CSS + HTML + JS)
├── README.md        # Este arquivo
└── (opcional) assets/
    └── suas-imagens.png
```

---

## 🧠 Tecnologias utilizadas

- HTML5
- CSS3 (Flexbox, Grid, animações, variáveis)
- JavaScript (Vanilla)
- html2canvas – renderização da thumb em PNG

---

## 👤 Créditos

Desenvolvido por Gilberto Martins (Peek Security)

- 🔗 [GitHub](https://github.com/PSecurity)
- 🔗 [TikTok](https://tiktok.com/@peeksecurity)
- 🔗 [Blog](https://psecurity.github.io/PSecurity/)

---

## 📄 Licença

MIT – sinta-se à vontade para usar, modificar e distribuir.
Só mantenha os créditos, combinado? 😉

---

## 🤝 Contribuições

Sugestões e melhorias são bem-vindas. Abra uma issue ou envie um pull request.

---

Fala rapaziada, baixa aí, customiza do seu jeito e faz a sua arte hacker.
Tamo junto, segue nos! 🚀