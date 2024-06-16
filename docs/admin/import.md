[Home](/) > [Admin](/admin) >

# Import

## Benutzer:innen importieren

Speziell für die Ersteinrichtung können Benutzer:innen aus einer Excel-Datei importiert werden, statt sie einzeln manuell anzulegen.
Die Spalten der Excel-Datei müssen folgendermassen angelegt sein:
```
Vorname | Nachname | Email | Instrument/Stimme
```

!!! tip
    Es wird empfohlen, die auf der Seite verlinkte Beispiel-Excel-Datei herunterzuladen und den Import entsprechend dieser Datei aufzubauen.

Ist die Excel-Datei erstellt, kann diese hochgeladen werden. Wenn die erste Zeile eine Kopfzeile ist, also die Spaltennamen enthält, bitte die Checkbox «Kopfzeile?» ankreuzen, damit diese Zeile nicht importiert wird. Dann auf «Importieren» klicken.

Die Daten aus der Excel-Datei werden eingelesen und in einer Voransicht angezeigt. Wenn die dargestellten Daten in Ordnung sind, kann der Import mit Klick auf «Daten ok, importieren» endgültig ausgeführt werden.  
Sind die Daten in der Vorschau noch fehlerhaft, mit «Abbrechen» den Import stoppen, die Daten korrigieren und den Import nochmals starten.

Wenn ein:e Benutzer:in bereits in einem anderen Verein existiert (identifiziert über die gleiche Email-Adresse), wird kein neues Benutzerkonto angelegt, sondern das bereits vorhandene auch für den aktuellen Verein verwendet. D.h. der/die Benutzer:in kann das gleiche Login/Passwort für beide Vereine verwenden.

Alle importierten Benutzer:innen erhalten automatisch die Rolle eines/einer «normalen» Benutzer:in.
Existiert ein Benutzerkonto für diesen Verein bereits, wird es nicht überschrieben (und behält damit z.B. auch seine Admin-Rolle).

## Anlässe importieren

Zum Beispiel am Anfang eines Jahres können Anlässe (Proben und Konzerte) aus einer Excel-Datei importiert werden, statt sie einzeln manuell anzulegen.
Die Spalten der Excel-Datei müssen folgendermassen angelegt sein:
```
Datum [TT.MM.JJJJ] | Beginn [SS:MM] | Ende [SS:MM] | Titel | Ort | Öffentlicher Auftritt [1 = Ja, 0 = Nein]
```
Bitte beachten:

- Das Datum muss in Excel als Datum erkannt bzw. formatiert sein, damit der Import funktioniert
- Zeiten (Beginn und Ende) bitte mit Doppelpunkt zwischen Stunden und Minuten eingeben, damit der Import funktioniert
- Die letzte Zeile «Öffentlicher Auftritt» muss die Zahl 1 enthalten, wenn der Termin als öffentlicher Auftritt markiert (gelb hinterlegt) werden soll. Für Proben etc. die Zahl 0 eingeben (oder leer lassen).

!!! tip
    Es wird empfohlen, die auf der Seite verlinkte Beispiel-Excel-Datei herunterzuladen und den Import entsprechend dieser Datei aufzubauen.


Ist die Excel-Datei erstellt, kann diese hochgeladen werden. Wenn die erste Zeile eine Kopfzeile ist, also die Spaltennamen enthält, bitte die Checkbox «Kopfzeile?» ankreuzen, damit diese Zeile nicht importiert wird. Dann auf «Importieren» klicken.

Die Daten aus der Excel-Datei werden eingelesen und in einer Voransicht angezeigt. Wenn die dargestellten Daten in Ordnung sind, kann der Import mit Klick auf «Daten ok, importieren» endgültig ausgeführt werden.  
Sind die Daten in der Vorschau noch fehlerhaft, mit «Abbrechen» den Import stoppen, die Daten korrigieren und den Import nochmals starten.