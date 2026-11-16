# Ibadica (العربية) — style bibliographique CSL

Style bibliographique [CSL](https://citationstyles.org/) de l'éditeur [Ibadica](https://www.ibadica.org/), entièrement en arabe, en système auteur-date. Il suit la structure du Chicago Manual of Style (auteur-date) adaptée aux usages académiques arabes. Il fonctionne avec Zotero, Mendeley et tout logiciel fondé sur citeproc-js.

Le fichier à installer est [`ibadica.csl`](ibadica.csl). L'ancienne version multilingue est conservée dans [`ancienne-version/`](ancienne-version/), mais n'est plus maintenue.

## Installation

1. Téléchargez [`ibadica.csl`](ibadica.csl).
2. Dans Zotero : Réglages › Citer › Styles, bouton « + », puis choisissez le fichier.
3. Dans Word ou LibreOffice, choisissez le style **Ibadica (العربية)** dans les préférences du document Zotero.

Si vous aviez installé une version antérieure (« Ibadica (Arabic, author-date) »), supprimez-la : l'identifiant du style a changé.

## Exemples

Citations dans le texte :

<p dir="rtl">(الشماخي 1430هـ/2009م، ج2، ص 45) · (الكندي والريامي 2012) · (الكندي وآخرون 2012) · (الشماخي د.ت، ق 12أ)</p>

Livre (édition critique, date double, pagination) :
<p dir="rtl">الشماخي، أحمد بن سعيد. 1430هـ/2009م. <b>كتاب السير</b>. تحقيق محمد حسن. ط2. ج2. بيروت: دار المدار الإسلامي. 350 ص.</p>

Ouvrage collectif :
<p dir="rtl">الجعبيري، فرحات ومحمد بابا عمي (إشراف). 2015. <b>الإباضية في الدراسات المعاصرة</b>. سلسلة الدراسات الإباضية، رقم 5. مسقط: وزارة الأوقاف والشؤون الدينية.</p>

Œuvre anonyme éditée (le titre remplace l'auteur) :
<p dir="rtl"><b>السير والجوابات لعلماء وأئمة عمان</b>. 1406هـ/1986م. تحقيق سيدة إسماعيل كاشف. 2 ج. مسقط: وزارة التراث القومي والثقافة.</p>

Chapitre d'un ouvrage collectif :
<p dir="rtl">مصطفى، بشير. 2015. «الإباضية في جربة». في <b>الإباضية في الدراسات المعاصرة</b>، إشراف فرحات الجعبيري، ص 112-145. مسقط: وزارة الأوقاف والشؤون الدينية.</p>

Partie d'une édition critique :
<p dir="rtl">أبو عمار، عبد الكافي. 1417هـ/1997م. «باب في الإمامة». في <b>الدليل والبرهان</b>، تأليف أبو يعقوب الوارجلاني، تحقيق مصطفى بابزيز، ج3، ص 20-31. مسقط: وزارة التراث.</p>

Article de revue :
<p dir="rtl">بوعصبانة، عمر. 2020. «المؤسسات الدينية الإباضية في وادي ميزاب». <b>مجلة الدراسات التاريخية</b>، مج 12، ع 3، ص 45-67. https://doi.org/10.1234/abcd.2020.12.</p>

Compte rendu :
<p dir="rtl">الصوافي، خالد. 2010. مراجعة لكتاب <b>كتاب السير</b>، تأليف أحمد بن سعيد الشماخي. <b>مجلة نزوى</b>، ع 40، ص 201-205.</p>

Thèse :
<p dir="rtl">بن عيسى، أحمد. 2014. <b>الحياة العلمية في وارجلان</b>. إشراف محمد الصالح مرمول. أطروحة دكتوراه، جامعة الجزائر 2، الجزائر. 512 ص.</p>

Manuscrit :
<p dir="rtl">الشماخي، أحمد بن سعيد. د.ت. <b>سير المشائخ</b>. مخطوط، مكتبة بولاك، باريس، رقم MS.ARA.1931. 257 ق. تاريخ الاطلاع: 3 نوفمبر 2020. http://archive.org/details/MS.ARA.1931.</p>

Lettre :
<p dir="rtl">أطفيش، محمد بن يوسف. 1330هـ/1912م. رسالة إلى سليمان الباروني، بني يزقن، 12 مارس. مكتبة القطب، بني يزقن، رقم ر 45.</p>

Entrée d'encyclopédie :
<p dir="rtl">ناصر، محمد صالح. 2008. «الإمامة». في <b>معجم مصطلحات الإباضية</b>، إشراف فرحات الجعبيري، ج1، ص 80-84. مسقط: وزارة الأوقاف والشؤون الدينية.</p>

Communication non publiée :
<p dir="rtl">الراشدي، سالم. 2013. «فقه النوازل عند الإباضية». ورقة قُدِّمت في ندوة تطور العلوم الفقهية، مسقط، 8 أبريل.</p>

Page web :
<p dir="rtl">الحجري، يوسف. 2021. «فهرس المخطوطات العمانية». موقع إباضيكا، 3 مايو. تاريخ الاطلاع: 1 أكتوبر 2026. https://www.ibadica.org/.</p>

Données manquantes :
<p dir="rtl">البرادي، أبو القاسم. 1302هـ/1885م. <b>الجواهر المنتقاة</b>. د.م: د.ن. 350 ص.</p>

## Conventions

- Titres d'ouvrages, de revues et de manuscrits en gras ; titres d'articles, de chapitres et de pages web entre guillemets « ».
- Ponctuation arabe (، et ؛) ; conjonction « و » attachée au nom suivant.
- Abréviations : ط (édition), ج (volume d'un livre), مج (volume d'une revue), ع (numéro), ص (page), ق (folio), د.ت (sans date), د.م (sans lieu), د.ن (sans éditeur).
- Plages de pages avec un trait d'union simple (« ص 45-67 ») : le tiret demi-cadratin est inversé par l'algorithme bidirectionnel dans un texte de droite à gauche.

## Guide de saisie dans Zotero

| Besoin | Saisie |
|---|---|
| Date hégirienne | `original-date: 1430` dans le champ Extra (année grégorienne dans « Date ») |
| Éditeur critique (تحقيق) | Rôle « Éditeur », avec un auteur ou une date hégirienne |
| Direction d'un collectif (إشراف) | Rôle « Éditeur » sans auteur ni date hégirienne, ou `editorial-director: Nom \|\| Prénom` dans Extra |
| Directeur de thèse | Rôle « Collaborateur » (affiché إشراف) |
| Copiste d'un manuscrit | Rôle « Collaborateur » (affiché نسخ) |
| Bibliothèque d'un manuscrit ou d'une lettre | Champ « Archive » ; ville dans « Lieu » ; cote seule dans « Cote » (affichée « رقم … ») |
| Nombre de pages ou de folios | Champ « Nb de pages » : un nombre, pas une plage |
| Lieu d'écriture d'une lettre | Champ « Lieu de l'événement » |
| Courriel | `genre: رسالة إلكترونية` dans Extra |
| Communication | Champ « Type » : un nom simple (ورقة، مداخلة، محاضرة) ; le style ajoute « قُدِّمت في » |

### La règle تحقيق / إشراف

CSL n'a qu'un rôle « éditeur ». Le style le rend par تحقيق quand l'ouvrage a un auteur (ou, pour un chapitre, quand le livre a un auteur) ou une date hégirienne, et par إشراف sinon. Le rôle `editorial-director`, saisi dans Extra, force toujours إشراف ; il permet aussi d'avoir à la fois un directeur (إشراف) et un éditeur critique (تحقيق).

## Limites connues

Ces limites tiennent au langage CSL lui-même et ne peuvent pas être corrigées dans le style :

- les lettres de désambiguïsation sont latines (2020a, 2020b) au lieu de أ، ب ;
- l'article « ال » compte dans le tri alphabétique ;
- les chiffres et les noms sont affichés tels que saisis : un nom comme « أبو يعقوب » reste au nominatif après تحقيق ou تأليف ;
- seuls les mois grégoriens existent : pour une lettre datée en hégirien, seule l'année apparaît ;
- comme `original-date` sert à la date hégirienne, la date d'une première édition ne peut pas s'afficher ; on peut l'écrire dans le champ « Édition ».

## English summary

Arabic-only author-date style of the publisher Ibadica, modelled on Chicago author-date. Key conventions: bold titles for books and periodicals, guillemets for articles and chapters, Arabic punctuation, Hijri/Gregorian double dates (Hijri year entered as `original-date`), and a distinction between critical editor (تحقيق, CSL `editor` when the work has an author or a Hijri date) and director of a collective volume (إشراف, CSL `editorial-director`, or `editor` without author). In theses `contributor` is the supervisor; in manuscripts it is the copyist.

## Licence

[Creative Commons Attribution-ShareAlike 3.0](http://creativecommons.org/licenses/by-sa/3.0/) — Soufien Mestaoui / Ibadica.
