# SAÉ S1.05-06 - Dassault Systèmes

Ce dépôt contient le site web que nous avons réalisé en groupe pour la SAÉ 1.05-06, en première année de BUT Informatique à l'IUT Nord Franche-Comté (Belfort, groupe S1A1). Il présente l'entreprise française Dassault Systèmes, spécialisée dans les logiciels de conception 3D et les jumeaux virtuels : son histoire, ses domaines d'activité, ses produits, son économie et son empreinte écologique. Chaque membre du groupe a réalisé au moins une page, et son nom apparaît dans le pied de page.

Le site existe en français et en anglais, avec un bouton de traduction dans la barre de navigation.

## Accès au site

Le site est hébergé sur [GitHub Pages](https://enesim21.github.io/DASSAULT-SYSTEME/), et aussi sur [GitLab Pages](https://dassault-systeme-79006b.gitlab.io/) et [Bitbucket Pages](https://dassaultsysteme.bitbucket.io/) puisque le groupe compte cinq membres. Le code source se trouve dans le [dépôt GitHub du projet](https://github.com/enesim21/DASSAULT-SYSTEME).

## Membres du groupe

- [Sami BEN SLIMA (référent)](mailto:sami.ben_slima@edu.univ-fcomte.fr?subject=SAE_1_05_06)  
- [Enes AVSAR](mailto:enes.avsar@edu.univ-fcomte.fr?subject=SAE_1_05_06)  
- [Jonathan BUHL](mailto:jonathan.buhl@edu.univ-fcomte.fr?subject=SAE_1_05_06)  
- [Marius BAUDON--RIGAL](mailto:marius.baudon--rigal@edu.univ-fcomte.fr?subject=SAE_1_05_06)  
- [Moubaraka AHAMAD](mailto:moubaraka.ahamad@edu.univ-fcomte.fr?subject=SAE_1_05_06)  

## Arborescence du site

```
DASSAULT-SYSTEME
├── index.html
├── histoire.html
├── domaines.html
├── produits.html
├── economie.html
├── ecologie.html
├── README.md
├── css
│   ├── commun.css      (barre de navigation, pied de page, bouton de langue)
│   ├── accueil.css
│   ├── histoire.css
│   ├── domaines.css
│   ├── produits.css
│   ├── economie.css
│   └── ecologie.css
├── js
│   └── traduction.js   (traduction français / anglais)
├── images
│   ├── logo.png
│   ├── favicon.ico
│   ├── accueil
│   ├── histoire
│   ├── Produit
│   └── economie
└── doc                 (captures W3C, EcoIndex et contributeurs)
```

## Choix de conception

Sami a réalisé un style tile pour le groupe. Toutes les pages utilisent donc la même palette de couleurs (#293947, #0B5D75, #429DAD, #BAE9EA, #E9F6FD), la police Space Grotesk et le même fond clair, #E9F6FD.

La barre de navigation et le pied de page sont identiques sur toutes les pages et regroupés dans `css/commun.css`. Le lien de la page ouverte est mis en gras dans le menu, et chaque pied de page indique l'auteur de la page. Les bannières et les titres ont la même taille sur les pages de contenu, sur le modèle de la page Produits.

Pour la traduction, le script `js/traduction.js` remplace les textes de la page à partir d'un dictionnaire et garde la langue choisie d'une page à l'autre. Les graphiques de la page Économie ont été faits avec Excel à partir des chiffres publiés par Dassault Systèmes, puis exportés en images. Les images ont été redimensionnées et compressées pour que chaque page obtienne la note A sur EcoIndex.

## Validation des pages

Toutes les pages ont été testées avec le [Nu Html Checker](https://validator.w3.org/nu/) (W3C) et avec [EcoIndex](https://www.ecoindex.fr/). Ces tests ont été faits par Enes AVSAR.

### Page d'accueil

Page réalisée par Sami BEN SLIMA. La validation W3C ne donne aucune erreur ([détail](https://validator.w3.org/nu/?showsource=yes&showoutline=yes&showimagereport=yes&doc=https%3A%2F%2Fenesim21.github.io%2FDASSAULT-SYSTEME%2Findex.html)) et EcoIndex donne la note A.

<img src="doc/w3c_index.jpg" width="400" alt="capture d'écran de la validation W3C de la page d'accueil">

<img src="doc/ecoindex_index.jpg" width="400" alt="capture d'écran EcoIndex de la page d'accueil (note A)">

### Histoire

Page réalisée par Moubaraka AHAMAD. La validation W3C ne donne aucune erreur ([détail](https://validator.w3.org/nu/?showsource=yes&showoutline=yes&showimagereport=yes&doc=https%3A%2F%2Fenesim21.github.io%2FDASSAULT-SYSTEME%2Fhistoire.html)) et EcoIndex donne la note A.

<img src="doc/w3c_histoire.jpg" width="400" alt="capture d'écran de la validation W3C de la page Histoire">

<img src="doc/ecoindex_histoire.jpg" width="400" alt="capture d'écran EcoIndex de la page Histoire (note A)">

### Domaines

Page réalisée par Jonathan BUHL. La validation W3C ne donne aucune erreur ([détail](https://validator.w3.org/nu/?showsource=yes&showoutline=yes&showimagereport=yes&doc=https%3A%2F%2Fenesim21.github.io%2FDASSAULT-SYSTEME%2Fdomaines.html)) et EcoIndex donne la note A.

<img src="doc/w3c_domaines.jpg" width="400" alt="capture d'écran de la validation W3C de la page Domaines">

<img src="doc/ecoindex_domaines.jpg" width="400" alt="capture d'écran EcoIndex de la page Domaines (note A)">

### Produits

Page réalisée par Marius BAUDON--RIGAL. La validation W3C ne donne aucune erreur ([détail](https://validator.w3.org/nu/?showsource=yes&showoutline=yes&showimagereport=yes&doc=https%3A%2F%2Fenesim21.github.io%2FDASSAULT-SYSTEME%2Fproduits.html)) et EcoIndex donne la note A.

<img src="doc/w3c_produits.jpg" width="400" alt="capture d'écran de la validation W3C de la page Produits">

<img src="doc/ecoindex_produits.jpg" width="400" alt="capture d'écran EcoIndex de la page Produits (note A)">

### Économie

Page réalisée par Enes AVSAR. La validation W3C ne donne aucune erreur ([détail](https://validator.w3.org/nu/?showsource=yes&showoutline=yes&showimagereport=yes&doc=https%3A%2F%2Fenesim21.github.io%2FDASSAULT-SYSTEME%2Feconomie.html)) et EcoIndex donne la note A.

<img src="doc/w3c_economie.jpg" width="400" alt="capture d'écran de la validation W3C de la page Économie">

<img src="doc/ecoindex_economie.jpg" width="400" alt="capture d'écran EcoIndex de la page Économie (note A)">

### Écologie

Page réalisée par Jonathan BUHL. La validation W3C ne donne aucune erreur ([détail](https://validator.w3.org/nu/?showsource=yes&showoutline=yes&showimagereport=yes&doc=https%3A%2F%2Fenesim21.github.io%2FDASSAULT-SYSTEME%2Fecologie.html)) et EcoIndex donne la note A.

<img src="doc/w3c_ecologie.jpg" width="400" alt="capture d'écran de la validation W3C de la page Écologie">

<img src="doc/ecoindex_ecologie.jpg" width="400" alt="capture d'écran EcoIndex de la page Écologie (note A)">

## Répartition du travail

Sami BEN SLIMA est le référent du groupe : il a organisé le travail, réalisé le style tile et la page d'accueil. Moubaraka AHAMAD a fait la page Histoire, Jonathan BUHL les pages Domaines et Écologie, et Marius BAUDON--RIGAL la page Produits. Enes AVSAR a fait la page Économie et ses graphiques Excel, la barre de navigation et le pied de page communs (`css/commun.css`), la traduction français / anglais (`js/traduction.js`), les tests W3C et EcoIndex, la compression des images et ce README.

## Contributeurs

Correspondance entre les comptes GitHub et les membres du groupe :

| Compte GitHub | Membre |
|---|---|
| sami9z | Sami BEN SLIMA |
| enesim21 | Enes AVSAR |
| magolorh2-spec | Jonathan BUHL |
| mariusbrigal33-hub | Marius BAUDON--RIGAL |
| moubarakaahamad-png | Moubaraka AHAMAD |

![capture d'écran sur la contribution des membres du projet](doc/contributeurs.jpg)
