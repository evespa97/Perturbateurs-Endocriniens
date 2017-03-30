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

.dropdown {
    position: relative;
    display: inline-block;
}

.dropdown-content {
    display: none;
    position: absolute;
    background-color: #0B3B39;
    min-width: 160px;
    box-shadow: 0px 8px 16px 0px rgba(0,0,0,0.2);
    padding: 12px 16px;
    z-index: 1;
}

.dropdown:hover .dropdown-content {
    display: block;
}

header {background: #0B3B39;color:white;}
footer {background: #aaa;color:white;}

header {
    list-style-type:none;
    padding:0;
}

@media all and (min-width: 768px) {
    .article {-webkit-flex:5 0px;flex:5 0px;-webkit-order:2;order:2;}
    footer {-webkit-order:3;order:3;}
}
</style>
</head>

<body style="background-color:powderblue;">

<div class="flex-container">
<header>
  <ul>
  <li><a href="Explications scientifiques.md">Un problème de santé publique</a></li>
  <li><a href="#">Des intérêts confrontés</a></li>
  <li><a href="#">Une législation difficile</a></li>
</ul>
</header>

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

<div class="dropdown">
  <span>Mouse over me</span>
  <div class="dropdown-content">
    <p>Hello World!</p>
  </div>
</div>

</body>
</html>
