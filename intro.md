# HTML Einführung

## Wir werden behandeln:

- Was ist HTML?
- Neue Wörter
- Allgemeine HTML-Auszeichnung
- Konventionen beim Schreiben von Markup
- Mehr Auszeichnungsmöglichkeiten (HTML5)
- Hierarchien innerhalb von HTML


# Was ist HTML?

## Hyper Text Markup Language

Anmerkungen:

was bedeutet das genau?

- Im Grunde ist es nur eine Möglichkeit für uns, die Daten, die wir über das Internet übertragen, zu *annotieren*


# Fun Facts

- 1989 erfand Tim Berners-Lee HTML am CERN
- CERN ist ein europäisches Labor
- HTML wurde erfunden, um Informationen zwischen Forschern am CERN auszutauschen


# Neue Wörter

### Markup
- die Symbole oder Codes die wir verwenden, um den Inhalt in der HTML-Datei zu beschreiben. Manchmal werden sie auch Tags bezeichnet.

<p>Beispiel</p>

###  Präsentation
- Markup, das sich rein auf die Darstellung des Inhalts konzentriert

### Semantisch
- Markup, das sich auf die Bedeutung des Inhalts konzentriert.

<h1> hier kommt text rein </h1>



# Gemeinsame HTML-Auszeichnung

Bevor wir uns Markup ansehen schauen wir uns einige typische Darstellungsanforderungen an, die in einem Dokument auftreten können


**Kopfzeile** (der Titel eines Dokuments)

**Absatz** Fließtext

**Starker/Fetter Text** Text der in einer Form wichtig ist

**Hervorgehobener / kursiver Text** Text der in einer hervorgehoben wurde

**Listen** Zeilenpositionen, die in der Reihenfolge ihres Auftretens erscheinen können

**Bilder**


Kopfzeile:
<h1></h1> ... <h6></h6>

Absatz:
<p></p>

Starker/ fettgedruckter Text:
<strong></strong>

Hervorgehobener / kursiver Text:
<em></em>

Listen/sortiert:

<ul>
	<li>test</li>
	<li>banane</li>
	<li>apfel</li>
</ul>
Verwendet man wenn die Reihenfolge keine Rolle spielt
- test
- banane
- apfel

ul steht für unordered list

Liste sortiert:

<ol>
	<li>Herr der Ringe</li>
	<li>Sophies Welt</li>
</ol>

Verwendet man wenn die Reihenfolge eine Rolle spielt

1. Herr der Ringe
2. Sophies Welt


ol stands for ordered list


**Bilder**

<img />

Img= Image (Englisch für Bild)


**Horizontale Linie**

<hr />


**Teiler**

<div></div>


**Break** in der nächsten Zeile anfangen

<br />
