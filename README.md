# SAÉ S1.05-06 - Dassault Systèmes

## Sujet

[Site web Dassault Systèmes (GitHub Pages)](https://enesim21.github.io/DASSAULT-SYSTEME/)

Le site est également hébergé en miroir sur GitLab Pages et Bitbucket Pages (groupe de 5 membres) :
- [GitLab Pages](https://dassault-systeme-79006b.gitlab.io/)
- [Bitbucket Pages](https://dassaultsysteme.bitbucket.io/)

Dépôt du projet : [github.com/enesim21/DASSAULT-SYSTEME](https://github.com/enesim21/DASSAULT-SYSTEME)

## Membres du groupe :

- [Sami BEN SLIMA (référent)](mailto:sami.ben-slima@edu.univ-fcomte.fr?subject=SAE_1_05_06)  
- [Enes AVSAR](mailto:enes.avsar@edu.univ-fcomte.fr?subject=SAE_1_05_06)  
- [Jonathan BUHL](mailto:jonathan.buhl@edu.univ-fcomte.fr?subject=SAE_1_05_06)  
- [Marius BAUDON--RIGAL](mailto:marius.baudon--rigal@edu.univ-fcomte.fr?subject=SAE_1_05_06)  
- [Moubaraka AHAMAD](mailto:moubaraka.ahamad@edu.univ-fcomte.fr?subject=SAE_1_05_06)  

## Présentation

Ce dépôt correspond à un site web créé en HTML, CSS et JavaScript dans le cadre de la SAÉ 1.05-06 au département Informatique de l'IUT Nord Franche-Comté (Belfort), par les étudiants du groupe S1A1.
Le site présente l'entreprise française Dassault Systèmes, spécialisée dans les logiciels de conception 3D et les jumeaux virtuels. Il revient sur son histoire, ses domaines d'activité, ses principaux produits, son économie et son empreinte écologique. Chaque membre du groupe a réalisé au moins une page, avec le nom de son auteur indiqué en pied de page.

Le site est disponible en français et en anglais grâce à un bouton de traduction présent dans la barre de navigation.

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

- **Charte graphique commune** : Sami a réalisé un « style tile » pour le groupe. Toutes les pages utilisent la même palette de couleurs (#293947, #0B5D75, #429DAD, #BAE9EA, #E9F6FD) et la police Open Sans pour le menu.
- **Barre de navigation et pied de page identiques** sur toutes les pages, regroupés dans `css/commun.css`. Le lien de la page ouverte est mis en gras dans le menu, et chaque pied de page indique l'auteur de la page.
- **Bannière et titre** de même taille sur les pages de contenu, sur le modèle de la page Produits.
- **Traduction français / anglais** : un bouton discret dans le menu permet de passer le site en anglais. Le script `js/traduction.js` remplace les textes de la page à partir d'un dictionnaire, et garde la langue choisie d'une page à l'autre.
- **Graphiques** de la page Économie réalisés avec Excel à partir des chiffres publiés par Dassault Systèmes, puis exportés en images.
- **Éco-conception** : les images ont été redimensionnées et compressées pour que chaque page obtienne la note A sur EcoIndex.

## Développement du site et validation des pages

Toutes les pages ont été testées avec le [Nu Html Checker](https://validator.w3.org/nu/) (W3C) et avec [EcoIndex](https://www.ecoindex.fr/).
Les tests W3C et EcoIndex ont été faits par **Enes AVSAR**.

### Page d'accueil

**Auteur : Sami BEN SLIMA**  

Vérification W3C : [Détail ICI](https://validator.w3.org/nu/?showsource=yes&showoutline=yes&showimagereport=yes&doc=https%3A%2F%2Fenesim21.github.io%2FDASSAULT-SYSTEME%2Findex.html) (0 erreur)
<img src="doc/w3c_index.jpg" width="400" alt="capture d'écran de la validation W3C de la page d'accueil">

<img src="doc/ecoindex_index.jpg" width="400" alt="capture d'écran EcoIndex de la page d'accueil (note A)">

### Histoire

**Auteur : Moubaraka AHAMAD**  

Vérification W3C : [Détail ICI](https://validator.w3.org/nu/?showsource=yes&showoutline=yes&showimagereport=yes&doc=https%3A%2F%2Fenesim21.github.io%2FDASSAULT-SYSTEME%2Fhistoire.html) (0 erreur)

<img src="doc/w3c_histoire.jpg" width="400" alt="capture d'écran de la validation W3C de la page Histoire">

<img src="doc/ecoindex_histoire.jpg" width="400" alt="capture d'écran EcoIndex de la page Histoire (note A)">

### Domaines

**Auteur : Jonathan BUHL**  

Vérification W3C : [Détail ICI](https://validator.w3.org/nu/?showsource=yes&showoutline=yes&showimagereport=yes&doc=https%3A%2F%2Fenesim21.github.io%2FDASSAULT-SYSTEME%2Fdomaines.html) (0 erreur, 0 avertissement)

<img src="doc/w3c_domaines.jpg" width="400" alt="capture d'écran de la validation W3C de la page Domaines">

<img src="doc/ecoindex_domaines.jpg" width="400" alt="capture d'écran EcoIndex de la page Domaines (note A)">

### Produits

**Auteur : Marius BAUDON--RIGAL**  
Vérification W3C : [Détail ICI](https://validator.w3.org/nu/?showsource=yes&showoutline=yes&showimagereport=yes&doc=https%3A%2F%2Fenesim21.github.io%2FDASSAULT-SYSTEME%2Fproduits.html) (0 erreur)

<img src="doc/w3c_produits.jpg" width="400" alt="capture d'écran de la validation W3C de la page Produits">

<img src="doc/ecoindex_produits.jpg" width="400" alt="capture d'écran EcoIndex de la page Produits (note A)">

### Économie

**Auteur : Enes AVSAR**  

Vérification W3C : [Détail ICI](https://validator.w3.org/nu/?showsource=yes&showoutline=yes&showimagereport=yes&doc=https%3A%2F%2Fenesim21.github.io%2FDASSAULT-SYSTEME%2Feconomie.html) (0 erreur, 0 avertissement)

<img src="doc/w3c_economie.jpg" width="400" alt="capture d'écran de la validation W3C de la page Économie">

<img src="doc/ecoindex_economie.jpg" width="400" alt="capture d'écran EcoIndex de la page Économie (note A)">

### Écologie

**Auteur : Jonathan BUHL**  

Vérification W3C : [Détail ICI](https://validator.w3.org/nu/?showsource=yes&showoutline=yes&showimagereport=yes&doc=https%3A%2F%2Fenesim21.github.io%2FDASSAULT-SYSTEME%2Fecologie.html) (0 erreur, 0 avertissement)

<img src="doc/w3c_ecologie.jpg" width="400" alt="capture d'écran de la validation W3C de la page Écologie">

<img src="doc/ecoindex_ecologie.jpg" width="400" alt="capture d'écran EcoIndex de la page Écologie (note A)">

## Répartition du travail
### Coordination du groupe

- Sami BEN SLIMA (référent) : organisation du groupe, « style tile » et charte graphique

### Développement du site

- Sami BEN SLIMA
  - Page d'accueil
- Moubaraka AHAMAD
  - Page Histoire
- Jonathan BUHL
  - Page Domaines
  - Page Écologie
- Marius BAUDON--RIGAL
  - Page Produits
- Enes AVSAR
  - Page Économie et ses graphiques (Excel)
  - Barre de navigation et pied de page communs (`css/commun.css`)
  - Traduction français / anglais (`js/traduction.js`)
  - Tests W3C et EcoIndex, compression des images, README

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
