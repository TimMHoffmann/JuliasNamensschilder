## Namensschildgenerator

Ein kleines Werkzeug zum Erstellen von Namensschildern zum Falten – als Tischaufsteller.
Alles läuft in einer einzigen `index.html`, ohne Server und ohne Abhängigkeiten.

### Was es kann
- Vier Druckvorlagen, jeweils quer oder hoch:
  - **A5 zum Zuschneiden** (empfohlen) – ein Schild auf A4 mit Schnittmarken
  - **2 Schilder zum Zuschneiden** – auf A4, je 184 × 135,5 mm
  - **A5-Papier** – ein Schild, kein Schneiden
  - **2 Schilder auf A4** – je A5, in der Mitte teilen
- Motivrahmen in vier Stilen, aus 83 an- und abwählbaren Motiven zusammengewürfelt
- Vorder- und Rückseite getrennt gestalten: Text, **leer** oder **Schreiblinien** zum Selberschreiben
- Schrift, Größe (auch automatisch), Zeilenabstand, Farbe, Ausrichtung, Versalien, Schatten
- Vorschau lässt sich drehen, damit die Rückseite beim Bearbeiten nicht auf dem Kopf steht
- Export als **PNG** oder **PDF** (150/300/600 dpi) in Originalgröße
- Helles und dunkles Design, Rückgängig/Wiederholen, automatisch gesicherter Entwurf

### Druck und weißer Rand
Normale Drucker können nicht bis an die Papierkante drucken und lassen ringsum etwa 3–5 mm frei.
Deshalb gibt es drei Varianten:

- **Zum Zuschneiden:** Die Motive laufen 3 mm über die Schnittkante hinaus, außen sitzen
  Schnittmarken. Nach dem Schneiden bleibt kein weißer Rand – mit jedem Drucker.
- **Weißer Rand:** ein gleichmäßiger, bewusst freier Rand (3–12 mm).
- **Randlos:** Motive bis an die Papierkante – nur für Drucker mit Randlos-Druck.

Die Seitengröße im Druckdialog wird automatisch auf das Papier der Vorlage gesetzt
(`@page { size: …; margin: 0 }`). Im Druckdialog Skalierung **100 %** und Ränder **Keine** wählen.
Auf **iPhone und iPad** (und in Safari) über die PDF-Datei drucken – der Druckdialog bietet das an.

### Hinweis
- Privates Hobbyprojekt, nur zu Demonstrationszwecken
- Keine Datenerhebung – Eingaben bleiben lokal im Browser
- Keine Gewährleistung
