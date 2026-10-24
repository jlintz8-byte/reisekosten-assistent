# Reisekosten-Assistent

Einfaches Tool zum Erfassen von **Verpflegungsmehraufwand** und **Reisebelegen** – komplett anonymisiert über Mitarbeiternummern. Kein Server, kein Backend, keine Datenbank: Alles läuft im Browser.

## Funktionen

- **Verpflegungsmehraufwand:** An-/Abreisetag mit Uhrzeit erfassen; Tagessätze (14 € für An-/Abreisetag 8–24 h, 28 € je vollem Tag), Mahlzeiten-Abzüge (Frühstück 20 %, Mittag 40 %, Abend 40 % vom 28-€-Satz) und Übernachtungspauschale (20 €/Nacht bei selbst organisierten Übernachtungen) werden automatisch berechnet.
- **Belege (Fotoscan):** Belegfoto mit der Handy-Kamera aufnehmen; Betrag, Datum, Kategorie und Zweck eintragen – das Foto wird mitgespeichert.
- **Anonymisierung:** Mitarbeiter werden ausschließlich über Nummern identifiziert. Neue Nummern lassen sich im Tool anlegen; die Zuordnung Nummer → Person liegt bei der Lohnbuchhaltung.
- **Abrechnung:** Zahlungsavis mit Rechnungsnummer (VL-Nummer-Betrag) als Vorschau und als PDF herunterladen (Druckdialog → „Als PDF speichern") und selbst an die Lohnbuchhaltung mailen.

## Website aktivieren (GitHub Pages)

1. Repository öffnen → **Settings** → **Pages**
2. **Source:** Deploy from a branch → **Branch:** main, **Ordner:** /(root)
3. **Save** – nach ca. einer Minute erreichbar unter:

`https://<dein-konto>.github.io/reisekosten-assistent/`

## Datenschutz

Alle Eingaben bleiben lokal im Browser (localStorage). Es werden keine Daten an einen Server gesendet. Kein Backend, keine Cookies, kein Tracking.

## Hinweis

Die Berechnungslogik folgt der internen Vorlage „Verpflegungsmehraufwand" (Stand 15.07.2024). Keine Gewähr – Abrechnungen von der Lohnbuchhaltung prüfen lassen. Auslandstagespauschalen werden von der Buchhaltung eingetragen; Reisedaten trotzdem erfassen.
