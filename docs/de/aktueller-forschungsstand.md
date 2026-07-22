# Aktueller Forschungsstand: Swissphone Memo

## Bestätigte Beobachtungen

- Quarzbeschriftung: `QS421 / 20.94 / TEW5E`
- IC im HF-/ZF-Bereich: `MC3367DW`
- Gemessene Spektralkomponenten: ungefähr 20,99 MHz, 41,88 MHz und 83,76–83,78 MHz
- Das Signal ist nur vorhanden, wenn beide Platinen miteinander verbunden sind.
- Pin 2 und Pin 3 liegen im Ruhezustand ungefähr bei 3,0 V.
- TEST002 zeigte auf Pin 2 und Pin 3 während 20 Sekunden keine Pegelwechsel.
- Pin 4 blieb in den bisherigen Messungen Low.
- Die äußere Buchse der untersuchten Ladeschale ist eine BNC-Buchse.

## Gestützte Interpretation

Pin 2 und Pin 3 entsprechen sehr wahrscheinlich einer seriellen Schnittstelle mit Logikpegeln um 3 V. Eine direkte Verbindung mit klassischem RS-232-Pegel ist daher nicht empfohlen.

## Arbeitshypothesen

- Pin 1 könnte eine Lade-, Erkennungs- oder Power-Management-Funktion besitzen.
- Pin 4 könnte nur in einem speziellen Betriebszustand verwendet werden.
- Die Kanalauswahl könnte über eine elektronisch abgestimmte Oszillatorschaltung erfolgen.

## Offene Fragen

- Richtung von TX und RX
- Baudrate und Protokoll
- Funktion von Pin 1 und Pin 4
- Signalweg der BNC-Buchse
- Speicherort der Konfiguration
