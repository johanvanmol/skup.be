--- 
contenttype: blog
wordpress_id: 118
layout: posts-blog
title: "SketchUp kopieën en reeksen (arrays)"
date: 2009-05-20 19:42:37 +02:00
wordpress_url: http://www.skup.be/?p=118
featuredimg: /assets/images/blog/skp-reeksen_extern.jpg
featuredalt: skp-reeksen_extern
---
Wie al een tijdje met SketchUp werkt, weet ongetwijfeld dat SketchUp op
het eerste zicht geen kopieer gereedschap bevat. Het kopieer gereedschap
zit namelijk verborgen achter het verplaats gereedschap (de move tool).
Om te **kopiëren**, doe je daarom net alsof je een object wil
verplaatsen, maar houd je terwijl je dit doet een toets op je
toetsenbord ingedrukt:

-   de **OPTION** (alt) toets als je een **Mac** gebruiker bent
-   de **CTRL** toets als je een **Windows** gebruiker bent

![skp-reeksen-basis][]
*(Een staafje, gekopieerd over een afstand van 10 meter.)*

Kopiëren is basiskennis. Als je een stap verder wil gaan, kan je heel eenvoudig **meervoudige
kopieën** (=reeksen of arrays) van een object maken: dit doe je door
-net nadat je een kopie maakte- in te typen hoeveel kopieën je in het
totaal nodig hebt:

-   Wanneer je een object over een afstand van 10 meter kopieert, en je
    typt meteen daarna "**x5**" of "**\*5**" in, dan wordt het kopieer
    commando 5 maal uitgevoerd, en bekom je dus 5 kopieën. De kopieën
    staan telkens 10 meter van elkaar. Deze reeksen worden ook wel
    **externe reeksen** genoemd.

![skp-reeksen-extern][]
*(Een externe reeks. Meteen na het kopiëren werd "x5" ingetypt.)*

-   De vorige naam deed het al vermoeden: er bestaan ook
    **interne reeksen**. Deze creëer je door net na het kopiëren "**/5**"
    in te typen. Als het oorspronkelijke object over een afstand van 10
    meter gekopieerd werd, zullen er nu echter geen kopieën om de 10
    meter bijgemaakt worden, maar worden de extra kopieën verdeeld
    binnen de oorspronkelijk 10 meter: er bevindt zich nu dus een kopie
    om de 2 meter.

![skp-reeksen-intern][]
*(Een interne reeks. Meteen na het kopiëren werd "/5" ingetypt.)*


*Dit alles is ook van
toepassing op het roteer gereedschap (de rotate tool): wanneer je
roteert en tegelijk OPTION of CTRL ingedrukt houdt, bekom je een kopie.
Door meteen daarna “x” of “/” -gevolgd door een aantal- in te typen,
creëer je een reeks.* Tip: aangezien we bij het creëren van reeksen
steeds **meerdere kopieën van een zelfde object** maken, is het het
slimst om dit object op voorhand om te zetten in een **component**.

[skp-reeksen-basis]: /assets/images/blog/skp-reeksen_basis.jpg "skp-reeksen_basis"

[skp-reeksen-extern]: /assets/images/blog/skp-reeksen_extern.jpg "skp-reeksen_extern"

[skp-reeksen-intern]: /assets/images/blog/skp-reeksen_intern.jpg "skp-reeksen_intern"
