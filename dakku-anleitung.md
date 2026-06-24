# Dativ & Akkusativ — Anleitung Live-Klassenraum

## Zwei Dateien, zwei Zwecke

- **dakku-solo.html** — Solo-Übung ohne Anmeldung. Läuft sofort, alles im Browser, Fortschritt im localStorage. Für Selbststudium / Hausaufgabe.
- **dakku-live.html** — Live-Klassenraum mit Firebase. Du startest eine Session, die TN treten mit Code bei, du siehst alles in Echtzeit.

Beide nutzen dieselben Inhalte aus **dakku-data.js** (muss im selben Ordner liegen).

## So läuft die Live-Stunde (Onlinekurs)

1. Du öffnest **dakku-live.html** → „🖥️ Lehrkraft". Du bekommst sofort einen 4-stelligen Code (z. B. `K7QM`).
2. Die TN öffnen dieselbe Seite (Link teilen) → „📱 Teilnehmer:in" → Code + Name eingeben.
3. In deinem Dashboard erscheinen die Namen live. Drei Tabs:
   - **Live-Fortschritt** — wer ist online, wie weit (Balken), richtig/falsch.
   - **Pro Modul** — Häkchen, welches Modul wer abgeschlossen hat.
   - **Schwierige Aufgaben** — welche Aufgaben die meisten Fehler verursachten (gut für die Nachbesprechung).
4. Die TN arbeiten in ihrem Tempo durch die drei Module (Beine-Methode → feste Präpositionen → Reflexivpronomen). Falsch beantwortete Aufgaben kommen am Ende des Moduls erneut.

## Wichtig

- Die Firebase-Config (Projekt „lern-deutsch-arash") ist fest eingebaut — du musst nichts eintragen.
- Daten landen unter `dakku_sessions/[CODE]/` in deiner Realtime Database.
- Für den Kurs sollten die Datenbank-Regeln read/write erlauben (wie bei deinen anderen Spielen).
- WLAN-Ausfall? Dann einfach die Solo-Version nutzen — die braucht kein Internet (außer dem ersten Laden).

## Die Beine-Methode (Teil 1, didaktischer Kern)

- 1 Bein = Nominativ (schlafen, kommen)
- 2 Beine = Nominativ + Akkusativ (haben, kaufen, sehen)
- 3 Beine = Nominativ + Dativ + Akkusativ (geben, schenken, zeigen)
- Ausnahmen mit 2 Beinen, aber Dativ: helfen, danken, gefallen, gehören, vertrauen, antworten, folgen
