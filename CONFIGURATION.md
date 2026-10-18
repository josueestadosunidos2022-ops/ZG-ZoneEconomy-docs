# ZoneEconomy 1.3.3 — configuración / configuration

## Español

ZoneEconomy usa **una sola billetera GodieCoin** de ZoneCrates; no crea un segundo saldo. El servidor valida compras, canjes e intercambios. La pareja cliente/servidor 1.3.3 debe instalarse con ZoneCrates 2.0.5 o posterior en ambos lados y ZoneCore 2.1.2 o posterior en servidor.

### `config/zoneeconomy-common.toml`

```toml
[cambio]
precio_comprar_moneda_fisica = 2000
valor_canjear_moneda_fisica = 2000
```

`precio_comprar_moneda_fisica` descuenta saldo virtual por cada moneda física recibida. `valor_canjear_moneda_fisica` abona saldo virtual por cada moneda física entregada. Los dos valores aceptan enteros positivos y se aplican independientemente; cambiar uno no ajusta el otro. Edita el TOML con el servidor detenido y reinicia. Respalda el mundo y datos de jugadores antes de cambios de versión.

### Comandos y permisos

| Nodo | Función | Sin proveedor de rangos |
|---|---|---|
| `zoneeconomy.balance` | `/saldo`, `/money`, `/dinero`, `/godiecoin saldo` | Permitido |
| `zoneeconomy.trade` | `/intercambiar`, `/tradear` | Permitido |
| `zoneeconomy.bank.npc` | Banco presencial de Easy NPC | Permitido |
| `zoneeconomy.bank` | `/banco` y conversión por comando | Denegado |
| `zoneeconomy.admin` | Ajuste de saldo y banqueros | Denegado |

`/godiecoin comprar <cantidad>` y `/godiecoin canjear <cantidad>` expresan **número de monedas físicas**. `retirar` y `depositar` son alias conservados. `/godiecoin dar|quitar|fijar` requiere `zoneeconomy.admin`. `/godiecoin banquero crear|vincular|quitar` requiere además Easy NPC Core y Config UI 7.12.1 para la función de NPC; sin esos mods la economía puede cargar, pero no crear banqueros. El banco portátil `/banco` puede concederse con `zoneeconomy.bank` a un rango VIP sin habilitar administración.

El intercambio exige una revisión final y confirmación de ambos jugadores; cambios en las ofertas invalidan las confirmaciones. El diario de transacciones se guarda en los datos del mundo y debe respaldarse junto con los datos de jugadores. En 1.3.3 se reparan las ofertas de comerciantes **vanilla** con monedas físicas antiguas al abrirlos; comerciantes de otros mods conservan su política anterior.

## English

ZoneEconomy uses the **single ZoneCrates GodieCoin wallet**; it does not create another balance. Install the matching 1.3.3 server/client pair, ZoneCrates 2.0.5+ on both sides, and ZoneCore 2.1.2+ on the server. Server logic validates purchases, redemptions and trades.

`config/zoneeconomy-common.toml` has `[cambio] precio_comprar_moneda_fisica=2000` (virtual coins charged for one physical coin) and `valor_canjear_moneda_fisica=2000` (virtual coins credited for one physical coin). These are independent positive integer rates. Edit with the server stopped and restart; back up world and player data first.

The permission table above lists public balance, trade and NPC banking nodes and restricted portable banking/admin nodes. `/godiecoin comprar|canjear <amount>` counts **physical coins**; `retirar` and `depositar` remain aliases. Easy NPC Core and Config UI 7.12.1 are needed only for banker NPC features. Player trades require both parties to review and confirm the current offers. Version 1.3.3 repairs existing **vanilla** merchant offers containing old physical GodieCoins when opened; it does not rewrite modded merchants globally.

