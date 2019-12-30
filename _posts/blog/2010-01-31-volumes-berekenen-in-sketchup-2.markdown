--- 
contenttype: blog
wordpress_id: 470
layout: posts-blog
title: Volumes berekenen in SketchUp
date: 2010-01-31 11:58:39 +01:00
wordpress_url: http://www.skup.be/?p=470
featuredimg: /assets/images/blog/w_volume.png
featuredalt: VolumeCalculator volume
---
In SketchUp kan je snel en intuïtief 3D objecten tekenen. Wanneer je
echter wil nameten wat je tekende, zal je op een vreemde beperking
stuiten: SketchUp kan slechts 2 dimensies opmeten (lengtes en
oppervlaktes). Volumes berekenen behoort niet tot de standaard
mogelijkheden van SketchUp. Toch is het iets wat veel mensen willen
kunnen.

![VolumeCalculator eindresultaat][]

Gelukkig is het mogelijk SketchUp uit te breiden met een **script**,
waardoor **volumes berekenen** wel mogelijk wordt: het
“VolumeCalculator” script. Je kan het **VolumeCalculator script**
[hier][] downloaden (zelf vond ik het op [deze website][]). Als je niet
weet hoe je een SketchUp script moet installeren, verwijs ik je graag
door naar dit artikel: [SketchUp uitbreiden met scripts][]. Zodra je het
script installeerde, kan je het op volgende manier gebruiken:

* Uiteraard moet je eerst een volume tekenen, wat minder voor de hand ligt
is dat je van dit volume ook **een groep of een component** moet
**maken** (=gans het volume selecteren, rechtsklikken en “make group” of
“make component” kiezen).

![VolumeCalculator make group][]

* Enkel wanneer je van het volume een groep of een component maakte,
kan je het volume opnieuw selecteren, en opnieuw rechtsklikken, waarna
je zal zien dat er onderaan in het **contextmenu** een **extra optie**
verscheen: "**Volume**". Klik hierop om het instellingenvenster te
openen (Volume Parameters).

![VolumeCalculator volume][]

* Om een volume te berekenen, moet je eerst een aantal **parameters
instellen**. In de praktijk zijn enkel de eerste 2 paramaters van
belang: **Units** (eenheden) en **Accuracy** (nauwkeurigheid).

![VolumeCalculator parameters][]

* Via "**Units**" geef je aan **in welke eenheid je het volume wil
berekenen**. “Cu” staat hierbij voor Cubic. “cu.m” staat dus voor
"[cubic metre][]" of "[kubieke meter][]" wat waarschijnlijk de meest
gebruikte eenheid is. Indien gewenst kunnen ook andere eenheden gebruikt
worden:

	- Cc of [kubieke centimeter][]
	- Cu.yds of [kubieke yard][]
	- Cu.ft of [kubieke foot][]
	- Cu.ins of [kubieke inch][]
	- Litres of [liter][]
	- Cl of [centiliter][]
	- Ml of [milliliter][]
	- Gallons (UK) of imperial [gallon][]
	- Gallons (USA) of US [gallon][]
	- [Quarts][] (USA)
	- Pints (UK) of imperial [pint][]
	- Pints (USA) of US [pint][]

![VolumeCalculator eenheden][]

* Via "**Accuracy**" geef je aan **hoe nauwkeurig de volumeberekening
moet gebeuren**: Van nauwkeurig naar minder nauwkeurig: 0.5, 1, 2, 5 of
10%. Later volgt waarschijnlijk nog een artikel met meer
achtergrondinformatie rond het VolumeCalculator script, voorlopig
volstaat het om te weten dat de volumeberekening een benaderende methode
gebruikt, een dat een kleiner percentage een nauwkeuriger resultaat
oplevert. Het nadeel is dat de berekening bij een klein percentage/hoge
nauwkeurigheid (veel) langer duurt. Je zal dus steeds twee zaken moeten
afwegen: snelheid versus nauwkeurigheid.

![VolumeCalculator accuracy][]

* Nu de twee belangrijkste parameters ingesteld werden, kan je op “OK”
klikken, zodat de berekening start. Zodra ze voltooid is, krijg je nog
**2 vragen** voorgeschoteld. Voorlopig volstaat het "**No**" te
**antwoorden** op deze 2 vragen. (Ook hier geldt: later volgt
waarschijnlijk nog een artikel met meer achtergrondinformatie rond het
VolumeCalculator script).

![VolumeCalculator vraag 1][]

![VolumeCalculator vraag 2][]

* Klaar! Het volume werd berekend, en verscheen in de gewenste eenheid
boven de groep of de component.

![VolumeCalculator eindresultaat][]



[hier]: http://www.skup.be/sketchup-oefenbestanden/VolumeCalculator.rb "SKUP - VolumeCalculator script"

[deze website]: http://www.crai.archi.fr/RubyLibraryDepot/Ruby/em_geo_page.htm "Ruby Library Depot"

[SketchUp uitbreiden met scripts]: http://www.skup.be/sketchup-uitbreiden-met-scripts/ "SKUP - SKetchUp uitbreiden met scripts"

[cubic metre]: http://en.wikipedia.org/wiki/Cubic_metre "Wikipedia - cubic metre"

[kubieke meter]: http://nl.wikipedia.org/wiki/Kubieke_meter "Wikipedia - kubieke meter"

[kubieke centimeter]: http://nl.wikipedia.org/wiki/Kubieke_centimeter "Wikipedia - kubieke centimeter"

[kubieke yard]: http://en.wikipedia.org/wiki/Cubic_yard "Wikipedia - cubic yard"

[kubieke foot]: http://en.wikipedia.org/wiki/Cubic_foot "Wikipedia - cubic foot"

[kubieke inch]: http://en.wikipedia.org/wiki/Cubic_inch "Wikipedia - cubic inch"

[liter]: http://nl.wikipedia.org/wiki/Liter "Wikipedia - liter"

[centiliter]: http://nl.wikipedia.org/wiki/Centiliter "Wikipedia - centiliter"

[milliliter]: http://nl.wikipedia.org/wiki/Milliliter "Wikipedia - milliliter"

[gallon]: http://nl.wikipedia.org/wiki/Gallon "Wikipedia - gallon"

[Quarts]: http://nl.wikipedia.org/wiki/Quart_(eenheid) "Wikipedia - quart"

[pint]: http://nl.wikipedia.org/wiki/Pint "Wikipedia - pint"



[VolumeCalculator eindresultaat]: /assets/images/blog/w_eindresultaat.png "VolumeCalculator eindresultaat"

[VolumeCalculator make group]: /assets/images/blog/w_make-group.png "VolumeCalculator make group"

[VolumeCalculator volume]: /assets/images/blog/w_volume.png "VolumeCalculator volume"

[VolumeCalculator parameters]: /assets/images/blog/w_parameters.png "VolumeCalculator parameters"

[VolumeCalculator eenheden]: /assets/images/blog/w_eenheden.png "VolumeCalculator eenheden"

[VolumeCalculator accuracy]: /assets/images/blog/w_accuracy.png "VolumeCalculator accuracy"

[VolumeCalculator vraag 1]: /assets/images/blog/w_vraag-1.png "VolumeCalculator vraag 1"

[VolumeCalculator vraag 2]: /assets/images/blog/w_vraag-2.png "VolumeCalculator vraag 2"

[VolumeCalculator eindresultaat]: /assets/images/blog/w_eindresultaat.png "VolumeCalculator eindresultaat"