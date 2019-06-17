# Jour 4
Nous présentons ici l'intégration de plusieurs services en ligne dans notre site web. Chacun de ces sites fournis directement le code HTML/CSS/JS d'intégration.

## Google services
Google propose un grand nombre de services en ligne. Nous ne présentons ici que l'intégration de Google Map, d'une vidéo Youtube et d'une police Google Fonts.

Vous trouverez ici les imprim-écrans des différentes étapes à suivre pour intégrer ces différents services :

<a href="https://docs.google.com/presentation/d/e/2PACX-1vTLmGtfz9n-WrBU_SiyQgcKNcaaRmbqAAmJ5BQuWSUupa2B9sqL04YmkLfjyHc_cxZwL3o_t6Im3c-g/pub?start=false&loop=false&delayms=60000" target="_blanck">Google services demo</a>

Une fois le code d'intégration récupérer, il doit être collé là où l'on souhaite voir apparaitre le service. 

### <a href="https://www.google.com/maps/" target="_blanck">Google Map</a>(l.132)
```html
<iframe src="https://www.google.com/maps/embed?pb=!1m16!1m12!1m3!1d45250.95061196091!2d-0.608091850603113!3d44.85854041698775!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!2m1!1smuffins!5e0!3m2!1sfr!2sfr!4v1560421401402!5m2!1sfr!2sfr" width="600" height="450" frameborder="0" style="border:0" allowfullscreen></iframe>
```
### <a href="https://www.youtube.com/" target="_blanck">Vidéo Youtube</a>(l.82)
```html
<iframe width="500" height="300" src="https://www.youtube.com/embed/fBuSNu2m3XA" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
```

### <a href="https://fonts.google.com/" target="_blanck">Google Fonts</a>
Google fonts nous fournit deux lignes de code. 

Une ligne permettant de faire le lien vers la feuille de style CSS de Google Fonts (balise "link") à coller dans le head du html (avant le link vers notre propre page de style "style.css) (l.6):
```html
<link href="https://fonts.googleapis.com/css?family=Pacifico&display=swap" rel="stylesheet">
```

La seconde ligne est une propriété "font-family" qui doit être collé dans le fichier style.css, entre les accolades des élements que l'on souhaite modifier. Dans notre exemple les éléments sont les titres h1, h2, h3 et h4 modifiés aux lignes 10 et 15 :
```css
font-family: 'Pacifico', cursive;
```

## <a href="https://fontawesome.com/" target="_blanck">Font Awesome</a>

<a href="https://fontawesome.com/" target="_blanck">Font Awesome</a> est un services qui permet de récupérer un grand nombre icones (dont les logo des réseaux sociaux) sous forme de police et donc de pouvoir modifier leur taille, leur couleur et leur couleur de fond très falicement (avec les propriétés font-size, color et background). 

Vous trouverez ici les imprim-écrans des différentes étapes à suivre pour intégrer ce service :

<a href="https://docs.google.com/presentation/d/e/2PACX-1vR_nPGm05oNGHC-bbJDOYtubMDld9FiunNOBVQR0h_i4oE8uU_vCAXtOrcuxze172Mc9e7l3xeTnjUm/pub?start=false&loop=false&delayms=60000" target="_blanck">Font Awesome demo</a>

Il faut d'abord lier notre projet à Font Awesome. Pour cela on copie la ligne de code récupérér dans l'onglet "start" à la ligne 178 juste avant la fermeture de la balise </body> car la ligne inclut du JS :
```html
<script src="https://kit.fontawesome.com/18ee24e4d3.js"></script>
```
En suite, on choisi un icone. une fois l'icone choisi, on récupère le code d'intégration et on le colle là où l'on souhaite voir apparaitre l'icone. Dans notre exemple à la ligne 43, 46 et 49.
```html
<i class="fab fa-facebook-square"></i>
```

## <a href="https://getbootstrap.com/" target="_blanck">Bootstrap</a>

Vous trouverez ici les imprim-écrans des différentes étapes à suivre pour intégrer ce service :

<a href="https://docs.google.com/presentation/d/e/2PACX-1vR_nPGm05oNGHC-bbJDOYtubMDld9FiunNOBVQR0h_i4oE8uU_vCAXtOrcuxze172Mc9e7l3xeTnjUm/pub?start=false&loop=false&delayms=60000" target="_blanck">Bootstrap demo</a>

Une fois le code d'intégration récupérer, il doit être collé là où l'on souhaite voir apparaitre le service. 

