# Normbrief (DIN 5008) mit Markdown und MultiMarkdown

_© 2014 Wolfgang Reszel für [Mac & i](http://www.mac-and-i.de)_

Mit diesem Stylesheet (CSS) kann man mittels [Markdown](http://www.mac-and-i.de/markdown) private Briefe oder auch Geschäftsbriefe verfassen. Dabei wird das Anschriftsfenster von Briefumschlägen unterstützt. Der Briefkopf mit Bankdaten und Kontaktdaten erscheint in einer zweiten Spalte ([siehe Beispiel](http://htmlpreview.github.io/?https://raw.github.com/mac-and-i/Normbrief-mit-Markdown/master/Muster-Normbrief.html)).

* [Muster-Normbrief als Markdown-Datei](https://raw.github.com/mac-and-i/Normbrief-mit-Markdown/master/Muster-Normbrief.md)
* [Beispiel-Export aus Marked 2](http://htmlpreview.github.io/?https://raw.github.com/mac-and-i/Normbrief-mit-Markdown/master/Muster-Normbrief.html)
* [Einführung in Markdown](http://www.mac-and-i.de/markdown)  
	Mit Syntax-Übersicht zum Ausrdrucken sowie umfangreiche Linkliste zu Apps für iOS und OS X

## Installation

Die CSS-Datei Bei den meisten Programmen muss die CSS-Datei lediglich in einen Ordner kopiert werden.

* **Marked** (Version 1 und 2)
	CSS-Datei nach `~/Library/Application Support/Marked/Custom CSS/` kopieren und über die Einstellungen unter Style manuell zu den Custom CSS hinzufügen.
* **Mou**
	`~/Library/Application Support/Mou/CSS`
* **LightPaper**
	`~/.lightpaper/Themes`
* **Ulysses**
	Die CSS-Datei über die Schaltfläche _Stile hinzufügen ..._ im Stile-Bereich der Einstellungen importieren.
	
  
## Struktur des Dokuments:

Damit der Normbrief funktioniert, muss das Dokument folgende Struktur aufweisen. (Siehe auch Muster-Normbrief.md)

1. Briefkopf als Blockqote `>` mit Überschrift `#`
2. Trennlinie `----`
3. Absender `##`/Anschrift als Blockquote `>` (für Fensterumschlag)
4. Trennlinie `----`
5. Datum als Blockquote `>`
6. Fließtext
7. Grußformal als Blockquote `>`
8. Weiterer Text

## Lizenz

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
