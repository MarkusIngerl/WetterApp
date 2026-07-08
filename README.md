
# Temperaturanzeige 1.0

Ein einfaches Python-Programm zum Abrufen und Anzeigen aktueller Wetterdaten.

## Beschreibung

Die Anwendung bezieht Wetterdaten über die öffentliche API von **wttr.in** und liest die aktuelle Temperatur einer vom Benutzer gewählten Stadt aus.

Nach dem Start wird der Benutzer aufgefordert, einen Stadtnamen einzugeben. Nach Bestätigung mit der **ENTER-Taste** werden die Wetterdaten abgerufen und die aktuelle Temperatur ausgegeben.

## Verwendete Datenquelle

Die Wetterdaten werden über folgende Schnittstelle bezogen:

https://wttr.in/

Beispiel:

https://wttr.in/Berlin?format=j1

Die Daten werden im JSON-Format geliefert und anschließend im Python-Programm ausgewertet.

## Funktionen

- Eingabe einer gewünschten Stadt
- Abruf aktueller Wetterdaten über das Internet
- Verarbeitung von JSON-Daten
- Ausgabe der aktuellen Temperatur
- Einfache Bedienung über die Konsole

## Verwendete Technologien

- Python
- Requests
- JSON

## Beispiel

```text
Von welcher Stadt möchtest du die Temperatur wissen?
> Berlin

Aktuelle Temperatur in Berlin: 24 °C
