# testreact
<!DOCTYPE html>
<html>
<head>
<meta charset="utf-8">
<style type="text/css">
*{
margin: 0px;
padding: 0px;
font-family: Avenir, sans-serif;
}
nav{
width: 100%;
  margin: 0px auto 20px auto;
background-color: white;
position: sticky;
top: 0px;
}
nav ul{
list-style-type: none;
}
  nav li{
float: left;
width: 20%;/*100% divisé par le nombre d'éléments de menu*/
text-align: center;/*Centre le texte dans les éléments de menu*/
}
/*Evite que le menu n'ait une hauteur nulle*/
nav ul::after{
content: "";
display: table;
clear: both;
}
nav a{
display: block; /*Toute la surface sera cliquable*/
text-decoration: none;
color: black;
border-bottom: 2px solid transparent;/*Evite le décalage des éléments sous le menu à cause de la bordure en :hover*/
padding: 5px 0px;/*Agrandit le menu et espace la bordure du texte*/
}
nav a:hover{
color: orange;
border-bottom: 2px solid gold;
}
</style>
<title>DHIB Yassine</title>
</head>
  <body style="background-image: url(scre.jpg)">
<nav>
<ul>
<li><a href="teste.html">Accueil</a></li>
<li><a href="test.html">Produit d'Asie</a></li>
<li><a href="cv.html">Produit d'Afrique</a></li>
<li><a href="test.html">Produit d'Europe</a></li>
<li><a href="cv.html">Produit d'Amerique</a></li>
</ul>
</nav>
<div>
<h1 style="color:white"> <center> BIENVENUE DANS MON SITE </center></h1>
<p style="color:#4E9ED9; padding: 50px; font-weight: 800; margin: 150px; background-color: black;"> Bienvenue , je me présente Yassine Dhib je suis ravie de vous voir dans mon site et j'espére que vous pourrer
vivre une bonne experience sur mon site et pouvoir vivre de nouvel experience merci bien 
Le but de ce site est de vous proposer un maximun de produit venant des 4 coin du monde . </p>
</div>
<p style="color:white;margin-top:350px"> </p>
</body>
</html> 
