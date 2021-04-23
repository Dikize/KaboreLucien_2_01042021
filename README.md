# KaboreLucien_2_01042021

## Environnement Front-End
<hr>

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

<br><br>

## Intégration du contenu conformément à la maquette
<hr>
<br>

### Découpage de la page en plusieur section selon la sémanthique de MDN et de la W3C.

<br><br>

### <h1>header</h1> 

><h3>Navbar</h3> <br>

>> Navbar doté du logo du site ainsi que des url qui permet à l'utilisateur de s'inscrire, de ce deplacer dans la section hébergement et activité(évite le scroll de l'utilisateur pour atteindre son objectif).
> <br>
><h3>Bar de recherche</h3> <br>

>>Composer d'un logo search, un input avec un placeholder pour indiquer à l'utilisateur qu'il peut saisir une ville, ainsi qu'un boutton (doté d'un effet hover qui change la couleur au survol) pour envoyer les données saisie. 
>>
>> Dans l'optipe permettre à l'utilisateur de chercher hôtel et activité dans la ville souhaiter. 
>
><h3>Filtres</h3> <br> 

>> L'espace filtre est composer de 4 bouttons dotter de d'un effet hover un changement de couleur au survol ainsi qu'une ombre.
>>
>> Un système qui permet à l'utilisateur de filtrer les recherche selon sa situation, desir...

<br><br>

### Main <hr> <br>
><h3>Section Hébergement</h3>
>
>> Toutes les cards sont dotées d'une animation transform translateY qui donne un effet de déplacement vers le hauts au survol, un box-shadow qui offre une ombre, donnant ainsi à l'utilisateur l'impression que les cards sont sur élever. Chaque cards est composés du titre de l'hôtel, le tarif ainsi qu'un système de notation en forme d'étoile(couleur bleu pour 1 et gris pour 0). 
>>
>> section Hébergement (prestation principale du site proposant des hôtels) possedant comme enfants des cards dans des balise articles. <br> <br>
> <h3>aside populaire</h3>
> 
>> Un aside qui régroupe les hôtel les plus populaire, également composer de card dans des balise article 

<br><br>

<h2>aside</h2> <hr> <br>

><h3>Activités</h3> <br>

>> Une prestation supplementaire pour des activités à proximité des hôtels.
>> 

<br>

<h1>footer </h1> <br>

><h3> </h3> <br>
>> 
>> 


# Choix sémantique

<br><br>

> **Header : pour délimiter l’entête générale du site web** <hr>
> <br>
> NavBar <hr>
>> Composer d'une liste non ordonné, donc des ul avec des enfants li qui possède chacun des href comme descendant qui permet ainsi au visiteur de navigué sur les differentes url à l'intérieur de la page, ici le logo et inscription pointe nul part. Activité et Hebergement servent d'ancrage, ils nous mènent sur les sections respectives.   
> <br>
> Titre<hr>
>>le titre entourer de strong pour spécifier au robot que ce texte est important. Il abrite different mots clef qui facilitera le référencement du site et également facilité le ciblage du site en tappant (Hébergement, vacances rêve). 
><hr> 
> form <hr> <br>
>> La barre de recherche ce trouve dans un form car le clique permettra à un utilisateur d'envoyer des données de recherche.
>> 

> **section Hébergement :** <hr> <br>
>> 
>> Article va permettre de signaler aux robots d’indexation quel éléments sont en lien avec le sujet de la page ici les card d'hébergement et d'activité ce rejoignent car ce sont les prestations offerte par Reservia.
>>
>>
```
grid: 
```

> **aside : éléments complémentaire au contenu** <hr> <br> 
>> 
>> 
```
grid: 
```

> **aside :** <hr> <br>
>> 
>> 

```
grid: 
```
<br><br>

> **Footer:** <hr>
>> 
>> 



