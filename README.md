# Panther

**Hardware und Software gemeinsam gedacht.**

<img src="assets/panther.jpg" width="640" alt="Zwei Panther als Symbol für das Zusammenspiel von Hardware und Software" />

Die beiden Panther stehen für Hardware und Software. Erst ihr abgestimmtes Zusammenspiel macht das System für den Anwender nutzbar und schafft die Voraussetzung für den Erfolg des Projekts.

## Worum geht es?

Panther ist das Konzept einer leisen, kompakten RISC-V-Workstation mit eigenständiger Gestaltung. Das Ziel: einschalten und direkt arbeiten können – mit aufeinander abgestimmter Hardware, Arbeitsumgebung, Anwendungen und einem durchdachten Updateweg.

**Stand: Konzeptphase.** Die Anforderungen werden gesammelt und abgestimmt. Zielboard, technische Umsetzung und Verfügbarkeit der gewünschten Software werden noch geprüft.

[Projektwebseite](https://mac-address.de/projects/panther/) · [Konzept im Detail](docs/KONZEPT.md) · [Offene Fragen](docs/OFFENE_FRAGEN.md) · [Mitwirken](docs/MITWIRKEN.md)

## Festgelegt

- Hardware und Software werden als zusammengehörendes System entwickelt; der Nutzen für den Anwender ist der Maßstab.
- Dieses Vorhaben wird auf GitHub unter dem Namen **Panther** geführt.
- Die beiden Panther bilden das gemeinsame Symbol für Hardware und Software. Der bisherige Schriftzug wird vorerst weggelassen.

## Gewünscht

- RISC-V als Zielplattform, eine leise und kompakte Bauform und externe USB-C-PD-Stromversorgung.
- Eine passende Arbeitsumgebung auf Basis von NEXTSPACE und Anwendungen für den Alltag.
- Ein WebKit-basierter Browser; Aloha wird zusätzlich als Alternative betrachtet.
- Ein dauerhaft aktualisierbares System; Flatpak ist ein Kandidat für Anwendungen und deren Updates.
- Aus historischen und nostalgischen Gründen ausdrücklich eine **VARTA CR2032 als CMOS-/RTC-Pufferbatterie**. Halterung und elektrische Einbindung werden mit dem Zielboard abgestimmt.

Die bisherigen Gehäuse- und Anschlussvorgaben sind im [Konzept](docs/KONZEPT.md) dokumentiert.

## Offen

Welches Board eignet sich? Wie werden Grafik, Kühlung und Anschlüsse umgesetzt? Welche Anwendungen laufen auf der Zielplattform? Wie funktionieren Installation, Updates und Wiederherstellung?

Diese Punkte sammeln wir als [offene Fragen](docs/OFFENE_FRAGEN.md). Feste Termine werden erst festgelegt, wenn die technischen Grundlagen geklärt sind.

## Verwandte Projekte

- [NEXTSPACE](https://github.com/trunkmaster/nextspace) – vorgesehene Grundlage der grafischen Arbeitsumgebung.
- [Flatpak](https://github.com/flatpak/flatpak) – Kandidat für Installation und Updates der Anwendungen.
- [ArtCraft / Crafting Apps](https://github.com/storytold) – quelloffene Kreativ- und Büroprogramme. [Projektwebseite](https://getartcraft.com/)
- [GNOME Web / Epiphany](https://apps.gnome.org/Epiphany/) – Kandidat für einen WebKit-basierten Browser. [Quellprojekt](https://gitlab.gnome.org/GNOME/epiphany)

Die Links zeigen technische Bezüge und mögliche Zusammenarbeit. Eine offizielle Partnerschaft oder gegenseitige Verlinkung ist bisher nicht vereinbart.

## Weitere Softwarekandidaten

[SoftMaker Office](https://www.softmaker.de/produkte/softmaker-office/features) ist die bevorzugte kommerzielle Office-Lösung. [Aloha Browser](https://alohabrowser.com/) wird als weitere Browseroption betrachtet. Passende RISC-V-Versionen und Möglichkeiten einer Vorinstallation sind jeweils noch zu prüfen.

## Mitwirken

Hinweise, Erfahrungen und Verbesserungsvorschläge sind willkommen. Über [Issues](https://github.com/pbsxr/Panther/issues) können Fragen und Vorschläge eingebracht werden. Bitte unterscheidet dabei belegte Eigenschaften, Wünsche und noch zu prüfende Ideen.

## Quellen und bisheriger Stand

Ausgangspunkt ist die [Konzeptseite auf mac-address.de](https://mac-address.de/projects/panther/). Sie nennt den Konzeptstand vom 28. August 2026 und verwendet inzwischen die Bezeichnung „Pro Light“. Der Abgleich von Namen und Konzeptständen bleibt offen; dieses Repository heißt Panther.

Das bisherige [GitHub Project](https://github.com/users/pbsxr/projects/1) bleibt als ergänzende Aufgabensammlung erhalten. Die öffentliche Dokumentation beginnt hier in der README.
