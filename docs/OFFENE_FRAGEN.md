# Offene Fragen und nächste Klärungen

Diese Sammlung beschreibt Klärungsbedarf ohne feste Termine. Eine Idee wird erst nach Prüfung und bewusster Entscheidung zur festgelegten Anforderung.

## Konzeptstand und Quellen konsolidieren

**Status: Sammlung / offen.**

[Projektseite](https://mac-address.de/projects/panther/) und vorhandene Chats zusammenführen. Webseite: Konzeptstand 28. August 2026, Bezeichnung „Pro Light“; Repository-Name bleibt vorerst Panther. Abweichungen abgleichen und Anforderungen als Konzeptvorgabe, Wunsch oder offene Entscheidung kennzeichnen.

**Ergebnis:** nachvollziehbarer Konzeptstand mit Quellen und Entscheidungsübersicht.

## RISC-V-Zielplattform und Auswahlkriterien festlegen

**Status: Ziel / Auswahl offen.**

Die Projektseite nennt RISC-V/RVA23 als Ziel sowie Mac Pro 5,1 als Übergangs- und Konzeptplattform. Zielboard und Kühlung sind nicht festgelegt. Anforderungen an Rechenleistung, Grafik, Speicher, Schnittstellen und Linux-Unterstützung sammeln; Kandidaten erst danach bewerten.

Ausdrücklich gewünscht: eine VARTA CR2032 als Pufferbatterie für CMOS/RTC – aus historischen und nostalgischen Gründen. Halterung und elektrische Einbindung sind mit dem Zielboard abzustimmen.

**Ergebnis:** begründete Plattformanforderungen und dokumentierte Auswahlentscheidung.

## Anschlussanordnung technisch absichern

**Status: dokumentierte Konzeptvorgaben, Umsetzung offen.**

USB-C-PD hinten unten und quer; 1× USB-C für Monitor/DisplayPort Alt Mode sowie 2× USB-C für Peripherie, Datenbuchsen hochkant. Mindestens 1× 2,5-Gbit-Ethernet, bevorzugt 2×. Thunderbolt bleibt Wunsch. Interne Verkabelung oder eine Anschlussplatine sind mögliche Lösungen.

**Ergebnis:** geprüfter Anschlussplan mit Funktionen und Positionen.

## Gehäuse, Kühlung und Freigabestift konkretisieren

**Status: Konzept / Konstruktion offen.**

Rahmen laut Webseite: etwa 23 cm Höhe ohne Füße/Griffe, 19 cm Tiefe, 8–9 cm Breite mit Spielraum. Silberne Metallwirkung, bündige Seitenklappe, externe USB-C-PD-Versorgung. Der „Remove Before Flight“-Stift soll eine Niederspannungs-/Enable-Funktion schalten, nicht den gesamten PD-Leistungsstrom. Board, Kühlung, Wartungszugang und Umsetzung gemeinsam prüfen.

## Wechselbare Datenträger prüfen

**Status: Wunsch / offen.**

Eine Möglichkeit für externe beziehungsweise wechselbare Speicherkarten wurde angesprochen; CFast war eine Idee. Format, Anschluss, Einbauort und tatsächlicher Bedarf sind noch nicht entschieden. SD, CFexpress und ein austauschbarer Einschub sind bislang Vorschläge.

**Ergebnis:** begründete Entscheidung über Bedarf und gegebenenfalls eine passende Lösung.

## Arbeitsumgebung und Anwendungen definieren

**Status: Softwareziel / Auswahl und Kompatibilität offen.**

Bisheriger Konzeptstand: Ubuntu 22.04 LTS, NEXTSPACE 0.95 und GNOME Commander.

- [ArtCraft / Crafting Apps](https://github.com/storytold): Kreativ- und Büroprogramme; einzelne Anwendungen nach Reifegrad und RISC-V-Portierbarkeit bewerten.
- [SoftMaker Office](https://www.softmaker.de/softmaker-office-entdecken-vergleich): bevorzugte kommerzielle Office-Lösung; RISC-V-Unterstützung und Vorinstallation offen.
- WebKit-Browser bevorzugt; [GNOME Web / Epiphany](https://apps.gnome.org/Epiphany/) als Kandidat prüfen.
- [Aloha](https://alohabrowser.com/posts-aloha-browser-linux-release/): alternative Browseroption; Linux-Beta vorhanden, Desktop auf Chromium-Basis; RISC-V-Build prüfen.
- Geeignete PDF-Anwendung auswählen; ArtCraft/Crafting Apps mitprüfen.

**Ergebnis:** priorisierte Anwendungsliste mit Quellen, Verfügbarkeit und Teststatus.

[Konzeptseite](https://mac-address.de/projects/panther/)

## Installations- und Updatekonzept entwickeln

**Status: Ziel / Lösungsweg offen.**

Flatpak als Baustein für Installation und Updates der Anwendungen untersuchen. Passende RISC-V-Anwendungen und Laufzeitumgebungen sowie die Desktop-Anbindung prüfen. Aktualisierung von Basissystem und Firmware zusätzlich planen. Wiederherstellung nach fehlgeschlagenen Updates berücksichtigen.

**Ergebnis:** nachvollziehbarer Installations- und Updateweg für ein dauerhaft benutzbares Panther-System.

## Bildmaterial und Projektauftritt sichern

**Status: Referenz vorhanden / Aufbereitung offen.**

Das JPEG mit den zwei Panthern ist als Bildreferenz in der Repository-README hinterlegt. Die beiden Panther symbolisieren das notwendige Zusammenspiel von Hardware und Software für ein nutzbares System und den Projekterfolg. Ein geeignetes Original mit Transparenz wird noch gesucht. Den bisherigen Schriftzug vorerst weglassen. Namen „Panther“ und „Pro Light“ mit dem Konzeptstand abgleichen.

**Ergebnis:** geordnete Bildquellen und abgestimmter Projektauftritt.

