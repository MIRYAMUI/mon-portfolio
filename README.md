<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8">
  <title>Portfolio – Accueil</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: 'Century Gothic', sans-serif;
      background-color: #f5f5f5;
      color: #222;
    }

header {
  background-color: white;
  padding: 20px 40px;
  display: flex;
  justify-content: flex-end;
  gap: 30px;
  box-shadow: 0 2px 4px rgba(0,0,0,0.1);
  position: sticky;
  top: 0;
  z-index: 10;
  border-bottom: 2px solid #353535;
}

    header a {
      text-decoration: none;
      color: #222;
      font-weight: bold;
      font-size: 1rem;
      transition: color 0.3s;
    }

    header a:hover {
      color: #DF98AF;
    }

	.hero {
  background: url('fond.png') no-repeat center center/cover;
  color: white;
}

    .hero {
      height: 90vh;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      text-align: center;
      padding: 0 20px;
    }

    .hero h1 {
      font-size: 2.5rem;
      margin-bottom: 10px;
    }

    .hero p {
      font-size: 1.2rem;
      margin-bottom: 40px;
    }

    .hero a.button {
      background-color: #F7BF2F;
      color: black;
      text-decoration: none;
      padding: 12px 24px;
      border-radius: 6px;
      font-weight: bold;
      transition: background 0.3s;
    }

    .hero a.button:hover {
      background-color: #F7BF2F;
	color: white;
    }

    @media (max-width: 600px) {
      .hero h1 {
        font-size: 1.8rem;
      }

      .hero p {
        font-size: 1rem;
      }

      header {
        justify-content: center;
        flex-wrap: wrap;
        gap: 5px;
      }
    }
  </style>
</head>
<body>

<header>
  <div style="flex: 1;">
    <a href="#accueil">
      <img src="Fichier 1.png" alt="Logo" style="height: 50px;">
    </a>
  </div>
  <nav style="display: flex; gap: 30px;">
    <a href="#accueil">ACCUEIL</a>
    <a href="#projets">PROJETS</a>
    <a href="#contact">CONTACT</a>
  </nav>
</header>


  <section class="hero" id="accueil">
    <h1>Bienvenue sur mon portfolio !</h1>
    <p>Découvrez l’entièreté de mon travail (et de mon parcours) !</p>
    <a href="#projets" class="button">Je découvre</a>
  </section>

  <section id="projets" style="padding: 60px 40px; background-color: #fff; border: 2px solid #353535; border-radius: 3px">
    <h2 style="text-align: center; font-size: 2rem; margin-bottom: 40px; color: #DF98AF;">Mes Projets</h2>

    <div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(250px, 1fr)); gap: 30px;">
      
      <div style="background: #f0f0f0; ; border: 2px solid #353535; border-radius: 8px; overflow: hidden; box-shadow: 0 2px 8px rgba(0,0,0,0.05);">
        <img src="https://via.placeholder.com/400x250" alt="Projet 1" style="width: 100%; display: block;">
        <div style="padding: 20px;">
          <h3 style="margin-bottom: 10px;">Projet 1</h3>
          <p>Courte description de ton projet ici. Parle du contexte, de l'outil utilisé ou du résultat obtenu.</p>
        </div>
      </div>

      <div style="background: #f0f0f0; ; border: 2px solid #353535; border-radius: 8px; overflow: hidden; box-shadow: 0 2px 8px rgba(0,0,0,0.05);">
        <img src="Rectangle 7.png" alt="Projet 2" style="width: 100%; display: block;">
        <div style="padding: 20px;">
          <h3 style="margin-bottom: 10px;">Projet 2</h3>
          <p>Un autre projet. Tu peux mettre un lien, un visuel, ou même un mini texte explicatif.</p>
        </div>
      </div>

      <div style="background: #f0f0f0; ; border: 2px solid #353535; border-radius: 8px; overflow: hidden; box-shadow: 0 2px 8px rgba(0,0,0,0.05);">
        <img src="https://via.placeholder.com/400x250" alt="Projet 3" style="width: 100%; display: block;">
        <div style="padding: 20px;">
          <h3 style="margin-bottom: 10px;">Projet 3</h3>
          <p>Encore un exemple de ton travail ou d'un projet de formation / perso.</p>
        </div>
      </div>

    </div>
  </section>
  <footer style="text-align:center; padding: 30px; background:#222; color: white;">
    &copy; 2025 Miryam Djae – Tous droits réservés
  </footer>

</body>
</html>
