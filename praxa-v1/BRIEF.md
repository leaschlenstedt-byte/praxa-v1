# PRAXA Skills — Agent Brief V1: Minimal

## Deine Aufgabe
Baue eine vollständige, produktionsreife Landing Page basierend auf der bestehenden `index.html`. Die Seite soll radikal minimalistisch bleiben — eine Frage, eine Antwort, ein CTA, Pricing. Das ist alles.

## Was du NICHT ändern sollst
- Die Grundstruktur: Hero (voller Screen) + Pricing + Footer
- Den Inhalt der Frage und des Antworttexts
- Das Pricing (3 Pakete, alle "Auf Anfrage")

## Was du verbessern sollst

### Design & Code
- Responsiveness auf Mobile perfektionieren (iPhone 14, 390px)
- Smooth scroll zum Pricing-Bereich
- Schriften lokal cachen oder Fallbacks setzen falls Google Fonts nicht lädt
- Meta-Tags ergänzen: og:title, og:description, og:image, description
- Favicon einbauen (einfaches SVG-Favicon mit "P" reicht)

### Interaktion
- Der Scroll-Hinweis "Preise" unten links soll beim Klick sanft zu Pricing scrollen
- Beim Hover über die Pricing-Karten: subtile Elevation (kein Farbwechsel)
- DE/EN Toggle soll die aktuelle Sprache im localStorage speichern

### Qualität
- HTML validieren (keine fehlenden alt-Tags, korrekte Heading-Hierarchie)
- CSS aufräumen: keine ungenutzten Klassen
- Keine externen Abhängigkeiten außer Google Fonts

## Tech Stack
- Vanilla HTML/CSS/JS — kein Framework
- Eine einzige index.html Datei
- Keine Build-Tools nötig

## Deploy
GitHub Pages — die Seite muss als statische index.html funktionieren.

## Ziel
Jemand landet auf der Seite, liest die Frage, versteht in 5 Sekunden worum es geht, klickt "Demo buchen". Alles andere ist Rauschen.
