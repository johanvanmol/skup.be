--- 
contenttype: blog
wordpress_id: 754
layout: posts-blog
title: Het volume van een object weergeven in SketchUp 8
date: 2011-12-03 16:29:50 +01:00
wordpress_url: http://www.skup.be/?p=754
featuredimg: /assets/images/blog/00_volume.jpg
featuredalt: 00_volume
---
In oudere SketchUp versies was het berekenen van volumes een vrij
omslachtige taak. Je moest [SketchUp hiervoor uitbreiden met een
script][]. Met de release van SketchUp 8 kwam hier verandering in. In
deze versie kan je gewoon **rechtsklikken op een object**, en het
**Entity Info venster** openen. In dit venster wordt het **volume** als
één van de eigenschappen weergegeven.

![00-volume][]

Dit lijkt niet meteen voer voor een nieuw artikel. Toch kan het handig
zijn alle **aandachtspunten** even te overlopen:

-   Het Entity Info venster geeft enkel het volume van solids (vaste
    vormen) weer.
-   Een solid (vaste vorm) is:
	-   Een component of groep met een beperkt gesloten volume. Een solid
    (vaste vorm) mag geen openingen bevatten \> (ontbrekende vlakken of
    vlakken die niet doorlopen tot een lijn).
-   Concreet moet je, om een solid ( vaste vorm) aan te maken, volgende
    stappen doorlopen:

	-	Een gesloten volume tekenen (bijvoorbeeld een vlak, dat je met behulp van Push/Pull in een volume omzet).
	-	Dit volume selecteren en er een groep of component van maken (rechtsklikken en **Make Component** of **Make Group** kiezen)
	-	Belangrijk: de groep of component mag geen:
		-   openingen bevatten (vermijd ontbrekende vlakken)
		
		![01-opening][]
		
		-   verdwaalde of overtollige lijnen bevatten (zogenaamde *“stray lines”*)
    
    	![02-overtollig][]
    
		-   overtollige verborgen geometrie bevatten (vink in het **View menu** de optie \*\*Hidden Geometry\*\* aan, om eventuele verborgen geometrie zichtbaar te maken)
		
		![03-verborgen][]
		
		-   overlappende elementen bevatten
		
		![04-overlappend][]

Samengevat kan je het volume van een object sinds SketchUp 8 gewoon
aflezen in het Entity Info venster. Wanneer dit niet lukt, selecteerde
je waarschijnlijk geen solid (vaste vorm), en kan je bovenstaande
aandachtspunten best even overlopen.

[SketchUp hiervoor uitbreiden met een script]: http://www.skup.be/volumes-berekenen-in-sketchup-2/ "Volumes berekenen in SketchUp"



[00-volume]: /assets/images/blog/00_volume.jpg "00_volume"

[01-opening]: /assets/images/blog/01_opening.jpg "01_opening"

[02-overtollig]: /assets/images/blog/02_overtollig.jpg "02_overtollig"

[03-verborgen]: /assets/images/blog/03_verborgen.jpg "03_verborgen"

[04-overlappend]: /assets/images/blog/04_overlappend.jpg "04_overlappend"
