# bremen-city-content

Inhalte fuer bremen.city. Die Website holt `content.json` zweimal taeglich ab.

## Regeln fuer content.json
- `events[]`: slug, title, excerpt, content (HTML), start, end (Format YYYY-MM-DDTHH:MM), ort, adresse, preis ("0" = frei), ticket (URL, optional)
- `news[]`: slug, title, excerpt, content (HTML), date, sources (Liste von URLs, PFLICHT - ohne Quelle wird nichts veroeffentlicht)
- Nur Tatsachen aus Primaerquellen (Polizei, Senat, Veranstalter, BSAG, Behoerden). Eigene Formulierung, keine uebernommenen Saetze.
- Keine Namen von Privatpersonen, keine Vorverurteilung ("soll", "nach Angaben der Polizei").
- Eintraege nie loeschen, nur ergaenzen oder korrigieren (gleicher slug = Aktualisierung).
