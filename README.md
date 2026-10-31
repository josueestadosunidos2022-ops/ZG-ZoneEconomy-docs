# ZoneEconomy 1.4.0-beta7

## English

Banking, physical/virtual GodieCoins and player trades backed by the ZoneCrates wallet. Beta7 adds optional exact batch conversion ratios, such as 11 virtual for 10 physical, while retaining previous price behavior when [cambio].usar_relaciones_por_lote=false. Confirmation follows trade revisions; invalid offered assets or insufficient balance revoke confirmations. Preserve balances, worlds and existing configuration. Use beta7 on both sides.

## Español

Banco, GodieCoins físicos/virtuales e intercambios entre jugadores con cartera de ZoneCrates. Beta7 añade relaciones exactas por lote, por ejemplo 11 virtuales por 10 físicas, conservando el comportamiento anterior si [cambio].usar_relaciones_por_lote=false. Los cambios inválidos de objetos ofrecidos o saldo revocan confirmaciones. Conserva saldos, mundo y configuración; usa beta7 en ambos lados.


| Side / Lado | Version | File |
|---|---|---|
| server | 1.4.0-beta7 | `zoneeconomy-server-1.4.0-beta7-protected.jar` |
| client | 1.4.0-beta7 | `zoneeconomy-client-1.4.0-beta7-protected.jar` |

## Dependencies / Dependencias

- **server**: zonecore: Required Dependency ([2.1.2,)); zonecrates: Required Dependency ([2.0.5,)); zoneessentials: Optional Dependency ([4.2.11,)); zonelag: Optional Dependency ([4.1.0,))
- **client**: zonecrates: Required Dependency ([2.0.5,))

## Installation / Instalación

Install only the file for each side. Never mix two versions or both side distributions in one mods folder. Back up the world and preserve TOML/player data. Dedicated-server-only mods do not belong in a client modpack.

Instala solo el archivo del lado correspondiente. No mezcles versiones ni ambos JAR en una carpeta mods. Respalda mundo y conserva TOML/progreso. Los mods exclusivos de servidor no van en el modpack de cliente.

Protected public files retain features without distributing private source, mappings or production configuration/account data. File/resources/shared schemas and isolated server startup/clean save were checked; no new GUI/full-modpack or live multiplayer test was performed. File availability depends on CurseForge approval.

Los archivos públicos conservan funciones con protección, sin fuentes, mappings ni datos privados. Se verificaron archivos/esquemas y arranque/cierre local aislado; no una nueva prueba gráfica o multijugador real. Disponibilidad sujeta a aprobación de CurseForge.

## Ownership / Titularidad

Original ZONE code and artwork © Elgochogms. All Rights Reserved. Public documentation repository only; source and mappings remain private.
