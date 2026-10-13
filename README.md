synapsDRUM – 4-Kanal Analog Eurorack Drum Synthesizer

synapsDRUM ist ein analoger 4-Kanal Eurorack-Drum-Synthesizer, der klassische Percussion-Schaltkreise (wie Kick, Snare und Hi-Hat) in einem kompakten Modul vereint.
Features

    4 integrierte Drum-Kanäle für klassische analoge Percussion-Sounds (Kick, Snare, Hi-Hat etc.).

    Twin-T Oszillatoren für druckvolle Kick-Töne.

    Duale Rauschgeneratoren und RC-Bandpassfilter für realistische Snares und metallische Hi-Hats.

    SMD-Design für platzsparenden und zuverlässigen Aufbau im Eurorack-System.

Projektstruktur

synapsDRUM/
├── kick.kicad_sch         # Schaltplan: Kick-Drum-Schaltung
├── snare.kicad_sch        # Schaltplan: Snare-Drum-Schaltung
├── hihat.kicad_sch        # Schaltplan: Hi-Hat / Rauschgenerator
├── filter.kicad_sch       # Schaltplan: RC-Bandpassfilter & Shaping
├── drum.kicad_pcb         # KiCad PCB Layout
├── drum.kicad_pro         # KiCad Hauptprojekt
└── .gitignore             # Git-Ausschlusskriterien für temporäre KiCad-Dateien
Hardware & Design

Das Modul wurde in KiCad als modulares System aufgebaut, um die verschiedenen Percussion-Sektionen sauber zu trennen und klanglich zu optimieren.
Voraussetzungen / Design-Tools

    KiCad (Empfohlen: v7 oder neuer)

    Passende Footprints und Bauteilbibliotheken für SMD-Bestückung

Inbetriebnahme & Git

Um das Projekt lokal zu klonen:

git clone https://github.com/hanebuechenes/synapsDRUM.git

Öffne anschließend die Datei drum.kicad_pro in KiCad, um das Layout oder die Schaltpläne anzupassen.
Lizenz

Dieses Projekt ist unter der CERN Open Hardware Licence / MIT License veröffentlicht.
