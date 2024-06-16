[Home](/) > [Admin](/admin) >

# Vereinseinstellungen verwalten

## Vereinsangaben
Das Feld "Name" ist obligatorisch und wird als Titel, im Kalender etc. angezeigt.

Die Felder Adresse 1, Adresse 2, PLZ, Ort, Land, Telefon, Email, Website dienen vor allem internen Zwecken und sind optional.

Als Logo kann eine JPEG- oder PNG-Datei hochgeladen werden. Zur Anzeige wird das Logo automatisch auf 45px Höhe verkleinert.

## Plan
Der Grundplan für die Anzeige der An- und Abwesenheiten besteht aus einer bestimmten Anzahl von Zeilen und Spalten. Hier können Breite (Anzahl Spalten) und Höhe (Anzahl Zeilen) den Bedürfnissen des Vereins angepasst werden.

## Abmeldungen und Warnungen

### Spätestmögliche Abmeldung

Her kann eingestellt werden, wieviele Stunden vor einem Anlass noch eine Abmeldung per bin-dabei.ch möglich ist (mit der Idee, dass ganz kurzfristige Abmeldungen direkt den Verantwortlichen mitgeteilt werden sollten).

Wenn ein Konzert um 20:00 beginnt und für Auftritte eine Grenze von 2 Stunden eingestellt ist, sind die An- und Abwesenheiten für dieses Konzert ab 18:00 gesperrt.

Der Wert (in Stunden) kann für Proben und Auftritte getrennt definiert werden.

### Warn-Emails bei kurzfristigen Abmeldungen
Bei kurzfristigen Abmeldungen (d.h. Tage vor einem Anlass) können (getrennt für Proben und Konzerte) Warn-Emails an die Verantwortlichen geschickt werden.

Dafür kann eine Grenze von Anzahl Tagen vor dem Anlass (z.B. 7 Tage = 1 Woche) und eine Liste von Empfänger-Emails (mehrere Emails per Komma trennen) definiert werden.

Wenn zum Beispiel für Konzerte eine Grenze von 14 Tage und die Email-Adresse der MUKO-Präsidentin eingetragen wurden, erhält diese ein Email, wenn sich 10 Tage vor dem Konzert jemand abmeldet, und kann allenfalls noch eine Aushilfe organisieren.

Wird die Anzahl Tage oder die Liste der Emails freigelassen, werden für diese Kategorie (Probe oder Konzert) keine Emails verschickt.


## Andere Einstellungen

## Notenverwaltung
* Nur bei abonnierter Notenverwaltung verfügbar *

## Aufgebot per Email
Zu den einzelnen Anlässen kann automatisch eine Email mit dem Aufgebot und allen in bin-dabei.ch verfügbaren Informationen erstellt werden. Die entsprechenden Vorlagen (Templates) für Email-Betreff und Email-Text können hier angepasst werden.

### Platzhalter
Um die Informationen in den Text einbetten zu können, stehen diese Platzhalter zur Verfügung:

- [organisation-name] = Name des Vereins
- [event-date] = Anlass Datum
- [event-title] = Anlass Titel
- [location] = Ort
- [repertoire] = Programm/Noten
- [tenue] = Tenue
- [notes] = Bemerkungen

### Standard-Templates
#### Email-Betreff
Für den Email-Betreff lautet die Standard-Einstellung wie folgt:
```
[organisation-name]: [event-date] [event-title]
```
was z.B. folgenden Betreff ergeben kann:

> Musikverein Testingen: So. 28.07.25 16:00 Kirchenkonzert

#### Email-Text
Für den Email-Text lautet die Standard-Einstellung wie folgt:
```
Liebe Musikantinnen und Musikanten

Hier das Aufgebot für den [event-date]: [event-title]

Ort: [location]

Programm/Noten: [repertoire]

Tenue: [tenue]

[notes]

Musikalische Grüsse
[organisation-name]
```
was z.B. folgendes Email ergeben kann:

> Liebe Musikantinnen und Musikanten
> 
> Hier das Aufgebot für den So. 28.07.24 16:00: Kirchenkonzert
> 
> Ort: Ref. Kirche Testingen
> 
> Programm/Noten: Gemäss Programm Kirchenkonzert
> 
> Tenue: Uniform komplett
> 
> Instrumentendepot im Kirchgemeindehaus
> 
> Musikalische Grüsse
> Musikverein Testingen