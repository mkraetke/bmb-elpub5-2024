# bmb-elpub5-2024

Modul Elektronisches Publizieren V im Studiengang Buch- und Medienproduktion an der HTWK Leipzig

Inhalt          | Beschreibung
----------------|-------------
Moduldauer      | 8 Wochen
Regelsemester   | Wintersemester 7. Semester
Umfang          | 4 SWS
Typ             | Wahlmodul
ECTS            | 5
Sprache         | Deutsch
Voraussetzungen | Grundlegendes Kenntnisse in den Technologien XML, XSLT, HTML und CSS
Arbeitslast     | 150 Stunden, davon 64 SWS (entspricht 4 SWS), 85 Stunden angeleitetes Selbststudium und Prüfungsvorbereitung, 1 Stunde Prüfung (Präsentation)

## Remote

Die Veranstaltung kann auch Remote angeboten werden.

Zur Kommunikation und zum Teilen von Inhalten für alle steht ein [Chanty](https://elpub5-2024.chanty.com)-Workspace bereit. (Der Workspace wird nach der Prüfung wieder entfernt).

Nachfragen können natürlich auch via E-Mail gestellt werden.

## Veranstaltungen

| Nr. | Datum  | Zeit        | Beschreibung     |
|-----|--------|-------------|------------------|
| 1.  | 21.10. |  9:30-12:45 | Einführung, BITS |
| 2.  | 28.10. |  9:30-12:45 | XSLT             |
| 3.  | 04.11. |  9:30-12:45 | XSLT             |
| 4.  | 11.11. |  9:30-12:45 | Schematron       |
| 5.  | 18.11. |  9:30-12:45 | PrintCSS         |
| 6.  | 25.11. |  9:30-12:45 | PrintCSS         |
| 7.  | 02.12. |  9:30-12:45 | Konsultation     |
| 8.  | 16.12. |  9:30-12:45 | Prüfung          |

## Aufgaben

1. Konvertierung von [XHTML](https://www.w3.org/TR/xhtml1/) aus [JATS](https://jats.nlm.nih.gov/publishing/tag-library/1.1/index.html)
2. Prüfen der JATS-Daten mit [ISO Schematron](http://schematron.com/)
3. Erstellen einer Druckvorlage mit PrintCSS

### Schematron

1. kwd-group muss mindestens drei kwd-Elemente enthalten
2. die Elemente volume und issue dürfen ausschließlich Zahlen enthalten.
3. pub-date day, month und year entsprechend nur aus Zahlen bestehen bzw. die richtige Anzahl von Stellen.
4. Letzte Seite muss größer als die erste Seite sein. &lt; und &gt;
5. Copyright Jahr muss größer als 1990 sein.
6. Der Dateiname in related-article muss immer mit der Endung ".pdf" enden.
7. Journal-Code muss fünfstellig sein.

## Abgabe

* XSLT, Schematron, CSS
* als Zip: `elpub5-2024_nachname_vorname.zip`

## Prüfungsablauf

* Dauer: 15 Minuten plus 5 Minuten Vorbereitung plus 5 Minuten Auswertung (gesamt: 25 Minuten)
* fehlerfreie Konvertierung mit oXygen und Prince zeigen
* Präsentation der Konvertierungsergebnisse
* Praktische Fragen zu den Themengebieten XSLT, Schematron, PrintCSS

## Editoren

* oXygen XML
* Notepad++ (mit XML-Plugin)

## Literatur

### JATS

#### Dokumentation

[Web-Dokumentation von JATS](https://jats.nlm.nih.gov/publishing/tag-library/1.3/element/journal-id.html)

#### Tutorials

[Introduction to JATS von Debbie Lapeyre](https://www.xml.com/articles/2018/10/12/introduction-jats/)

### XSLT

#### Spec

https://www.w3.org/TR/xslt20/

#### Bücher

* Michael Kay: XSLT 2.0 and XPath 2.0 Programmer's Reference
* Doug Tidwell: XSLT

#### Tutorials

* [Norman Walsh: Introduction to XSLT 2.0](https://nwalsh.com/docs/tutorials/extreme2006/plain.html
)
* [W3Schools: XSLT Introduction](https://www.w3schools.com/xml/xsl_intro.asp)

### Schematron

#### Spec

https://standards.iso.org/ittf/PubliclyAvailableStandards/c055982_ISO_IEC_19757-3_2016.zip

#### Bücher

Marko Hedler, Nico Kutscherauer: Schematron: effiziente XML Business Rules für XML-Dokumente

#### Tutorials

* [data2type: Schematron](https://www.data2type.de/xml-xslt-xslfo/schematron/)
* [David J. Birnbaum : Schematron Introduction](http://dh.obdurodon.org/schematron-intro.xhtml)
* [xml.com Introduction to Schematron](https://www.xml.com/pub/a/2003/11/12/schematron.html)

### PrintCSS

#### Spec

* [CSS Paged Media Module Level 3](https://www.w3.org/TR/css-page-3/)
* [CSS Generated Content for Paged Media Module](https://www.w3.org/TR/css-gcpm-3/)
* [CSS Fragmentation Module Level 3](https://www.w3.org/TR/css-break-3/)

#### Tutorials

* [Andreas Jung: print css rocks](https://print-css.rocks/)
* [Rachel Andrew: A Guide To The State Of Print Stylesheets In 2018](https://www.smashingmagazine.com/2018/05/print-stylesheets-in-2018/)
* [Rachel Andrew: Designing For Print With CSS](https://www.smashingmagazine.com/2015/01/designing-for-print-with-css/)
* [Antenna House: Introduction to CSS for Paged Media](https://www.antennahouse.com/hubfs/PDFS/CSS%20for%20Paged%20Media/CSS-Print-en-2019-02-15.pdf)

