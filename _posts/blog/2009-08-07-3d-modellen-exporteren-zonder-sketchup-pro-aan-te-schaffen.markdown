--- 
contenttype: blog
wordpress_id: 339
layout: posts-blog
title: 3D modellen exporteren zonder SketchUp Pro aan te schaffen
date: 2009-08-07 16:46:28 +02:00
wordpress_url: http://www.skup.be/?p=339
featuredimg: /assets/images/blog/collada_2.png
featuredalt: collada_2
---
In een [vorig artikel][] haalde ik aan dat het mogelijk is om 3D
modellen vanuit SketchUp naar andere 3D programma’s te exporteren,
zonder daarvoor de Pro versie aan te moeten schaffen. In dit artikel leg
ik stap voor stap uit hoe je hier aan begint:

-   Kies in het menu voor
    **File\>Export\>3D Model…**
-   In het venster dat verschijnt kan je een naam opgeven voor het
    geëxporteerde bestand, en kan je kiezen onder welke vorm je je 3D
    model wil exporteren. Dit is waar je tegen de beperkingen van de
    gratis SketchUp versie aanloopt: **je kan enkel Google Earth
    bestanden (=KMZ bestanden) exporteren**. Toch is dit wat we willen
    doen. Geef een naam op, en bewaar je 3D model als KMZ bestand.
    *(Zodra je op OK klikt, verschijnt er een venster met “export
    results”. Dit venster mag gewoon gesloten worden.)*

![SketchUp - export - Google Earth][]

-   Wanneer je dubbelklikt op het KMZ bestand dat SketchUp zonet
    aanmaakte, wordt dit -zoals je kon verwachten- geopend in Google
    Earth.
-   Om verder te gaan, moet je eerst wat meer weten over **[KMZ
    bestanden][]: in feite zijn dit archieven (ZIP bestanden)** die alle
    noodzakelijk informatie bevatten om een SketchUp 3D model correct
    weer te geven in Google Earth.
-   Dit is dan ook de omweg die we moeten volgen: door het **KMZ archief
    in een ZIP archief te veranderen** (=KMZ extensie vervangen door ZIP
    extensie), kunnen we dit archief voortaan openen.

![SketchUp - KMZ bestand in ZIP bestand omzetten][]

-   Het **ZIP archief bevat steeds een “models” map met daarin een DAE
    bestand**.

![SketchUp - Inhoud KMZ bestand][]

![SketchUp - Collada (DAE) bestand][]

-   Een DAE bestand (of *digital asset exchange* bestand), ook
    gekend als [COLLADA bestand][], is een **vrij nieuw 3D
    bestandsformaat dat met een hele reeks 3D programma’s compatibel
    is**: [Cinema4D][], [Blender][], [Maya][] en [3ds Max][] (via
    plugins), …

**Conclusie**: hoewel het
op het eerste zicht onmogelijk lijkt om 3D modellen te exporteren vanuit
de gratis SketchUp versie, is dit slechts schijn. Het is mogelijk Google
Earth bestanden te exporteren: dit zijn in feite archieven die COLLADA
bestanden bevatten (=zowat de best uitwisselbare 3D bestanden).

[vorig artikel]: http://www.skup.be/sketchup-versus-sketchup-pro/ "SketchUp versus SketchUp Pro"

[KMZ bestanden]: http://nl.wikipedia.org/wiki/Keyhole_Markup_Language "Wikipedia - KML"

[COLLADA bestand]: http://en.wikipedia.org/wiki/COLLADA "Wikipedia - COLLADA"

[Cinema4D]: http://www.maxon.net/products/cinema-4d.html "Cinema4D"

[Blender]: http://www.blender.org/ "Blender"

[Maya]: http://usa.autodesk.com/adsk/servlet/pc/index?id=13577897&siteID=123112 "Maya"

[3ds Max]: http://usa.autodesk.com/adsk/servlet/pc/index?id=13567410&siteID=123112 "3ds Max"



[SketchUp - export - Google Earth]: /assets/images/blog/collada_1.png "collada_1"

[SketchUp - KMZ bestand in ZIP bestand omzetten]: /assets/images/blog/collada_2.png "collada_2"

[SketchUp - Inhoud KMZ bestand]: /assets/images/blog/collada_3.png "collada_3"

[SketchUp - Collada (DAE) bestand]: /assets/images/blog/collada_4.png "collada_4"
