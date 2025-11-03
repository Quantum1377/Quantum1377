<!-- README.md (CYBERPUNK — Tudo se mexendo) -->
<!-- FEITO PARA: AbnerAnanias -->
<!-- Cole este arquivo em: AbnerAnanias/AbnerAnanias -->

<!-- =========================
     BANNER PRINCIPAL (SVG - fundo pulsante + partículas)
   ========================= -->

<svg width="100%" height="260" viewBox="0 0 1200 260" preserveAspectRatio="none" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Banner Cyberpunk">
  <defs>
    <linearGradient id="neon" x1="0" x2="1">
      <stop offset="0%" stop-color="#ff4dff"/>
      <stop offset="40%" stop-color="#00e6ff"/>
      <stop offset="100%" stop-color="#00ff99"/>
    </linearGradient>
    <filter id="blurGlow">
      <feGaussianBlur stdDeviation="6" result="blur"/>
      <feMerge><feMergeNode in="blur"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>
    <pattern id="grid" width="40" height="40" patternUnits="userSpaceOnUse">
      <path d="M40 0 L0 0 0 40" stroke="#0b0b12" stroke-width="1"/>
    </pattern>
  </defs>

  <!-- fundo -->
  <rect width="1200" height="260" fill="#06050a" />
  <rect width="1200" height="260" fill="url(#grid)" opacity="0.05"/>

  <!-- partículas neon -->
  <g fill="none" stroke="url(#neon)" stroke-opacity="0.15" stroke-width="2">
    <path d="M0 170 C 200 140, 400 220, 600 170 S 1000 140, 1200 170">
      <animate attributeName="d" dur="9s" repeatCount="indefinite"
        values="
          M0 170 C200 140,400 220,600 170 S1000 140,1200 170;
          M0 150 C200 190,400 100,600 150 S1000 190,1200 150;
          M0 170 C200 140,400 220,600 170 S1000 140,1200 170"/>
    </path>
  </g>

  <!-- título com brilho e 'glitch' -->
  <g filter="url(#blurGlow)">
    <text x="56" y="88" font-family="Segoe UI, Roboto, Arial" font-size="44" font-weight="800" fill="#e9f4ff">
      ABNER ANANIAS
    </text>
    <text x="58" y="132" font-family="Consolas, 'Courier New', monospace" font-size="18" fill="#9ff">
      Engenheiro de Software • Web Full-Stack • Ciência da Computação
    </text>
  </g>

  <!-- Marquee de luzes -->
  <g transform="translate(0,190)">
    <rect x="0" y="0" width="1200" height="40" fill="#00000022"/>
    <text x="1200" y="28" font-family="monospace" font-size="18" fill="#ff66f0">
      <tspan>⚡ CYBERPUNK PORTFOLIO · ENGINEERING · OPEN SOURCE · AI · SYSTEMS · DEVOPS · UI/UX · PERFORMANCE</tspan>
      <animate attributeName="x" from="1200" to="-3200" dur="20s" repeatCount="indefinite" />
    </text>
  </g>

  <!-- partículas brilhantes -->
  <g>
    <circle cx="1060" cy="52" r="3" fill="#00e6ff">
      <animate attributeName="r" values="2;7;2" dur="2.5s" repeatCount="indefinite"/>
      <animate attributeName="cy" values="52;40;52" dur="3.2s" repeatCount="indefinite"/>
    </circle>
    <circle cx="1120" cy="118" r="2.5" fill="#ff4dff">
      <animate attributeName="r" values="2;9;2" dur="3s" repeatCount="indefinite"/>
    </circle>
  </g>
</svg>

---

<!-- =========================
     BADGES PISCANTES (shields.io)
   ========================= -->

<p>
  <img src="https://img.shields.io/badge/-JavaScript-111827?style=for-the-badge&logo=javascript&logoColor=F7DF1E" alt="JS" >
  <img src="https://img.shields.io/badge/-TypeScript-111827?style=for-the-badge&logo=typescript&logoColor=3178C6" alt="TS" >
  <img src="https://img.shields.io/badge/-React-111827?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React" >
  <img src="https://img.shields.io/badge/-Next.js-111827?style=for-the-badge&logo=next.js&logoColor=white" alt="Next" >
  <img src="https://img.shields.io/badge/-Node.js-111827?style=for-the-badge&logo=node.js&logoColor=339933" alt="Node">
  <img src="https://img.shields.io/badge/-Python-111827?style=for-the-badge&logo=python&logoColor=3776AB" alt="Python">
</p>

<!-- Badge pulsante (usando SVG embutido) -->
<svg width="100%" height="40" viewBox="0 0 900 40" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Pulsing badges">
  <rect x="0" y="0" width="900" height="40" fill="#07050a"/>
  <g font-family="Arial" font-size="14" fill="#fff">
    <rect x="12" y="8" rx="6" ry="6" width="140" height="24" fill="#1a0b2c">
      <animate attributeName="fill" values="#1a0b2c;#2a0044;#1a0b2c" dur="3s" repeatCount="indefinite"/>
    </rect>
    <text x="30" y="24" fill="#ff66f0">Cyberpunk • Everything Moves</text>

    <rect x="180" y="8" rx="6" ry="6" width="200" height="24" fill="#0b1a2c">
      <animate attributeName="fill" values="#0b1a2c;#00334d;#0b1a2c" dur="2.6s" repeatCount="indefinite"/>
    </rect>
    <text x="190" y="24" fill="#00f6ff">Full-Stack • Engenharia de Software</text>

    <rect x="400" y="8" rx="6" ry="6" width="240" height="24" fill="#0b1a20">
      <animate attributeName="fill" values="#0b1a20;#26002e;#0b1a20" dur="3.6s" repeatCount="indefinite"/>
    </rect>
    <text x="420" y="24" fill="#7dffb0">Ciência da Computação • Pesquisa</text>
  </g>
</svg>

---

## 🚀 Sobre mim (futurista)
<details>
<summary><strong>Olá — clique pra abrir</strong></summary>

```text
Olá! Eu sou o Abner Ananias — Engenheiro de Software e Desenvolvedor Full-Stack.
Transformo requisitos em sistemas escaláveis com UI que brilha. Estudo Ciência da Computação,
arquiteto backends resilientes, e adoro performance e design interativo.