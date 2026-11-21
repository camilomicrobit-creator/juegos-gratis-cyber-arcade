<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no" />
  <title>Cyber Neon Arcade Hub 2077 | Juegos Gratis Online HTML5</title>
  <meta name="description" content="Juega gratis online a Cyber Snake 2077, Cyber Pong 2077, Cyber Brick Breaker 2077 y Cyber Runner 2077. Minijuegos arcade retro estilo neón y cyberpunk directamente en tu navegador sin descargar." />
  <meta name="keywords" content="juegos gratis, juegos arcade online, cyber snake 2077, cyber pong 2077, cyber brick breaker, cyber runner, juegos html5, juegos retro neon" />
  <meta name="robots" content="index, follow" />
  
  <!-- Open Graph / Redes Sociales -->
  <meta property="og:title" content="Cyber Neon Arcade Hub 2077 - Juegos Gratis" />
  <meta property="og:description" content="Colección de 4 minijuegos arcade retro estilo cyberpunk en HTML5. ¡Juega gratis en navegador o celular!" />
  <meta property="og:type" content="website" />

  <!-- Datos Estructurados Schema.org para Google -->
  <script type="application/ld+json">
  {
    "@context": "https://schema.org",
    "@type": "VideoGame",
    "name": "Cyber Neon Arcade Hub 2077",
    "description": "Plataforma gratuita de 4 minijuegos arcade retro con estética neón y cyberpunk: Cyber Snake, Cyber Pong, Cyber Brick Breaker y Cyber Runner.",
    "genre": ["Arcade", "Retro", "Action"],
    "playMode": "SinglePlayer",
    "applicationCategory": "Game",
    "operatingSystem": "Web Browser",
    "offers": {
      "@type": "Offer",
      "price": "0",
      "priceCurrency": "USD"
    }
  }
  </script>

  <style>
    :root {
      --bg-dark: #07070f;
      --panel-bg: #0f1123;
      --neon-cyan: #00f3ff;
      --neon-pink: #ff007f;
      --neon-green: #39ff14;
      --neon-yellow: #ffe600;
      --text-main: #e2e8f0;
    }

    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
      user-select: none;
      -webkit-user-select: none;
    }

    body {
      background-color: var(--bg-dark);
      color: var(--text-main);
      font-family: 'Segoe UI', Roboto, Helvetica, Arial, sans-serif;
      display: flex;
      flex-direction: column;
      align-items: center;
      min-height: 100vh;
      overflow-x: hidden;
    }

    header {
      width: 100%;
      max-width: 800px;
      padding: 16px 20px;
      display: flex;
      justify-content: space-between;
      align-items: center;
      border-bottom: 1px solid rgba(0, 243, 255, 0.25);
      background: rgba(15, 17, 35, 0.9);
    }

    h1 {
      font-size: 1.3rem;
      letter-spacing: 2px;
      text-transform: uppercase;
      color: var(--neon-cyan);
      text-shadow: 0 0 10px rgba(0, 243, 255, 0.7);
    }

    .btn-menu {
      background: transparent;
      border: 1px solid var(--neon-pink);
      color: var(--neon-pink);
      padding: 6px 14px;
      font-weight: bold;
      border-radius: 4px;
      cursor: pointer;
      text-transform: uppercase;
      font-size: 0.85rem;
      box-shadow: 0 0 8px rgba(255, 0, 127, 0.3);
      transition: all 0.2s;
      display: none;
    }

    .btn-menu:hover {
      background: var(--neon-pink);
      color: #fff;
      box-shadow: 0 0 15px var(--neon-pink);
    }

    /* Hub Grid */
    #hub-screen {
      width: 100%;
      max-width: 800px;
      padding: 25px 20px;
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
      gap: 20px;
    }

    .game-card {
      background: var(--panel-bg);
      border: 1px solid rgba(0, 243, 255, 0.3);
      border-radius: 10px;
      padding: 20px;
      display: flex;
      flex-direction: column;
      justify-content: space-between;
      transition: transform 0.2s, box-shadow 0.2s;
      cursor: pointer;
      position: relative;
      overflow: hidden;
    }

    .game-card:hover {
      transform: translateY(-4px);
      border-color: var(--neon-cyan);
      box-shadow: 0 0 20px rgba(0, 243, 255, 0.3);
    }

    .game-card h2 {
      font-size: 1.25rem;
      margin-bottom: 8px;
      color: var(--neon-cyan);
    }

    .game-card p {
      font-size: 0.9rem;
      color: #94a3b8;
      margin-bottom: 16px;
      line-height: 1.4;
    }

    .card-footer {
      display: flex;
      justify-content: space-between;
      align-items: center;
      border-top: 1px solid rgba(255, 255, 255, 0.08);
      padding-top: 12px;
      font-size: 0.85rem;
    }

    .high-score {
      color: var(--neon-yellow);
      font-weight: bold;
    }

    .play-badge {
      background: rgba(0, 243, 255, 0.15);
      color: var(--neon-cyan);
      padding: 4px 10px;
      border-radius: 4px;
      font-weight: bold;
    }

    /* Game Screen */
    #game-screen {
      display: none;
      flex-direction: column;
      align-items: center;
      width: 100%;
      max-width: 800px;
      padding: 15px;
    }

    .hud {
      width: 100%;
      max-width: 480px;
      display: flex;
      justify-content: space-between;
      margin-bottom: 10px;
      font-size: 1rem;
      font-weight: bold;
      color: var(--neon-green);
      text-shadow: 0 0 6px rgba(57, 255, 20, 0.5);
    }

    canvas {
      background: #04040a;
      border: 2px solid var(--neon-cyan);
      box-shadow: 0 0 20px rgba(0, 243, 255, 0.25);
      border-radius: 6px;
      max-width: 100%;
      touch-action: none;
    }

    .controls-hint {
      margin-top: 10px;
      font-size: 0.85rem;
      color: #94a3b8;
      text-align: center;
    }

    /* Touch D-Pad */
    .touch-controls {
      margin-top: 15px;
      display: grid;
      grid-template-columns: repeat(3, 60px);
      grid-template-rows: repeat(2, 55px);
      gap: 8px;
      justify-content: center;
    }

    .touch-btn {
      background: rgba(0, 243, 255, 0.12);
      border: 1px solid var(--neon-cyan);
      color: var(--neon-cyan);
      font-size: 1.3rem;
      border-radius: 8px;
      display: flex;
      align-items: center;
      justify-content: center;
      cursor: pointer;
    }

    .touch-btn:active {
      background: var(--neon-cyan);
      color: #000;
    }

    .up { grid-column: 2; grid-row: 1; }
    .left { grid-column: 1; grid-row: 2; }
    .down { grid-column: 2; grid-row: 2; }
    .right { grid-column: 3; grid-row: 2; }
  </style>
</head>
<body>

  <header>
    <h1>⚡ CYBER ARCADE 2077</h1>
    <button id="btn-back" class="btn-menu" onclick="returnToMenu()">◄ MENÚ</button>
  </header>

  <main id="hub-screen">
    <div class="game-card" onclick="startGame('snake')">
      <div>
        <h2>🐍 Cyber Snake 2077</h2>
        <p>Deslízate por la red digital, absorbe nodos de energía neón y evita chocar contra tu propia estela.</p>
      </div>
      <div class="card-footer">
        <span class="high-score">RÉCORD: <span id="score-snake">0</span></span>
        <span class="play-badge">JUGAR ►</span>
      </div>
    </div>

    <div class="game-card" onclick="startGame('pong')">
      <div>
        <h2>🏓 Cyber Pong 2077</h2>
        <p>Duelo clásico de reflejos cibernéticos contra la IA. Supera su defensa con disparos acelerados.</p>
      </div>
      <div class="card-footer">
        <span class="high-score">RÉCORD: <span id="score-pong">0</span></span>
        <span class="play-badge">JUGAR ►</span>
      </div>
    </div>

    <div class="game-card" onclick="startGame('brick')">
      <div>
        <h2>🧱 Cyber Brick Breaker</h2>
        <p>Destruye el cortafuegos de bloques luminosos rebotando el pulso de energía sin dejarlo caer.</p>
      </div>
      <div class="card-footer">
        <span class="high-score">RÉCORD: <span id="score-brick">0</span></span>
        <span class="play-badge">JUGAR ►</span>
      </div>
    </div>

    <div class="game-card" onclick="startGame('runner')">
      <div>
        <h2>🏃 Cyber Runner 2077</h2>
        <p>Corre a toda velocidad por la autopista de datos y salta sobre las barreras láser.</p>
      </div>
      <div class="card-footer">
        <span class="high-score">RÉCORD: <span id="score-runner">0</span></span>
        <span class="play-badge">JUGAR ►</span>
      </div>
    </div>
  </main>

  <section id="game-screen">
    <div class="hud">
      <span id="hud-title">JUEGO</span>
      <span>PUNTOS: <span id="hud-score">0</span></span>
    </div>
    <canvas id="gameCanvas" width="480" height="480"></canvas>
    <div class="controls-hint" id="controls-text">Usa las flechas del teclado o los botones táctiles</div>
    
    <div class="touch-controls">
      <button class="touch-btn up" onpointerdown="handleInput('UP')">▲</button>
      <button class="touch-btn left" onpointerdown="handleInput('LEFT')">◄</button>
      <button class="touch-btn down" onpointerdown="handleInput('DOWN')">▼</button>
      <button class="touch-btn right" onpointerdown="handleInput('RIGHT')">►</button>
    </div>
  </section>

  <script>
    const canvas = document.getElementById('gameCanvas');
    const ctx = canvas.getContext('2d');
    let currentGame = null;
    let gameLoopId = null;
    let score = 0;

    // Web Audio API Synthesizer
    const audioCtx = new (window.AudioContext || window.webkitAudioContext)();
    function playTone(freq, type = 'square', duration = 0.08) {
      if (audioCtx.state === 'suspended') audioCtx.resume();
      const osc = audioCtx.createOscillator();
      const gain = audioCtx.createGain();
      osc.type = type;
      osc.frequency.setValueAtTime(freq, audioCtx.currentTime);
      gain.gain.setValueAtTime(0.08, audioCtx.currentTime);
      gain.gain.exponentialRampToValueAtTime(0.001, audioCtx.currentTime + duration);
      osc.connect(gain);
      gain.connect(audioCtx.destination);
      osc.start();
      osc.stop(audioCtx.currentTime + duration);
    }

    // High Scores
    function loadScores() {
      ['snake', 'pong', 'brick', 'runner'].forEach(g => {
        const s = localStorage.getItem('cyber_high_' + g) || 0;
        document.getElementById('score-' + g).innerText = s;
      });
    }

    function saveScore(game, val) {
      const prev = parseInt(localStorage.getItem('cyber_high_' + game) || 0);
      if (val > prev) {
        localStorage.setItem('cyber_high_' + game, val);
        loadScores();
      }
    }

    function updateScore(val) {
      score = val;
      document.getElementById('hud-score').innerText = score;
      if (currentGame) saveScore(currentGame, score);
    }

    function returnToMenu() {
      if (gameLoopId) cancelAnimationFrame(gameLoopId);
      clearInterval(gameLoopId);
      currentGame = null;
      document.getElementById('game-screen').style.display = 'none';
      document.getElementById('btn-back').style.display = 'none';
      document.getElementById('hub-screen').style.display = 'grid';
      loadScores();
    }

    // Game States
    let state = {};

    function startGame(game) {
      currentGame = game;
      updateScore(0);
      document.getElementById('hub-screen').style.display = 'none';
      document.getElementById('game-screen').style.display = 'flex';
      document.getElementById('btn-back').style.display = 'block';

      if (game === 'snake') initSnake();
      if (game === 'pong') initPong();
      if (game === 'brick') initBrick();
      if (game === 'runner') initRunner();
    }

    // 1. CYBER SNAKE
    function initSnake() {
      document.getElementById('hud-title').innerText = 'CYBER SNAKE 2077';
      document.getElementById('controls-text').innerText = 'Flechas / WASD para girar';
      state = {
        grid: 20,
        snake: [{x: 10, y: 10}, {x: 9, y: 10}, {x: 8, y: 10}],
        dx: 1, dy: 0,
        food: {x: 15, y: 15},
        tick: 0
      };
      function loop() {
        gameLoopId = requestAnimationFrame(loop);
        if (++state.tick < 6) return;
        state.tick = 0;

        const head = {x: state.snake[0].x + state.dx, y: state.snake[0].y + state.dy};
        if (head.x < 0 || head.x >= 24 || head.y < 0 || head.y >= 24 ||
            state.snake.some(s => s.x === head.x && s.y === head.y)) {
          playTone(150, 'sawtooth', 0.3);
          initSnake();
          updateScore(0);
          return;
        }
        state.snake.unshift(head);
        if (head.x === state.food.x && head.y === state.food.y) {
          playTone(620, 'sine', 0.1);
          updateScore(score + 10);
          state.food = {x: Math.floor(Math.random()*24), y: Math.floor(Math.random()*24)};
        } else {
          state.snake.pop();
        }

        ctx.fillStyle = '#04040a';
        ctx.fillRect(0, 0, 480, 480);

        // Food
        ctx.fillStyle = '#ff007f';
        ctx.shadowBlur = 12;
        ctx.shadowColor = '#ff007f';
        ctx.fillRect(state.food.x*20+2, state.food.y*20+2, 16, 16);

        // Snake
        ctx.fillStyle = '#00f3ff';
        ctx.shadowColor = '#00f3ff';
        state.snake.forEach((s, idx) => {
          ctx.fillStyle = idx === 0 ? '#39ff14' : '#00f3ff';
          ctx.fillRect(s.x*20+1, s.y*20+1, 18, 18);
        });
        ctx.shadowBlur = 0;
      }
      loop();
    }

    // 2. CYBER PONG
    function initPong() {
      document.getElementById('hud-title').innerText = 'CYBER PONG 2077';
      document.getElementById('controls-text').innerText = 'Izquierda / Derecha para mover la paleta';
      state = {
        px: 200, pw: 80,
        ax: 200,
        bx: 240, by: 240, vx: 4, vy: 4
      };
      function loop() {
        gameLoopId = requestAnimationFrame(loop);
        state.bx += state.vx;
        state.by += state.vy;

        if (state.bx <= 8 || state.bx >= 472) { state.vx *= -1; playTone(300); }
        // AI
        if (state.ax + 40 < state.bx) state.ax += 3.3;
        if (state.ax + 40 > state.bx) state.ax -= 3.3;

        // Top Paddle (AI)
        if (state.by <= 25 && state.bx >= state.ax && state.bx <= state.ax + 80) {
          state.vy = Math.abs(state.vy);
          playTone(400);
        }
        // Bottom Paddle (Player)
        if (state.by >= 455 && state.bx >= state.px && state.bx <= state.px + state.pw) {
          state.vy = -Math.abs(state.vy) * 1.04;
          updateScore(score + 10);
          playTone(550);
        }
        if (state.by < 0) {
          updateScore(score + 50);
          playTone(800, 'triangle', 0.2);
          state.bx = 240; state.by = 240; state.vy = 4;
        }
        if (state.by > 480) {
          playTone(140, 'sawtooth', 0.3);
          updateScore(0);
          state.bx = 240; state.by = 240; state.vy = -4;
        }

        ctx.fillStyle = '#04040a';
        ctx.fillRect(0, 0, 480, 480);

        // Net
        ctx.strokeStyle = 'rgba(0,243,255,0.2)';
        ctx.setLineDash([8, 8]);
        ctx.beginPath(); ctx.moveTo(0, 240); ctx.lineTo(480, 240); ctx.stroke();
        ctx.setLineDash([]);

        ctx.shadowBlur = 10;
        ctx.fillStyle = '#ff007f'; ctx.shadowColor = '#ff007f';
        ctx.fillRect(state.ax, 12, 80, 10);

        ctx.fillStyle = '#00f3ff'; ctx.shadowColor = '#00f3ff';
        ctx.fillRect(state.px, 458, state.pw, 10);

        ctx.fillStyle = '#39ff14'; ctx.shadowColor = '#39ff14';
        ctx.beginPath(); ctx.arc(state.bx, state.by, 8, 0, Math.PI*2); ctx.fill();
        ctx.shadowBlur = 0;
      }
      loop();
    }

    // 3. CYBER BRICK BREAKER
    function initBrick() {
      document.getElementById('hud-title').innerText = 'CYBER BRICK BREAKER';
      document.getElementById('controls-text').innerText = 'Izquierda / Derecha para mover la barra';
      const bricks = [];
      for (let r = 0; r < 5; r++) {
        for (let c = 0; c < 7; c++) {
          bricks.push({x: 15 + c*65, y: 40 + r*26, alive: true, color: r % 2 === 0 ? '#ff007f' : '#00f3ff'});
        }
      }
      state = { px: 195, bx: 240, by: 400, vx: 3.5, vy: -3.5, bricks };
      function loop() {
        gameLoopId = requestAnimationFrame(loop);
        state.bx += state.vx;
        state.by += state.vy;

        if (state.bx <= 8 || state.bx >= 472) { state.vx *= -1; playTone(320); }
        if (state.by <= 8) { state.vy *= -1; playTone(320); }

        if (state.by >= 445 && state.bx >= state.px && state.bx <= state.px + 90) {
          state.vy = -Math.abs(state.vy);
          playTone(480);
        }

        state.bricks.forEach(b => {
          if (b.alive && state.bx > b.x && state.bx < b.x + 58 && state.by > b.y && state.by < b.y + 18) {
            b.alive = false;
            state.vy *= -1;
            updateScore(score + 20);
            playTone(680);
          }
        });

        if (state.bricks.every(b => !b.alive)) {
          initBrick();
          return;
        }
        if (state.by > 480) {
          playTone(130, 'sawtooth', 0.3);
          updateScore(0);
          initBrick();
          return;
        }

        ctx.fillStyle = '#04040a';
        ctx.fillRect(0, 0, 480, 480);

        state.bricks.forEach(b => {
          if (!b.alive) return;
          ctx.fillStyle = b.color;
          ctx.shadowBlur = 8; ctx.shadowColor = b.color;
          ctx.fillRect(b.x, b.y, 58, 18);
        });

        ctx.fillStyle = '#39ff14'; ctx.shadowColor = '#39ff14';
        ctx.fillRect(state.px, 452, 90, 10);

        ctx.fillStyle = '#ffe600'; ctx.shadowColor = '#ffe600';
        ctx.beginPath(); ctx.arc(state.bx, state.by, 7, 0, Math.PI*2); ctx.fill();
        ctx.shadowBlur = 0;
      }
      loop();
    }

    // 4. CYBER RUNNER
    function initRunner() {
      document.getElementById('hud-title').innerText = 'CYBER RUNNER 2077';
      document.getElementById('controls-text').innerText = 'Arriba / Espacio para saltar obstáculos';
      state = { py: 380, vy: 0, grounded: true, obsX: 500, speed: 6, frame: 0 };
      function loop() {
        gameLoopId = requestAnimationFrame(loop);
        state.frame++;
        if (state.frame % 10 === 0) updateScore(score + 1);

        state.py += state.vy;
        if (state.py < 380) {
          state.vy += 0.7;
          state.grounded = false;
        } else {
          state.py = 380;
          state.vy = 0;
          state.grounded = true;
        }

        state.obsX -= state.speed;
        if (state.obsX < -30) {
          state.obsX = 480 + Math.random() * 180;
          state.speed = Math.min(11, state.speed + 0.2);
        }

        // Collision
        if (state.obsX < 95 && state.obsX + 24 > 65 && state.py + 40 > 385) {
          playTone(140, 'sawtooth', 0.3);
          updateScore(0);
          initRunner();
          return;
        }

        ctx.fillStyle = '#04040a';
        ctx.fillRect(0, 0, 480, 480);

        // Floor
        ctx.strokeStyle = '#00f3ff';
        ctx.lineWidth = 2;
        ctx.beginPath(); ctx.moveTo(0, 420); ctx.lineTo(480, 420); ctx.stroke();

        // Player
        ctx.fillStyle = '#00f3ff'; ctx.shadowBlur = 12; ctx.shadowColor = '#00f3ff';
        ctx.fillRect(65, state.py, 30, 40);

        // Obstacle
        ctx.fillStyle = '#ff007f'; ctx.shadowColor = '#ff007f';
        ctx.fillRect(state.obsX, 385, 24, 35);
        ctx.shadowBlur = 0;
      }
      loop();
    }

    function handleInput(dir) {
      if (currentGame === 'snake') {
        if (dir === 'UP' && state.dy === 0) { state.dx = 0; state.dy = -1; }
        if (dir === 'DOWN' && state.dy === 0) { state.dx = 0; state.dy = 1; }
        if (dir === 'LEFT' && state.dx === 0) { state.dx = -1; state.dy = 0; }
        if (dir === 'RIGHT' && state.dx === 0) { state.dx = 1; state.dy = 0; }
      }
      if (currentGame === 'pong') {
        if (dir === 'LEFT') state.px = Math.max(0, state.px - 35);
        if (dir === 'RIGHT') state.px = Math.min(400, state.px + 35);
      }
      if (currentGame === 'brick') {
        if (dir === 'LEFT') state.px = Math.max(0, state.px - 35);
        if (dir === 'RIGHT') state.px = Math.min(390, state.px + 35);
      }
      if (currentGame === 'runner') {
        if ((dir === 'UP' || dir === 'ACTION') && state.grounded) {
          state.vy = -13;
          playTone(520, 'sine', 0.12);
        }
      }
    }

    window.addEventListener('keydown', e => {
      if (['ArrowUp', 'ArrowDown', 'ArrowLeft', 'ArrowRight', ' '].includes(e.key)) e.preventDefault();
      if (e.key === 'ArrowUp' || e.key === 'w' || e.key === 'W') handleInput('UP');
      if (e.key === 'ArrowDown' || e.key === 's' || e.key === 'S') handleInput('DOWN');
      if (e.key === 'ArrowLeft' || e.key === 'a' || e.key === 'A') handleInput('LEFT');
      if (e.key === 'ArrowRight' || e.key === 'd' || e.key === 'D') handleInput('RIGHT');
      if (e.key === ' ') handleInput('ACTION');
    });

    loadScores();
  </script>
</body>
</html>
