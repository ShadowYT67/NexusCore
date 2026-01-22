# NexusCore v1.0 | 12 modułów(Pluginów) (Paper 1.21.8-1.21.11)

Nowoczesny NexusCore ktory z polczeniu z EssentialsX tworzy zarobiste combo...

### Wymagania żeby NexusCore zadziałał:
**`System:`**
- **Silnik** — Paper 1.21.8
- **Java** — 21+

**`Pluginy:`**
- **EssentialsX**
- **Vault**
- **LuckPerms**.
- **PlaceholderAPI**.

### Czemu NexusCore wazy tak duzo?
> **Przez ładowanie sterownikow sql i mysql do .jar.**

## Commands

| Komenda | Aliasy | Opis | Użycie | Permission |
|---|---|---|---|---|
| `/edit` | `nexusitem`, `enchant` | Edycja przedmiotów (CustomEnchant). | `/edit <customenchant\|enchant\|glow\|rename\|lore\|hide\|hideall\|unbreakable\|reload\|help>` | `NexusCore.CustomEnchant.use` |
| `/nxban` | — | Ban stały (PERM) | `/nxban <gracz> [powód]` | `NexusCore.Ban.ban` |
| `/nxtempban` | — | Ban czasowy | `/nxtempban <gracz> <czas> [powód]` | `NexusCore.Ban.tempban` |
| `/nxbanip` | — | Ban IP | `/nxbanip <gracz> [powód]` | `NexusCore.Ban.banip` |
| `/nxunban` | — | Unban | `/nxunban <gracz>` | `NexusCore.Ban.unban` |
| `/nxunbanip` | — | Unban IP | `/nxunbanip <gracz>` | `NexusCore.Ban.unban` |
| `/nxbanlist` | — | GUI lista banów | `/nxbanlist` | `NexusCore.Ban.banlist` |
| `/portfel` | — | Otwiera GUI portfela | `/portfel` | — |
| `/portfel2` | — | Admin portfel | `/portfel2 reload` \| `/portfel2 give <nick> <ilosc>` | `NexusCore.Portfel.admin.reload` |
| `/nxafk` | — | Zarządzanie strefami AFK | `/<command> <selector\|reload\|create>` | `NexusCore.StrefaAFK.Admin.selector` |
| `/efekt` | — | Zarządzanie efektami (fly, jumpboost) | `/efekt <fly\|jumpboost> <gracz> [czas]` | `NexusCore.Effects.give` |
| `/gamma` | — | Włącza lub wyłącza tryb Night Vision (Gamma) | `/gamma` | `NexusCore.Gamma.use` |
| `/kosz` | — | Otwiera twój kosz | `/kosz` | `NexusCore.Kosz.use` |
| `/edycje` | — | Zarządzanie edycjami | `/edycje <start\|pauza\|znow\|usun\|reload> <nazwa>` | `NexusCore.StartEdycji.admin` |
| `/itemshop` | — | Otwiera link do sklepu | `/itemshop` | `NexusCore.Links.itemshop` |
| `/discord` | — | Otwiera link do Discorda | `/discord` | `NexusCore.Links.discord` |
| `/dc` | — | Skrót do Discorda | `/dc` | `NexusCore.Links.discord` |
| `/otchlan` | — | Otwiera Otchłań, jeśli jest aktywna. | `/otchlan` | — |
| `/setspawn` | — | Ustaw spawn | `/setspawn` | `NexusCore.SetSpawn.admin` |
| `/spawn` | — | Teleportuj się na spawn | `/spawn` | `NexusCore.SetSpawn.spawn` |
| `/rtp` | — | Losowa teleportacja | `/rtp` | — |
| `/setrtprange` | — | Ustaw zasięg RTP | `/setrtprange` | `NexusCore.RTP.setrtprange` |
| `/security` | — | Security module admin | `/security reload` | `NexusCore.Security.admin` |

## Permissions

| Permission | Default | Opis / moduł |
|---|---|---|
| `NexusCore.CustomEnchant.use` | op | Addons: użycie `/edit`. |
| `NexusCore.CustomEnchant.admin` | op | Addons: admin. |
| `NexusCore.CustomEnchant.unsafe` | op | Addons: unsafe. |
| `NexusCore.Ban.ban` | op | Ban: ban stały. |
| `NexusCore.Ban.tempban` | op | Ban: tempban. |
| `NexusCore.Ban.banip` | op | Ban: ban IP. |
| `NexusCore.Ban.unban` | op | Ban: unban/unbanip. |
| `NexusCore.Ban.banlist` | op | Ban: GUI banlist. |
| `NexusCore.Portfel.admin.reload` | op | Portfel: admin `/portfel2`. |
| `NexusCore.StrefaAFK.Admin.selector` | op | StrefaAFK: admin. |
| `NexusCore.Effects.give` | op | Effekt: nadawanie efektów. |
| `NexusCore.Links.itemshop` | true | Links: `/itemshop`. |
| `NexusCore.Links.discord` | true | Links: `/discord`, `/dc`. |
| `NexusCore.Gamma.use` | op | Gamma: `/gamma`. |
| `NexusCore.Security.admin` | op | Security: `/security reload`. |
| `NexusCore.Security.AntySpy.bypass` | op | Security: bypass (AntySpy). |
