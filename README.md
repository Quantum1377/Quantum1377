<!-- README.md — Perfil Exagerado e Animado para AbnerAnanias -->
<!-- Substitua YOUR_GITHUB_USERNAME pelo seu username se necessário -->

<!-- ==========================
     CABEÇALHO ANIMADO (SVG)
   ========================== -->

<svg width="100%" height="220" viewBox="0 0 1200 220" preserveAspectRatio="none" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Banner animado">
  <defs>
    <linearGradient id="g1" x1="0" x2="1" y1="0" y2="1">
      <stop offset="0%" stop-color="#00F5A0"/>
      <stop offset="50%" stop-color="#00C2FF"/>
      <stop offset="100%" stop-color="#C800FF"/>
    </linearGradient>
    <filter id="glow">
      <feGaussianBlur stdDeviation="8" result="coloredBlur"/>
      <feMerge>
        <feMergeNode in="coloredBlur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>
  </defs>

  <rect width="1200" height="220" fill="#010114"/>
  <!-- Fundo dinâmico -->
  <g fill="none" stroke="url(#g1)" stroke-opacity="0.18">
    <path d="M0 120 C 200 60, 400 180, 600 120 S 1000 60, 1200 120" stroke-width="3">
      <animate attributeName="d" dur="8s" repeatCount="indefinite"
        values="
          M0 120 C 200 60, 400 180, 600 120 S 1000 60, 1200 120;
          M0 100 C 200 140, 400 40, 600 100 S 1000 140, 1200 100;
          M0 120 C 200 60, 400 180, 600 120 S 1000 60, 1200 120"/>
    </path>
  </g>

  <!-- Título grande com brilho -->
  <text x="48" y="90" font-family="Segoe UI, Roboto, Arial" font-size="44" fill="white" font-weight="700" filter="url(#glow)">
    Abner Ananias — Engenharia de Software • Full-Stack
  </text>

  <!-- Texto futurista digitando (SVG text + animate) -->
  <text x="50" y="140" font-family="Consolas, 'Courier New', monospace" font-size="20" fill="#BFE9FF">
    <tspan id="t1">Criando sistemas robustos · Ciência da Computação · Web Full-Stack</tspan>
    <animate xlink:href="#t1" attributeName="opacity" from="0.2" to="1" dur="1.5s" begin="0s" fill="freeze" />
    <animate attributeName="x" from="50" to="50" dur="1s" begin="0s" fill="freeze"/>
  </text>

  <!-- Partículas neon -->
  <g>
    <circle cx="1080" cy="30" r="3" fill="#00C2FF" >
      <animate attributeName="r" values="2;6;2" dur="2s" repeatCount="indefinite" />
      <animate attributeName="cy" values="30;20;30" dur="3s" repeatCount="indefinite" />
    </circle>
    <circle cx="1120" cy="80" r="2.5" fill="#C800FF">
      <animate attributeName="r" values="2;7;2" dur="2.2s" repeatCount="indefinite" />
    </circle>
  </g>
</svg>

<!-- ==========================
     Badges coloridos & animados
   ========================== -->

<p align="left">
  <!-- Tech badges (shields.io - dinâmicos) -->
  <img alt="JavaScript" src="https://img.shields.io/badge/-JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E" />
  <img alt="TypeScript" src="https://img.shields.io/badge/-TypeScript-323330?style=for-the-badge&logo=typescript&logoColor=3178C6" />
  <img alt="Node" src="https://img.shields.io/badge/-Node.js-333?style=for-the-badge&logo=node.js&logoColor=339933" />
  <img alt="React" src="https://img.shields.io/badge/-React-323330?style=for-the-badge&logo=react&logoColor=61DAFB" />
  <img alt="Next.js" src="https://img.shields.io/badge/-Next.js-323330?style=for-the-badge&logo=next.js&logoColor=white" />
  <img alt="Python" src="https://img.shields.io/badge/-Python-323330?style=for-the-badge&logo=python&logoColor=3776AB" />
  <img alt="PHP" src="https://img.shields.io/badge/-PHP-323330?style=for-the-badge&logo=php&logoColor=777BB4" />
  <img alt="C#" src="https://img.shields.io/badge/-C%23-323330?style=for-the-badge&logo=c-sharp&logoColor=239120" />
  <img alt="SQL" src="https://img.shields.io/badge/-SQL-323330?style=for-the-badge&logo=postgresql&logoColor=4169E1" />
</p>

---

## 🚀 Sobre mim
<details open>
<summary><strong>Resumo (clique para expandir)</strong></summary>

Olá! Eu sou o **Abner** — Desenvolvedor Web Full-Stack e Engenheiro de Software.  
Gosto de construir experiências digitais escaláveis, desde APIs rápidas até interfaces que encantam. Estudo Ciência da Computação e sempre busco combinar **engenharia sólida** com **design interativo**.

**Áreas de foco:** Engenharia de Software, Web Full-Stack, Arquitetura de Sistemas, DevOps básico, performance, segurança e UX.  
</details>

---

## 🎯 Perfil tecnológico (animado)
<!-- Skill bars em SVG (animação de largura) -->
<svg width="100%" height="220" viewBox="0 0 1000 220" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Skills">
  <style>
    /* Não confie em estilos complexos — a animação SMIL é usada para as barras */
  </style>

  <!-- Labels -->
  <text x="40" y="40" font-family="Inter, Arial" font-size="16" fill="#BFE9FF">JavaScript</text>
  <rect x="150" y="28" width="700" height="16" rx="8" fill="#222" />
  <rect x="150" y="28" width="0" height="16" rx="8" fill="#FFDC64">
    <animate attributeName="width" from="0" to="680" dur="1.6s" begin="0.2s" fill="freeze" />
  </rect>

  <text x="40" y="80" font-family="Inter, Arial" font-size="16" fill="#BFE9FF">TypeScript / React</text>
  <rect x="150" y="68" width="700" height="16" rx="8" fill="#222" />
  <rect x="150" y="68" width="0" height="16" rx="8" fill="#61DAFB">
    <animate attributeName="width" from="0" to="640" dur="1.7s" begin="0.4s" fill="freeze" />
  </rect>

  <text x="40" y="120" font-family="Inter, Arial" font-size="16" fill="#BFE9FF">Node.js / Backend</text>
  <rect x="150" y="108" width="700" height="16" rx="8" fill="#222" />
  <rect x="150" y="108" width="0" height="16" rx="8" fill="#3C873A">
    <animate attributeName="width" from="0" to="620" dur="1.8s" begin="0.6s" fill="freeze" />
  </rect>

  <text x="40" y="160" font-family="Inter, Arial" font-size="16" fill="#BFE9FF">Python / Ciência da Computação</text>
  <rect x="150" y="148" width="700" height="16" rx="8" fill="#222" />
  <rect x="150" y="148" width="0" height="16" rx="8" fill="#306998">
    <animate attributeName="width" from="0" to="520" dur="1.9s" begin="0.8s" fill="freeze" />
  </rect>
</svg>

---

## 📈 GitHub Stats (gráficos dinâmicos)
<!-- Estes cards puxam imagens de serviços (funcionam direto no README). Substitua o username se necessário. -->
<p>
  <img align="left" src="https://github-readme-stats.vercel.app/api?username=YOUR_GITHUB_USERNAME&show_icons=true&theme=radical&hide_border=true" alt="GitHub Stats" />
  <img align="right" src="https://github-readme-stats.vercel.app/api/top-langs/?username=YOUR_GITHUB_USERNAME&layout=compact&theme=radical&hide_border=true" alt="Top Languages" />
</p>
<div style="clear: both;"></div>

> Dica: se quiser o modo *verbose* nos stats (com streaks e stats mais detalhados), me pede que eu adiciono variações com `hide`/`theme`/`card_width` e etc.

---

## 🔁 Atividade Recente (falso feed animado)
<details>
<summary><strong>Últimos commits & projetos (visual)</strong></summary>

<!-- Feed falso / estilizado com ícones animados via emoji -->
- ✨ **Projeto:** `grand-portfolio` — Nova UI animada (Recentemente)
- 🛠️ **Projeto:** `payments-platform` — API & integração de pagamentos
- 🚀 **Projeto:** `race-sim-tools` — Mini utilitário para simuladores (experimentais)
- 📦 **Publicação:** `npm` package (beta) — `abner-utils`

</details>

---

## ★ Projetos em Destaque
> Pequenas cards com descrição curta. Substitua links e descrições conforme quiser.

| Projeto | Descrição | Tech |
|---|---:|---|
| [grand-portfolio](https://github.com/YOUR_GITHUB_USERNAME/grand-portfolio) | Portfólio pessoal — UI animada, SSR, PWA. | Next.js · TypeScript · Tailwind |
| [payments-platform](https://github.com/YOUR_GITHUB_USERNAME/payments-platform) | Plataforma de pagamentos (demo). | Node.js · Express · PostgreSQL |
| [race-sim-tools](https://github.com/YOUR_GITHUB_USERNAME/race-sim-tools) | Ferramentas para simuladores (telemetria). | Python · Flask |

---

## 📬 Contato & Redes
<p>
  <a href="mailto:seu-email@exemplo.com"><img src="https://img.shields.io/badge/-Email-323330?style=for-the-badge&logo=gmail&logoColor=white" /></a>
  <a href="https://www.linkedin.com/in/YOUR_LINKEDIN"><img src="https://img.shields.io/badge/-LinkedIn-323330?style=for-the-badge&logo=linkedin&logoColor=0A66C2" /></a>
  <a href="https://twitter.com/YOUR_TWITTER"><img src="https://img.shields.io/badge/-Twitter-323330?style=for-the-badge&logo=twitter&logoColor=1DA1F2" /></a>
  <a href="https://www.instagram.com/YOUR_INSTAGRAM"><img src="https://img.shields.io/badge/-Instagram-323330?style=for-the-badge&logo=instagram&logoColor=E1306C" /></a>
  <a href="https://discord.gg/YOUR_DISCORD"><img src="https://img.shields.io/badge/-Discord-323330?style=for-the-badge&logo=discord&logoColor=7289DA" /></a>
</p>

---

## ✨ Extras — Easter eggs animados
- Barras de progresso animadas, badges que piscam, e SVGs com tipografia futurista já incluídas.  
- Quer inserir um **GIF animado** maior (ex.: demo do seu app) ou um vídeo? Posso gerar a tag e instruções para hospedar no GitHub Pages ou em uma CDN.

---

## ❗ Como personalizar rápido
1. Substitua `YOUR_GITHUB_USERNAME` por `AbnerAnanias` (ou seu username real).  
2. Atualize os links dos projetos e redes.  
3. Se quiser que eu **já coloque seu username** em tudo e gere o README final pronto com `AbnerAnanias` no lugar, eu faço agora (sem pedir nada mais) — quer que eu substitua tudo por `AbnerAnanias` e te entregue o README já pronto?

---

## 🧩 Observações finais
- Este README é **muito exagerado** por design — ideal para chamar atenção.  
- Algumas empresas preferem algo mais sóbrio; se você quiser duas versões (exagerada e minimal), eu gero a segunda.  
- Posso também gerar **assets (SVG/GIF)** separados para usar em Issues, PR templates, ou no seu site pessoal.

---

Se quiser que eu **já coloque seu username `AbnerAnanias`** nos cards e gere o README final já com essas substituições, eu já faço agora e te retorno o arquivo pronto. Quer que eu substitua tudo por `AbnerAnanias` e finalize o README? 😎🔥