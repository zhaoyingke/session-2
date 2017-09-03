# session-2
Anatomie d'une page web, initiation au langage HTML

## Étapes

- [ ] Forker ce projet dans votre espace personnel sur Github
- [ ] Cloner le fork dans Github Desktop

Vous allez travailler sur le fichier index.html, qui contient la structure minimale d'une page web. Tout le contenu doit donc s'écrire au sein du bloc `<body></body>`

- [ ] En utilisant au maximum la liste de balises disponibles ci-dessous, et en utilisant la chanson de votre choix, créez une page contenant les paroles et la présentation de l'artiste.

Celui-ci doit s'approcher au maximum du rendu suivant : 

![Site paroles](https://github.com/edj-initiation-code/session-2/blob/master/screencapture-file-Users-julesbonnard-web-edj-session-2-index-html-1504459360156.png?raw=true)

> Pensez à "aérer" votre code en sautant des lignes et en créant des indentations. Cela ne modifie pas le rendu et permet une meilleure lisibilité.

## Listes de balises

> Le HTML est un langage de balises. Celles-ci servent de blocs qui structurent le contenu.

> La plupart s'ouvrent et se ferment : `<p>Mon texte</p>` (un paragraphe).

> Mais certaines sont autonomes : `<hr />` (une ligne horizontale).

> Les balisent doivent se fermer dans l'ordre inverse dont elles ont été ouvertes : 

> Code **valide** -> `<p>Les mots suivants sont <strong>en gras</strong></p>`

> Code **invalide** -> `<p>Les mots suivants sont <strong>en gras</p></strong>`

### Les blocs

- `<header>Le bloc qui contient le haut de la page</header>`
- `<nav>Le bloc qui contient le menu de la page</nav>`
- `<main>Le bloc qui contient la partie centrale de la page</main>`
- `<article>Un bloc qui contient le contenu important de la page</article>`
- `<aside>Un bloc qui contient le contenu additionnel de la page</aside>`
- `<footer>Le bloc qui contient le bas de la page</footer>`

Il existe aussi des blocs génériques, très (trop) utilisés : 

- `<div></div>`
- `<span></span>`

### Le texte

- `<p>Un paragraphe</p>`
- `<h1>Un titre très important</h1>`
- `<h2>Un titre un peu moins important</h2>`, et ainsi de suite h3, h4, h5, h6...
- `<strong>Un texte en gras</strong>`
- `<em>Un texte en italiques</em>`

### Les listes

Une liste non-ordonnée : 

```html
<ul>
  <li>Premier élément</li>
  <li>Deuxième élément</li>
  <li>Troisième élément</li>
</ul>
```

Une liste ordonnée : 

```html
<ol>
  <li>Premier élément</li>
  <li>Deuxième élément</li>
  <li>Troisième élément</li>
</ol>
```

### Les lignes

- Un saut de ligne : `<br />`
- Une ligne horizontale : `<hr />`
