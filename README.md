# Test-Technique-pour-D-veloppeur-fullstack-NodeJS-ReactJS
Test Technique de Développeur fullstack NodeJS/ReactJS pour la société Bericolor



Pour la troisième exercice "Front_end" concernant l'ajout d'un effet parallaxe sur la photo principale ainsi que sur les trois photos des trois chambres j'ai suivi les étapes suivantes: 

1): Tout d'abord j'ai organisé et nettoyé le code html.

2): Pour le parallax j'ai utilisé le plugin JQUERY "paroller.js", qui permet un effet de défilement de parallaxe sur les éléments sélectionnés. Vous pouvez l'utiliser sur des éléments avec une propriété d'arrière-plan ou sur tout autre élément. il est aussi facile à utiliser... 

3)Les étapes d'installation :

 - il faut que la bibliothèque JQUERY soit soit déjà présentée, ou il faut le télécharger et le mettre dans le code comme ça
  <script src="jquery.paroller.min.js"></script> 

  - aussi il faut initialiser "paroller.js" en ajout le code suivant:
   <script> $('.mega').paroller(); </script>

4)L'utilisation: 

  - En ajout le nom de class "mega" dans le HTML. 

  -Pour activer l'effet de défilement parallaxe, vous pouvez utiliser les attributs data-paroller- * sur les éléments sélectionnés  ou définir des valeurs via jQuery.'facteur' définit la vitesse et la distance de l'effet de parallaxe de l'élément sur le défilement.

  et finalement j'ai ajouter le class "mega" et les et les propriétés de bibliothèque paralox.js dans mes 3 images .


<img alt="Suite Club" class="mega align-center" data-paroller-factor="0.1" data-paroller-type="foreground" src="img/suiteclub/2m-min.jpg"> 
    
<img alt="Suite Club" class="mega align-center" data-paroller-factor="0.1" data-paroller-type="foreground" src="img/suiteclub/2m-min.jpg">
      
Et pour la photo principale:

<ul>
   <li class="mega align-center" data-paroller-factor="0.2" data-paroller-transition="transform .2s linear" data-paroller-type="foreground"><img alt="piscine" src="img/accueil/accueil55m-min.jpg"></li>
 </ul>

