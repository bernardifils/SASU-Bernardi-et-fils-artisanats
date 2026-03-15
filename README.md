# SASU-Bernardi-et-fils-artisanats
html


<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <meta name="description" content="Bernardi & Fils Artisanats SASU – Vente et pose de marbre, carrelage, parquet et rénovation complète." />
  <title>Bernardi & Fils Artisanats SASU</title>
  <style>
    :root {
      --couleur-principale: #c2a676;
    }
    body {
      font-family: "Georgia", serif;
      margin: 0;
      background: white;
      color: #333;
      line-height: 1.6;
    }
    header {
      background: white;
      border-bottom: 1px solid #ddd;
      display: flex;
      align-items: center;
      justify-content: space-between;
      padding: 10px 40px;
      flex-wrap: wrap;
    }
    header img {
      height: 60px;
    }
    nav a {
      text-decoration: none;
      color: #555;
      margin: 0 12px;
      font-weight: 500;
    }
    nav a:hover {
      color: var(--couleur-principale);
    }
    .hero {
      background: url('[images.unsplash.com](https://images.unsplash.com/photo-1576847445919-44d1c0ec2c6c?auto=format&fit=crop&w=1600&q=80)') center/cover no-repeat;
      color: white;
      text-align: center;
      padding: 120px 20px;
    }
    .hero h2 {
      font-size: 2.3em;
      margin-bottom: 10px;
      text-shadow: 1px 1px 3px rgba(0,0,0,0.7);
    }
    .hero p {
      font-size: 1.2em;
      margin-bottom: 25px;
      text-shadow: 1px 1px 2px rgba(0,0,0,0.6);
    }
    .hero a {
      text-decoration: none;
      background: var(--couleur-principale);
      color: white;
      padding: 12px 25px;
      border-radius: 4px;
      font-weight: bold;
    }
    h3 {
      text-align: center;
      margin-bottom: 20px;
      font-size: 1.7em;
    }
    .services, .realisations {
      display: flex;
      flex-wrap: wrap;
      justify-content: space-around;
      text-align: center;
      max-width: 1000px;
      margin: auto;
    }
    .service {
      flex: 1 1 220px;
      padding: 15px;
      margin: 10px;
      border: 1px solid #eee;
      border-radius: 8px;
    }
    .service h4 {
      color: var(--couleur-principale);
    }
    .about, .contact {
      text-align: center;
      max-width: 800px;
      margin: auto;
    }
    .realisations img {
      width: 100%;
      border-radius: 6px;
      margin-bottom: 15px;
    }
    footer {
      background: #f2f2f2;
      text-align: center;
      padding: 25px;
      font-size: 0.9em;
      color: #666;
    }
    @media (max-width: 700px) {
      header {
        flex-direction: column;
      }
      nav { margin-top: 10px; }
      .services, .realisations { flex-direction: column; }
    }
  </style>
</head>
<body>
  <header>
    <img src="logo.png" alt="Logo Bernardi & Fils Artisanats" />
    <nav>
      <a href="#accueil">Accueil</a>
      <a href="#services">Services</a>
      <a href="#realisations">Réalisations</a>
      <a href="#apropos">À propos</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>
  <section class="hero" id="accueil">
    <h2>L’élégance du marbre, la précision de l’artisanat</h2>
    <p>Vente et pose de marbre, carrelage, parquet et finitions de qualité.</p>
    <a href="mailto:contact.bernardiartisanats@gmail.com">Demander un devis</a>
  </section>
  <section id="services">
    <h3>Nos Services</h3>
    <div class="services">
      <div class="service">
        <h4>Marbre & Pierre naturelle</h4>
        <p>Vente, pose, ponçage et   cristallisation de marbre et
          moquette de pierre
          pour un rendu d’exception.</p>
      </div>
      <div class="service">       <h4>Revêtements de sols et murs</h4>
        <p>Pose de carrelage, mosaïque et parquet selon vos envies et vos styles.</p>
      </div>
      <div class="service">
        <h4>Rénovation complète</h4>
        <p>Peinture, plaquisterie, plomberie et électricité, clés en main.</p>
      </div>
      <div class="service">
        <h4>Nettoyage & Finitions</h4>
        <p>Nettoyage de fin de chantier pour un rendu propre et soigné.</p>
      </div>
    </div>
  </section>
  <section id="apropos">
    <h3>À propos</h3>
    <div class="about">
      <p><strong>Bernardi & Fils Artisanats SASU</strong> est une entreprise familiale reconnue pour la qualité de son savoir-faire artisanal.  
      Chaque projet est réalisé avec passion, précision et respect des délais.</p>
    </div>
  </section>
  <section id="realisations">
    <h3>Nos Réalisations</h3>
    <div class="realisations">
      <img src="[images.unsplash.com](https://images.unsplash.com/photo-1615561048562-a2cde3f5aa0e?auto=format&fit=crop&w=900&q=80)" alt="Sol en marbre" />
      <img src="[images.unsplash.com](https://images.unsplash.com/photo-1599204854871-4090eea212cd?auto=format&fit=crop&w=900&q=80)" alt="Parquet et finitions" />
    </div>
  </section>
  <section id="contact">
    <h3>Contact</h3>
    <div class="contact">
      <p>📞 <a href="tel:+33659948495">06 59 94 84 95</a><br />
         📧 <a href="mailto:.bernardilionel69@gmail.com">bernardilionel69@gmail.com</a></p>
      <p>Nous répondrons rapidement à toutes vos demandes de devis ou de renseignements.</p>
    </div>
  </section>
  <footer>
    © 2024 Bernardi & Fils Artisanats SASU – Tous droits réservés
  </footer>
</body>
</html>
