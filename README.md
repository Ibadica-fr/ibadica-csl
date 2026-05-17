# Style bibliographique Ibadica (Chicago Author-Date bilingue Arabe/Latin)

Ce dépôt contient le fichier de style bibliographique CSL (Citation Style Language) pour le style Ibadica. Conçu sur la base du Chicago Manual of Style (18e édition, système Auteur-Date), ce style a été modifié pour traiter de manière transparente et dynamique les bibliographies bilingues et multilingues alternant entre l'arabe et les langues latines (principalement français et anglais). Il est particulièrement adapté aux travaux de recherche en SHS.

## Fonctionnalités principales

* **Aiguillage linguistique automatique :** Le style détecte la langue de chaque référence à partir des métadonnées de l'élément et adapte sa structure en conséquence, évitant ainsi le recours à des profils ou à des styles différents au sein d'un même document.
* **Respect des conventions typographiques locales :**
  * **Références latines :** Titres d'ouvrages en italique, séparation par des virgules occidentales et conjonctions de coordination standard (et / and).
  * **Références arabes :** Titres d'ouvrages en caractères gras (conformément aux usages académiques arabes), séparation par la virgule inversée (،) et conjonction de coordination arabe (و).
* **Contrôle de la bidirectionnalité (RTL/LTR) :** Insertion de caractères de contrôle Unicode masqués afin de stabiliser l'affichage de la ponctuation et des parenthèses dans les blocs de texte s'écrivant de droite à gauche.
* **Architecture anti-conflit de mémoire cache :** Les macros critiques (auteurs, contributeurs, dates, recensions et colloques) ont été intégralement scindées en blocs indépendants selon la langue. Cette approche neutralise les anomalies récurrentes du processeur de Zotero (citeproc-js) qui tend à appliquer à tort des termes arabes (tels que "تحرير" ou "فبراير") sur des notices occidentales lors de la compilation globale.
* **Normalisation des recensions :** Intégration directe des structures de phrases propres à chaque langue pour les comptes rendus de lecture afin de garantir l'exactitude grammaticale (ex. "Recension de... par..." en français et "Review of... by..." en anglais).

## Configuration requise dans Zotero

L'aiguillage automatique repose entièrement sur le champ **Langue** (Language) de vos notices Zotero. Pour un fonctionnement optimal, il est impératif d'utiliser les codes de langue ISO standardisés à deux ou trois lettres en minuscules.


## Procédure d'installation

1. Téléchargez le fichier `Ibadica (author-date).csl` depuis ce dépôt.
2. Dans Zotero, accédez au menu `Édition` > `Préférences` (ou `Zotero` > `Préférences` sur macOS).
3. Sélectionnez l'onglet `Citer`, puis l'onglet secondaire `Styles`.
4. Cliquez sur le bouton `+` situé sous la liste des styles, puis sélectionnez le fichier `.csl` téléchargé.
5. Dans votre traitement de texte habituel (Word, LibreOffice ou Google Docs), choisissez le style **Ibadica (Author-Date, bilingue Arabe/Latin)** via le module d'extension Zotero.

## Recommandation pour l'organisation de la bibliographie

En raison d'une limitation intrinsèque du processeur de style de Zotero concernant l'abréviation automatique des listes d'auteurs multiples (le terme *et al.*), le système applique globalement soit la mention latine (*et al.*), soit la mention arabe (*وآخرون*) à l'ensemble du document selon le profil de la première notice longue qu'il traite dans le cache.

Pour contourner cette contrainte technique, il est fortement recommandé de séparer votre bibliographie finale en deux sections distinctes dans votre manuscrit :
1. Une section dédiée aux sources en caractères latins (français, anglais, etc.).
2. Une section dédiée aux sources en caractères arabes.

Cette séparation s'effectue simplement dans votre traitement de texte en insérant la bibliographie par le biais de collections ou de marqueurs ciblés depuis le plugin Zotero. 
## Licence

Ce style bibliographique est distribué sous licence **Creative Commons Attribution - Partage dans les Mêmes Conditions 3.0 non transposé (CC BY-SA 3.0)**. Vous êtes libre de copier, distribuer et modifier ce style, sous réserve de citer l'auteur d'origine (Soufien Mestaoui / Projet Ibadica) et de publier vos modifications sous une licence identique.