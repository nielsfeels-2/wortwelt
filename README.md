# ⛏️ WortWelt – Lernspiel für Klasse 1

Ein gamifiziertes, browserbasiertes Lernspiel für die Grundschule (Klasse 1, Lehrplan NRW).
Offline lauffähig, anonym, ohne Anmeldung – optimiert fürs iPad.

**▶️ Live spielen:** https://nielsfeels-2.github.io/wortwelt/

![QR-Code zur Live-Version](qr-wortwelt-klasse1.png)

## Klassen

Oben im Hub lässt sich die **Klassenstufe** wählen. Verfügbar: **Klasse 1** und **Klasse 2** (Klasse 3, 4 und Vorschule folgen). Jede Klasse hat dieselben Fächer, aufbauend auf den Kompetenzen des Schuljahres.

## Fächer (NRW)

- **📖 Deutsch** – Anlaute, Groß-/Kleinschreibung, Silben, Wörter lesen, Blitzlesen, Lückenwörter, Wörter schreiben, Sätze & Satzverständnis
- **🔢 Mathe** – Zählen & Mengen bis 10, Plus & Minus bis 10, Rechnen bis 20 (mit Zehnerübergang), Zahlzerlegung und Sachaufgaben
- **🌍 Sachunterricht** – alle fünf Lehrplan-Bereiche: Körper/Sinne/Gesundheit, Tiere & Pflanzen, Jahreszeiten & Wetter, Verkehr & Umwelt, Zeit & Zusammenleben
- **🎵 Musik** – Instrumente erkennen, laut/leise · hoch/tief · schnell/langsam, Singen, Reime & Rhythmus

Englisch beginnt in NRW erst ab Klasse 3 und ist daher (noch) kein Fach. Oben im Startbildschirm („Hub") lässt sich zwischen den Fächern umschalten. Avatar, Edelsteine und Erfolge sind fächerübergreifend, die Level-Fortschritte pro Fach getrennt. Jedes Fach ist so aufgebaut, dass am Ende die für Klasse 1 erwartete Kompetenzstufe erreicht wird.

## Üben, was noch wackelt (Spaced Repetition)

Falsch beantwortete Aufgaben landen in einer **Übungskiste pro Fach**. In der 🎯 Übungs-Challenge kommen die **schwächsten Aufgaben zuerst**; eine Aufgabe gilt erst als gelernt, wenn sie mehrmals (an verschiedenen Tagen) richtig beantwortet wurde (Leitner-Prinzip). So wird gezielt das wiederholt, was das Kind noch nicht sicher kann.

## Für wen?

Kinder im ersten Schuljahr – auch für Nichtleser geeignet: Alle Aufgaben werden per Sprachausgabe vorgelesen (Zahlen und Rechenaufgaben als „2 plus 3 gleich 5").

## Spielprinzip (kindgerecht & fair)

- Jedes Level ist ein kleiner Monster-Kampf: sechs richtige Aufgaben besiegen das Monster.
- **Belohnung nur für echtes Lernen** – Edelsteine (💎) gibt es ausschließlich für richtige Antworten. Kein Echtgeld, keine Käufe, kein Pay-to-win.
- **Fehler kosten nie Fortschritt.** Ein optionaler, abschaltbarer Schaden-Modus bietet mehr Herausforderung.
- **Eigener Avatar** aus selbst gezeichneten SVG-Figuren: drei Grundtypen (Minen-Kind, Tier, Roboter), frei einfärbbar, mit Gesicht, Hut, Werkzeug und Begleiter – im Avatar-Studio zusammenstellbar (Farben gratis, Extra-Teile per Edelstein, manche Teile durch Erfolge).
- Variable Belohnungen, Sammel-Schatzkammer, Tages-Challenge und ein Fehler-Training halten motiviert – ohne Kinder unter Druck zu setzen (Session-Bremse nach ~3 Einheiten).
- **Erwachsenen-Ecke** mit Lernstand (richtige Antworten, Quote, Übungsbedarf) für Eltern und Lehrkraft.

## Datenschutz

Keine Accounts, kein Tracking, keine Namen. Der Spielstand wird ausschließlich lokal im Browser (`localStorage`) gespeichert. DSGVO-freundlich.

## Technik

- **Eine einzige `index.html`** – kein Build-Schritt, kein Framework, kein CDN, keine externen Fonts oder Bilder. Grafik aus Emojis, CSS und Inline-SVG.
- Läuft offline in jedem modernen Browser; als Website über GitHub Pages bereitgestellt.

## Deployment (GitHub Pages)

Dieser Ordner ist der komplette Inhalt des Repos `nielsfeels-2/wortwelt`.
`index.html` liegt im Wurzelverzeichnis und wird von GitHub Pages direkt ausgeliefert.
Zum Aktualisieren einfach die neue `index.html` committen/hochladen – die Live-URL und der QR-Code bleiben gleich.

## Weiterentwicklung

`index.html` ist zugleich die Master-Datei und die WortWelt-Engine-Referenz. Technische Doku (Architektur, Aufgabentypen, Änderungslog) liegt im übergeordneten Projekt unter `14_LERNAPPS/WORTWELT-ENGINE.md`.

## Nutzung & Rechte

Eigenes Unterrichtsmaterial für den schulischen Einsatz. Emoji-Darstellung kann je nach Gerät/Betriebssystem leicht variieren.
