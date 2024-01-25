<!DOCTYPE html>
<html lang="fr">
<meta charset="UTF-8">
<meta http-equiv="X-UA-Compatible" content="IE=edge">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<head>
    <title>Accueil</title>
    <!--lien(s) css-->
    <link rel="stylesheet" href="style.css">
    <link rel="robots" href="/robots.txt">
    <!--Liens pour fichier favicon-->
    <link rel="icon" href="/favicon.ico" type="image/x-icon" />
    <!--liens bootstrapt css et js-->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css" rel="stylesheet"
        integrity="sha384-EVSTQN3/azprG1Anm3QDgpJLIm9Nao0Yz1ztcQTwFspd3yD65VohhpuuCOmLASjC" crossorigin="anonymous">

    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/js/bootstrap.bundle.min.js"
        integrity="sha384-MrcW6ZMFYlzcLA8Nl+NtUVF0sA7MsXsP1UyJoMp4YLEuNSfAP+JcXn/tWtIaxVXM"
        crossorigin="anonymous"></script>

</head>
<body>
    <header>
    <nav class="navbar navbar-expand-lg navbar-light color-navbar" id="navbar-padding">
        <a class="navbar-brand" href="accueil.html"><h1 id="titreh1">Le bien être par le massage</h1></a>
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation" id="button-toggle" >
          <span class="navbar-toggler-icon" id="bar-toggle-icon"></span>
        </button>
        <div class="collapse navbar-collapse navbar_modif" id="navbarNav">
          <ul class="navbar-nav">
            <li class="nav-item active margin_elmt_navbar">
              <a class="nav-link" href="accueil.html"><h3 class="font-size-h3">Philosophie</h3></a>
            </li>
            <li class="nav-item margin_elmt_navbar">
              <a class="nav-link" href="prestations.html"><h3 class="font-size-h3">Prestations</h3></a>
            </li>
            <li class="nav-item margin_elmt_navbar">
              <a class="nav-link" href="gallerie.html"><h3 class="font-size-h3">Galerie</h3></a>
            </li>
            <li class="nav-item margin_elmt_navbar">
              <a class="nav-link" href="contact.html"><h3 class="font-size-h3">Contact</h3></a>
            </li>
          </ul>
        </div>
      </nav>
    </header>
    <main>
      <div class="row">
        <div class="col content-center">
          <img class="samuel_1" src="samuel_1.jpeg" alt="samuel_1">
        </div>
        <div class="col start-left">
          <div class="format-colum">
            <h2 class="titre-h2">Philosophie de vie</h2>
            <p class="backgroud-p">J’ai toujours placé l’humain au centre de mes préoccupations, c’est la raison pour laquelle 
              je me suis lancé dans le massage bien être. </p>
            <p class="backgroud-p">Voici quelques années, j’ai reçu un massage californien et cela a été un merveilleux voyage. 
              Après un échange avec le masseur et je me suis dit : pourquoi ne pas me former pour à mon 
              tour essayer de procurer aux gens ces sensations. </p>
          </div>
        </div>
      </div>
      <div class="row margin_bottom">
        <div class="col start-end">
          <div class="format-colum">
            <p class="backgroud-p">Les épreuves de la vie m'ont appris qu’il était primordial de prendre soin de sa santé mentale et physique. 
              Le massage bien être vous apportera un regain de vitalité ainsi qu’une déconnexion totale de l’esprit. Vous en ressortirez plus apaisé, détendu, avec je l’espère un regard plus positif sur votre vie. </p>
            <p class="backgroud-p">Durant la séance, nous prendrons le temps d’échanger sur vos besoins et émotions du moment. 
                Ensuite j’adapterais le massage en fonction de vos attentes.</p>
          </div>
        </div>
        <div class="col content-center"> 
          <img class="Encens" src="encens.jpeg" alt="Encens">
        </div> 
      </div>
    </main>
  </body>
  <footer class="footer-format">
    <div class="div_footer_format">
        <a  id="contact_link" class="contact_footer" href="contact.html"><h4>Contact</h4></a>
        <a class="" href="https://www.instagram.com/samuel.plumerat?igsh=dXliZ280MmFwbm8y" target="_blank"><img class="itg_logo" src="itg_logo.png" alt="Instagram"></a>
      </div>
  </footer>
</html>
