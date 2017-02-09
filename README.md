# Cours de html & css (2016-2017)

## Description

Ce repo contient le code écrit durant le cours de html & css à EPSI Lille, session 2016-2017.

## Prérequis

L'utilisation de ce repo nécessite l'installation des applications suivantes :

- git
- nodejs + npm
- bower
- ruby
- sass

## Installation

Downloadez un zip du repo ou clonez le avec git.

Ensuite installez les dépendances avec bower :

    cd epsi-arras-html-css-2016-2017
    bower install

## Structure type d'un projet html, css & js statique

    document-root/
      bower_components/
        bootstrap/
        jquery/
      css/
        *.css
      img/
        *.gif
        *.jpg
        *.jpeg
        *.png
        *.svg
      js/
        *.js
      sass/
        *.sass
        *.scss
      bower.json
      index.html
      *.html

## Compilation des fichiers sass / scss

Ouvrez un terminal (cmd sous windows) puis déplacez vous jusqu'au dossier racine (le document-root) de votre projet avec la commande `cd`.

Pour compiler le fichier `style.scss` tapez :

    sass sass/style.scss css/style.css

Pour demander à sass d'autocompiler dès qu'un changement est détecté tapez :

    sass --watch sass:css

## Où trouver de la doc sur html, css et sass

- [HTML element reference - HTML | MDN](https://developer.mozilla.org/en-US/docs/Web/HTML/Element)
- [CSS reference - CSS | MDN](https://developer.mozilla.org/en-US/docs/Web/CSS/Reference)
- [Sass: Syntactically Awesome Style Sheets](http://sass-lang.com/)

## Déboguez votre code html & css

- tester la compatibilité des navigateurs avec une fonctionnalité : [Can I use... Support tables for HTML5, CSS3, etc](http://caniuse.com/)
- validation de code html4 : [The W3C Markup Validation Service](https://validator.w3.org/)
- validation de code html5 : [Ready to check - Nu Html Checker](https://validator.w3.org/nu/)
- validation de code css : [Service de validation CSS du W3C](https://jigsaw.w3.org/css-validator/)

## Medias

Voici les sources des médias utilisés.

### Photos

fichiers : 0a_b9g-rm6w-austin-neill.jpg, 0a_b9g-rm6w-austin-neill-160x106.jpg

sources : [Photo by Austin Neill | Unsplash](https://unsplash.com/?photo=0A_b9G-Rm6w)

licence : [Creative Commons — CC0 1.0 Universal](https://creativecommons.org/publicdomain/zero/1.0/)

### Icônes

fichiers : iconmonstr-check-mark-4-48.png

sources : [Check Mark 4 - PNG - iconmonstr](http://iconmonstr.com/check-mark-4/?png)

licence : [License Agreement - iconmonstr](http://iconmonstr.com/license/)


fichiers : iconmonstr-x-mark-4-24.png

sources : [X Mark 4 - PNG - iconmonstr](http://iconmonstr.com/x-mark-4/?png)

licence : [License Agreement - iconmonstr](http://iconmonstr.com/license/)


