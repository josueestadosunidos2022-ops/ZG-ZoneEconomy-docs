# ZoneEconomy

## Current update / Actualización actual — 2026-10-23

Protected public builds prepared for Minecraft 1.20.1 / Forge 47.4.x / Java 17. Files become available after CurseForge approval. / Compilaciones públicas protegidas; los archivos estarán disponibles cuando CurseForge los apruebe.

GodieCoin-specific stack handling supports up to 264 coins without changing ordinary item stacks or requiring BiggerStacks. Includes the current wallet and transaction fixes.

| Side / Lado | Version / Versión | File / Archivo |
|---|---|---|
| server | 1.4.0-beta5 | `zoneeconomy-server-1.4.0-beta5-protected.jar` |
| client | 1.4.0-beta5 | `zoneeconomy-client-1.4.0-beta5-protected.jar` |

Install only the JAR for each side; never put both side JARs in one mods folder. Back up the world and preserve existing player data and TOML files. / Instala solo el JAR correspondiente a cada lado; conserva mundo, progreso y TOML existentes.

**server dependencies / dependencias:** ZoneCore: Required Dependency ([2.1.2,)); ZoneCrates: Required Dependency ([2.0.5,)); ZoneEssentials: Optional Dependency ([4.2.11,)); ZoneLag: Optional Dependency ([4.1.0,)).

**client dependencies / dependencias:** ZoneCrates: Required Dependency ([2.0.5,)).

Archive checks and isolated dedicated-server startup do not certify graphical gameplay, real multiplayer or the full modpack. / Las verificaciones de archivo y arranque aislado no certifican cliente gráfico, multijugador real ni modpack completo.

## Earlier reference / Referencia anterior

The following reference predates this update. Use the current versions and side instructions above when they differ. / La referencia siguiente es anterior; prevalecen las versiones y las indicaciones de lado de esta actualización.

## Update / Actualización — 2026-10-17

Selected version / Versión seleccionada: **server 1.4.0-beta2 / client 1.4.0-beta2**. New file availability depends on CurseForge approval / La disponibilidad de los archivos nuevos depende de su aprobación en CurseForge.

See [changes, exact files and installation](UPDATES-2026-10-17.md) / Consulta [cambios, archivos e instalación](UPDATES-2026-10-17.md). Preserve the world and TOML files / Conserva mundo y TOML.

## English

GodieCoin balances, banking and server-validated player trades. Current pair: server **1.4.0-beta2** and client **1.4.0-beta2**, Minecraft 1.20.1 / Forge 47.x.

### Installation

Install the labeled server JAR on the server and its compatible client JAR on players' clients. Both files belong to the same CurseForge project. The two version numbers may differ; follow the stated pair, never mix releases. Required mod dependencies shown by current source metadata: **ZoneCore, ZoneCrates**. Check the dependency version range of the exact uploaded file before installation.

### Configuration

Edit generated TOML files while the server or game is stopped unless a documented reload command is available. Back up persistent data before updates.

| Config file | Use |
|---|---|
| `config/zoneeconomy-common.toml` | Independent purchase and redemption rates; defaults are 2000 virtual coins per physical coin. |

See [configuration reference](CONFIGURATION.md) for keys detected in source and [release compatibility](RELEASES.md) for version-pair rules.

## Español

Saldos GodieCoin, banco e intercambios validados por el servidor. Pareja actual: servidor **1.4.0-beta2** y cliente **1.4.0-beta2**, Minecraft 1.20.1 / Forge 47.x.

### Instalación

Instala el JAR marcado servidor en el servidor y su JAR cliente compatible en los clientes. Ambos archivos pertenecen al mismo proyecto CurseForge. Los números de versión pueden diferir; respeta la pareja indicada y no mezcles entregas. Dependencias obligatorias indicadas por los metadatos actuales: **ZoneCore, ZoneCrates**. Comprueba el rango de versión del archivo exacto que instales.

### Configuración

Edita los TOML generados con el servidor o juego detenido, salvo que exista un comando de recarga documentado. Respalda los datos persistentes antes de actualizar.

| Archivo de configuración | Uso |
|---|---|
| `config/zoneeconomy-common.toml` | Tasas independientes de compra y canje; valor inicial de 2000 monedas virtuales por cada moneda física. |

Consulta la [referencia de configuración](CONFIGURATION.md) para claves detectadas en el código y la [compatibilidad de entregas](RELEASES.md) para las parejas de versiones.

## Ownership / Titularidad

Documentation and original ZONE visual assets © Elgochogms. This repository contains documentation and a project avatar only; it does not distribute mod source code, private mappings, server secrets or production configuration.
