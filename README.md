<!-- ========================== -->
<!--      ABRN README START      -->
<!-- ========================== -->

<div align="center">

  <!-- ABRN Typing + Glitch -->
  <h1 style="
    font-family: 'Courier New', monospace;
    font-size: 4em;
    color: #0ff;
    position: relative;
    animation: glitch 1s infinite;
  ">
    ABRN
  </h1>

  <svg width="0" height="0">
    <defs>
      <filter id="glitch">
        <feColorMatrix in="SourceGraphic" type="matrix"
          values="1 0 0 0 0
                  0 1 0 0 0
                  0 0 1 0 0
                  0 0 0 1 0"/>
      </filter>
    </defs>
  </svg>

  <!-- Animated Neon Cobras -->
  <div style="display:flex; justify-content:center; gap:20px; margin:20px;">
    <div style="width:100px; height:100px; border-radius:50%; border: 4px solid #0ff; box-shadow: 0 0 10px #0ff; animation: snake 2s infinite;"></div>
    <div style="width:100px; height:100px; border-radius:50%; border: 4px solid #f0f; box-shadow: 0 0 10px #f0f; animation: snake 2.2s infinite;"></div>
    <div style="width:100px; height:100px; border-radius:50%; border: 4px solid #ff0; box-shadow: 0 0 10px #ff0; animation: snake 2.5s infinite;"></div>
  </div>

  <!-- Terminal Sobre Mim -->
  <pre style="
    background: rgba(0,0,0,0.8);
    padding: 20px;
    border-radius: 10px;
    color:#0ff;
    font-family: 'Courier New', monospace;
    font-size: 1em;
    animation: blink 1s infinite;
  ">
+ Olá, eu sou ABRN
+ Desenvolvedor Full Stack & Freelancer
+ Crio soluções personalizadas para comércios
- ⚠️ Este README é Cyberpunk Ultra Animado
  </pre>

  <!-- Badges -->
  <p>
    <a href="https://github.com/Quantum1337">
      <img src="https://img.shields.io/badge/GitHub-Quantum1337-%2300ffff?style=for-the-badge&logo=github&logoColor=black&labelColor=111111"/>
    </a>
    <a href="https://twitter.com/NewtonnnNI">
      <img src="https://img.shields.io/badge/Twitter-NewtonnnNI-%2300ffff?style=for-the-badge&logo=twitter&logoColor=black&labelColor=111111"/>
    </a>
    <a href="https://wa.me/5511976602720">
      <img src="https://img.shields.io/badge/WhatsApp-Chat-%2300ffff?style=for-the-badge&logo=whatsapp&logoColor=black&labelColor=111111"/>
    </a>
  </p>

  <!-- Stats -->
  <img src="https://github-readme-stats.vercel.app/api?username=Quantum1337&show_icons=true&theme=tokyonight" alt="ABRN GitHub Stats" style="margin:20px;"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Quantum1337&layout=compact&theme=tokyonight" alt="ABRN Top Languages"/>

</div>

<!-- CSS Animations -->
<style>
@keyframes glitch {
  0% { text-shadow: 2px 0 #f0f, -2px 0 #0ff; }
  20% { text-shadow: -2px 2px #f0f, 2px -2px #0ff; }
  40% { text-shadow: 2px -2px #f0f, -2px 2px #0ff; }
  60% { text-shadow: -2px 0 #f0f, 2px 0 #0ff; }
  80% { text-shadow: 2px 2px #f0f, -2px -2px #0ff; }
  100% { text-shadow: 0 0 #f0f, 0 0 #0ff; }
}

@keyframes snake {
  0% { transform: translateY(0) rotate(0deg); }
  50% { transform: translateY(-20px) rotate(180deg); }
  100% { transform: translateY(0) rotate(360deg); }
}

@keyframes blink {
  0%, 50%, 100% { opacity: 1; }
  25%, 75% { opacity: 0.3; }
}
</style>

<!-- ========================== -->
<!--      ABRN README END        -->
<!-- ========================== -->