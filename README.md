<html>
<head>
<style> 
.flex-container {
    display: -webkit-flex;
    display: flex;  
    -webkit-flex-flow: row wrap;
    flex-flow: row wrap;
    text-align: center;
}

.flex-container > * {
    padding: 15px;
    -webkit-flex: 1 100%;
    flex: 1 100%;
}

.article {
    text-align: left;
}

/* Style The Dropdown Button */
.dropbtn {
    background-color: #0B3B39;
    color: white;
    padding: 16px;
    font-size: 16px;
    border: none;
    cursor: pointer;
}

/* The container <div> - needed to position the dropdown content */
.dropdown {
    position: relative;
    display: inline;
}

/* Dropdown Content (Hidden by Default) */
.dropdown-content {
    display: none;
    position: absolute;
    background-color: none;
    min-width: 160px;
    box-shadow: 0px 8px 16px 0px rgba(0,0,0,0.2);
    z-index: 1;
}

/* Links inside the dropdown */
.dropdown-content a {
    color: white;
    padding: 12px 16px;
    text-decoration: circle;
    display: block;
}

/* Change color of dropdown links on hover */
.dropdown-content a:hover {background-color: powderblue}

/* Show the dropdown menu on hover */
.dropdown:hover .dropdown-content {
    display: block;
    position: absolute;
}

/* Change the background color of the dropdown button when the dropdown content is shown */
.dropdown:hover .dropbtn {
    background-color: #0B3B39;
}

footer {background: #aaa;color:white;}


@media all and (min-width: 768px) {
    .article {-webkit-flex:5 0px;flex:5 0px;-webkit-order:2;order:2;}
    footer {-webkit-order:3;order:3;}
}

</style>

<body style="background-color:powderblue;">

<div class="flex-container">

<div class="dropdown">
<button class="dropbtn"><a href="#">Accueil</a></button>
    </div>
  
<div class="dropdown">
  <button class="dropbtn">Un problème de santé publique</button>
  <div class="dropdown-content">
    <a href="#">Article 1</a>
    <a href="#">Article 2</a>
    <a href="#">Article 3</a>
    </div>  

<div class="dropdown">
  <button class="dropbtn">Des intérêts confrontés</button>
  <div class="dropdown-content">
    <a href="#">Article 1</a>
    <a href="#">Article 2</a>
    <a href="#">Article 3</a>
  </div>

<div class="dropdown">
  <button class="dropbtn">Une législation difficile</button>
  <div class="dropdown-content">
    <a href="#">Article 1</a>
    <a href="#">Article 2</a>
    <a href="#">Article 3</a>
  </div>
</div>



<article class="article">
  <h1>Introduction</h1>
  <p>Nous sommes six étudiantes du double cursus Sciences et Sciences Sociales entre SciencesPo et l'université Pierre et Marie Curie.</p>
  <p><strong>Venez découvrir la controverse!</strong></p>
  
<p>Cliquer sur les produits pour les voir de plus près:</p>

<img src="perturbateurs endocriniens.jpg" alt="Perturbateurs endocriniens" usemap="#pertumap" style="width:600px;height:600px;">

<map name="pertumap">
  <area shape="rect" coords="45,195,140,430" alt="Biberon" href="http://social-sante.gouv.fr/sante-et-environnement/risques-microbiologiques-physiques-et-chimiques/article/bisphenol-a">
</map>
   
</article>

<footer>Copyright &copy; The Best</footer>
</div>

</body>
</html>
