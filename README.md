# synapsDRUM – 4-Kanal Analog Eurorack Drum Synthesizer

synapsDRUM ist ein analoger 4-Kanal Eurorack-Drum-Synthesizer, der klassische Percussion-Schaltkreise (Kick, Snare, Hi-Hat) in einem kompakten Modul vereint.

---

## Features

* **4 analoge Kanäle:** Dedizierte Schaltungen für klassische Percussion-Sounds.
* **Twin-T Oszillatoren:** Für druckvolle Kick-Töne und tiefe Bässe.
* **Rauschgenerator & Filter:** Duale Rauschquellen und RC-Bandpassfilter für realistische Snares und metallische Hi-Hats.
* **SMD-Design:** Platzsparend und für zuverlässigen Aufbau im Eurorack optimiert.

---

## Projektstruktur

synapsDRUM/
├── kick.kicad_sch         # Schaltplan: Kick-Drum-Schaltung
├── snare.kicad_sch        # Schaltplan: Snare-Drum-Schaltung
├── hihat.kicad_sch        # Schaltplan: Hi-Hat / Rauschgenerator
├── filter.kicad_sch       # Schaltplan: RC-Bandpassfilter & Shaping
├── drum.kicad_pcb         # KiCad PCB Layout
├── drum.kicad_pro         # KiCad Hauptprojekt
└── .gitignore             # Git-Ausschlusskriterien für temporäre Dateien


## Hardware & Design

Das Modul wurde in KiCad modular aufgebaut, um die verschiedenen Percussion-Sektionen sauber zu trennen und klanglich optimal anzupassen.
Voraussetzungen & Tools

    KiCad (Empfohlen: Version 7 oder neuer)

    Passende SMD-Footprints und Bauteilbibliotheken


## Inbetriebnahme & Git

Um das Projekt lokal zu klonen, nutze diesen Befehl im Terminal:

git clone [https://github.com/hanebuechenes/synapsDRUM.git](https://github.com/hanebuechenes/synapsDRUM.git)

Öffne anschließend die Datei drum.kicad_pro in KiCad.


## Lizenz

Veröffentlicht unter der CERN Open Hardware Licence / MIT License.

