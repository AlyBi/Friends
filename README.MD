# Friends - Fichier HTML

## Description

Ce fichier HTML contient la structure de base de la page Web pour la série télévisée Friends. Il définit les différentes sections de la page et leur contenu, ainsi que les liens vers les fichiers CSS et JavaScript utilisés pour styliser et ajouter des fonctionnalités à la page.

## Utilisation

Ce fichier HTML est la base de votre page Web. Lorsque vous ouvrez ce fichier dans un navigateur Web, il affiche la page telle qu'elle a été conçue en utilisant les styles définis dans les fichiers CSS liés et les fonctionnalités ajoutées par les fichiers JavaScript liés.

## Structure du fichier

Le fichier HTML est structuré en plusieurs sections qui correspondent aux différentes parties de la page Web. Chaque section est définie par une balise `section` et contient du contenu spécifique à cette partie de la page.

Voici un aperçu des différentes sections du fichier HTML et de leur contenu:

- La première section, définie par la balise `header`, contient le logo et le titre de la série Friends.
- La section suivante, avec la classe `serie-presentation`, contient une présentation générale de la série, avec un titre, une image et du texte descriptif.
- La section suivante, avec la classe `serie-information`, contient des informations plus détaillées sur la série, notamment son synopsis.
- La section suivante, avec la classe `serie-acteurs`, contient une liste des principaux acteurs de la série avec des liens vers leurs pages Wikipédia.
- La section suivante, avec la classe `serie-images`, contient une galerie d'images de la série avec des titres et des descriptions pour chaque image.
- La dernière section, définie par la balise `footer`, contient les informations de copyright pour la page et un lien vers mon portfolio.
- Un lien vers un site distant est placé sur chaque acteur, le lien s'ouvre dans une page différente.
- Les liens survolés réagissent (fond et couleur en respectant l'arrondi).

## Friends - Fichier CSS

## Description CSS

- Ce fichier CSS contient les styles utilisés pour styliser la page Web de la série télévisée Friends. Il définit les couleurs, les polices, les marges, les espacements et d'autres propriétés visuelles des différents éléments de la page.
- Utilisation de la font Oswald pour garantir le rendu des titres, fait avec [Google fonts](https://fonts.google.com/).

## Utilisation CSS

- Ce fichier CSS est lié à la page HTML du projet en utilisant une balise `link` dans l'en-tête de la page. Lorsque la page est chargée dans un navigateur Web, les styles définis dans ce fichier sont appliqués aux différents éléments de la page pour leur donner l'apparence souhaitée.

## Structure du fichier CSS

- Le fichier CSS est structuré en plusieurs sections qui correspondent aux différentes parties de la page Web. Chaque section contient des sélecteurs CSS qui ciblent des éléments spécifiques de la page et des blocs de déclaration qui définissent les styles à appliquer à ces éléments.

Voici un aperçu des différentes sections du fichier CSS et de leur contenu:

- Utilisation du box-model.
- La première section définit des variables CSS pour les couleurs et les espacements utilisés dans le reste du fichier.
- La section suivante définit des styles généraux pour tous les éléments de la page, tels que la couleur d'arrière-plan et les polices.
- Les sections suivantes définissent des styles pour les différentes parties de la page, telles que l'en-tête, le corps principal et le pied de page.
- La section `.serie-presentation` définit des styles pour la présentation générale de la série.
- La section `.serie-information` définit des styles pour les informations plus détaillées sur la série.
- La section `.serie-acteurs` définit des styles pour la liste des principaux acteurs de la série.
- La section `.serie-images` définit des styles pour la galerie d'images de la série.

Le fichier CSS contient également des règles `@media` qui permettent d'appliquer des styles différents en fonction de la taille de l'écran. Ces règles sont utilisées pour rendre la page responsive et lui permettre de s'adapter aux différents appareils.
