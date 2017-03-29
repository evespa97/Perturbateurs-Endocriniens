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

header {background: #0B3B39;color:white;}
footer {background: #aaa;color:white;}
.nav {background:#088A85;color:black}

.nav ul {
    list-style-type: none;
    padding: 0;
}
.nav ul a {
    text-decoration: none;
}

@media all and (min-width: 768px) {
    .nav {text-align:left;-webkit-flex: 1 auto;flex:1 auto;-webkit-order:1;order:1;}
    .article {-webkit-flex:5 0px;flex:5 0px;-webkit-order:2;order:2;}
    footer {-webkit-order:3;order:3;}
}
</style>
</head>

<body style="background-color:powderblue;">

<div class="flex-container">
<header>
  <h1>Les Perturbateurs endocriniens</h1>
</header>

<nav class="nav">
<ul>
  <li><a href="#">Un problème de santé publique</a></li>
  <li><a href="#">Des intérêts confrontés</a></li>
  <li><a href="#">Une législation difficile</a></li>
</ul>
</nav>

<article class="article">
  <h1>Introduction</h1>
  <p>Nous sommes six étudiantes du double cursus Sciences et Sciences Sociales entre SciencesPo et l'université Pierre et Marie Curie.
  <strong>Venez découvrir la controverse!</strong></p>
  
<p>Cliquer sur les produits pour les voir de plus près:</p>

<img src="perturbateurs endocriniens.jpg" alt="Perturbateurs endocriniens" usemap="#pertumap" style="width:600px;height:600px;">

<map name="pertumap">
  <area shape="rect" coords="55,190,140,430" alt="Biberon" href="http://social-sante.gouv.fr/sante-et-environnement/risques-microbiologiques-physiques-et-chimiques/article/bisphenol-a">
</map>
   
</article>

<footer>Copyright &copy; The Best</footer>
</div>

</body>
</html>
