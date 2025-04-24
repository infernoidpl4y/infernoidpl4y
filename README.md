<div align="center">
  <style>
    .glitch {
      font-size: 2.5rem;
      font-family: 'Courier New', monospace;
      text-shadow: 2px 2px #2ecc71;
      animation: glitch 1s infinite;
    }
    @keyframes glitch {
      0% { text-shadow: 2px 2px #2ecc71; }
      25% { text-shadow: -2px -2px #2ecc71; }
      50% { text-shadow: 2px -2px #2ecc71; }
      75% { text-shadow: -2px 2px #2ecc71; }
    }
    .terminal {
      border: 2px solid #00ff00;
      max-width: 800px;
      margin: 2rem auto;
      padding: 2rem;
      border-radius: 5px;
      box-shadow: 0 0 15px #00ff00;
      background: #2c3e50;
      color: #ecf0f1;
      font-family: 'Courier New', monospace;
    }
    .section {
      margin: 3rem 0;
      padding: 2rem;
      background: rgba(0, 0, 0, 0.3);
    }
    .project-card {
      background: #1a252f;
      border: 1px solid #00ff00;
      padding: 1.5rem;
      margin: 1rem 0;
      transition: all 0.3s;
    }
    .project-card:hover {
      transform: translateY(-5px);
      box-shadow: 0 0 15px #00ff00;
    }
    .tech-tag {
      display: inline-block;
      background: #2c3e50;
      padding: 0.3rem 0.8rem;
      border-radius: 15px;
      font-size: 0.8rem;
      border: 1px solid #2ecc71;
      margin: 0.2rem;
    }
    .project-link {
      display: inline-block;
      margin-top: 1rem;
      padding: 0.5rem 1rem;
      background: #2ecc71;
      color: #2c3e50;
      text-decoration: none;
      font-weight: bold;
    }
    .project-link:hover {
      background: #00ff00;
    }
    nav a {
      color: #00ff00;
      text-decoration: none;
      margin: 0 1rem;
      padding: 0.5rem;
      border-bottom: 2px solid transparent;
      transition: all 0.3s;
    }
    nav a:hover {
      border-color: #2ecc71;
    }
  </style>

  <div class="terminal">
    <h1 class="glitch">InfernoidPl4y</h1>
    
    <nav>
      <a href="#about">Sobre Mí</a>
      <a href="#skills">Habilidades</a>
      <a href="#experience">Experiencia</a>
      <a href="#projects">Proyectos</a>
      <a href="#certifications">Certificaciones</a>
      <a href="#contact">Contacto</a>
    </nav>

    <div id="about" class="section">
      <h2>Ronnie Molina Martínez</h2>
      <p>🔐 Cybersecurity Researcher | 👨‍💻 Full-Stack Developer</p>
      <p>18 años | Apasionado por la seguridad ofensiva</p>
    </div>

    <div id="skills" class="section">
      <h2>🛠 Habilidades Técnicas</h2>
      <div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(200px, 1fr)); gap: 1rem;">
        <div style="background: #34495e; padding: 1rem; text-align: center; border: 1px solid #00ff00;">
          <h3>Pentesting</h3>
          <p>OWASP Top 10, Metasploit, Burp Suite</p>
        </div>
        <div style="background: #34495e; padding: 1rem; text-align: center; border: 1px solid #00ff00;">
          <h3>Desarrollo</h3>
          <p>Python, C++, JavaScript</p>
        </div>
        <div style="background: #34495e; padding: 1rem; text-align: center; border: 1px solid #00ff00;">
          <h3>Web Hacking</h3>
          <p>XSS, SQLi, CSRF, JWT Exploits</p>
        </div>
      </div>
    </div>

    <div id="experience" class="section">
      <h2>⏳ Experiencia</h2>
      <div style="border-left: 3px solid #2ecc71; padding-left: 2rem; margin-left: 1rem;">
        <div style="margin: 1.5rem 0; padding: 1rem; border: 1px dashed #00ff00;">
          <h3>3 años - Pentesting Autodidacta</h3>
          <p>Análisis de vulnerabilidades en entornos controlados</p>
        </div>
        <div style="margin: 1.5rem 0; padding: 1rem; border: 1px dashed #00ff00;">
          <h3>1 año - Web Hacking</h3>
          <p>Estudio de vulnerabilidades modernas en aplicaciones web</p>
        </div>
        <div style="margin: 1.5rem 0; padding: 1rem; border: 1px dashed #00ff00;">
          <h3>Desarrollo de Herramientas</h3>
          <p>Creación de scripts para automatización de pruebas</p>
        </div>
      </div>
    </div>

    <div id="projects" class="section">
      <h2>🚀 Proyectos Destacados</h2>
      <div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(300px, 1fr)); gap: 1.5rem;">
        <div class="project-card">
          <h3>XSS Lab</h3>
          <p>Entorno controlado para experimentar con vulnerabilidades XSS</p>
          <div>
            <span class="tech-tag">Python</span>
            <span class="tech-tag">Flask</span>
            <span class="tech-tag">HTML/CSS</span>
            <span class="tech-tag">Cybersecurity</span>
          </div>
          <a href="https://xsslabinteractive.pythonanywhere.com/" class="project-link" target="_blank">Ver Proyecto</a>
        </div>
        
        <div class="project-card">
          <h3>Log_Analizer</h3>
          <p>Herramienta para monitorear y analizar logs en tiempo real</p>
          <div>
            <span class="tech-tag">Python</span>
            <span class="tech-tag">Cybersecurity</span>
          </div>
          <a href="https://github.com/infernoidpl4y/Log_Analyzer" class="project-link" target="_blank">Ver Proyecto</a>
        </div>
        
        <div class="project-card">
          <h3>Web Vulnerability Scanner</h3>
          <p>Herramienta para detección de vulnerabilidades OWASP Top 10</p>
          <div>
            <span class="tech-tag">Python</span>
            <span class="tech-tag">Requests</span>
            <span class="tech-tag">BeautifulSoup</span>
          </div>
          <a href="#" class="project-link" style="background: #7f8c8d;">Próximamente</a>
        </div>
      </div>
    </div>

    <div id="certifications" class="section">
      <h2>📜 Certificaciones</h2>
      <div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(250px, 1fr)); gap: 1.5rem;">
        <div style="background: #1a252f; padding: 1.5rem; border: 1px solid #2ecc71; text-align: center;">
          <h3>CWAP</h3>
          <p>Certificación en Pentesting de Aplicaciones Web</p>
          <a href="certificaciones/certificate-196197b1.pdf">
            <img src="https://img.shields.io/badge/Certificacion-CWAP-red" alt="CWAP">
          </a>
        </div>
        <div style="background: #1a252f; padding: 1.5rem; border: 1px solid #2ecc71; text-align: center;">
          <h3>Google Dorking</h3>
          <p>Certificación en técnicas avanzadas de búsqueda</p>
          <a href="certificaciones/certificate-9212e0e1.pdf">
            <img src="https://img.shields.io/badge/Certificacion-GoogleDorking-red" alt="GOOGLEDORKING">
          </a>
        </div>
      </div>
    </div>

    <div id="contact" class="section">
      <h2>🗒 Contacto</h2>
      <p>Email: <a href="mailto:infernoidpl4y@gmail.com" style="color: #00ff00;">infernoidpl4y@gmail.com</a></p>
      <p>GitHub: <a href="https://github.com/InfernoidPl4y" target="_blank" style="color: #2ecc71;">github.com/InfernoidPl4y</a></p>
    </div>
  </div>
</div>

<script>
  // Los efectos de hover y animaciones se mantienen con CSS inline
  // El scroll suave requeriría JavaScript adicional que no es soportado en todos los README.md
</script>
