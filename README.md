# Gelände-Navi Winterhafen

Navigation am Werftgelände per QR-Code und GPS. Die ganze App ist die Datei `index.html`
(Lageplan, Wegenetz, Routing, GPS, QR-Schilder), sie läuft ohne Server über GitHub Pages.

## Adressen
- Start (Ziel wählen): `/` · Start fest an der Einfahrt: `/#von-standort`
- Warenannahme: `/#standort-m50` · zurück zur Ausfahrt: `/#m50-standort`
- Beliebige Route: `/#<von>-<nach>`, z. B. `/#standort-w16` · Ziel ab aktuellem Standort: `/#ziel-m47`
- QR-Schilder erzeugen: `/#qr`

Die Hauptrouten folgen der Einbahn-Runde: hin über die Oststraße, zurück über die Westseite (Kai).
Alle anderen Ziele: kürzester Weg über die Verkehrsflächen des Lageplans.

## Ziele
`standort`, `m50` (Warenannahme), `pallg`, `pgast1`, `pgast2`,
ÖSWAG Maschinenbau `m1 m3 m9 m9d m14 m33 m46 m46b m47 m48 m52 m54 m55 m56`,
ÖSWAG Werft Linz `w10 w10d w13 w16 w46 w46b`. Positionen aus den GPS-Daten der Gebäudeeingänge.
