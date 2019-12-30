--- 
contenttype: blog
layout: posts-blog
title: Afprinten op schaal in SketchUp
featuredimg: /assets/images/blog/layout_scale.png
featuredalt: Google SketchUp Pro - Layout - Scale instellen
---

Ik krijg regelmatig de vraag of het mogelijk is om SketchUp tekeningen op schaal af te printen.

Hoewel dit perfect mogelijk is met de gratis versie van SketchUp, is dit veel makkelijker met SketchUp Pro.
SketchUp Pro bevat namelijk een extra hulpprogramma, [Layout][], dat specifiek ontworpen werd om ontwerppresentaties te maken, waaronder prints op schaal.
In Layout volstaat het rechts te klikken op een ingeladen 3D beeld, en in het context menu de gewenste schaal te kiezen onder "Scale".

![layout-scale][]

Wanneer je niet wil investeren in SketchUp Pro (en Layout), en hetzelfde wil bereiken in de gratis versie van SketchUp, moet je op voorhand enkele zaken weten:

## Perspectief uitschakelen

Het is niet mogelijk om een perspectieftekening op schaal af te drukken.  Enkel standaardzichten zonder perspectief (bovenaanzicht, vooraanzicht, isometrie, …) kunnen op schaal afgedrukt worden.

1. Om één van deze standaardzichten op te roepen, werk je via het menu: **Camera > Standard Views > …**
2. Vervolgens moet je aangeven dat je geen perspectief wil gebruiken (opnieuw via het camera menu): **Camera > Parallel Projection**

## Print instellingen

Om het hierboven aangemaakte zicht op schaal af te printen werk je via het File menu: **File > Print….**
(Op een Mac: **File > Document Setup...**)

![sketchup-printdialog][]

Vooral de instellingen onder **“Print Size”** zijn van belang:

1. **“Fit to page”** moet uitgevinkt zijn.  Indien dit niet het geval is, wordt het model afgedrukt om op één volledige pagina te passen.  De schaal wordt in dit geval automatisch bepaald, afhankelijk van de grootte van uw pagina.
2. **“Use model extents”** moet aangevinkt zijn.  In dit geval wordt enkel datgene wat je tekende afgedrukt, en wordt er geen rekening gehouden met de lege ruimte rondom je tekening.

Om een schaal in te stellen moet je 2 getallen ingeven (nog steeds onder **“Print Size: Scale”**).  De verhouding tussen deze 2 getallen bepaalt de schaal.  Om een tekening op schaal 1/100 af te drukken, geef je bijvoorbeeld het volgende in:

1. Bij **“In the printout”** 1
2. Bij **“In SketchUp”** 100

*Tenslotte nog een aandachtspunt (nog steeds onder “Print Size: Page Size”): onder “Page size” zie je bij “Width” en “Height” automatisch afmetingen verschijnen.  Deze afmetingen bepalen hoe groot je afdruk uiteindelijk zal zijn.  Uiteraard moeten deze afmetingen kleiner zijn dan de grootte van het papier waarop je afdrukt.  Indien dit niet het geval is, zal je afdruk niet op één pagina passen.*

Conclusie: afdrukken op schaal is mogelijk met de gratis versie van SketchUp, maar het is omslachtig.  SketchUp Pro en Layout bieden op dit vlak heel wat voordelen.



[Layout]: http://sketchup.google.com/intl/en/product/layout.html "Google SketchUp Pro - Layout"



[layout-scale]: /assets/images/blog/layout_scale.png "Google SketchUp Pro - Layout - Scale instellen"

[sketchup-printdialog]: /assets/images/blog/sketchup_printdialog.png "Google SketchUp  - Print dialoogvenster"

