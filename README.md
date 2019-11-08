# HomeMatic_CSS
[CSS](https://de.wikipedia.org/wiki/Cascading_Style_Sheets)-Datei für die HomeMatic CCU in Verbindung mit dem FireFox Addon Stylus.

## Übersicht
Ein modernes Design:

![WebUI Neu](/images/WebUI_Neues_Design_1_sm.png)

für die etwas in die Jahre gekommene Oberfläche der HomeMatic WebUI:

![WebUI Original](/images/WebUI_Original_sm.png)

### Voraussetzungen
Die CSS-Datei benötigt  _keine_ Installation auf der CCU.
Stattdessen wird diese über FireFox-Addon [Stylus](https://addons.mozilla.org/en-US/firefox/addon/styl-us/) eingebunden.
Dieses "überschreibt" die vorhandenen Style-Sheets, die von der CCU geladen werden, direkt im Browser.

### Installation
Nach der Installation von Stylus wird die CCS-Datei in Stylus importiert:

![Bearbeiten](/images/HomeMatic_CSS__Stylus_bearbeiten.png)

und den Inhalt der CSS-Datei einfügen:

![Einfuegen](/images/HomeMatic_CSS__Stylus_einfuegen.png)

danach ist eine Anpassung der IP-Adressen, auf die IP bzw. URL der CCU, in den einzelnen Code-Bereichen nötig:

![IP](/images/HomeMatic_CSS__Gilt_fuer.png).

Hierzu noch ein schönes Video von [Verdrahtet](https://www.verdrahtet.info) auf [YouTube](https://www.youtube.com/watch?v=nxAQbJ4O01g)

### Anpassungen
Nach dem Import sieht man in Stylus mehrere Code-Bereiche:

 1. Changelog, CSS-Variablen zum einfachen Anpassen und des Drucklayouts ![Variablen](/images/HomeMatic_CSS__CSS-Variablen.png)![CSS_Print](/images/HomeMatic_CSS__Print.png)
 2.  Allgemeine Stile
 3. die restlichen Stile
 4. das Hintergrundbild
 
 ## Diskussion / Vorschläge
Bitte auch die Diskussion dazu im [HomeMatic-Forum](https://homematic-forum.de/forum/viewtopic.php?f=41&t=46033) beachten.

## ToDo

Die Reihenfolge entspricht keiner Priorität.

 - [ ] Anleitung vervollständigen
 - [ ] CSS-Variablen vervollständigen
 - [ ] Status / Geräte-Controls überarbeiten
 - [ ] Status / Gewerke
 - [ ] Status / Räume
 - [ ] Status / Favoriten
 - [ ] Status / Systemprotokoll - Header
 - [ ] Direkte Verknüpfungen
 - [ ] Einstellungen - Unterpunkte Header
 - [ ] Popup - Allgemeine Geräteeinstellungen
 - [ ] Popups - Kanalauswahl / Geräteauswahl usw.
 - [ ] Geräteeinstellungen / Formular-Inputs verbergen
 - [ ] auf ein Addon "umbauen"
 - [ ] zweites Design: "Hell"

Optional:
 - [ ] als Addon?
 - [ ] wenn es ein Addon wird: Die Geräte-Bilder durch Fotos ersetzen?
 - [ ] Auf CUx erweitern?

 ## Author
 Thorsten Willert

 [Homepage](http://www.thorsten-willert.de/)

 ## Lizenz
 Das ganze steht unter der [Apache 2.0](https://github.com/THWillert/HomeMatic_CSS/blob/master/LICENSE) Lizenz.
.
