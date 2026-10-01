# TODO

Kleine Ideen und Beobachtungen, die gebündelt umgesetzt werden (nicht sofort).

- **Legende überlappt:** Im Radar überlappt die Legende von *Tools* (Ring TRIAL, Einträge 20ff.) die Überschrift *Platform & Infrastructure*, weil *Tools* viele Einträge hat. Betroffen: legend_offset / legend_line_height in docs/index.html bzw. docs/radar.js (legend_transform). Ggf. Legende in zwei Spalten oder mehr Abstand je Quadrant.
- **Ring-Namen im Infotext:** Der Text unter dem Radar nennt den Ring *ADOPT*, im Radar heißt er *IN USE*. Texte in docs/index.html (Abschnitt "What is the TEQ Radar?") angleichen.
- **Node-Version im Deploy:** .github/workflows/deploy-swa.yml nutzt Node 18 (EOL). Auf aktuelle LTS anheben und mit yarn --frozen-lockfile testen.
- **Pflege der Daten:** Einträge werden manuell in docs/config/quadrant-*.json gepflegt, Datum in docs/config-metadata.json. Idee: Datum automatisch setzen oder per Workflow-Erinnerung (z. B. quartalsweise Issue) auf Aktualisierung hinweisen.
- **Design-Feinschliff:** Inhalte der SVG-Legende sind klein (11px). Prüfen, ob Legende/Blips für Mobile (aktuell horizontal scrollbar) separat als Liste dargestellt werden sollen.
