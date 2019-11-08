# HomeMatic_CSS
[CSS](https://de.wikipedia.org/wiki/Cascading_Style_Sheets)-Datei für die HomeMatic CCU-WebUI in Verbindung mit dem FireFox Addon Stylus.

## Übersicht
Ein modernes Design:

![WebUI Neu](/images/WebUI_Neues_Design_1_sm.png)

für die etwas in die Jahre gekommene Oberfläche der HomeMatic WebUI:

![WebUI Original](/images/WebUI_Original_sm.png)

### Voraussetzungen
Die CSS-Datei benötigt  _keine_ Installation auf der CCU.
Stattdessen wird diese über FireFox-Addon Stylus eingebunden.
[Stylus](https://addons.mozilla.org/en-US/firefox/addon/styl-us/)
Dieses "überschreibt" die vorhandenen Style-Sheets, die von der CCU geladen werden, direkt im Browser.

### Installation
Nach der Installation von Stylus wird die CCS-Datei in Stylus importiert:

![WebUI Original](/images/HomeMatic_CSS__Stylus_bearbeiten.png)

*hier kommen noch Bilder*

danach ist noch eine Anpassung der IP-Adressen, auf die IP bzw. URL der CCU, in den einzelnen Code-Bereichen nötig:

![WebUI Original](/images/HomeMatic_CSS__Gilt_fuer.png)

Hierzu noch ein schönes Video von [Verdrahtet](https://www.verdrahtet.info) auf [YouTube](https://www.youtube.com/watch?v=nxAQbJ4O01g)

### Anpassungen
Nach dem Import sieht man in Stylus mehrere Code-Bereiche:

 1. Changelog, CSS-Variablen zum einfachen Anpassen und den Druck ![WebUI Original](/images/HomeMatic_CSS__CSS-Variablen.png)![WebUI Original](/images/HomeMatic_CSS__Print.png)
 3. Allgemeine Stile
 4. die restlichen Stile
 5. das Hintergrundbild
 
 ## Diskussion / Vorschläge
Bitte auch die Diskussion dazu im [HomeMatic-Forum](https://homematic-forum.de/forum/viewtopic.php?f=41&t=46033) beachten.

 ## Author
 Thorsten Willert

 [Homepage](http://www.thorsten-willert.de/)

 ## Lizenz
 Das ganze steht unter der [Apache 2.0](https://github.com/THWillert/HomeMatic_CSS/blob/master/LICENSE) Lizenz.
.
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTg2MTk2NTU1NF19
-->