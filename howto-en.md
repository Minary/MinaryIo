---
layout: page
title: Howto
lang: en
permalink: /howto/
---

Minary kann auf zwei Arten gestartet werden:
  - Doppelklick auf Minary.exe
  - Doppelklick auf eine Template-Datei

Das Doppelklicken der Datei Minary.exe erlaubt einen individuell konfigurierten Angriff. Diese Variante ist für Tests und Experimente im eigenen Netzwerk geeignet.  

Doppelklicken auf eine Template-Datei (Dateierweiterung: .mry) führt alle benötigten Schritte automatisiert durch, die für einen spezifischen Angriff nötig sind. Templates werden verwendet, wenn ein Angriff auf ein bestimmtes System (z.b. Facebook Login) ausgeführt werden soll.

  
## Doppelklick auf Minary.exe

Doppelklicke die Datei **Minary.exe** im Installations-Verzeichnis. Minary wird sich dann in einem neutralen Zustand öffnen und kann für einen Angriff nach Bedarf konfiguriert werden. Vor dem Angriffs müssen folgenden drei Schritte durchgeführt werden:
  * Aktiviere die Plugins, die für den Angriff benötigt werden
  * Scanne das Netzwerk nach Ziel-Computern, die angegriffen werden sollen
  * Starte den Angriff und beobachte die Ausgaben in den Plugin-Tabs  

![Minary in neutralem Zustand](/assets/minary/default_screen.png){:class="img-responsive"}
    
  
## Doppelklick auf eine Template-Datei
Eine Template-Datei ist eine Vorlage für Minary, die einen Angriff automatisiert durchführt. Folgende Schritte werden dabei im Minary durchlaufen: 
  - Benötigte Module werden geladen und nicht-benötigte Module werden entfernt
  - Das LAN wird nach potenziellen Zielsystemen durchsucht (falls aktiviert)
  - Zielsysteme werden ausgewählt und aktiviert (falls aktiviert)
  - Der Angriff wird gestartet (falls aktiviert)

Templates können entweder selbst generiert werden oder es stehen einige Templates auf der [Projektseite]({{ "/de/findings" | relative_url }}) zum Download bereit. Lade eine Template-Datei auf den Rechner und doppelklicke anschliessend die Template-Datei um den Angriff automatisch zu starten.


![Minary gestartet durch ein Template](/assets/minary/loading_template.png){:class="img-responsive"}

Zu berücksichtigen ist, dass Minary vorher bereits einmal aufgestartet wurde. Ansonsten weiss Windows nicht, was es mit der Template-Datei anstellen muss.
