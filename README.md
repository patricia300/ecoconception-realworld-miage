# TP M2 MIAGE - Eco-conception

**Note: Ce TP approche l'optimisation d'une application par l'absurde. L'objectif de ce TP sera donc de rendre une application la moins éco-conçu possible. Ne refaites pas ça chez vous**

## Objectif

Afin d'éco-concevoir une application, et après avoir abordé les étapes 1 et 2 de l'éco-conception, nous allons nous abordé la partie concernant la réalisation.
Pour cette étape, vous allez partir de ce fork Angular du [projet Realworld](https://github.com/gothinkster/realworld).

Le but ne sera pas de l'optimiser et à l'inverse, de dégrader l'application en prenant les bonnes pratiques d'éco-conception à contre pied.

## Déroulé

### Etape 1 : installation

1. Faire une fork du repo répertoire
2. Ajouter le remote source : `git remote add source https://github.com/pbelabbes/ecoconception-realworld-miage`
3. Installer les dépendance : `yarn install`
4. Lancer l'application : `yarn start` et vérifier que tout fonctionne
5. Modifier le fichier `binome.md`
6. Faire un commit `init binome`
7. Pousser son commit

**Notes: Pour mettre à jour le fork depuis la source : `git pull source main`**

### Etape 2 : Développement

1. Choisir une bonne pratique (ex: 1 - Optimiser le parcours utilisateur)
2. Analyser la bonne pratique
3. Interpreter les mauvaises pratiques à laquelle celle-ci répond
4. Appliquer le mauvaise pratique dans le code
5. Faire un commit de votre modification avec pour titre : `BP<n°BonnePratique> - <libellé de la bonne pratique>`
6. Recommencer

## Notation

Il faut faire le plus de points possibles, chaque bonne pratique traité apporte un certains nombre de point en fonction de 3 critères, ça priorité, sa difficulté de mise en oeuvre et son impact écologique.
Les points seront ensuite calculer et une note sera donner en fonction du classement du binôme.

## Bonnes pratiques :

Détails des bonnes pratiques ici : [https://github.com/cnumr/best-practices/tree/main](https://github.com/cnumr/best-practices/tree/main)

|     | Bonnes pratiques                                                                       | Priorité | Mise en oeuvre | Impact écologique | Nombre de points |
| --- | -------------------------------------------------------------------------------------- | -------- | -------------- | ----------------- | ---------------- |
| 1   | Optimiser le parcours utilisateur                                                      | 5        | 4              | 5                 | 4,67             |
| 2   | Préférer la saisie assistée à l'autocomplétion                                         | 3        | 3              | 3                 | 3,00             |
| 3   | Favoriser un design simple, épuré, adapté au web                                       | 4        | 3              | 3                 | 3,33             |
| 4   | Privilégier une approche "mobile first", à défaut un chargement adaptatif              | 4        | 4              | 5                 | 4,33             |
| 5   | Respecter le principe de navigation rapide dans l’historique                           | 3        | 4              | 3                 | 3,33             |
| 6   | Limiter le nombre de requêtes HTTP                                                     | 4        | 3              | 4                 | 3,67             |
| 7   | Stocker les données statiques localement                                               | 4        | 3              | 4                 | 3,67             |
| 8   | Favoriser les pages statiques                                                          | 4        | 3              | 5                 | 4,00             |
| 9   | Remplacer les boutons officiels de partage des réseaux sociaux                         | 4        | 4              | 4                 | 4,00             |
| 10  | Découper les CSS                                                                       | 4        | 4              | 4                 | 4,00             |
| 11  | Limiter le nombre de CSS                                                               | 4        | 4              | 4                 | 4,00             |
| 12  | Préférer les CSS aux images                                                            | 4        | 3              | 4                 | 3,67             |
| 13  | Écrire des sélecteurs CSS efficaces                                                    | 3        | 3              | 3                 | 3,00             |
| 14  | Grouper les déclarations CSS similaires                                                | 3        | 3              | 2                 | 2,67             |
| 15  | Utiliser les notations CSS abrégées                                                    | 2        | 3              | 2                 | 2,33             |
| 16  | Fournir une CSS print                                                                  | 3        | 4              | 3                 | 3,33             |
| 17  | Favoriser les polices standards                                                        | 4        | 3              | 4                 | 3,67             |
| 18  | Préférer les glyphs aux images                                                         | 4        | 3              | 4                 | 3,67             |
| 19  | Valider les pages auprès du W3C                                                        | 3        | 5              | 2                 | 3,33             |
| 20  | Externaliser les CSS et JavaScript                                                     | 4        | 4              | 4                 | 4,00             |
| 21  | Ne pas redimensionner les images coté navigateur                                       | 4        | 4              | 4                 | 4,00             |
| 22  | Éviter d'utiliser des images matricielles pour l'interface                             | 4        | 4              | 4                 | 4,00             |
| 23  | Optimiser les images vectorielles                                                      | 4        | 4              | 4                 | 4,00             |
| 24  | Utiliser le chargement paresseux                                                       | 4        | 4              | 5                 | 4,33             |
| 25  | Utiliser le rechargement partiel d'une zone de contenu                                 | 4        | 3              | 4                 | 3,67             |
| 26  | Éviter les animations JavaScript / CSS                                                 | 4        | 3              | 5                 | 4,00             |
| 27  | N'utilisez que les portions indispensables des librairies JavaScript et frameworks CSS | 4        | 4              | 4                 | 4,00             |
| 28  | Ne pas faire de modification du DOM lorsqu’on le traverse                              | 4        | 4              | 4                 | 4,00             |
| 29  | Rendre les éléments du DOM invisibles lors de leur modification                        | 3        | 4              | 4                 | 3,67             |
| 30  | Réduire au maximum le repaint (appearence) et le reflow (layout)                       | 4        | 4              | 4                 | 4,00             |
| 31  | Utiliser la délégation d'évènements                                                    | 3        | 3              | 4                 | 3,33             |
| 32  | Modifier plusieurs propriétés CSS en 1 seule fois                                      | 3        | 4              | 2                 | 3,00             |
| 33  | Mettre en cache les objets souvent accédés en JavaScript                               | 4        | 3              | 4                 | 3,67             |
| 34  | Réduire les accès au DOM via JavaScript                                                | 3        | 3              | 3                 | 3,00             |
| 35  | Minifier les fichiers CSS, JavaScript, HTML et SVG                                     | 4        | 3              | 4                 | 3,67             |
| 36  | Compresser les fichiers CSS, JavaScript, HTML et SVG                                   | 4        | 3              | 4                 | 3,67             |
| 37  | Combiner les fichiers CSS et JavaScript                                                | 4        | 3              | 4                 | 3,67             |
| 38  | Optimiser les images                                                                   | 4        | 3              | 4                 | 3,67             |
| 39  | Optimiser la taille des cookies                                                        | 3        | 4              | 3                 | 3,33             |
| 40  | Favoriser HSTS Preload list aux redirections 301                                       | 4        | 3              | 4                 | 3,67             |
| 41  | Mettre en cache les réponses Ajax                                                      | 3        | 2              | 4                 | 3,00             |
| 42  | Adapter les sons aux contextes d'écoute                                                | 2        | 2              | 3                 | 2,33             |
| 43  | Adapter les textes au web                                                              | 3        | 3              | 3                 | 3,00             |
| 44  | Adapter les vidéos aux contextes de visualisation                                      | 3        | 2              | 3                 | 2,67             |
| 45  | Limiter les outils d'analytics et les données collectées                               | 4        | 3              | 4                 | 3,67             |
| 46  | Limiter l'utilisation des GIFs animés                                                  | 3        | 3              | 3                 | 3,00             |
| 47  | Éviter la lecture et le chargement automatique des vidéos et des sons                  | 4        | 3              | 4                 | 3,67             |
| 48  | Utiliser les compartiments CSS                                                         | 3        | 2              | 4                 | 3,00             |
| 49  | Fournir une alternative textuelle aux contenus multimédias                             | 4        | 3              | 5                 | 4,00             |
| 50  | Économiser de la bande passante grace à un ServiceWorker                               | 4        | 3              | 4                 | 3,67             |
| 51  | Mettre en place un sitemap efficient                                                   | 2        | 3              | 2                 | 2,00             |
| 52  | Assurer la compatibilité avec les plus anciens appareils et logiciels du parc          | 4        | 3              | 5                 | 4,00             |
| 53  | Réduire le volume de données stockées au strict nécessaire                             | 4        | 4              | 4                 | 4,00             |
| 54  | Limiter le recours aux canvas                                                          | 3        | 4              | 4                 | 3,67             |
| 55  | S'assurer que les parcours utilisateurs permettent de réaliser leur action prévue      | 4        | 4              | 4                 | 4,00             |
| 56  | Avoir un titre de page et une metadescription pertinents avec le contenu de la page    | 4        | 4              | 4                 | 4,00             |
| 57  | Ne charger des données/du code que lorsqu'elles sont/il est nécessaire                 | 4        | 3              | 5                 | 4,00             |
| 58  | Préférer une PWA à une application mobile native similaire au site web                 | 3        | 3              | 3                 | 3,00             |
| 59  | Éviter les temps de blocages par des traitements JavaScript trop longs                 | 4        | 3              | 4                 | 3,67             |
| 60  | Mettre en place une architecture élastique                                             | 3        | 3              | 4                 | 3,33             |
| 61  | Limiter le nombre d'appels aux API HTTP                                                | 4        | 3              | 5                 | 4,00             |
| 62  | Limiter le recours aux carrousels                                                      | 4        | 4              | 4                 | 4,00             |
| 63  | Mettre en place un "Circuit breaker"                                                   | 2        | 2              | 2                 | 2,00             |
| 64  | Favoriser le "Request collapsing"                                                      | 2        | 2              | 2                 | 2,00             |
| 65  | Préférer la pagination au défilement infini                                            | 3        | 4              | 3                 | 3,33             |
| 66  | Sécuriser l'accès à l'administration                                                   | 2        | 2              | 2                 | 2,00             |
| 67  | Ne pas afficher les documents à l'intérieur des pages                                  | 3        | 1              | 4                 | 2,67             |
