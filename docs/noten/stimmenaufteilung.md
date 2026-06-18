[Home](/) > [Notenverwaltung](/noten) >

# Stimmenaufteilung

Du hast ein Sammel-PDF – eine Partitur mit allen Einzelstimmen, oder einen Stapel eingescannter Stimmen – und möchtest daraus einzelne, sauber benannte Stimmen-PDFs. Auch mehrere PDFs, die zum selben Stück gehören (z.B. Partitur und Stimmen in getrennten Dateien), kannst du zusammen verarbeiten. Die **Stimmenaufteilung** nimmt dir das ab: Sie liest jede Seite KI-gestützt, erkennt Instrument, Seitenzahl und Mehrfach-Kopien, fügt zusammengehörende Seiten zu einer Stimme zusammen und benennt die Dateien nach deinem Nummernschema. Du prüfst das Resultat und lädst es als ZIP herunter.

!!! warning "Noch in Erprobung"
    Die Stimmenaufteilung steckt noch in der Testphase. Wenn etwas nicht klappt oder eine Stimme falsch aufgeteilt wird, melde es uns bitte an [info@bin-dabei.ch](mailto:info@bin-dabei.ch) – mit Angabe deines **Vereins** und des **Stücktitels**, damit wir es nachvollziehen können.

!!! warning "Kosten"
    Während der Testphase ist die Stimmenaufteilung für deinen Verein **kostenlos**. Im Hintergrund entstehen aber externe Kosten (der KI-Lesedienst). Für den regulären Betrieb behalten wir uns deshalb eine **Kostenbeteiligung** vor – voraussichtlich als **Pauschale**; die Details sind noch offen.

!!! note "Voraussetzung"
    Die Stimmenaufteilung muss für deinen Verein freigeschaltet sein (durch die bin-dabei-Administration). Danach findest du sie im Menü unter **«Noten» → «Stimmenaufteilung»**. Zugriff haben nur Bibliothekar:innen und Vereinsadmins.

## 1. PDF(s) hochladen

Ziehe ein oder mehrere PDFs in das Upload-Feld oder wähle sie aus. Alle PDFs, die du in einem Schritt hochlädst, gehören zu **einem Stück** – typisch sind das eine Partitur-Datei und eine Datei mit allen Stimmen, oder auch alles in einem einzigen PDF.

Du musst Titel und Komponist **nicht** vorab eintippen: Sie werden beim Lesen vorgeschlagen und du bestätigst oder korrigierst sie nachher.

## 2. Verarbeitung

Nach dem Hochladen siehst du einen Fortschrittsbalken. Die Verarbeitung läuft im Hintergrund und dauert je nach Umfang ein paar Minuten – jede Seite wird einzeln gelesen. Du kannst die Seite offen lassen; sie aktualisiert sich von selbst und zeigt das Ergebnis, sobald es fertig ist.

!!! tip
    Ein grosses PDF (z.B. 100 Seiten) braucht ein paar Minuten. Das ist normal: Der Lesedienst ist auf rund eine Seite pro Sekunde begrenzt. Du kannst in der Zwischenzeit anderswo weiterarbeiten und später auf die Aufteilung zurückkommen.

## 3. Ergebnis prüfen und korrigieren

Oben bestätigst oder korrigierst du **«Stücktitel»** und **«Komponist/Arrangeur»**. Darunter listet eine Tabelle alle erkannten Stimmen:

| Spalte | Bedeutung |
| --- | --- |
| **Übernehmen** | Häkchen entfernen, um eine Stimme **nicht** ins ZIP aufzunehmen. |
| **Sortiercode** | Das Nummern-Präfix aus deinem Schema (z.B. `04b`). Bestimmt Dateiname und Sortierreihenfolge – frei editierbar, leer lassen heisst «kein Präfix». |
| **Instrument** | Die Stimmenbezeichnung. Editierbar; sie wird in den Dateinamen übernommen. |
| **Seiten** | Welche Seiten des Quell-PDFs zu dieser Stimme gehören. |
| **Kopien** | Wie viele identische Exemplare im PDF gefunden wurden (es wird nur eines extrahiert). |
| **Hinweis** | Automatische Anmerkungen, z.B. «4 copies → kept 1» oder «1 page(s) rotated 180°». |
| **Vorschau** | Öffnet die fertige Stimme als PDF in einem neuen Tab. |

Was die Aufteilung dabei automatisch erledigt:

- **Mehrfach-Kopien** derselben Stimme werden zu einer zusammengefasst (in der Spalte «Kopien» siehst du, wie viele es waren).
- Die **Partitur** wird als eigene Stimme «Partitur» mitgeliefert.
- **Kopfüber gedruckte Folgeseiten** von gefalteten Stimmen (Faltkarten/Marschbüchlein) werden automatisch aufrecht gedreht.
- Verlage drucken oft in GROSSBUCHSTABEN – Titel und Stimmennamen werden in normale Schreibweise gebracht.

!!! tip "Zwei falsch getrennte Seiten zusammenführen"
    Liest die KI eine mehrseitige Stimme versehentlich als zwei (z.B. «E Horn 2» und «Eb Horn 2»), gib einfach beiden dasselbe Instrument. Sobald zwei aufeinanderfolgende Zeilen identisch heissen, erscheint ein Häkchen **«↑ mit voriger zusammenführen»** (standardmässig angekreuzt). Beim Herunterladen werden die beiden Teile dann zu **einer** PDF verbunden.

### Plausibilitäts-Hinweise

Über der Tabelle können zwei Hinweise erscheinen:

- **«Einige Seiten konnten nicht gelesen werden»** – einzelne Seiten sind beim Lesen ausgefallen (meist vorübergehende Überlastung des Dienstes). Lass die Aufteilung in diesem Fall nochmals laufen.
- **«Einige Seiten sind in keiner Stimme enthalten»** – diese Seiten des Quell-PDFs sind in keiner Stimme gelandet. Bei Titel- oder Leerseiten ist das normal; sonst lohnt sich ein Blick, ob eine Seite verloren ging.

## 4. Herunterladen

Zwei Tasten, die **beide zuerst deine Korrekturen speichern**:

- **«Überprüfung speichern»** – speichert die Bearbeitung, ohne herunterzuladen (du kannst später weitermachen).
- **«Speichern & ZIP herunterladen»** – speichert und gibt das ZIP mit allen übernommenen Stimmen aus.

Die Dateien im ZIP heissen nach dem Schema `Sortiercode_Komponist_Werk_Instrument`, sodass sie in deinem Notenarchiv gleich richtig einsortiert sind.

!!! note "Was die Aufteilung (noch) nicht kann"
    Komplett um 90° quer eingescannte Stücke werden nicht automatisch gedreht. Und so gut die Erkennung ist – ein kurzer Blick in die Vorschau lohnt sich, bevor du die Stimmen ins Archiv übernimmst.
