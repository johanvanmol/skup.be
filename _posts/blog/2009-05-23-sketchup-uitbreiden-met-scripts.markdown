--- 
contenttype: blog
wordpress_id: 136
layout: posts-blog
title: SketchUp uitbreiden met scripts
date: 2009-05-23 14:19:35 +02:00
wordpress_url: http://www.skup.be/?p=136
featuredimg: /assets/images/blog/sketchup-script.png
featuredalt: sketchup-script
---
SketchUp is een uitgebreid en krachtig 3D programma. Toch zullen er
altijd mensen zijn die SketchUp niet uitgebreid genoeg vinden: mensen
die van mening zijn dat er bepaalde gereedschappen ontbreken, of dat
bepaalde ingewikkelde bewerkingen eenvoudiger moeten kunnen. De makers
van SketchUp hielden hier gelukkig rekening mee: SketchUp kan
uitgebreid/aangepast worden met scripts. Scripts doen precies wat
hierboven vermeld werd: ze voegen extra gereedschappen toe aan SketchUp,
of vereenvoudigen bepaalde bewerkingen. Wie zelf kan programmeren, kan
z’n eigen scripts schrijven. Wie dit niet kan, kan bestaande scripts
downloaden ([Smustard.com][] en [Ruby library depot][] zijn twee sites
waar je SketchUp scripts kan vinden).

![sketchup-script][]

### SketchUp scripts installeren

Het installeren van scripts is een fluitje van een cent:

1.  Om te beginnen moet je het script dat je wil gebruiken naar je
    computer downloaden.
2.  Als je een .ZIP bestand (een archief) downloadde, moet je dit eerst
    nog even uitpakken (door erop te dubbelklikken). Het uiteindelijke
    script heeft een .RB extensie.
3.  Als SketchUp geopend is, moet het programma even afgesloten worden.
4.  Daarna moet je het script (het .RB bestand) gewoon in de juiste map plaatsen:
    -   Als je een **Mac** hebt, plaats je het hier:
        **‘Hard Drive’/Users/*gebruikersnaam*/Library/Application Support/Google
        SketchUp 7/SketchUp/Plugins**
    -   Als je een **PC** hebt, plaats je het hier:
        **C:/Program Files/Google/Google SketchUp 7/Plugins**

5.  Als je SketchUp tenslotte terug opstart, wordt het script
    automatisch gevonden. Afhankelijk van het script, kan je nieuwe
    opties vinden in het (nieuwe) Plugins menu, door rechts te klikken,
    …

![sketchup-plugins-folder][]

### Voorbeeld: CurveStitcher script

Om dit alles aan te tonen zullen we het CurveStitcher script downloaden,
installeren en gebruiken. Je vindt dit script [hier][], op Smustard.com.
Via de download link (rechtsboven), kan je **curvestitcher.rb**
downloaden. Zodra je dit script in de juiste map plaatst (zie stap 4
hierboven), en SketchUp opnieuw opstart, vind je in SketchUp een nieuw
menu-onderdeel: **Plugins**.

![sketchup-plugins-menu][]

CurveStitcher is een script dat 2 geselecteerde lijnen (edges) verbindt,
en op die manier een vlak aanmaakt.

Je kan bijvoorbeeld 2 willekeurige bogen tekenen, ze allebei selecteren,
en via het menu: **Plugins \>Curve Stitcher** het vlak dat door de 2 bogen beschreven wordt
aanmaken:

![curvestitcher-lijnen][]
*(1 - twee bogen in de ruimte)*

![curvestitcher-vlak][]
*(2 - CurveStitcher deed z’n werk)*

![curvestitcher-geselecteerd][]
*(3 - alles geselecteerd)*

### Conclusie

Bovenstaand voorbeeld illustreert de kracht van scripts. Als je alle
geometrie selecteert, kan je zien dat er door één commando automatisch
25 lijnen werden aangemaakt. Scripts kunnen je dus ongelooflijk veel
werk besparen. De nadelen neem ik er dan ook graag bij: scripts zijn
moeilijk te vinden, en vaak komen ze zonder documentatie. Je zal dus
intensief moeten zoeken en uitproberen om de scripts die je nodig hebt
te vinden.

[Smustard.com]: http://www.smustard.com/ "Smustard.com"

[Ruby library depot]: http://www.crai.archi.fr/RubyLibraryDepot/Ruby/RUBY_Library_Depot.htm "Ruby library depot"

[hier]: http://www.smustard.com/script/CurveStitcher "Smustard.com - CurveStitcher Plugin"



[sketchup-plugins-menu]: /assets/images/blog/sketchup-plugins-menu.png "sketchup-plugins-menu"

[curvestitcher-lijnen]: /assets/images/blog/curvestitcher-lijnen.jpg "curvestitcher-lijnen"

[curvestitcher-vlak]: /assets/images/blog/curvestitcher-vlak.jpg "curvestitcher-vlak"

[curvestitcher-geselecteerd]: /assets/images/blog/curvestitcher-geselecteerd.jpg "curvestitcher-geselecteerd"

[sketchup-script]: /assets/images/blog/sketchup-script.png "sketchup-script"

[sketchup-plugins-folder]: /assets/images/blog/sketchup-plugins-folder.jpg "sketchup-plugins-folder"
