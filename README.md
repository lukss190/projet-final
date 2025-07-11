<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8">
  <title>Salon Holla - Coiffure</title>
  <style>
    * {
      box-sizing: border-box;
    }

    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background-color: #fff8f9;
    }

    header {
      position: relative;
      text-align: center;
      color: white;
    }

    header img {
      width: 100%;
      height: 300px;
      object-fit: cover;
      filter: brightness(65%);
    }

    header h1 {
      position: absolute;
      top: 50%;
      left: 50%;
      transform: translate(-50%, -50%);
      font-size: 3.5em;
      margin: 0;
      text-shadow: 2px 2px 6px rgba(0,0,0,0.5);
    }

    section {
      max-width: 1000px;
      margin: 40px auto;
      padding: 0 20px;
    }

    h2 {
      color: #c2185b;
      text-align: center;
      margin-bottom: 20px;
    }

    .services {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
      gap: 20px;
      text-align: center;
    }

    .service {
      background-color: #ffe4ec;
      padding: 20px;
      border-radius: 12px;
      box-shadow: 0 0 8px rgba(0,0,0,0.1);
    }

    .reservation-form {
      background-color: white;
      padding: 30px;
      border-radius: 16px;
      box-shadow: 0 0 20px rgba(0,0,0,0.1);
      max-width: 500px;
      margin: 30px auto;
    }

    label {
      display: block;
      margin-top: 15px;
      font-weight: bold;
    }

    input, select {
      width: 100%;
      padding: 10px;
      margin-top: 5px;
      border: 1px solid #ccc;
      border-radius: 8px;
    }

    .btn-reserver {
      margin-top: 25px;
      display: block;
      width: 100%;
      padding: 12px;
      background-color: #eec197;
      color: white;
      text-align: center;
      text-decoration: none;
      font-size: 16px;
      border-radius: 10px;
    }

    .btn-reserver:hover {
      background-color: #f5cf7d;
    }

    footer {
      text-align: center;
      padding: 20px;
      background-color: #f8f8f8;
      color: #666;
      margin-top: 40px;
    }
  </style>
</head>
<body>

  <!-- Bannière -->
  <header>
    <img src="https://i.pinimg.com/736x/1f/2f/32/1f2f3228eec5b82eecb5ca094bba002f.jpg" alt="Salon Holla">
    <h1>Salon Holla</h1>
  </header>

  <!-- Présentation -->
  <section>
    <h2>Bienvenue chez Salon Holla</h2>
    <p style="text-align:center;">Nous vous accueillons avec passion pour sublimer votre beauté. Profitez de nos services professionnels dans une ambiance chaleureuse à Alger.</p>
  </section>

  <!-- Nos services -->
  <section>
    <h2>Nos services</h2>
    <div class="services">
      <div class="service">
        <h3>Coupe</h3>
        <p>Pour femmes, hommes et enfants.</p>
      </div>
      <div class="service">
        <h3>Brushing</h3>
        <p>Un look impeccable pour chaque occasion.</p>
      </div>
      <div class="service">
        <h3>Coloration</h3>
        <p>Exprimez votre style avec nos colorations tendance.</p>
      </div>
      <div class="service">
        <h3>Soin capillaire</h3>
        <p>Offrez santé et éclat à vos cheveux.</p>
      </div>
    </div>
  </section>

  <!-- Réservation -->
  <section>
    <h2>Réservez une séance</h2>
    <form class="reservation-form">
      <label for="nom">Nom complet</label>
      <input type="text" id="nom" name="nom" required>

      <label for="tel">Téléphone</label>
      <input type="tel" id="tel" name="tel" required>

      <label for="service">Service</label>
      <select id="service" name="service" required>
        <option value="">-- Choisissez un service --</option>
        <option value="coupe">Coupe</option>
        <option value="brushing">Brushing</option>
        <option value="coloration">Coloration</option>
        <option value="soin">Soin capillaire</option>
      </select>

      <label for="date">Date</label>
      <input type="date" id="date" name="date" required>

      <label for="heure">Heure</label>
      <input type="time" id="heure" name="heure" required>

      <!-- Lien vers watessap ou un vrai site -->
      <a href="https://wa.me/213661234567" class="btn-reserver" target="_blank">
        Réserver sur wetsap
      </a>
    </form>
  </section>

  <!-- Pied de page -->
  <footer>
    &copy; 2025 Salon Holla - Tous droits réservés
  </footer>

</body>
</html>
