# KaboreLucien_2_01042021

# Environnement Front-End
<br>

### Visual Studio Code

> **Extension Studio Code :** <hr>
> 
>> Live Server
> 
>> GitLens — Git supercharged
> 
>> Bracket Pair Colorizer
> 
>> Firefox
> 
>> Chrome

<br>

## Intégration du contenu conformément à la maquette
<hr>
<br><br>

# Desktop 
<br> <br>

<h2>Header</h2> <br>

### Un entête composer de :

* <p>bar de navigation qui habrite 4 url (le logo, hébergements & activité qui servent de bar d'ancrage pour nous améner dans leurs section respective et le dernier url pour s'inscrire?)</p><br>
* <p>un titre en gras accrocheur et déffinissant la prestation principale du site, ainsi qu'un paragraphe.</p><br>
* <p>Un champ de recherche composer d'un logo,un input avec un placeholder pour indiquer à l'utilisateur un exemple de saisie ainsi qu'un boutton (avec un effet au survol) pour envoyer les informations</p><br>
* <p>Une partie filtre composer de 4 bouttons. Chacun possedant un logo ainsi qu'un effet de couleur au survol.</p><br>
* <p>Un logo information avec un paragraphe qui indique à proximativement le nombre de logement disponible dans la ville selectionner</p><br><br>
  
<h2>main</h2><br>

### main composer de :
* <p>Note: Chaque article est doté d'une animation qui donne un effet de sur élevation vers le haut, ainsi qu'une box-shadow</p><br><br>
* <p>Une section Hébergement habritant 6 articles. Chaque article est composé d'un titre (nom de l'hôtel) le tarif pour une nuit ainsi qu'un système de notation en forme d'étoile(1 pour bleu et 0 pour gris)</p><br>
* <p>Un aside lateral avec 3 articles concernant les hôtels les plus populaires</p><br>
* <p>Un url pour afficher le reste des articles</p><br><br>


<h2>aside Activité</h2><br>

* <p>Une section composer de 6 articles, proposant differentes activité dans la ville. Les 6 articles sont disposer sur 4 colonnes, Un article qui prend 100% de la hauteur disponible sur une colonne, 2 articles sur une colonne(1 qui prend 50% le 2èm prend 40% et un ecart de 10% entre les 2) </p><br>
* <p>chaque articler est doté des mêmes animations que ceux de la partie hébergements</p><br><br>

<h2>footer</h2><br>

* <p>Le footer habrite les mentions légales la charte, l'utilisation des données d'utilisateurs, les conditions de ventes, contact</p><br><br>


# tablette (769px)
<br> <br>

<h2>Header</h2> <br>

* <p>La dispotion reste à proximativement identique qu'en desktops, la difference ce trouve au niveau du filtre qui passe sur 2 lignes pour eviter que l'utilisateur scroll en largeur. </p><br><br>


<h2>main</h2><br>

### Au niveau du main :
* <p>L'aside latéral passe au dessus de la section hébergements et occupe toute l'espace, et la dispotion des article passe également en ligne et plus en colonne</p><br>
* <p>Les articles de l'hébergement gardes la même dispotion</p><br>


<h2>aside Activité</h2><br>

* <p>Les articles sont disposés en 2 colonnes. Sur la premiere colonne le premier article prend 430px et les suivants 205px, sur la deuxieme colonnes même principe juste la disposition des articles qui sont inversés </p><br>


<h2>footer</h2><br>

* <p>Le footer garde la même disposition et même emplacement au pied du site</p><br><br>


# mobile 
<br> <br>

<h2>Header</h2> <br>


* <p>La navbar passe sur deux colonnes, le logo et l'url s'inscrire reste sur la première colonne, la second colonne est occupé par les deux url d'ancrage avec une bordure bottom qui vir au bleu lors d'un survol et un clique ainsi que le texte</p><br>
* <p>le boutton du champ de recherche change de format avec un logo à la place du texte et rétricie également</p><br>
* <p>Au niveau du filtre, les boutton prennnent 2 colonnes, 3 sur une colonne et le familial possède ça propre colonne.</p><br><br>


<h2>main, aside Activité</h2>

* <p>tous les élements du main à l'aside activité passe sur une seule colonne pour éviter le scroll sur la largeur, et possède la même largeur</p><br>
* <p>Les articles de l'aside activité possède toutes la même hauteur et largeur</p><br>
* <p>Le footer également passe sur une seul colonne</p><br><br><br><br>





# Choix sémantique

<br><br>

> **Header : pour délimiter l’entête générale du site web** <hr>
> <br>
>><h3>NavBar</h3> <br> 
>> <nav> a pour fonction de regrouper les liens de navigation considérés comme majeurs ou jugés suffisamment pertinents.
>>
>> Composer d'une liste non ordonné, donc des ul avec des enfants li qui possède chacun des href comme descendant qui permet ainsi au visiteur de navigué sur les differentes url à l'intérieur de la page, ici le logo et inscription pointe nul part. Activité et Hebergement servent d'ancrage, ils nous mènent sur les sections respectives.   
> <br>
> 
><h3>h1 h2 h3</h3><hr>
>
>>le titre entourer de strong pour spécifier au robot que ce texte est important. Il abrite different mots clef qui facilitera le référencement du site et également facilité le ciblage du site en tappant (Hébergement, vacances rêve). <br>
><br>
>
><h3>form</h3> 
>
>> La barre de recherche ce trouve dans un form car le clique permettra à un utilisateur d'envoyer des données de recherche.
>> 

> **section Hébergement :** <hr> <br>
>> 
>> Article va permettre de signaler aux robots d’indexation quel éléments sont en lien avec le sujet de la page ici les card d'hébergement et d'activité ce rejoignent car ce sont les prestations offerte par Reservia.