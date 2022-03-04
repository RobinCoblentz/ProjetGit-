# ProjetGit
<h1>Découvrons git à travers un projet de site vitrine.</h1> <br>
<h3>Le but de ce projet est la découverte des outils git, et l'amélioration des compétances html/css</h3> <br>

<ul><h4>Participant :</h4>
<br>
  <li>Rédouan Rémili </li>
  <li>Amel Krifah  </li>
  <li>Robin Coblentz </li>
  <li>Coline Salvi</li>
  </ul>
<br>

<h3>Présentation</h3>

<p>Le projet sera un onepage séparé en plusieurs séctions, qui aura pour but la présentation d'une agence de dev freelence.
Chaque séction sera géré par une personne, afin de limiter les conflit.</p>

<h3>Technologie</h3>

<p>On utilisera une stack html/css/js, un framework gulp et bootstrap pour gagner du temps et optimiser le workflow des taches répétitive.</p>

<h3>Workflow</h3>

<ul><h4>On utilisera 4 branches :</h4><br>

<li>Homepage (sert a développer pour Robin)</li><br>
<li>preprod (sert de branche de visu)</li><br>
<li>dev (branche propre au developpement)</li><br>
<li>main (sert de branche de recette)</li><br>
<li>amel (sert a développer pour Amel)</li><br>
</ul><br>
Chacun des membre du groupe doit avoir sa propre branch car même si nous travaillons sur des fichiers diférents, si l'on push tous sur la même branch cela posera des problème et des conflits car il faudra que l'on arrête tous notre travail et que l'on pull à chaque nouveau push d'un membre du groupe. Alors que si l'on travail sur des branch chacun nous pouvons push tant que l'on veut car il s'agit de notre branch perso. Et c'est seulement la branch develop puis main qui nécessitera des pull request.  

<h3>Source</h3>

<p>On utilisera une maquette de laquelle on s'inspirera</p><br>
<a>https://pin.it/5c259q6</a>

<p>Nous utiliseront la version 5.1 de bootsrtap, car elle comporte des animation et des éléments proche de la maquette</p><br>
<a>https://getbootstrap.com/docs/5.1/getting-started/download/</a>

<p>Gulp sera utilisé pour l'optimisation de l'intégration des images</p><br>
<a>https://gulpjs.com</a>

<p>Unsplash nous servira de banque d'image libre de droit</p><br>
<a>https://unsplash.com/</a>

<p>Undraw servira de banque de graphisme d'animation</p><br>
<a>https://undraw.co/search</a>


<h3>Plan d'action</h3>

<p>Le développement du site sera répartie entre les 4 participants de la manière suivante:</p><br>

<p>Coline Salvi s'occupera du header</p><br>
<p>Robin Coblentz s'occupera de la partie objectif</p><br>
<p>Amel Krifah s'occupera de la partie cards</p><br>
<p>Rédouan Rémili s'occupera du footer</p><br><br>

<p>Afin d'éviter au maximum les conflits, chaques parties sera développé dans un fichier différant.</p><br>
<p>Chaque partie sera développé dans section</p><br>
<p>On fusionnera par la suite les parties dans le fichier index.html</p><br>

<h3>Problematique</h3>
<p>Plusieurs même branch dev ont été créer car lors d'un push -u. Objectif : crer une branch temporaire (temp) à partir de la branch dev avec la commande "git branch temp", puis push la branch. Ensuite supprimer les 2 branch dev, crer une nouvelle branch develop unique (à partir de temp) et faire une merge des branch temp et develop nouvellement créer. Pour finir, supprimer la branch temp. 
Il s'agit ensuite de communiquer ces changement au reste du groupe pafin que chacun d'eux supprime le branch dev en local et fasse un "git fetch" pour recuperer la nouvelle branch develop</p>
<h3>Travaille fait</h3>
<p> On c'est répartit les tâches. On c'est chacun positionner sur une branche pour développer sans soucis</p>

