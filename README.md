# HomeMatic_CSS
CSS Datei für die HomeMatic CCU-WebUI in Verbindung mit dem FireFox Addon Stylus.

## Übersicht
Ein
Die modernes Design:

![WebUI Neu](/images/WebUI_Neues_Design_1_sm.png)

für die etwas in die Jahre gekommene, Oberfläche der HomeMatic WebUI:

![WebUI Original](/images/WebUI_Original_sm.png)

### Voraussetzungen
Die CSS-Datei benötigt  _keine_ Installation auf der CCU-WebUI.
Stattdessen wird diese über FireFox-Addon Stylus eingebunden.
[Stylus](https://addons.mozilla.org/en-US/firefox/addon/styl-us/)
Dieses "überschreibt" die vorhandenen Style-Sheets, die von der CCU-WebUI geladen werden, direkt im Browser.

### Installation
Nach der Installation von Stylus wird die CCS-Datei in Stylus importiert:

![WebUI Original](/images/HomeMatic_CSS__Stylus_bearbeitCSS-Variablen.png)

*hier kommen noch Bilder*

danach ist eine Anpassung der IP-Adressen, auf die IP bzw. URL der CCU, in den einzelnen Code-Bereichen nötig:

![WebUI Original](/images/HomeMatic_CSS__Gilt_fuer.png).

Hierzu noch ein schönes Video von [Verdrahtet](https://www.verdrahtet.info) auf [YouTube](https://www.youtube.com/watch?v=nxAQbJ4O01g)

### Anpassungen
Nach dem Import sieht man in Stylus mehrere Code-Bereiche:

![WebUI Original](/images/HomeMatic_CSS__CSS-Varia

 1. Changelog, CSS-Variablen zum einfachen npassen en Druck
 2. Allgemeine Stile
 3. die restlichen Stile
 4. das Hintergrundbild
 
 ## Diskussion / Vorschläge
Bitte auch die Diskussion dazu im [HomeMatic-Forum](https://homematic-forum.de/forum/viewtopic.php?f=41&t=46033) beachten.

 ## Author
 Thorsten Willert
 
 [Homepage](http://www.thorsten-willert.de/)

 ## Lizenz
 Das ganze steht unter der [Apache 2.0](https://github.com/THWillert/HomeMatic_CSS/blob/master/LICENSE)Lizenz.
.
<!--stackedit_data:
eyJoaXN0b3J5IjpbMTU1Nzc4MzQxMiwtMzA5OTIyODU0XX0=
-->