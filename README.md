# The Client - Website
Dit is een prototype van de Drop & Heal webapp.


## Inhoudsopgave Readme

  * [Beschrijving](#beschrijving)
  * [Kenmerken](#kenmerken)
  * [Bronnen](#bronnen)
  * [Licentie](#licentie)

## Beschrijving
Drop & Heal wil jongvolwassenen op een toegankelijke en gepersonalizeerde manier bijstaan bij het rouwproces.
De webapp zal met behulp van vragenlijsten bepalen welke opdrachten het beste bij een persoon passen.

De pagina is responsive en is Mobile first ontworpen en gemaakt. 

De website is te zien op [nyathene.github.io/the-client-website](https://nyathene.github.io/the-client-website/)

<img alt="Drop en Heal desktop webpagina" src="https://github.com/Nyathene/the-client-website/blob/main/docs/Screenshots/Desktop.png?raw=true" width="885">
_Layout van de intro / homepage_

## Kenmerken

De website is gebouwd met [HTML](#html) en [CSS](#CSS).

### HTML
Hieronder staat de basis structuur uitgelegd met de setting in de [HEAD](#HEAD) en opmaak van de [BODY](#BODY):

#### HEAD
In de Head word de CSS file geladen, en het lettertype wordt hier vanuit de Google library opgeroepen.

 ```html
      <link rel="stylesheet" href="styles/intro.css">
      <link href="https://fonts.googleapis.com/css2?family=Figtree:ital,wght@0,300..900;1,300..900&display=swap" rel="stylesheet">
  ```
#### BODY
  In de Body staat er tekst, een figuur en een knop. De vetgedrukte tekst staat in de [H1](#H1) vetgedrukt, de kleine tekst staat in een [P](#P), de plaatjes staan in een [figure](#FIGURE) en de knop is een [Button](#BUTTON) in een link.

  ##### H1
  De vetgedrukte tekst, "Drop & Heal", staat hier eminent en focaal.
  ##### P
  De niet-vetgedrukte tekst staat hier iets minder focaal.
  #### FIGURE
<img alt="Figures" src="https://github.com/Nyathene/the-client-website/blob/main/docs/Screenshots/figures.png?raw=true" width="885">
_Screenshot van de Figures_

  De img's, dat wil zeggen de "blurs" en het logo/symbool, zitten in een Figure. Dit is omdat ze vrijstaande elementen zijn.
  ```html
     <figure class="rechtsboven"><img src="../assets/blur/blauw.png"></figure>
     <figure class="logo transparent"><img src="../assets/RT1.png"></figure>
  ```
  #### BUTTON
  De knoppen zitten in een "a" element, zodat het een link wordt.
  ```html
     <a class="button" href="intro/Intro2.html">
        <button class="button starten">
            <p>starten</p>
        </button>
    </a>
  ```

### CSS
De CSS geeft aan hoe groot de elementen zijn, welke kleur en positie ze moeten hebben, en welke lettertypes er worden gebruikt.
#### display:grid
De tekst en knopjes zitten in een grid die ervoor zorgt dat de elementen op de juiste plaats komen te zitten
#### width
De breedte van de foto's worden bepaald door deze CSS property
#### Media Queries
De regel '@media (min-width:600px)' zorgt ervoor dat bepaalde CSS regels alleen gelden bij een scherm dat boven de 600 pixels breed is
<img alt="Drop en Heal smartphone webpagina" src="https://github.com/Nyathene/the-client-website/blob/main/docs/Screenshots/Mobiel.jpeg?raw=true" width="885">
_Layout van de intro / homepage op een smal scherm_


## Bronnen
Calvino Grande Trial font https://www.cdnfonts.com/calvino-grande-trial.font
CSS Grid https://developer.mozilla.org/en-US/docs/Web/CSS/grid
Figure https://developer.mozilla.org/en-US/docs/Web/HTML/Element/figure
Figtree font https://fonts.google.com/specimen/Figtree
## Licentie

This project is licensed under the terms of the [MIT license](./LICENSE).
