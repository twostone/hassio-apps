# Twostone Home Assistant Apps

Home-Assistant-Apps (Add-ons) von twostone in einem Repository.

[![Repository zu Home Assistant hinzufügen][my-ha-badge]][my-ha-url]

Oder manuell: **Einstellungen → Apps → App Store → ⋮ → Repositories** und
`https://github.com/twostone/hassio-apps` hinzufügen.

## Apps

| App | Version | Architekturen | Beschreibung |
| --- | --- | --- | --- |
| [Essensplanung](https://github.com/twostone/meal-planner) | [v0.16.0](https://github.com/twostone/meal-planner/tree/v0.16.0) | aarch64, amd64 | Wöchentliche Essensplanung für den Haushalt |
| [Garmin Insights](https://github.com/twostone/garmin-insights) | [v0.6.0](https://github.com/twostone/garmin-insights/tree/v0.6.0) | aarch64, amd64 | Garmin-Daten lokal spiegeln, auswerten und per PWA, REST-API und MCP nutzen |
| [Sweatbook](https://github.com/twostone/sweatbook) | [v1.10.0](https://github.com/twostone/sweatbook/tree/v1.10.0) | aarch64, amd64 | Training tracken und planen |

## Wie dieses Repository gepflegt wird

Die App-Verzeichnisse und diese README werden vom
[repository-updater](https://github.com/hassio-addons/repository-updater) geschrieben – bitte nicht von Hand
ändern. Jede App lebt in ihrem eigenen Repo; nach einem Release baut es das Image
(`ghcr.io/twostone/<app>:<version>`) und meldet sich per `repository_dispatch` hier. Welche Apps
dazugehören, steht in [`.apps.yml`](.apps.yml). Die gemeinsamen Workflows liegen in
[twostone/hassio-workflows](https://github.com/twostone/hassio-workflows).

Fehler und Wünsche bitte im Repo der jeweiligen App melden.

[my-ha-badge]: https://my.home-assistant.io/badges/supervisor_add_addon_repository.svg
[my-ha-url]: https://my.home-assistant.io/redirect/supervisor_add_addon_repository/?repository_url=https%3A//github.com/twostone/hassio-apps