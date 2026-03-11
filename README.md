<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Mon Parcours — Portfolio</title>
  <meta name="description" content="Portfolio personnel - Étudiant ENSIBS Cybersécurité. CV interactif, projets et compétences." />
  <link rel="stylesheet" href="style.css" />
  <link href="https://fonts.googleapis.com/css2?family=Space+Grotesk:wght@300;400;500;600;700&family=JetBrains+Mono:wght@400;500;600&display=swap" rel="stylesheet" />
</head>
<body>

  <!-- NAVBAR -->
  <nav class="navbar" id="navbar">
    <div class="nav-container">
      <a href="#accueil" class="nav-logo">MP</a>
      <div class="nav-links" id="navLinks">
        <a href="#accueil">Accueil</a>
        <a href="#apropos">À propos</a>
        <a href="#competences">Compétences</a>
        <a href="#projets">Projets</a>
        <a href="#contact">Contact</a>
      </div>
      <button class="nav-toggle" id="navToggle" aria-label="Menu">
        <span></span><span></span><span></span>
      </button>
    </div>
  </nav>

  <!-- HERO -->
  <section id="accueil" class="hero">
    <div class="hero-bg">
      <canvas id="heroCanvas"></canvas>
      <div class="hero-overlay"></div>
    </div>
    <div class="hero-content fade-up">
      <p class="hero-tag">Bienvenue sur mon portfolio</p>
      <h1 class="hero-title">Mon <span class="gradient-text glow-text">Parcours</span></h1>
      <p class="hero-subtitle">
        <!-- TODO: Modifier cette description -->
        Étudiant en cybersécurité à l'ENSIBS · Développeur passionné · Créateur de projets
      </p>
      <div class="hero-buttons">
        <a href="#projets" class="btn btn-primary">Voir mes projets</a>
        <a href="#contact" class="btn btn-outline">Me contacter</a>
      </div>
    </div>
    <div class="scroll-indicator">
      <svg width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
        <polyline points="6 9 12 15 18 9"></polyline>
      </svg>
    </div>
  </section>

  <!-- À PROPOS -->
  <section id="apropos" class="section">
    <div class="container">
      <div class="section-header fade-up">
        <h2>À <span class="gradient-text">propos</span></h2>
        <div class="section-line"></div>
      </div>

      <div class="about-grid">
        <div class="about-bio fade-up">
          <p>
            Je suis étudiant en première année à l'ENSIBS Lorient, spécialité cybersécurité. 
            Passionné par le développement et la sécurité informatique, je travaille sur des projets 
            personnels qui me permettent d'approfondir mes compétences.
          </p>
          <p>
            En-dehors de mes études, je développe des mods pour des jeux vidéo, crée des sites web
            et customise mon système d'exploitation linux.
          </p>

          <div class="about-info">
            <div class="info-item">
              <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M21 10c0 7-9 13-9 13s-9-6-9-13a9 9 0 0 1 18 0z"/><circle cx="12" cy="10" r="3"/></svg>
              <span>Lorient, Bretagne</span>
            </div>
            <div class="info-item">
              <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M22 10v6M2 10l10-5 10 5-10 5z"/><path d="M6 12v5c3 3 10 3 12 0v-5"/></svg>
              <span>ENSIBS — Cybersécurité (2025-2030)</span>
            </div>
            <div class="info-item">
              <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><rect x="2" y="7" width="20" height="14" rx="2"/><path d="M16 21V5a2 2 0 0 0-2-2h-4a2 2 0 0 0-2 2v16"/></svg>
              <span>Ouvert aux opportunités de stage</span>
            </div>
          </div>
        </div>

        <div class="about-timeline fade-up">
          <h3>Formation</h3>
          <div class="timeline">
            <div class="timeline-item">
              <div class="timeline-dot"></div>
              <p class="timeline-date">2022-2025</p>
              <p class="timeline-title">Bac général Maths / Physique / NSI</p>
              <p class="timeline-desc">Lycée du Pays de Retz, Pornic</p>
            </div>
            <div class="timeline-item">
              <div class="timeline-dot"></div>
              <!-- TODO: Dates -->
              <p class="timeline-date">2025 - Présent</p>
              <p class="timeline-title">ENSIBS — Ingénieur Cybersécurité</p>
              <p class="timeline-desc">École Nationale Supérieure d'Ingénieurs de Bretagne Sud, Lorient</p>
            </div>
          </div>

          <h3 style="margin-top: 2rem;">Expérience</h3>
          <div class="timeline">
            <div class="timeline-item">
              <div class="timeline-dot dot-accent"></div>
              <p class="timeline-date accent-text">2026-Présent</p>
              <p class="timeline-title">Début de developpement d'un jeux sur Unreal Engine</p>
              <p class="timeline-desc">Avec des amis debut d'un developpement d'un jeu vidéo sur le concept de SCP</p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- COMPÉTENCES -->
  <section id="competences" class="section section-alt">
    <div class="container">
      <div class="section-header fade-up">
        <h2>Mes <span class="gradient-text">Compétences</span></h2>
        <div class="section-line"></div>
      </div>

      <div class="skills-grid">
        <!-- Langages -->
        <div class="skill-card fade-up">
          <h3>Langages</h3>
          <div class="skill-list">
            <div class="skill-item">
              <div class="skill-info"><span>Python</span><span class="skill-pct">60%</span></div>
              <div class="skill-bar"><div class="skill-fill" data-width="60"></div></div>
            </div>
            <div class="skill-item">
              <div class="skill-info"><span>Lua</span><span class="skill-pct">30%</span></div>
              <div class="skill-bar"><div class="skill-fill" data-width="30"></div></div>
            </div>
            <div class="skill-item">
              <div class="skill-info"><span>HTML/CSS</span><span class="skill-pct">65%</span></div>
              <div class="skill-bar"><div class="skill-fill" data-width="65"></div></div>
            </div>
            <div class="skill-item">
              <div class="skill-info"><span>C/C++</span><span class="skill-pct">20%</span></div>
              <div class="skill-bar"><div class="skill-fill" data-width="20"></div></div>
            </div>
          </div>
        </div>

        <!-- Outils -->
        <div class="skill-card fade-up">
          <h3>Outils & Frameworks</h3>
          <div class="skill-list">
            <div class="skill-item">
              <div class="skill-info"><span>Discord.py</span><span class="skill-pct">75%</span></div>
              <div class="skill-bar"><div class="skill-fill" data-width="75"></div></div>
            </div>
            <div class="skill-item">
              <div class="skill-info"><span>Git / GitHub</span><span class="skill-pct">70%</span></div>
              <div class="skill-bar"><div class="skill-fill" data-width="70"></div></div>
            </div>
            <div class="skill-item">
              <div class="skill-info"><span>Linux</span><span class="skill-pct">85%</span></div>
              <div class="skill-bar"><div class="skill-fill" data-width="85"></div></div>
            </div>
            <div class="skill-item">
              <div class="skill-info"><span>Unity</span><span class="skill-pct">15%</span></div>
              <div class="skill-bar"><div class="skill-fill" data-width="15"></div></div>
            </div>
          </div>
        </div>

        <!-- Langues -->
        <div class="skill-card fade-up">
          <h3>Langues</h3>
          <div class="skill-list">
            <div class="skill-item">
              <div class="skill-info"><span>Français</span><span class="skill-pct">95%</span></div>
              <div class="skill-bar"><div class="skill-fill" data-width="95"></div></div>
            </div>
            <div class="skill-item">
              <div class="skill-info"><span>Anglais</span><span class="skill-pct">85%</span></div>
              <div class="skill-bar"><div class="skill-fill" data-width="85"></div></div>
            </div>
            <div class="skill-item">
              <div class="skill-info"><span>Russe</span><span class="skill-pct">75%</span></div>
              <div class="skill-bar"><div class="skill-fill" data-width="75"></div></div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- PROJETS -->
  <section id="projets" class="section">
    <div class="container">
      <div class="section-header fade-up">
        <h2>Mes <span class="gradient-text">Projets</span></h2>
        <div class="section-line"></div>
      </div>

      <div class="projects-grid">
        <!-- MemoryTrainer -->
        <div class="project-card fade-up">
          <div class="project-bar bar-primary"></div>
          <div class="project-content">
            <div class="project-header">
              <div class="project-icon">
                <svg width="32" height="32" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M12 8V4H8"/><rect width="16" height="12" x="4" y="8" rx="2"/><path d="M2 14h2"/><path d="M20 14h2"/><path d="M15 13v2"/><path d="M9 13v2"/></svg>
              </div>
              <div>
                <h3>MemoryTrainer</h3>
                <p class="project-subtitle">Site Web — Entraînement mémoire</p>
              </div>
            </div>
            <p class="project-desc">
              Site Web interactif développé en JavaScript / HTML / CSS permettant aux utilisateurs d'entraîner leur mémoire 
              avec des exercices variés : mémorisation de séquences, de nombres.
            </p>
            <div class="project-tags">
              <span>JavaScript</span>
              <span>HTML</span>
              <span>CSS</span>
            </div>
            <div class="project-links">
              <a href="https://github.com/le-capitaliste/Memorytrainer" target="_blank" rel="noopener noreferrer">
                <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M15 22v-4a4.8 4.8 0 0 0-1-3.5c3 0 6-2 6-5.5.08-1.25-.27-2.48-1-3.5.28-1.15.28-2.35 0-3.5 0 0-1 0-3 1.5-2.64-.5-5.36-.5-8 0C6 2 5 2 5 2c-.3 1.15-.3 2.35 0 3.5A5.403 5.403 0 0 0 4 9c0 3.5 3 5.5 6 5.5-.39.49-.68 1.05-.85 1.65-.17.6-.22 1.23-.15 1.85v4"/><path d="M9 18c-4.51 2-5-2-7-2"/></svg>
                Code source
              </a>
            </div>
          </div>
        </div>

        <!-- Mod Hoi4 -->
        <div class="project-card fade-up">
          <div class="project-bar bar-accent"></div>
          <div class="project-content">
            <div class="project-header">
              <div class="project-icon">
                <svg width="32" height="32" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M12 22s8-4 8-10V5l-8-3-8 3v7c0 6 8 10 8 10"/></svg>
              </div>
              <div>
                <h3>Mod Hoi4</h3>
                <p class="project-subtitle">Developpement d'un mod pour le jeu Hearts of Iron IV</p>
              </div>
            </div>
            <p class="project-desc">
              Developement du mod "The Fire Rises" avec une equipe de developpeurs pour le jeu de stratégie Hearts of Iron IV, ajoutant une nouvelle faction, 
              des événements et des mécaniques de jeu pour une faction spécifique.
            </p>
            <div class="project-tags">
              <span>pseudo-code Hoi4</span>
              <span>Communautaire</span>
              <span>Github</span>
              <span>Mod</span>
            </div>
            <div class="project-links">
              <a href="https://steamcommunity.com/sharedfiles/filedetails/?id=3350890356&searchtext=The+fire+rises">
                <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M18 13v6a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2V8a2 2 0 0 1 2-2h6"/><polyline points="15 3 21 3 21 9"/><line x1="10" y1="14" x2="21" y2="3"/></svg>
                Détails
              </a>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- CONTACT -->
  <section id="contact" class="section section-alt">
    <div class="container">
      <div class="section-header fade-up">
        <h2>Me <span class="gradient-text">Contacter</span></h2>
        <div class="section-line"></div>
      </div>

      <div class="contact-grid">
        <div class="contact-info fade-up">
          <p>Vous avez un projet, une question ou juste envie de discuter ? N'hésitez pas à me contacter !</p>

          <div class="contact-links">
            <a href="mailto:xxx@proton.me" class="contact-link">
              <div class="contact-icon">
                <svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><rect width="20" height="16" x="2" y="4" rx="2"/><path d="m22 7-8.97 5.7a1.94 1.94 0 0 1-2.06 0L2 7"/></svg>
              </div>
              <span>xxx@proton.me</span>
            </a>
            <a href="https://github.com/Capi360" target="_blank" rel="noopener noreferrer" class="contact-link">
              <div class="contact-icon">
                <svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M15 22v-4a4.8 4.8 0 0 0-1-3.5c3 0 6-2 6-5.5.08-1.25-.27-2.48-1-3.5.28-1.15.28-2.35 0-3.5 0 0-1 0-3 1.5-2.64-.5-5.36-.5-8 0C6 2 5 2 5 2c-.3 1.15-.3 2.35 0 3.5A5.403 5.403 0 0 0 4 9c0 3.5 3 5.5 6 5.5-.39.49-.68 1.05-.85 1.65-.17.6-.22 1.23-.15 1.85v4"/><path d="M9 18c-4.51 2-5-2-7-2"/></svg>
              </div>
              <span>GitHub</span>
            </a>
          </div>
        </div>

        <form class="contact-form fade-up" id="contactForm">
          <div class="form-group">
            <label for="name">Nom</label>
            <input type="text" id="name" placeholder="Votre nom" required />
          </div>
          <div class="form-group">
            <label for="email">Email</label>
            <input type="email" id="email" placeholder="votre@email.com" required />
          </div>
          <div class="form-group">
            <label for="message">Message</label>
            <textarea id="message" rows="5" placeholder="Votre message..." required></textarea>
          </div>
          <button type="submit" class="btn btn-primary">
            <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><line x1="22" y1="2" x2="11" y2="13"/><polygon points="22 2 15 22 11 13 2 9 22 2"/></svg>
            Envoyer
          </button>
        </form>
      </div>
    </div>
  </section>

  <!-- FOOTER -->
  <footer class="footer">
    <div class="container footer-content">
      <p class="footer-sub">Fait avec <span class="accent-text">♥</span> à l'ENSIBS</p>
    </div>
  </footer>

  <script src="script.js"></script>
</body>
</html>

