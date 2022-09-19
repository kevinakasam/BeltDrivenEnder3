All files for the V2 version, you should use the V3.



Info for V2: with Voron Transmission


***English version below***


Achtung!
Ich bin kein Profi und betreibe 3D-Druck als mein Hobby. Also bitte überlegt selbst, wenn ihr euren Drucker umbaut und legt nicht einfach los. Für meinen Drucker passen die Teile hervorrangend. Die Drucke sehen wirklich perfekt aus.
Jeder trägt die Risiken eines Umbaus selbst.
Alle Teile können nach Belieben verändert werden. 


Upadte V2:
Im Gegensatz zur Version V1 könnt ihr diesesmal alle Teile vom Drucker wiederverwenden. Somit ist der Umbau einfacher, stabiler und günstiger. Selbst die Pulleys könntet ihr drucken und somit Geld sparem, würde ich jedoch nicht empfelen.
Die angebrachte Übersetzung ist die größte Neuerung. Dadurch erhöht ihr nicht nur eure Auflösung in Z, auch sinkt die X Achse nicht mehr 0, sobald diese keinen Strom mehr haben (entweder nach dem Druck oder sollte euer Strom ausfallen). Alle weiteren Vorteile des Mods findet ihr einen Punkt tiefer.


Vorab:
Mein Ender 3 hatte immer Probleme in der Z-Achse, welche auf eine krumme Spindel zurückzuführen waren. Daher habe ich beschlossen den Ender auch in Z auf Riemen umzubauen.

Dieser Umbau löst auch dem Problem einer hängenden x-Achse, auf der rechten Seite. Durch die beiden Riemen, laufen die beiden Seiten nicht nur synchron, sondern lassen sich auch auf den Millimeter genau einstellen.
Sollte man dieses Problem mit der X-Achse haben, ist dies also eine geeignete Lösung.	
Hier findet ihr die Modelle des Hotends und des Nema:
grabcad.com/library/cr10-stock-hot-end-1
grabcad.com/library/nema-17-stepper-motor-22


Voron Parts:
Die Übersetzung der Z Achse ist vom Voron übernommen. Mehr Infos zum Drucker erhaltet ihr hier: 
http://vorondesign.com/
https://github.com/VoronDesign

Die Datein der Übersetzung sind nicht meine Arbeit und daher auch nicht hier hochgeladen. Ich habe lediglich ein Teil angepasst um die Übersetzung an dem Ender anzubringen. Welche Teile ihr benötigt und wo ihr diese erhaltet, findet ihr unter "Printed Parts".


BOM (die Teile vom Ender werden nicht aufgeführt, Schrauben Muttern etc. werden wiederverwendet)
16x M5*8mm 
6x M5*40mm
4x M5*30mm (Für die oebre Strebe,  die originalen werden auch passen, haben dann aber nicht viel Restgewinde)
16x M5 T-Slot Nuts
10x M3*16
10x M3 Nuts
4x 608zz bearing
4x F623ZZ 3*10*4mm Bearing
3x GT2 20 8mm Pulley (bei einem muss der Flansch entfernt werden: https://www.youtube.com/watch?v=RKpxDKYOJYs)
2 Meter GT2 6mm Belt
1x GT2 Belt Loop (6mm wide) - 188mm http://s.click.aliexpress.com/e/ripvAfVQ (Affiliate Link from the Voron Guys)
0.4 Meter Welle (es reicht ein günstiger 8mm Aluminiumstab aus dem Baumarkt, die Welle muss später gekürzt werden) (ihr könnt ZUR NOT auch die Z Spindel verwenden)


Printed Parts
Die Ausrichtung der Teile ist willkürlich. Bitte findet für euch selbst die optimale Ausrichtung heraus.
V2 verwendet die meisten Teile aus V1, ihr findet diese in der V2.zip.

Alle Teile können ohne Support gedruckt werden.
Alle Teile müssen nur einmal gedruckt werden, außer 4x 'Clamp'(für V3 2xTensionerClampV3 und 2x TensionerBlockV3)  und ' 5x 'Spacer2'(2x für Links, 3x für Rechts)
	Wall line count: min. 5
	Infill: 50% oder mehr
	0.2mm Layerhight

Alle Originalteile sind auf der Voron GitHub-Website zu finden (Ich wiederhole, diese sind nicht meine Arbeit!):
https://github.com/VoronDesign/Voron-2/tree/Voron2.2/STLs/VORON2.2/Z_Drive/HD_Z_Drive

Für die Mod finden sich alle Teile hier: https://github.com/kevinakasam/BeltDrivenEnder3.git


Anleitung:
Es werden alle Teile wie auf den Fotos montiert.  Spacer2 sind die hinteren Abstandshalter der V-Slotwheels für die Platte an der die Riemen befestigt werden.
Die Belts benötigen eine Länge von ca. 88cm und werden bündig festgeklemmt.
Die steps/mm  werden für Z auf 400.00 gestellt werden. Sollte euer Ender 3 kein Eprom haben, schreibt 'M92 Z400.00;' in euren Start-Gcode.

Für den Zusammenbau der Übersetzung findet ihr hier eine Anleitung:
https://github.com/VoronDesign/Voron-2/tree/Voron2.2/manuals

Fertig!:) Viel Erfolg und happy printing!


***Englisch Version***

Attention!
I'm not an expert and 3D printing is my hobby. So please be careful when you rebuild your printer and don't just go ahead. For my printer the parts fit perfectly.
Everybody bears the risks of a modification himself.
All parts can be modified as you like. 


Upadte V2:
Compared to version V1 you can reuse all parts of the printer this time. So the conversion is easier, more stable and cheaper. You could even print the pulleys and save money, but I would not recommend it.

The translation is the biggest innovation. It not only increases your resolution in Z, but also the X axis does not drop to 0 as soon as it is out of power (either after printing or if your power fails). All other advantages of the mod you can find one point lower.


First things first:
My Ender 3 always had problems in the Z-axis, which were caused by a bent spindle. Therefore I decided to convert the Ender to belts in Z as well.

This conversion also solves the problem of a hanging x-axis on the right side. Because of the two belts, the two sides not only run synchronously, but can also be adjusted very precisely.

So if you have all these problems with the x-axis, this is a good solution.
	
Here you can find the models of the hotend and nema: 
grabcad.com/library/cr10-stock-hot-end-1
grabcad.com/library/nema-17-stepper-motor-22


Voron Parts:
The transmission of the Z-axis is taken from the Voron. More information about the printer can be found here: 
http://vorondesign.com/
https://github.com/VoronDesign

The files of the translation are not my work and therefore not uploaded here. I have only modified a part to attach the translation to the Ender. Which parts you need and where you can get them, you can find under "Printed Parts".

BOM (the parts of the ender are not listed, nuts and bolts etc. are reused)
16x M5*8mm 
6x M5*40mm
4x M5*30mm (for the top of the frame; the stock will work as well but only have a few millimeter to grip)
16x M5 T-Slot Nuts
10x M3*16
10x M3 Nuts
4x 608zz bearing
4x F623ZZ 3*10*4mm Bearing
3x GT2 20 8mm Pulley (Left,right, Voron pulley. The Motor Pulley is still the 16T 5mm one!!!) (for one puley you have to remove the flange): https://www.youtube.com/watch?v=RKpxDKYOJYs)
2 Meter GT2 6mm Belt
1x GT2 Belt Loop (6mm wide) - 188mm http://s.click.aliexpress.com/e/ripvAfVQ (Affiliate Link from the Voron Guys)
0.4 Meter rod (a cheap 8mm aluminum rod from the hardware store is enough) (you can also use the Z leadscrewbut thats not good for leadscreaw)


Printed Parts
The orientation of the parts is random. Please find out the optimal alignment by yourself.
V2 uses most parts from V1, you can find them in the V2.zip.

All parts can be printed without support.
All parts must be printed only once, except 4x 'Clamp' (for V3 2xTensionerClampV3 and 2x TensionerBlockV3)  and 5x 'Spacer2'(2x for left, 3x for right).
	Wall line count: min. 5
	Infill: 50% or more
	0.2mm layer height

All original parts can be found one the Voron GitHub site (I repeat these parts are not my work!):
https://github.com/VoronDesign/Voron-2/tree/Voron2.2/STLs/VORON2.2/Z_Drive/HD_Z_Drive

All parts for the mod can be found here: https://github.com/kevinakasam/BeltDrivenEnder3.git


Instructions:
All parts are assembled as shown in the photos.  Spacer2 are the rear spacers of the V-Slotwheels for the plate to which the belts are attached.

The Belts need a length of approximately 88cm and are clamped flush.
The steps/mm will be set to 400.00 for Z. If your Ender 3 has no eprom, write 'M92 Z400.00;' in your start code.

For the assembly of the translation you can find instructions here:
https://github.com/VoronDesign/Voron-2/tree/Voron2.2/manuals


Ready!:) Good luck and happy printing!

