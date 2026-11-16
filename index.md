---
title: Datenschutzerklärung – Verkehrszähler
---

# Datenschutzerklärung für die App „Verkehrszähler“

Stand: 16. November 2026 · gilt für die Android-App „Verkehrszähler“ (Paket `at.verkehrszaehler.app`)

## Kurz gesagt

- Die App funktioniert ohne Benutzerkonto, ohne Werbung und ohne Analyse- oder Tracking-Dienste. Wir betreiben keinen eigenen Server.
- Zählungen, Kreuzungen und Nachweisfotos werden **nur auf Ihrem Gerät** gespeichert. Wir als Anbieter haben darauf keinen Zugriff.
- Die Kamera wird nur während einer KI-Zählung genutzt. Die Bilder werden auf dem Gerät ausgewertet; **Videos werden nicht gespeichert**, Kamerabilder werden nicht übertragen. Gespeichert werden nur kleine Nachweisfotos, in denen Kennzeichen, Köpfe und erkannte Gesichter **verpixelt** sind.
- Eine Internetverbindung braucht die App nur für die Karte. Dabei werden Ihre IP-Adresse und der angezeigte Kartenausschnitt an die Kartendienste übermittelt (Abschnitt 6).
- Daten verlassen das Gerät sonst nur, wenn **Sie** sie aktiv teilen (z. B. eine Zählung als CSV, Excel oder PDF).

## 1. Verantwortlicher

[Boris Schinko]
[Ing. Josef Gattermaiergasse 1/1]
[2345 Brunn am Gebirge, Österreich]
E-Mail: [boris.schinko@gmail.com]

Für Fragen zum Datenschutz erreichen Sie uns unter der oben genannten E-Mail-Adresse.

## 2. Wofür die App gedacht ist

Die App unterstützt Verkehrszählungen an Kreuzungen: Fahrzeuge, Radfahrer und Fußgänger werden je Abbiegebeziehung und Zeitintervall gezählt – von Hand oder automatisch mit der Kamera. Ergebnisse lassen sich als CSV, Excel oder PDF ausgeben.

## 3. Daten, die nur auf Ihrem Gerät gespeichert werden

| Daten | Inhalt | Wie lange |
| --- | --- | --- |
| Kreuzungen und Vorlagen | Name, Straßennamen, Koordinaten der Kreuzung, Form, Zähllinien | bis Sie sie in der App löschen oder die App deinstallieren |
| Zählungen | Zeitpunkt, Fahrzeugklasse und Richtung jedes gezählten Objekts, Korrekturen | wie oben |
| Kopfdaten einer Zählung | was Sie eintragen: Name der zählenden Person, Wetter, Bemerkung, Auftragsnummer | wie oben |
| Nachweisfotos (nur KI-Zählung) | je gezähltem Objekt ein kleiner Bildausschnitt (höchstens 640 Pixel) und ein enger Objektausschnitt (höchstens 224 Pixel); Kennzeichen, Köpfe und erkannte Gesichter verpixelt | wie oben |
| Rahmen zu Nachweisfotos (nur KI-Zählung, ab Version 0.7) | Position der erkannten Objekte im Nachweisfoto und ggf. der beim Prüfen angepasste Rahmen – nur Zahlen, für das Nachtrainieren | wie oben |
| Gelerntes (nur KI-Zählung, ab Version 0.6) | zu jeder von Ihnen geprüften KI-Zählung eine Zahlenreihe (Merkmalsvektor des Objekts) und die gewählte Klasse – **kein Bild**; daraus erkennt die App ähnliche Fahrzeuge wieder. Löschbar unter Einstellungen → „Gelerntes vergessen“ | wie oben |
| Einstellungen | z. B. Kartendienst, Ausrichtung; ein optionaler Google-API-Schlüssel wird verschlüsselt gespeichert | wie oben |

Die App schließt sich von der automatischen Android-Datensicherung aus; die Daten werden also nicht in eine Cloud gesichert. Mit dem Deinstallieren der App werden alle Daten auf dem Gerät gelöscht.

Rechtsgrundlage: Die Speicherung auf Ihrem Gerät dient der Bereitstellung der von Ihnen genutzten Funktionen (Art. 6 Abs. 1 lit. b DSGVO bzw., soweit kein Vertrag besteht, unser und Ihr berechtigtes Interesse an einer funktionierenden App, Art. 6 Abs. 1 lit. f DSGVO).

## 4. Kamera

Die Kamera wird nur eingeschaltet, wenn Sie eine KI-Zählung starten. Die Bilder werden laufend **auf dem Gerät** ausgewertet (Erkennung von Fahrzeugen, Rädern und Personen mit der Bibliothek Google MediaPipe, genauere Fahrzeugklasse mit Google LiteRT; die Modelle sind in der App enthalten, darunter ein selbst nachtrainiertes Erkennungsmodell). Das Kamerabild wird weder als Video gespeichert noch übertragen.

Zu jedem automatisch gezählten Objekt speichert die App ein Nachweisfoto, damit Sie die Zählung prüfen und korrigieren können. Vor dem Speichern werden das Kennzeichenfeld jedes erkannten Fahrzeugs (mittig im unteren Teil), die Köpfe erkannter Personen und erkannte Gesichter automatisch verpixelt – der Rest bleibt erkennbar, damit Sie die Fahrzeugart prüfen können; das unverpixelte Bild wird nie gespeichert. Die automatische Verpixelung kann in Einzelfällen etwas übersehen – bitte prüfen Sie Nachweisfotos, bevor Sie sie weitergeben.

Hinweis für Zählende: Wer mit der App im öffentlichen Raum filmt, ist für diese Aufnahme selbst datenschutzrechtlich verantwortlich (z. B. als Auftragnehmer einer Verkehrszählung). Die App unterstützt Sie dabei, indem sie kein Video speichert und Personen sowie Kennzeichen verpixelt.

## 5. Standort

Den Standort fragt die App nur ab, wenn Sie „In der Nähe“ wählen oder die Karte auf Ihre Position setzen. Er wird auf dem Gerät verwendet, um nahe gespeicherte Kreuzungen zu finden und die Karte zu zentrieren. Ihr Standort wird nicht gespeichert und nicht an uns übermittelt. Beim Anzeigen der Karte wird jedoch der entsprechende Kartenausschnitt bei den Kartendiensten geladen (Abschnitt 6).

## 6. Internet: Kartendienste

Für die Karte und die Übernahme einer Kreuzung aus der Karte stellt die App Verbindungen zu folgenden Diensten her. Dabei werden technisch notwendige Daten übermittelt: Ihre IP-Adresse, Datum und Uhrzeit, die Kennung der App (Name und Version, keine persönlichen Daten) sowie der angezeigte bzw. ausgewählte Kartenausschnitt.

- **OpenStreetMap-Kartenkacheln** (`tile.openstreetmap.org`), betrieben von der OpenStreetMap Foundation. Datenschutzerklärung: <https://osmfoundation.org/wiki/Privacy_Policy>
- **Overpass-API** (`overpass-api.de`) zum Abruf der Straßendaten (Straßenverlauf, Namen, Einbahnen usw.) für den gewählten Ausschnitt. Betreiberangaben: <https://overpass-api.de>
- **Optional: Google Maps Platform** (Kartenkacheln und Satellitenbilder von `tile.googleapis.com`) – nur, wenn Sie in den Einstellungen einen eigenen Google-API-Schlüssel eintragen und die Google-Karte wählen. Anbieter ist Google; dabei können Daten in die USA übermittelt werden. Google ist nach dem EU-US Data Privacy Framework zertifiziert. Datenschutzerklärung: <https://policies.google.com/privacy>

Rechtsgrundlage ist unser berechtigtes Interesse an einer funktionierenden Kartenanzeige (Art. 6 Abs. 1 lit. f DSGVO). Ohne Internetverbindung funktioniert das Zählen weiterhin; nur Karte und Kartenübernahme stehen dann nicht zur Verfügung.

## 7. Teilen und Exportieren

Daten verlassen das Gerät außerdem nur, wenn Sie sie selbst über die Android-Funktion „Teilen“ weitergeben – z. B. eine Zählung als CSV-, Excel- oder PDF-Datei oder die „Trainingsdaten“ (ZIP mit verpixelten Nachweisfotos und den von Ihnen geprüften Klassen). Empfänger und Weg (E-Mail, Messenger, Cloud) wählen Sie; für die weitere Verarbeitung gelten die Bedingungen dieser Empfänger. Bitte geben Sie Kopfdaten mit Namen und Nachweisfotos nur an Personen weiter, die sie für die Zählung benötigen.

## 8. Berechtigungen

| Berechtigung | Wofür |
| --- | --- |
| Kamera | KI-Zählung (nur während einer Zählung) |
| Standort (genau bzw. ungefähr) | „In der Nähe“ und Kartenposition (nur auf Ihre Anfrage) |
| Internet, Netzwerkstatus | Karte und Straßendaten aus OpenStreetMap |

Alle Berechtigungen können Sie in den Android-Einstellungen jederzeit entziehen; die übrigen Funktionen bleiben nutzbar.

## 9. Bezug über Google Play

Wenn Sie die App über Google Play beziehen, verarbeitet Google dabei Daten (z. B. Ihr Google-Konto und die Installation) nach eigener Verantwortung und der Datenschutzerklärung von Google: <https://policies.google.com/privacy>. Wir erhalten von Google nur zusammengefasste Statistiken und gegebenenfalls Absturzberichte, die keine Rückschlüsse auf Ihre Zählungen zulassen.

## 10. Ihre Rechte

Sie haben nach der DSGVO das Recht auf Auskunft, Berichtigung, Löschung, Einschränkung der Verarbeitung, Datenübertragbarkeit und Widerspruch (Art. 15–21 DSGVO). Da die App Ihre Daten nur auf Ihrem Gerät speichert, können Sie diese jederzeit selbst einsehen, ändern, exportieren und löschen. Bei Fragen wenden Sie sich an die in Abschnitt 1 genannte Adresse.

Sie haben außerdem das Recht, sich bei einer Datenschutz-Aufsichtsbehörde zu beschweren, in Österreich bei der Datenschutzbehörde, Barichgasse 40–42, 1030 Wien, <https://www.dsb.gv.at>.

## 11. Änderungen

Wir passen diese Datenschutzerklärung an, wenn sich die App oder die Rechtslage ändert. Es gilt die jeweils hier veröffentlichte Fassung.
