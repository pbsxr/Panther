# Panther – Konzeptstand

<img width="640" alt="Zwei Panther als Symbol für das Zusammenspiel von Hardware und Software" src="../assets/panther.jpg" />

Die beiden Panther stehen für Hardware und Software. Erst ihr abgestimmtes Zusammenspiel macht das System für den Anwender nutzbar und schafft die Voraussetzung für den Erfolg des Projekts.

## Ziel

Panther ist das Konzept einer leisen, kompakten RISC-V-Workstation mit eigenständiger Gestaltung und einer direkt nutzbaren Arbeitsumgebung. Dieses Repository unter pbsxr sammelt Unterlagen, dokumentiert Entscheidungen und führt die offenen Entwicklungsaufgaben zusammen.

## Konzeptgrundlage

**Projektseite:** [mac-address.de/projects/panther](https://mac-address.de/projects/panther/)

Die Webseite nennt den Konzeptstand vom 28. August 2026 und verwendet inzwischen die Bezeichnung „Pro Light“. Der Name dieses Repositories bleibt vorerst **Panther**; Namen und Konzeptstände werden abgeglichen.

## Hardware und Gehäuse

- Ziel laut Konzeptseite: RISC-V/RVA23; Mac Pro 5,1 als Übergangs- und Konzeptplattform.
- Zielboard, Kühlung und technische Umsetzung sind noch offen.
- Ausdrücklich gewünscht: eine VARTA CR2032 als Pufferbatterie für CMOS/RTC – aus historischen und nostalgischen Gründen. Halterung und elektrische Einbindung sind mit dem Zielboard abzustimmen.
- Gehäuserahmen laut Webseite: etwa 23 cm Höhe ohne Füße/Griffe, 19 cm Tiefe und 8–9 cm Breite mit konstruktivem Spielraum; silberne Metallwirkung und bündige Seitenklappe.
- Externe USB-C-PD-Versorgung; Strombuchse hinten unten und quer, übrige USB-C-Buchsen hochkant.
- Vorgesehen: ein USB-C-Monitoranschluss mit DisplayPort Alt Mode, zwei USB-C-Anschlüsse für Peripherie und mindestens ein 2,5-Gbit-Ethernet-Anschluss, bevorzugt zwei. Thunderbolt ist ein Wunsch.
- Ein „Remove Before Flight“-Stift soll die Freigabe über eine Niederspannungs-/Enable-Funktion schalten. Konstruktion und Schaltung sind zu prüfen.

## Arbeitsumgebung und Updates

Der bisherige Softwarestand nennt Ubuntu 22.04 LTS und NEXTSPACE 0.95 als Ziel. Gewünscht sind ein WebKit-basierter Browser, GNOME Commander, Office-Software und eine geeignete PDF-Anwendung. SoftMaker Office wird bevorzugt; ArtCraft/Crafting Apps ist ein Kandidat für Kreativ- und Büroprogramme. Ein WebKit-basierter Browser bleibt bevorzugt; Aloha wird als mögliche Alternative untersucht. RISC-V-Verfügbarkeit und Integration müssen jeweils geprüft werden.

**Flatpak** gehört zum Installations- und Updatekonzept der Anwendungen. Die Aktualisierung von Basissystem und Firmware wird zusätzlich geplant.

## Nächste Schritte

Quellen und Anforderungen zusammenführen, Konzeptvorgaben von Wünschen und offenen Entscheidungen unterscheiden und daraus eine verbindliche Spezifikation entwickeln. Technische Möglichkeiten werden erst nach Prüfung festgelegt.

Das Motiv der beiden Panther verkörpert das gemeinsame Leitbild von Hardware und Software. Der bisherige Schriftzug wird vorerst weggelassen; ein geeignetes Original mit Transparenz wird noch gesucht.

## Verwandte Projekte

- [NEXTSPACE](https://github.com/trunkmaster/nextspace): vorgesehene Grundlage der grafischen Arbeitsumgebung. Panther-spezifische Anpassungen und die RISC-V-Unterstützung sind zu prüfen.
- [Flatpak](https://github.com/flatpak/flatpak): Kandidat für Installation und Aktualisierung der Anwendungen.
- [ArtCraft / Crafting Apps](https://github.com/storytold): quelloffene Kreativ- und Büroprogramme, unter anderem PhotoCraft, LightCraft, FilmCraft und WordCraft. [Offizielle Projektseite](https://getartcraft.com/). Reifegrad und RISC-V-Portierbarkeit der einzelnen Anwendungen prüfen.
- [GNOME Web / Epiphany](https://apps.gnome.org/Epiphany/): möglicher WebKit-basierter Browser; [Quellprojekt](https://gitlab.gnome.org/GNOME/epiphany). Integration in NEXTSPACE und RISC-V-Verfügbarkeit prüfen.

## Weitere Softwarekandidaten

- [SoftMaker Office](https://www.softmaker.de/softmaker-office-entdecken-vergleich): bevorzugte kommerzielle Office-Software. FreeOffice ist kostenlos erhältlich, aber ebenfalls proprietär. Ein offizielles offen lizenziertes Office-Quellprojekt ist bislang nicht nachgewiesen; RISC-V-Unterstützung und Möglichkeiten einer Vorinstallation sind offen.
- [Aloha Browser](https://alohabrowser.com/posts-aloha-browser-linux-release/): laut Hersteller seit 21. Mai 2026 als Linux-Beta mit .deb- und .rpm-Paketen verfügbar. Der Desktop-Browser verwendet Chromium; sein [Browserkern aloha-core](https://github.com/AlohaBrowser/aloha-core) ist auf GitHub. Aloha ist damit eine mögliche Alternative zum bevorzugten WebKit-Browser. Ein passender RISC-V-Build ist noch zu prüfen.

Diese Links dokumentieren technische Bezüge und mögliche Zusammenarbeit. Eine gegenseitige Verlinkung oder offizielle Partnerschaft ist noch nicht vereinbart.
