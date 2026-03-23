# PLC-Motorsteuerung-mit-EPLAN
## Projektbeschreibung

Dieses Projekt zeigt die Planung und Umsetzung einer Motorsteuerung mithilfe einer SPS (PLC), erstellt mit EPLAN.

- Schaltplan:
![Schaltplan](https://github.com/Nelson-Dzokam/PLC-Motorsteuerung-mit-EPLAN/blob/main/Screenshot%202026-03-23%20013633.png)
![Schaltplan(https://github.com/Nelson-Dzokam/PLC-Motorsteuerung-mit-EPLAN/blob/main/Screenshot%202026-03-23%20013556.png)

Ziel ist die Steuerung eines Drehstrommotors (3~) inklusive:

- Spannungsversorgung
- Schutz- und Schaltkomponenten
- SPS-Ansteuerung (24V DC)
- Ein-/Ausgänge für Steuerung und Signale

### Systemübersicht

Die Anlage besteht aus folgenden Hauptkomponenten:

#### Leistungsteil
- 3-Phasen-Netz (L1, L2, L3, N)
- Sicherung (-F1)
- Motorschutz / Schützsteuerung (-Q2)
- Drehstrommotor (-M1, 1.5 kW)

#### Steuerungsteil
- SPS (CPU 1211C DC/DC/DC)
- Digitale Eingänge (24V DC)
- Digitale Ausgänge zur Ansteuerung
- Versorgung: +24V / GND


