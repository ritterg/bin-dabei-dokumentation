[Home](/) > [Notenverwaltung](/noten) >

# Stimmenaufteilung

Du hast ein Sammel-PDF – eine Partitur mit allen Einzelstimmen, oder einen Stapel eingescannter Stimmen – und möchtest daraus einzelne, sauber benannte Stimmen-PDFs. Auch mehrere PDFs, die zum selben Stück gehören (z.B. Partitur und Stimmen in getrennten Dateien), kannst du zusammen verarbeiten. Die **Stimmenaufteilung** nimmt dir das ab: Sie liest jede Seite KI-gestützt, erkennt Instrument, Seitenzahl und Mehrfach-Kopien, fügt zusammengehörende Seiten zu einer Stimme zusammen und benennt die Dateien nach deinem Nummernschema. Du prüfst das Resultat und lädst es als ZIP herunter.

!!! warning "Noch in Erprobung"
    Die Stimmenaufteilung steckt noch in der Testphase. Wenn etwas nicht klappt oder eine Stimme falsch aufgeteilt wird, melde es uns bitte an [info@bin-dabei.ch](mailto:info@bin-dabei.ch) – mit Angabe deines **Vereins** und des **Stücktitels**, damit wir es nachvollziehen können.

!!! warning "Kosten"
    Während der Testphase ist die Stimmenaufteilung für deinen Verein **kostenlos**. Im Hintergrund entstehen aber externe Kosten (der KI-Lesedienst). Für den regulären Betrieb behalten wir uns deshalb eine **Kostenbeteiligung** vor – voraussichtlich als **Pauschale**; die Details sind noch offen.

!!! note "Seitenkontingent"
    Damit die Nutzung fair bleibt, hat jeder Verein ein **Seitenkontingent** pro Zeitraum (je nach Verein pro Tag, Monat oder Jahr – eingestellt durch die bin-dabei-Administration). Oben auf der Seite siehst du, **wie viele Seiten du im laufenden Zeitraum schon verbraucht hast** und **wann das Kontingent zurückgesetzt wird**. Gezählt werden die **gelesenen Seiten** eines Laufs.

    Ist das Kontingent ausgeschöpft, ist der Upload bis zum nächsten Reset gesperrt – du erhältst dann einen entsprechenden Hinweis. Brauchst du mehr, melde dich bei [info@bin-dabei.ch](mailto:info@bin-dabei.ch).

!!! note "Datenschutz: Schweizer KI von Infomaniak"
    Fürs Lesen der Seiten nutzt bin-dabei den KI-Dienst von **[Infomaniak](https://www.infomaniak.com/de/hosting/ai-services)** – das ist bewusst gewählt:

    - Die KI läuft auf einem **quelloffenen (Open-Source-)Modell** – keine Blackbox eines US- oder asiatischen Konzerns.
    - Betrieben wird sie **in der Schweiz**, in Infomaniaks eigenen Rechenzentren – ohne Abhängigkeit von ausländischen Anbietern.
    - Der Dienst ist **datenschutzkonform** nach Schweizer DSG und EU-DSGVO.
    - Die an die KI gesendeten Seiten werden **weder gespeichert noch zum Training** der KI verwendet – «Was du der KI anvertraust, gehört dir» (Infomaniak).
    - Und ökologisch: Der Betrieb läuft mit erneuerbarer Energie, deren Abwärme weiterverwendet wird und im Winter rund 6000 Wohnungen heizt.

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

Von oben nach unten: zuerst **Stücktitel** und **Komponist**, darunter das **Dateinamen-Muster**, und zuunterst die Tabelle mit allen erkannten Stimmen.

### Stücktitel und Komponist

Oben bestätigst oder korrigierst du **«Stücktitel»** und **«Komponist/Arrangeur»** – sie fliessen in die Dateinamen ein.

### Dateinamen-Muster

Das **Dateinamen-Muster** (direkt unter Titel/Komponist) bestimmt, wie die heruntergeladenen Stimmen-PDFs heissen. Du baust es aus Platzhaltern und freiem Text zusammen:

- `{sortiercode}` – das Sortier-Präfix der Stimme (z.B. `04b`)
- `{komponist}` – Komponist/Arrangeur
- `{titel}` – Stücktitel
- `{instrument}` – Instrumentbezeichnung

Beispiel: `{titel} [{sortiercode} - {instrument}]` ergibt `Beispielstück [04b - Klarinette 2]`. Leere Platzhalter (z.B. ein Stück ohne Komponist) werden samt überflüssiger Trennzeichen automatisch entfernt.

In der Tabelle unten siehst du dann pro Stimme in der Spalte **«Dateiname»** **live**, wie die Datei heissen wird – die Vorschau aktualisiert sich, sobald du das Muster, Titel/Komponist oder eine Zeile änderst.

!!! note "Standard pro Verein"
    Lässt du das Feld leer, gilt das **Standard-Muster deines Vereins** (von einem Vereinsadmin in den Vereinseinstellungen festlegbar). Hier beim Stück überschreibst du es nur für dieses eine Stück.

!!! tip "Fester Text pro Stück – z.B. Signatur"
    Weil das Muster pro Stück anpassbar ist, kannst du auch **festen Text** einbauen, der nur für dieses Stück gilt – etwa eine **Signatur/Archivnummer**: `{sortiercode}_{titel}_{instrument}_MB-1343` ergibt `04b_Beispielstück_Klarinette 2_MB-1343`.

### Die Stimmen-Tabelle

Die Tabelle listet alle erkannten Stimmen:

| Spalte | Bedeutung |
| --- | --- |
| **Übernehmen** | Häkchen entfernen, um eine Stimme **nicht** ins ZIP aufzunehmen. |
| **Sortiercode** | Das Nummern-Präfix der Stimme (z.B. `04b`), aus dem **Benennungsprofil deines Vereins** (von bin-dabei gepflegt). Bestimmt Dateiname und Sortierreihenfolge – pro Zeile frei editierbar, leer lassen heisst «kein Präfix». |
| **Instrument** | Die Stimmenbezeichnung. Editierbar; sie wird in den Dateinamen übernommen. |
| **Seiten** | Welche Seiten des Quell-PDFs zu dieser Stimme gehören. |
| **Kopien** | Wie viele identische Exemplare im PDF gefunden wurden (es wird nur eines extrahiert). |
| **Hinweis** | Automatische Anmerkungen, z.B. «4 copies → kept 1» oder «1 page(s) rotated 180°». |
| **Dateiname** | Live-Vorschau, wie die Datei am Schluss heissen wird (gemäss «Dateinamen-Muster» oben). |
| **Vorschau** | Öffnet die fertige Stimme als PDF in einem neuen Tab. |

Was die Aufteilung dabei automatisch erledigt:

- **Mehrfach-Kopien** derselben Stimme werden zu einer zusammengefasst (in der Spalte «Kopien» siehst du, wie viele es waren).
- Die **Partitur** wird als eigene Stimme «Partitur» mitgeliefert.
- **Auf dem Kopf stehende Folgeseiten** werden – soweit automatisch erkannt – aufrecht gedreht; kontrolliere im Zweifel kurz die Vorschau.
- Verlage drucken oft in GROSSBUCHSTABEN – Titel und Stimmennamen werden in normale Schreibweise gebracht.

!!! tip "Zwei falsch getrennte Seiten zusammenführen"
    Liest die KI eine mehrseitige Stimme versehentlich als zwei (z.B. «E Horn 2» und «Eb Horn 2»), gib einfach beiden dasselbe Instrument. Sobald zwei aufeinanderfolgende Zeilen identisch heissen, erscheint ein Häkchen **«↑ mit voriger zusammenführen»** (standardmässig angekreuzt). Beim Herunterladen werden die beiden Teile dann zu **einer** PDF verbunden.
### Plausibilitäts-Hinweise

Über der Tabelle können zwei Hinweise erscheinen:

- **«Einige Seiten konnten nicht gelesen werden»** – einzelne Seiten sind beim Lesen ausgefallen (meist vorübergehende Überlastung des Dienstes). Lass die Aufteilung in diesem Fall nochmals laufen.
- **«Einige Seiten sind in keiner Stimme enthalten»** – diese Seiten des Quell-PDFs sind in keiner Stimme gelandet. Bei Titel- oder Leerseiten ist das normal; sonst lohnt sich ein Blick, ob eine Seite verloren ging.

In beiden Hinweisen sind die **Seitenzahlen anklickbar** – ein Klick öffnet die betreffende Quellseite in einem neuen Tab, sodass du gleich siehst, worum es geht (z.B. ob es bloss eine Titelseite war).

## 4. Herunterladen

Zwei Tasten, die **beide zuerst deine Korrekturen speichern**:

- **«Überprüfung speichern»** – speichert die Bearbeitung, ohne herunterzuladen (du kannst später weitermachen).
- **«Speichern & ZIP herunterladen»** – speichert und gibt das ZIP mit allen übernommenen Stimmen aus.

Die Dateien im ZIP heissen nach dem **oben gewählten Dateinamen-Muster** (Standard: `{sortiercode}_{komponist}_{titel}_{instrument}`), sodass sie in deinem Notenarchiv gleich richtig einsortiert sind.

!!! note "Was die Aufteilung (noch) nicht kann"
    Komplett um 90° quer eingescannte Stücke werden nicht automatisch gedreht. Und so gut die Erkennung ist – ein kurzer Blick in die Vorschau lohnt sich, bevor du die Stimmen ins Archiv übernimmst.
