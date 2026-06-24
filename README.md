# Linie 1 Beruf B1/B2 (Brückenelement) — Begleit-Übungen

Interaktive Online-Übungen zum Lehrwerk **Linie 1 Beruf B1/B2 Brückenelement** (Klett),
Teil von **Lern Deutsch mit Arash** (arashguitoo.github.io).

## Inhalt (öffentlich)
- `index.html` — Startseite mit Buchcover und Lektionsübersicht
- `cover.jpg` — Buchcover
- `lektion1-uebung.html` — Lektion 1 „Eine neue Stelle", 4 Module à 30 Aufgaben
- `grammatik-perfekt.html` — Grammatik-Wiederholung „Das Perfekt": Erklärung + 30 gemischte Übungen
- `grammatik-temporale-konnektoren.html` — Temporale Konnektoren: Schaubild (Zeitachse) + 30 Übungen

## Lektion 1 — Module
1. Sich vorstellen & Profil
2. Der neue Arbeitsplatz (temporale Konnektoren, Verbposition)
3. Hobbys & Verben mit Ergänzungen
4. Beruflicher Werdegang & Lebenslauf (Reflexivpronomen)

## Mechanik
- Passwort-Gate zwischen den Modulen (Passwort als Belohnung am Modulende)
- Endless-Stack: falsch beantwortete Aufgaben kommen am Ende erneut
- Fortschritt in localStorage
- Modul-Zertifikat + Lektions-Zertifikat (PNG-Download) mit Namenseingabe
- Goatcounter-Analytics (aguitoo.goatcounter.com), Completion-Events pro Modul
- Aufgabentypen: Lesetext, Multiple Choice, Lückentext, Zuordnen, Wortsalat, Reihenfolge

## Deployment
Alle Dateien aus diesem Ordner ins GitHub-Pages-Repo legen. Keine Build-Schritte nötig.

## Zusatzlektion: Dativ & Akkusativ
- `dakku-solo.html` — Solo-Lektion (Beine-Methode, feste Präpositionen, Reflexivpronomen): 3 Module, 60 Übungen, kein Login
- `dakku-live.html` — Live-Klassenraum mit Firebase: Lehrkraft startet Session, TN treten mit Code bei, Fortschritt live
- `dakku-data.js` — gemeinsame Inhalte/Aufgaben für beide Versionen (muss im selben Ordner liegen)
- `dakku-anleitung.md` — Kurzanleitung für die Live-Stunde
