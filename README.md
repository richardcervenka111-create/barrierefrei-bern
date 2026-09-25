# Barrierefrei Bern

Mit Rollstuhl oder Kinderwagen ist die Frage nicht „wo ist ein WC“, sondern „wo ist eines, in das ich reinkomme“. Die Stadtkarte filtert das, aber nicht auf dem Handy in zwei Tipps.

Live: **https://richardcervenka111-create.github.io/barrierefrei-bern/**

Drei Sprachen (DE/EN/SK), „nächster Punkt“ mit Fussroute, kein Tracking, Standort bleibt im Gerät.

## Daten

Öffentliche WCs, Trinkbrunnen und Sitzbänke der Stadt Bern aus OpenStreetMap, gefiltert auf wheelchair=yes. Punkte ohne diesen Tag fehlen absichtlich: „unbekannt“ ist für jemanden im Rollstuhl keine Antwort. Die Nette-Toilette-Standorte der Stadt (WCs in Gastrobetrieben) sind nur drin, wenn sie in OSM erfasst sind.

`data.js`: 66 Punkte, OpenStreetMap-Stand 2026-09-24T23:09:59Z, gebaut am 2026-09-25 mit `_tools/make_map_app.py` (Overpass API, Bounding Box Stadt Bern 46.90–46.99 / 7.37–7.50). Lizenz ODbL, © OpenStreetMap-Beitragende. Karte: OSM-Kacheln, Leaflet 1.9.4 (cdnjs, mit Integritätsprüfung).

## Ehrlich gesagt

OpenStreetMap ist so gut wie die Leute, die es pflegen. Fehlt ein Punkt oder stimmt ein Detail nicht: in OpenStreetMap korrigieren, davon haben alle etwas. Diese Seite ersetzt keine offizielle Auskunft der Stadt.

## Lokal

`index.html` im Browser öffnen. Kein Build.

## Lizenz

Code MIT. Daten ODbL (OpenStreetMap).
