[Installation](#installation) | [Struktur des Dokuments](#struktur-des-dokuments) | [Lizenz](#lizenz)

# Normbrief (DIN 5008) mit Markdown und MultiMarkdown #

_v1.0.3  —  © 2014 Wolfgang Reszel für [Mac & i](http://www.mac-and-i.de)_

Mit diesem Stylesheet (CSS) kann man mittels [Markdown](http://www.mac-and-i.de/markdown) private Briefe oder auch Geschäftsbriefe verfassen. Dabei wird das Anschriftsfenster von Briefumschlägen berücksichtigt. Der Briefkopf mit Bank- und Kontaktdaten erscheint in einer zweiten Spalte ([siehe Beispiel](http://htmlpreview.github.io/?https://raw.github.com/mac-and-i/Normbrief-mit-Markdown/master/Muster-Normbrief.html)).

* [**Download**](https://github.com/mac-and-i/Normbrief-mit-Markdown/archive/v1.0.3.zip)
* [Beispiel-Export aus Marked 2](http://htmlpreview.github.io/?https://raw.github.com/mac-and-i/Normbrief-mit-Markdown/master/Muster-Normbrief.html)
* [Einführung in Markdown](http://www.mac-and-i.de/markdown)  
	Mit Syntax-Übersicht zum Ausrdrucken sowie umfangreiche Linkliste zu Apps für iOS und OS X
* [Einfacheres Brief-Stylesheet für Marked 2 auf www.maennig.de](http://maennig.de/briefe-markdown) 

## Installation

Die CSS-Datei funktioniert in vielen Programmen. Bei den meisten muss diese lediglich in einen Ordner kopiert werden.

### Mac-Programme ###

* **Marked** (Version 1 und 2)  
	CSS-Datei nach `~/Library/Application Support/Marked/Custom CSS/` kopieren und über die Einstellungen unter Style manuell zu den Custom CSS hinzufügen. Damit das Stylsheet die gleichen Ränder wie Safari verwendet, muss man alle __Druckränder in den Einstellungen auf 17 setzen__.
* **Mou**  
	  `~/Library/Application Support/Mou/CSS`
* **LightPaper**  
	  `~/.lightpaper/Themes`
* **Ulysses**  
	Die CSS-Datei über die Schaltfläche _Stile hinzufügen ..._ im Stile-Bereich der Einstellungen importieren. Um so ein Dokument zu drucken, muss es an Safari gesendet werden, da Ulysses zu große Standard-Druckränder verwendet.
* **Erato**  
	In den Einstellungen Preview theme auf Custom stellen und den Edit-Button klicken. Dann den Inhalt der Normbrief-CSS-Datei in die custom.css einfügen und speichern.
* **MultiMarkdown Composer**  
	In den Einstellungen unter Appearance den Button "Open Styles Folder" anklicken und dann die STYLE-Datei (nicht CSS) in den Ordner kopieren. Nach einem Neustart des Programms kann man das Style Sheet unter Appearance auswählen.
* **Byword** (siehe [unten](#programme-ohne-stylesheet-auswahl))
* **Coda 2** (siehe [unten](#programme-ohne-stylesheet-auswahl))
* **nvALT** (siehe [unten](#programme-ohne-stylesheet-auswahl))

#### Programme ohne Stylesheet-Auswahl ####

Einigen Programmen wie Byword (Mac) oder DownMarker (Windows) kann man das Stylesheet unterjubeln, indem man folgende Zeile an das Ende des Markdown-Dokuments anfügt.

`<style>@import url('file:///PFAD/ZU/Normbrief DIN 5008.css');</style>`
_(An den Pfad kommt man am schnellsten, indem man die CSS-Datei mit einem Browser öffnet.)_

Funktionieret nicht mit: **iA Writer**, **Marko**, **Markdown Life**

### iOS-Apps ###

* **Editorial**
	[Workflow mit Druckfunktion](http://editorial-app.appspot.com/workflows/search?q=Din+5008)
* **Nocs**  
	CSS-Datei in den Ordner mit den Markdown-Dokumenten legen und in `styles.css` umbenennen. Alternativ in den Einstellungen den Dateinamen bei _Folder Custom_ auf `Normbrief DIN 5008.css` setzen.
* **Textastic**  (siehe [unten](#apps-ohne-stylesheet-auswahl))

#### Apps ohne Stylesheet-Auswahl ####

Bei Apps mit Datei-Verwaltung wie Textastic (iOS) muss man die CSS-Datei in die App importieren und dann mit folgender Ergänzung am Ende des Markdown-Dokuments ansprechen.

`<style>@import url('/Normbrief DIN 5008.css');</style>`

Funktioniert nicht mit: **Byword**, **iA Writer**


## Struktur des Dokuments ##

Damit ein Markdown-Dokument korrekt als Normbrief dargestellt wird, muss es folgende Struktur aufweisen. (Siehe auch [Muster-Normbrief.md](https://raw.github.com/mac-and-i/Normbrief-mit-Markdown/master/Muster-Normbrief.md))

1. Briefkopf als Blockqote `>` mit Überschrift 1 `> #`
2. Trennlinie `----`
3. Anschrift als Blockquote `>` mit Absender als Überschrift 2 `> ##` (für Fensterumschlag)
4. Trennlinie `----`
5. Datum als Blockquote `>`
6. Betreff als Überschrift 3 `###`
7. Fließtext
8. Grußformel als Blockquote `>`
9. Weiterer Text

Je nach Converter muss gegebenenfalls jede Zeile in den Blockquotes mit zwei Leerzeichen `  ` enden.

## Lizenz ##

The MIT License (MIT)

Copyright (c) 2014 Wolfgang Reszel for Mac & i (Heise Zeitschriften Verlag)

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
