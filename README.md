# ZoneEconomy

## Current builds / Versiones actuales — 2026-11-04

| Side / Lado | Version / Versión | File / Archivo |
|---|---|---|
| server | 1.4.0-beta8 | [zoneeconomy-server-1.4.0-beta8-protected.jar](https://www.curseforge.com/projects/1738044/files/9438614) |
| client | 1.4.0-beta8 | [zoneeconomy-client-1.4.0-beta8-protected.jar](https://www.curseforge.com/projects/1738044/files/9438638) |

Minecraft 1.20.1 / Forge 47.4.x / Java 17. Protected public Beta builds; availability depends on each file approval. / Betas públicas protegidas; disponibilidad según aprobación de cada archivo.

## English — What is new

Astral bank/trade UI with virtual wallet, explicit GIVE/RECEIVE summary, focused amount field, trade revision/confirmation and clear expired-session feedback. Market/chat adds clickable routes and eight-row pages while preserving offline sales, paused /oferta announcements, exact batch conversion, guild callbacks and physical GodieCoins up to 264 per stack. No BiggerStacks requirement. Pair beta8 on both sides; Bank4/Trade2 retained. Uses the ZoneCrates wallet, not a separate economy database.

## Español — Novedades

Banco/intercambio astral con cartera, resumen ENTREGAS/RECIBES, foco en cantidad, revisión/confirmación y aviso de sesión vencida. Mercado/chat con rutas clicables y páginas de ocho filas; conserva ventas offline, anuncios /oferta pausados al desconectar, canje exacto por lotes, callback de gremios y monedas físicas hasta 264 por pila. No requiere BiggerStacks. Pareja beta8; conserva Bank4/Trade2. Usa cartera de ZoneCrates, no una base económica separada.

## Installation / Instalación

Use the exact server/client pair in the table. Do not mix earlier network revisions. / Usa la pareja exacta de la tabla; no mezcles revisiones de red anteriores.

Stop the affected instance, back up the world/config, remove only the previous same-mod/same-side JAR, and install the table version. Preserve character data, wallets and TOML. Do not put server-only dependencies on clients. / Detén la instancia, respalda mundo/config, sustituye solo el JAR anterior del mismo mod y lado, y conserva personajes, cartera y TOML. No instales dependencias exclusivas de servidor en el cliente.

## Dependencies / Dependencias

**server**: `zonecore` [2.1.2,) (required/obligatorio; SERVER); `zonecrates` [2.0.5,) (required/obligatorio; BOTH); `zoneessentials` [4.2.11,) (optional/opcional; SERVER); `zonelag` [4.1.0,) (optional/opcional; SERVER).

**client**: `zonecrates` [2.0.5,) (required/obligatorio; BOTH).

[Full changes and usage / Novedades y uso](RELEASE-2026-11-04.md) · [Configuration / Configuración](CONFIGURATION.md) · [Historical releases / Entregas históricas](RELEASES.md).

## Validation / Verificación

Original release checks and isolated startup/command registration of the protected set were reviewed. Shared schemas: Essentials 35, Guardian 13 and Misions 4 classes, with no mapping differences. This does not certify a new graphical client session, two-player gameplay, full third-party modpack, hosting deployment or FPS/TPS. / Revisadas las verificaciones de entrega y el arranque/registro de comandos del conjunto protegido. Esquemas compartidos sin diferencias de mapeo: Essentials 35, Guardian 13 y Misions 4 clases. No certifica una nueva sesión gráfica, dos jugadores, modpack completo, hosting ni FPS/TPS.

## Ownership / Titularidad

Original ZONE code and visual assets © Elgochogms. Public documentation only: no mod sources, private obfuscation maps, credentials or production player data. Existing rights of earlier distributions are preserved.
