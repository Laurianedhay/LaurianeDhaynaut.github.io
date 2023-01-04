<!DOCTYPE html>
<!-- rgb(165, 108, 184) -->
<html>
<head>
<title>Lauriane Dhaynaut</title>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href=ePortfolio2.css>
<link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Montserrat">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
<script src="https://kit.fontawesome.com/ecff8d8d3f.js" crossorigin="anonymous"></script>

<style>

</style>
</head>
<body>

<!-- Icon Bar (Sidebar - hidden on small screens) -->
<nav class="nav w3-hide-small petite-ecriture">
  <!-- Avatar image in top left corner -->
  <img src="images/nvLogo1.png" class="logo">
  <hr class="barre">
  <a href="#" class=" button-nav">
    <i class="fa fa-home icones"></i>
    <p>ACCUEIL</p>
  </a>
  <a href="#competences" class=" button-nav" >
    <i class="fa fa-user icones"></i>
    <p>COMPETENCES</p>
  </a>
  <a href="#projects" class=" button-nav">
    <i class="fa fa-eye icones"></i>
    <p>PROJETS</p>
  </a>
  <a href="#parcours" class=" button-nav">
    <i class="fas fa-solid fa-user-graduate icones"></i>
    <p>FORMATIONS</p>
  </a>
  <a href="#contact" class=" button-nav">
    <i class="fa fa-envelope icones"></i>
    <p>CONTACT</p>
  </a>
</nav>

<!-- Navbar on small screens (Hidden on medium and large screens) -->
<div class="w3-top w3-hide-large w3-hide-medium" id="myNavbar">
  <div class="w3-bar w3-black w3-opacity w3-hover-opacity-off w3-center w3-small">
    <a href="#" class="w3-bar-item button-nav" style="width:20% !important">ACCUEIL</a>
    <a href="#competences" class="w3-bar-item button-nav" style="width:20% !important">COMPETENCES</a>
    <a href="#projects" class="w3-bar-item button-nav" style="width:20% !important">PROJETS</a>
    <a href="#parcours" class="w3-bar-item button-nav" style="width:20% !important">FORMATIONS</a>
    <a href="#contact" class="w3-bar-item button-nav" style="width:20% !important">CONTACT</a>
  </div>
</div>

<!-- Page Content -->
<div class="everything">
  <!-- Header/Home -->
  <header>
    <h1> Lauriane Dhaynaut</h1>
    <p>Developpeur en alternance chez Benalu</p>
    <img src="images/10FDA8A8-41CA-4A3E-B6D4-98143BDAB007.jpg" alt="boy" class="image" width="992" height="1108">
  
  </header>
  <a href="images/Lauriane_Dhaynaut.pdf" download>
    <button class="button">
      
      <i class="fa fa-download"></i>Télécharger mon CV
    </button>
  </a> 



  <!-- About Section -->
  <div class="about">
    <h2>À propos de moi</h2>
    <hr class="barre">
    <p>Actuellement étudiante en alternance à l'IUT de Lille en BUT informatique, je souhaite développer mes compétences informatiques 
    </p>
  </div>

  <!-- Competences Section -->
  <div id="competences">
    <h2 class="w3-text-light-grey">Mes compétences</h2>
    <hr class="barre">
    <h3> Langages : </h3>
    <div class="w3-row w3-center w3-padding-16 w3-section w3-light-grey">
      <div class="w3-quarter w3-section">
        <span><img src="images/java.png" alt="LogoJava" class="image" ></span><br>
        Java
      </div>
      <div class="w3-quarter w3-section">
        <span><img src="images/html:css.png" alt="LogoHTMLCSS" class="image" ></span><br>
        HTML/CSS
      </div>
      <div class="w3-quarter w3-section">
        <span><img src="images/c.png" alt="LogoC" class="image" ></span><br>
        C
      </div>
      <div class="w3-quarter w3-section">
        <span class="w3-xlarge"><img src="images/js.png" alt="LogoJavaScript" class="image" ></span><br>
        JavaScript
      </div>
    </div>

    <h3 class="w3-padding-16 w3-text-light-grey"> Outils : </h3>
    <div class="w3-row w3-center w3-padding-16 w3-section w3-light-grey">
      <div class="w3-quarter w3-section">
        <span class="w3-xlarge"><img src="images/github.png" alt="LogoJava" class="image" ></span><br>
        Github
      </div>
      <div class="w3-quarter w3-section">
        <span class="w3-xlarge"><img src="images/gitlab.png" alt="LogoHTMLCSS" class="image" ></span><br>
        Gitlab
      </div>
      <div class="w3-quarter w3-section">
        <span class="w3-xlarge"><img src="images/vsc.png" alt="LogoC" class="image" ></span><br>
        Visual Studio Code
      </div>
      <div class="w3-quarter w3-section">
        <span class="w3-xlarge"><img src="images/eclipse.png" alt="LogoJavaScript" class="image" ></span><br>
        Eclipse
      </div>
    </div>

    <h3 class="w3-padding-16 w3-text-light-grey"> Bases de données : </h3>
    <div class="w3-row w3-center w3-padding-16 w3-section w3-light-grey">
      <div class="w3-quarter w3-section">
        <span class="w3-xlarge"><img src="images/postgresql.png" alt="LogoJava" class="image" ></span><br>
        PostgreSQL
      </div>
      <div class="w3-quarter w3-section">
        <span class="w3-xlarge"><img src="images/mongodb.png" alt="LogoHTMLCSS" class="image" ></span><br>
        MongoDB
      </div>
    </div>
  </div>
   
  <div id="projects">
    <!-- Grid for pricing tables -->
    <h2>Mes projets</h2>
    <hr class="barre">
    <div class="contenant">
      <div class="item1">
        <ul style="list-style-type: none;">
          <li class=" w3-xlarge w3-padding-32">Affectation tuteurs/tutorés</li>
          <li><img src="images/tuteurs.png" alt="AppTuteurs" class="image2" ><br></li>
          <li class="w3-padding-16">Langages utilisés : Java/JavaFX </li>
          <li class="w3-padding-24">
            <button class="button-project w3-padding-16">Bientôt disponible</button>
          </li>
        </ul>
      </div>

      <div class="item2">
        <a href="site/index2.html" style="text-decoration: none;" download>
        <ul style="list-style-type: none;">
          <li class=" w3-xlarge w3-padding-32">Création d'un site pour l'université </li>
          <li><img src="images/moovle.png" alt="siteMoovle" class="image2" ><br></li>
          <li class="w3-padding-16">Langages utilisés : HTML/CSS</li>
          <li class="w3-padding-24 ligne">
            <button class="button-project w3-padding-16">Voir</button>
          </li>
        </ul>
        </a>
      </div>
    <!-- End Grid/Pricing tables -->
    </div>
  </div>
  
  <!-- Parcours Section -->
  <div id="parcours">
    <h2>Mon parcours</h2>
    <hr class="barre">

    <section id="education">
      <div class="container">
          <div class="white-divider"></div>
          <div class="heading">
          </div>
          <div class="col-md-12">
              <ul class="timeline" style="list-style-type: none;">
                  <li id="panel3" style="display: block;">
                      <div class="timeline-badge"><img src="images/iut.jpg" alt="logo iut"> </div>
                      <div class="timeline-panel-container-inverted">
                          <div class="timeline-panel">
                              <div class="timeline-heading">
                                  <h3>IUT de Vileneuve d'Ascq</h3>
                                  <h4>BUT informatique</h4>
                                  <p class="text-muted"><span class="bi bi-clock-fill"></span> Septembre 2021 - Juillet 2024</p>
                              </div>
                              <div class="timeline-body">
                                  <p>Ce BUT nous forme afin de pouvoir aborder le monde du travail que ça soit dans la programmation ou dans le réseau et système</p>
                              </div>
                          </div>
                      </div>
                  </li>
                  <li>
                      <div class="panel2" id="panel4" style="display: block;">
                          <div class="timeline-badge"><img src="images/Palm B.webp" alt="logo palm"> </div>
                          <div class="timeline-panel-container">
                              <div class="timeline-panel">
                                  <div class="timeline-heading">
                                      <h3>Le Palm B - Serveuse</h3>
                                      <h4>Bandol, France</h4>
                                      <p class="text-muted"><span class="bi bi-clock-fill"></span> Mai 2020 - Septembre 2020</p>
                                      <p class="text-muted"><span class="bi bi-clock-fill"></span> Juin 2021 - Août 2021</p>
                                  </div>
                                  <div class="timeline-body">
                                      <p>Développement de mon esprit d'équipe, de ma rapidité.</p>
                                  </div>
                              </div>
                          </div>
                      </div>
                  </li>
                  <li>
                      <div class="timeline-badge"><img src="images/uberEats.jpeg" alt="logo uberEats"> </div>
                      <div class="timeline-panel-container-inverted">
                          <div class="timeline-panel">
                              <div class="timeline-heading">
                                  <h3>UberEats - Service Clientèle</h3>
                                  <h4>Lisbonne, Portugal</h4>
                                  <p class="text-muted"><span class="bi bi-clock-fill"></span> Septembre 2019 - Mai 2020</p>
                              </div>
                              <div class="timeline-body">
                                  <p>Prendre en charge les demandes et et problèmes des restaurateurs
                                    Respecter les procédures internes quant à la résolution du problème tout en assurant la meilleure qualité de service</p>
                              </div>
                          </div>
                      </div>
                  </li>
                  <li id="panel" style="display: block;">
                      <div class="timeline-badge"><img src="images/lespark.jpeg" alt="logo le s'park"> </div>
                      <div class="timeline-panel-container">
                          <div class="timeline-panel">
                              <div class="timeline-heading">
                                  <h3>Restaurant Le S'park, serveuse</h3>
                                  <h4>Lezennes, France</h4>
                                  <p class="text-muted"><span class="bi bi-clock-fill"></span> Août 2018 - Septembre 2019</p>
                              </div>
                              <div class="timeline-body">
                                  <p>Servir les clients et veiller au bon déroulement de leurs repas</p>
                              </div>
                          </div>
                      </div>
                  </li>
                  <li>
                      <div id="panel" style="display: block;">
                          <div class="timeline-badge"><img src="images/facLille.png" alt="logoFacLille"> </div>
                          <div class="timeline-panel-container-inverted">
                              <div class="timeline-panel">
                                  <div class="timeline-heading">
                                      <h3>Faculté de Biologie - Licence Biochimie</h3>
                                      <h4>Villeneuve d'Ascq, France</h4>
                                      <p class="text-muted"><span class="bi bi-clock-fill"></span> Septembre 2015 - Juin 2019</p>
                                  </div>
                                  <div class="timeline-body">
                                      <p></p>
                                  </div>
                              </div>
                          </div>
                      </div>
                  </li>
                  <li>
                      <div class="timeline-badge"><img src="images/téléchargement.png" alt="logo lycée Alexandre Ribot"> </div>
                      <div class="timeline-panel-container">
                          <div class="timeline-panel">
                              <div class="timeline-heading">
                                  <h3>Lycée Alexandre Ribot - Baccalauréat scientifique</h3>
                                  <h4>Saint-Omer, France </h4>
                                  <p class="text-muted"><span class="bi bi-clock-fill"></span> Septembre 2011 - Juin 2014</p>
                              </div>
                              <div class="timeline-body">
                                  <p>Spécialité SVT, mention assez-bien</p>
                              </div>
                          </div>
                      </div>
                  </li>
              </ul>
          </div>
      </div>
  </section>
  <!-- End Parcours Section -->
  </div>

  <!-- Contact Section -->
  <div id="contact">
    <h2>Me contacter</h2>
    <hr class="barre">

    <div class="w3-section">
      <p><i class="fa fa-map-marker fa-fw w3-text-white w3-xxlarge w3-margin-right"></i> Lille, France</p>
      <p><i class="fa fa-phone fa-fw w3-text-white w3-xxlarge w3-margin-right"></i> Téléphone : +33 6 99 81 56 80</p>
      <p><i class="fa fa-envelope fa-fw w3-text-white w3-xxlarge w3-margin-right"> </i> Email: dhaynautlauriane@gmail.com</p>
    </div><br>
    <p>N'hésitez pas à m'envoyer un message : </p>

    <form action="/action_page.php" target="_blank">
      <p><input class="w3-input w3-padding-16" type="text" placeholder="Name" required name="Name"></p>
      <p><input class="w3-input w3-padding-16" type="text" placeholder="Email" required name="Email"></p>
      <p><input class="w3-input w3-padding-16" type="text" placeholder="Subject" required name="Subject"></p>
      <p><input class="w3-input w3-padding-16" type="text" placeholder="Message" required name="Message"></p>
      <p>
        <button class="button" type="submit">
          <i class="fa fa-paper-plane"></i> ENVOYER
        </button>
      </p>
    </form>
  <!-- End Contact Section -->
  </div>
  
    <!-- Footer -->
  <footer class="divisions">
    <i class="fa fa-linkedin"><p>Lauriane Dhaynaut</p></i>
  <!-- End footer -->
  </footer>

<!-- END PAGE CONTENT -->
</div>

</body>
</html>
