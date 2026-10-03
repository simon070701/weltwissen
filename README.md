# Weltwissen

Geografie-Quiz zum Lernen von Ländern, Grenzen, Flaggen und Hauptstädten.

**Spielen:** https://simon070701.github.io/weltwissen/

Läuft im Browser auf Handy, Tablet und PC, ohne Anmeldung. Die Seite ist eine einzige
HTML-Datei (`index.html`); am PC lässt sie sich auch herunterladen und offline per
Doppelklick öffnen.

## Spielmodi

Wo liegt das? · Flaggen · Hauptstädte · Umriss erkennen · Weltkarte zuordnen (Grenzen) ·
Regionen-Quiz (Bundesländer, Bundesstaaten, Provinzen) · Gemischt

**Lernen:** Lernmodus mit Karteikarten nach Leitner (5 Fächer) und Statistik mit
Trefferquote, schwächsten Einträgen und Beherrschungskarte. Der Lernfortschritt bleibt im
Browser des jeweiligen Geräts, ohne Anmeldung.

## Als App auf dem Handy

- **iPhone/iPad:** Link in Safari öffnen → Teilen → „Zum Home-Bildschirm“. Empfohlen: Im
  Safari-Tab löscht Safari gespeicherte Daten nach sieben Tagen ohne Besuch, in der App nicht.
  App und Safari-Tab haben getrennte Lernstände.
- **Android:** Link in Chrome öffnen → Menü ⋮ → „Zum Startbildschirm hinzufügen“ bzw.
  „App installieren“.

Zum Starten braucht die App eine Internetverbindung.

## Quellen und Lizenzen

| Quelle | Lizenz | Verwendet für |
|---|---|---|
| [Natural Earth](https://www.naturalearthdata.com/) 5.1.1 | Public Domain | Grenzen, Regionen, Orte, Meerestiefen |
| [mledoze/countries](https://github.com/mledoze/countries) | [ODbL 1.0](https://opendatacommons.org/licenses/odbl/1.0/) | Länderliste, Namen, UN-Mitgliedschaft |
| [Wikidata](https://www.wikidata.org/) | CC0 | Hauptstädte, Regionscodes, Namen und Aliasse |
| [flag-icons](https://github.com/lipis/flag-icons) | MIT, © 2013 Panayiotis Lipiridis | Flaggen |

Die in `index.html` eingebettete Länderdatenbank ist eine aus mledoze/countries abgeleitete
Datenbank und steht unter der **Open Database License (ODbL) 1.0**. Der MIT-Lizenztext der
Flaggen steht als Kommentar am Anfang von `index.html`.

Software: React (MIT), d3-geo, d3-geo-projection, topojson-client (ISC), Tailwind CSS (MIT).
