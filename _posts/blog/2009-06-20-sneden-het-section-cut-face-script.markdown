--- 
contenttype: blog
wordpress_id: 314
layout: posts-blog
title: "Sneden: het \"Section-Cut Face\" script"
date: 2009-06-20 13:46:36 +02:00
wordpress_url: http://www.skup.be/?p=314
featuredimg: /assets/images/blog/Farnsworth-House.jpg
featuredalt: Farnsworth House
---
Dit is het laatste artikel in de “Sneden”-reeks. Om de leesbaarheid van
een snede te vergroten, is het een goed idee om een visueel onderscheid
te maken tussen zaken die doorgesneden worden, en zaken die niet
doorgesneden worden. Standaard doet men dit door doorgesneden volumes
zwart in te kleuren.

![Farnsworth House][]

SketchUp kent deze mogelijkheid helaas niet. We kunnen gelukkig wel
gebruik maken van een script dat deze taak op zich neemt: **het
“Section-Cut Face” script**. Je vindt dit script [hier][] ([Ruby library
depot][] - je moet dit script wel nog even in een tekstbestand plakken,
en opslaan met een .rb extensie). Meer uitleg over het installeren van
SketchUp-scripts vind je [hier][1]. We zullen het “Section-Cut Face”
script gebruiken in een bestaand 3D model: het [Farnsworth House][2] van
architect [Ludwig Mies van der Rohe][].

![Section-Cut Face context][]

Zodra het “Section-Cut Face” script geïnstalleerd werd, kan je
**rechts-klikken op een bestaand snede**, zodat er een context-menu
verschijnt, met onderaan een verwijzing naar het script: "**Add
Section-Cut Face**". Hierop klikken opent een dialoogvenster:

![Section-Cut Face dialoog][]

Eigenlijk hoeven we niets aan de instellingen te veranderen. Moest je
dit wel willen doen, kan je volgende richtlijnen volgen:

-   De kleuren die je kan kiezen onder "**Cut-Face**" en "**Cut-Edge**"
    zullen het uitzicht van doorgesneden volumes bepalen: je bepaalt de
    vlakkleur en de randkleur.
-   Onder "**Cut-Edge**" kan je de lijndikte van de snede bepalen: 0 tot
    20.
-   "**Cut Layer**" geeft aan in welke laag de “inleg” van het
    doorgesneden volume geplaatst zal worden. Deze komt standaard in een
    nieuwe laag te staan, zodat je hem makkelijk zichtbaar of
    onzichtbaar kan maken.

*Dit artikel is het derde deel in een 3-delige reeks over sneden:*

1.  *[Sneden en plannen met het “Section Plane” gereedschap][]*
2.  *[Het “Section Plane” gereedschap – deel 2: opties][]*
3.  *[Sneden: het “Section-Cut Face” script][]*

[hier]: http://www.crai.archi.fr/RubyLibraryDepot/Ruby/SectionCutface.rb "Ruby library depot - Section-Cut Face"

[Ruby library depot]: http://www.crai.archi.fr/RubyLibraryDepot/Ruby/RUBY_Library_Depot.htm "Ruby library depot"

[1]: http://www.skup.be/sketchup-uitbreiden-met-scripts/ "SKUP - scripts"

[2]: http://sketchup.google.com/3dwarehouse/details?mid=c9359236bc1dcda8b39026ead5439850&prevstart=48 "3D Warehouse - Farnsworth House"

[Ludwig Mies van der Rohe]: http://nl.wikipedia.org/wiki/Ludwig_Mies_van_der_Rohe "Wikipedia - Ludwig Mies van der Rohe"

[Sneden en plannen met het “Section Plane” gereedschap]: ../sneden-en-plannen-met-het-section-plane-gereedschap/ "Sneden en plannen met het “Section Plane” gereedschap"

[Het “Section Plane” gereedschap – deel 2: opties]: ../het-“section-plane”-gereedschap-deel-2-opties/ "Het “Section Plane” gereedschap – deel 2: opties"

[Sneden: het “Section-Cut Face” script]: http://www.skup.be/sneden-het-section-cut-face-script "Sneden: het "Section-Cut Face" script"



[Farnsworth House]: /assets/images/blog/Farnsworth-House.jpg "Farnsworth House"

[Section-Cut Face context]: /assets/images/blog/Section-Cut-Face-context.png "Section-Cut Face context"

[Section-Cut Face dialoog]: /assets/images/blog/Section-Cut-Face-dialoog.png "Section-Cut Face dialoog"