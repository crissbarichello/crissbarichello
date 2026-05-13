<style>
  @import url('https://fonts.googleapis.com/css2?family=JetBrains+Mono:wght@400;500;700&family=Sora:wght@300;400;600&display=swap');

  *, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }

  :root {
    --bg: #0d1117;
    --surface: #161b22;
    --surface2: #21262d;
    --border: #30363d;
    --text: #e6edf3;
    --muted: #7d8590;
    --accent: #58a6ff;
    --accent2: #3fb950;
    --accent3: #d2a8ff;
    --streak: #f78166;
  }
 /* langs */
  .langs-card {
    background: var(--surface);
    border: 1px solid var(--border);
    border-radius: 10px;
    padding: 1.25rem 1.5rem;
    margin-bottom: 1rem;
  }

  .langs-title {
    font-size: 0.72rem;
    color: var(--muted);
    text-transform: uppercase;
    letter-spacing: 0.06em;
    margin-bottom: 12px;
  }

  .lang-bar {
    height: 8px;
    border-radius: 4px;
    display: flex;
    overflow: hidden;
    margin-bottom: 12px;
  }

  .lang-list {
    display: flex;
    flex-wrap: wrap;
    gap: 12px;
  }

  .lang-item {
    display: flex;
    align-items: center;
    gap: 6px;
    font-size: 0.78rem;
    color: var(--muted);
  }

  .lang-dot {
    width: 10px;
    height: 10px;
    border-radius: 50%;
  }

  .lang-pct {
    color: var(--text);
    font-family: 'JetBrains Mono', monospace;
    font-size: 0.72rem;
  }
</style>
<div align="center">
  <h1>Olá, eu sou o Cristiano Barichello 👋</h1>
</div>

<div class="section-label">top languages</div>
  <div class="langs-card">
    <div class="langs-title">linguagens mais usadas</div>
    <div class="lang-bar">
      <div style="background:#3572A5; width:40%"></div>
      <div style="background:#F1E05A; width:25%"></div>
      <div style="background:#89e051; width:20%"></div>
      <div style="background:#e34c26; width:15%"></div>
    </div>
    <div class="lang-list">
      <div class="lang-item"><span class="lang-dot" style="background:#3572A5"></span>Python <span class="lang-pct">40%</span></div>
      <div class="lang-item"><span class="lang-dot" style="background:#F1E05A"></span>JavaScript <span class="lang-pct">25%</span></div>
      <div class="lang-item"><span class="lang-dot" style="background:#89e051"></span>Shell <span class="lang-pct">20%</span></div>
      <div class="lang-item"><span class="lang-dot" style="background:#e34c26"></span>HTML <span class="lang-pct">15%</span></div>
    </div>
  </div>

  <div class="code-section">
    <div class="code-header">
      top languages
      <button class="copy-btn" onclick="copy(this,'c3')">copiar</button>
    </div>
    <pre id="c3">[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=crissbarichello&layout=compact&theme=dark)](https://github.com/crissbarichello)</pre>
  </div>


<hr>

<div align="left">
  <h2>🚀 Sobre Mim</h2>
  <p>
    Com mais de <b>10 anos de experiência na área de TI</b>, minha trajetória reflete uma evolução sólida: desde o atendimento técnico em campo até a coordenação estratégica de infraestrutura. Essa vivência prática — passando pela telefonia, ADSL e fibra óptica — me deu a base necessária para liderar operações complexas com foco absoluto na entrega ao cliente final.
  </p>
  <p>
    Hoje, como <b>Coordenador de TI na Sysmo Sistemas</b>, gerencio um ecossistema crítico de infraestrutura, inventário e segurança. Sou um entusiasta da cultura <b>Open Source</b> e acredito na eficiência do software livre para construir ambientes resilientes, escaláveis e de baixo custo de licenciamento.
  </p>
</div>

<br>

<div align="left">
  <h3>🛠️ Destaques de Atuação e Expertise</h3>
  <ul>
    <li><b>Ecossistema Open Source:</b> Lidero a implementação e gestão de ferramentas essenciais como <b>Zabbix, Grafana, GLPI, PFSense e Redmine</b>.</li>
    <li><b>Virtualização e Linux:</b> Foco em ambientes virtualizados e servidores Linux, garantindo alta disponibilidade e otimização de recursos.</li>
    <li><b>Automação e Dados:</b> Utilizo <b>Python e SQL</b> para automatizar tarefas rotineiras e integrar sistemas.</li>
    <li><b>Gestão Estratégica:</b> Responsável por inventário, segurança da informação e redes.</li>
  </ul>
</div>

<br>

<div align="left">
  <h3>🎓 Formação</h3>
  <p>🎓 Bacharel em <b>Sistemas de Informação</b> pela UNOESC (2015).</p>
</div>

<br>

<div align="left">
  <h3>📫 Contatos</h3>
  <a href="https://www.linkedin.com/in/cristianobarichello" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn">
  </a>
  <a href="https://www.instagram.com/cristianobarichello" target="_blank">
    <img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white" alt="Instagram">
  </a>
</div>

<br>

<div align="center">
  <sub>Este README foi configurado com 💙 para refletir uma trajetória de evolução técnica e estratégica.</sub>
</div>
