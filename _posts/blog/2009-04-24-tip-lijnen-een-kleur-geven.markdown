--- 
contenttype: blog
wordpress_id: 50
layout: posts-blog
title: "Tip: lijnen een kleur geven"
date: 2009-04-24 19:40:14 +02:00
wordpress_url: http://www.skup.be/?p=50
featuredimg: /assets/images/blog/trap-color-by-axis.png
featuredalt: trap-color-by-axis
---
Wanneer SketchUp niet lijkt te werken (PUSH/PULL doet het niet, je kan
geen openingen maken in een gevel, …) ligt dit meestal niet aan
SketchUp, maar aan jezelf. Vaak zijn lijnen niet wat ze lijken (of wat
je ermee wilde bereiken) : ze liggen niet op het grondvlak, ze zijn niet
evenwijdig met een as, … Jammer genoeg merk je dit meestal te laat op:
op het moment dat je je model roteert, wanneer je problemen ondervindt,
…

![trap-color-by-axis][]


*(de trap in bovenstaand voorbeeld komt uit [dit 3D Warehouse model][])*

Daarom deze tip: je kan in SketchUp een optie instellen die ervoor zorgt
dat lijnen die evenwijdig zijn aan één van de gekleurde assen (X-Y-Z,
Rood-Groen-Blauw), gekleurd worden volgens de kleur van deze as. Een
lijn die evenwijdig is aan de groene as, zal zelf dus ook groen worden
als je deze optie instelt. Dit is handig omdat je dan in één oogopslag
kan zien aan welke as een bepaalde lijn evenwijdig is. Als een lijn niet
evenwijdig is aan één van de assen, blijft ze gewoon zwart. Deze optie
wordt "**Color - By Axis**" genoemd, en je stelt ze als volgt in:

![color-by-axis1][]

Open het “Styles” deelvenster via het menu:
**Window \> Styles**

1.  Kies via het drop-down menu de style “In Model”
2.  Ga naar het “Edit” tabblad
3.  Standaard kom je dan bij de “Edge” instellingen terecht (indien dit
    niet het geval is, moet je op het Edge icoon klikken. Het ziet eruit
    als een wireframe blokje.)
4.  Verander "**Color**" in "**By axis**"

(Je kan dit alles -in het Engels- nalezen op Google’s "[SketchUp Help][]" site)

Merk op dat er nog 2 andere opties beschikbaar zijn: “All
Same” en “By Material”.

-   "**All Same**" zorgt ervoor dat alle lijnen in je model dezelfde
    kleur krijgen. Deze kleur kan je instellen door de kleur van het
    vakje naast het drop-down menu aan te passen.
-   "**By Material**" zorgt ervoor dat je lijnen van een kleur kan
    voorzien met het PAINT BUCKET gereedschap, net zoals je dat bij
    vlakken gewoon bent.

[dit 3D Warehouse model]: http://sketchup.google.com/3dwarehouse/details?mid=66a0b2e94dacec623c231c3f2c107449&prevstart=0# "3D Warehouse - Stairs door Mesnic"

[SketchUp Help]: http://sketchup.google.com/support/bin/answer.py?hl=en&answer=36228 "SketchUp Help - Color - By Axis"



[trap-color-by-axis]: /assets/images/blog/trap-color-by-axis.png "trap-color-by-axis"

[color-by-axis1]: /assets/images/blog/color-by-axis1.png "color-by-axis1"

