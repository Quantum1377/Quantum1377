<!-- ========================== -->
<!--      ABNER README START     -->
<!-- ========================== -->

<div align="center">

  <!-- ABNER Typing + Glitch -->
  <h1 style="
    font-family: 'Courier New', monospace;
    font-size: 4em;
    color: #0ff;
    position: relative;
    animation: glitch 1s infinite, pulse 2s infinite;
  ">
    ABNER
  </h1>

  <!-- Botões Redes Sociais -->
  <p>
    <a href="https://github.com/Quantum1337" style="text-decoration:none;">
      <img src="https://img.shields.io/badge/GitHub-Quantum1337-%2300ffff?style=for-the-badge&logo=github&logoColor=white"/>
    </a>
    <a href="https://twitter.com/NewtonnnNI" style="text-decoration:none;">
      <img src="https://img.shields.io/badge/Twitter-NewtonnnNI-%231DA1F2?style=for-the-badge&logo=twitter&logoColor=white"/>
    </a>
    <a href="https://wa.me/5511976602720" style="text-decoration:none;">
      <img src="https://img.shields.io/badge/WhatsApp-Chat-%2325D366?style=for-the-badge&logo=whatsapp&logoColor=white"/>
    </a>
  </p>

  <!-- Linguagens que você domina -->
  <p class="badge-group">
    <img src="https://img.shields.io/badge/HTML5-%23E34F26?style=for-the-badge&logo=html5&logoColor=white"/>
    <img src="https://img.shields.io/badge/CSS3-%231572B6?style=for-the-badge&logo=css3&logoColor=white"/>
    <img src="https://img.shields.io/badge/JavaScript-%23F7DF1E?style=for-the-badge&logo=javascript&logoColor=black"/>
    <img src="https://img.shields.io/badge/Python-%233776AB?style=for-the-badge&logo=python&logoColor=white"/>
  </p>

  <!-- Sobre mim -->
  <pre style="
    background: rgba(0,0,0,0.85);
    padding: 20px;
    border-radius: 10px;
    color:#0ff;
    font-family: 'Courier New', monospace;
    font-size: 1em;
    animation: blink 1s infinite;
  ">
+ Olá, eu sou Abner
+ Especialista em Engenharia da Computação e Ciência da Computação
+ Desenvolvedor Full Stack & Freelancer
  </pre>

  <!-- Gráfico animado -->
  <div class="chart-container">
    <div class="chart-bar" style="--height:80%"></div>
    <div class="chart-bar" style="--height:60%"></div>
    <div class="chart-bar" style="--height:90%"></div>
    <div class="chart-bar" style="--height:50%"></div>
  </div>

  <!-- Cobrinha Animada (agora andando em volta do gráfico) -->
  <div class="snake-track">
    <div class="snake"></div>
  </div>

</div>

<!-- ========================== -->
<!--      ABNER README END       -->
<!-- ========================== -->

<style>
/* Glitch ABNER */
@keyframes glitch {
  0% { text-shadow: 2px 0 #f0f, -2px 0 #0ff; }
  20% { text-shadow: -2px 2px #f0f, 2px -2px #0ff; }
  40% { text-shadow: 2px -2px #f0f, -2px 2px #0ff; }
  60% { text-shadow: -2px 0 #f0f, 2px 0 #0ff; }
  80% { text-shadow: 2px 2px #f0f, -2px -2px #0ff; }
  100% { text-shadow: 0 0 #f0f, 0 0 #0ff; }
}

/* Pulsar cores do título */
@keyframes pulse {
  0%, 100% { color: #0ff; }
  50% { color: #f0f; }
}

/* Piscar texto Sobre Mim */
@keyframes blink {
  0%, 50%, 100% { opacity: 1; }
  25%, 75% { opacity: 0.3; }
}

/* Cobrinha andando */
@keyframes snakeMove {
  0% { left: -20px; top: 0; background: #0ff; }
  25% { background: #f0f; }
  50% { left: 280px; top: 0; background: #ff0; }
  75% { background: #f0f; }
  100% { left: -20px; top: 0; background: #0ff; }
}

/* Gráficos animados */
.chart-container {
  display: flex;
  justify-content: center;
  gap: 10px;
  margin: 20px auto;
  width: 300px;
  height: 100px;
  position: relative;
}
.chart-bar {
  width: 20px;
  background: linear-gradient(45deg,#0ff,#f0f,#ff0);
  border-radius: 5px;
  height: 0;
  animation: grow 2s forwards infinite alternate;
}
.chart-bar:nth-child(1) { animation-delay: 0s; }
.chart-bar:nth-child(2) { animation-delay: 0.3s; }
.chart-bar:nth-child(3) { animation-delay: 0.6s; }
.chart-bar:nth-child(4) { animation-delay: 0.9s; }
@keyframes grow {
  0% { height: 0; }
  100% { height: var(--height); }
}

/* Cobrinha andando em volta do gráfico */
.snake-track {
  width: 320px;
  height: 120px;
  position: relative;
  margin: 20px auto;
  border: 2px dashed #0ff;
  border-radius: 10px;
  overflow: hidden;
}
.snake {
  width: 20px;
  height: 20px;
  background: #0ff;
  border-radius: 50%;
  position: absolute;
  animation: snakeAround 4s linear infinite;
}
@keyframes snakeAround {
  0% { top: 0; left: 0; background: #0ff; }
  25% { top: 0; left: 300px; background: #f0f; }
  50% { top: 100px; left: 300px; background: #ff0; }
  75% { top: 100px; left: 0; background: #f0f; }
  100% { top: 0; left: 0; background: #0ff; }
}

/* Badges pulsantes */
.badge-group img {
  transition: transform 0.3s, filter 0.3s;
}
.badge-group img:hover {
  transform: scale(1.2) rotate(-5deg);
  filter: brightness(1.5);
}
</style>