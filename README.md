# Codex Cannoning
Hub repo for release of Codex 1.8 cannon server, client mods, and public world archives at time of shutdown on 2024-8-14.
- [Server](#server)
- [Archives](#archives)
- [Open-source Plugins](#open-source-plugins)
  - [Client-side](#client-side-mods)
  - [Server-side](#server-side-plugins)
- [Common Commands](#common-commands)

## Server
The server can be downloaded [here](https://codex-cannoning.s3.amazonaws.com/codex-server-v2024.10.6.7z). The configs have been cleaned up and it's ready to use. Doesn't include any data from OG server.

### Set-up
- In terminal, make sure `java -version` says 8 (if it doesn't work try `java --version`), or modify start.bat to use a specific java 8 installation. Don't DM me to fix your java installation.
- After starting server run `op` and `whitelist add` commands in terminal.

## Archives
The public world archives from 2024-8-14 can be downloaded [here](https://codex-cannoning.s3.amazonaws.com/codex-public-worlds.7z) (3 GB).


## Open-source Plugins/Mods
### Server-side Plugins
[SchemUploadPlugin](https://github.com/alex-huff/SchemUploadPlugin)

[CannonDebug](https://github.com/alex-huff/CannonDebug)

[CannonTracer](https://github.com/alex-huff/CannonTracer)

[SchematicaDiscord](https://github.com/alex-huff/SchematicaDiscord)

[Fire](https://github.com/alex-huff/Fire)

### Client-side Mods
[SchemUploadMod](https://github.com/alex-huff/SchemUploadMod)

[CannonDebugExtra](https://github.com/alex-huff/CannonDebugExtra)

[CannonTracerMod](https://github.com/alex-huff/CannonTracerMod)


## Common Commands
- `/tracer`, `/t` - will show all commands for CannonTracer
  - `/ct` - clears tracers. Alias for `/t clear`
  - `/tt` - toggles tracers. Alias for `/t t`
- `/f` - fill dispencers within 64 blocks with 576 TNT. Alias for `/dt 64 46 576`
- `/kd` - kills all entities in your world. Alias for `/killall entities`
- `/fire`, `/lever` - uses last button/lever

### Multiverse
- **List worlds:** `/mv list`
- **TP to world:** `/mv tp <world-name>`
- **Create superflat:** `/mv create <world-name> NORMAL -g CleanroomGenerator:`
