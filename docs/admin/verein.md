[Home](/) > [Admin](/admin) >

# Vereinseinstellungen verwalten

## Vereinsangaben
Das Feld "Name" ist obligatorisch und wird als Titel, im Kalender etc. angezeigt.

Die Felder Adresse 1, Adresse 2, PLZ, Ort, Land, Telefon, Email, Website dienen vor allem internen Zwecken und sind optional.

Als Logo kann eine JPEG- oder PNG-Datei hochgeladen werden. Zur Anzeige wird das Logo automatisch auf 45px Höhe verkleinert.

## Aufgebot per Email
Zu den einzelnen Anlässen kann automatisch eine Email mit dem Aufgebot und allen in bin-dabei.ch verfügbaren Informationen erstellt werden. Die entsprechenden Vorlagen (Templates) für Email-Betreff und Email-Text können hier angepasst werden.

### Platzhalter
Um die Informationen in den Text einbetten zu können, stehen diese Platzhalter zur Verfügung:

[organisation-name] = Name des Vereins
[event-date] = Anlass Datum
[event-title] = Anlass Titel
[location] = Ort
[repertoire] = Programm/Noten
[tenue] = Tenue
[notes] = Bemerkungen

### Standard-Templates
#### Email-Betreff
Für den Email-Betreff lautet die Standard-Einstellung wie folgt:
```
[organisation-name]: [event-date] [event-title]
```
was z.B. folgenden Betreff ergeben kann:

> Musikverein Testingen: So. 28.07.25 16:00 Kirchenkonzert

#### Email-Text
Für den Email-Betreff lautet die Standard-Einstellung wie folgt:
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
```
Liebe Musikantinnen und Musikanten

Hier das Aufgebot für den So. 28.07.24 16:00: Kirchenkonzert

Ort: Ref. Kirche Testingen

Programm/Noten: Gemäss Programm Kirchenkonzert

Tenue: Uniform komplett

Instrumentendepot im Kirchgemeindehaus

Musikalische Grüsse
Musikverein Testingen
```