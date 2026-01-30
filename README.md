# NexusCore v1.0 | 17 modułów(Pluginów) (Paper 1.21.8-1.21.11)

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

### Informacje...
> - **Czemu NexusCore tyle wazy?** - **Przez ładowanie sterownikow sql i mysql do .jar.**
> - **Co do Aktualizacji?** - **Beda co jakis czas darmowe (Chyba ze posiadasz konto premium to wtedy masz caly czas).

**`Wszystkie moduły:`**
- **Addons**
- **StrefaAFK**
- **StartEdycji**
- **Portfel**
- **Security**
- **SetSpawn**
- **Rtp**
- **Otchlan**
- **Ban**
- **Mute**
- **Helpop**
- **Chat**
- **ChatFormat**
- **Effekt**
- **Gamma**
- **Kosz**
- **Links**

## Commands

| Komenda | Aliasy | Opis | Użycie | Permission |
|---------|--------|------|--------|------------|
| `/edit` | `nexusitem`, `enchant` | Edycja przedmiotów (CustomEnchant) | `/edit <customenchant\|enchant\|glow\|rename\|lore\|hide\|hideall\|unbreakable\|reload\|help>` | `NexusCore.CustomEnchant.use` |
| `/nxban` | — | Ban stały (PERM) | `/nxban <gracz> [powód]` | `NexusCore.Ban.ban` |
| `/nxtempban` | — | Ban czasowy | `/nxtempban <gracz> <czas> [powód]` | `NexusCore.Ban.tempban` |
| `/nxbanip` | — | Ban IP | `/nxbanip <gracz> [powód]` | `NexusCore.Ban.banip` |
| `/nxunban` | — | Unban gracza | `/nxunban <gracz>` | `NexusCore.Ban.unban` |
| `/nxunbanip` | — | Unban IP | `/nxunbanip <gracz>` | `NexusCore.Ban.unban` |
| `/nxbanlist` | — | GUI lista banów | `/nxbanlist` | `NexusCore.Ban.banlist` |
| `/chat` | — | Zarządzanie chatem | `/chat <on\|off\|cc>` | `NexusCore.Chat.use` |
| `/portfel` | — | Otwiera GUI portfela | `/portfel` | — |
| `/portfel2` | — | Admin portfel | `/portfel2 reload` \| `/portfel2 give <nick> <ilosc>` | `NexusCore.Portfel.admin.reload` |
| `/nxafk` | — | Zarządzanie strefami AFK | `/nxafk <selector\|reload\|create>` | `NexusCore.StrefaAFK.Admin.selector` |
| `/efekt` | — | Zarządzanie efektami | `/efekt <fly\|jumpboost> <gracz> [czas]` | `NexusCore.Effects.give` |
| `/kit` | — | Otwiera GUI z kitami | `/kit [reload]` | `NexusCore.EssentialsKit.use` |
| `/gamma` | — | Włącza/wyłącza Night Vision | `/gamma` | `NexusCore.Gamma.use` |
| `/helpop` | — | Wyślij zgłoszenie HelpOp | `/helpop <wiadomość>` | `NexusCore.HelpOp.use` |
| `/zgloszenialista` | — | Lista zgłoszeń HelpOp | `/zgloszenialista` | `NexusCore.HelpOp.admin` |
| `/kosz` | — | Otwiera twój kosz | `/kosz` | `NexusCore.Kosz.use` |
| `/edycje` | — | Zarządzanie edycjami | `/edycje <start\|pauza\|znow\|usun\|reload> <nazwa>` | `NexusCore.StartEdycji.admin` |
| `/itemshop` | — | Otwiera link do sklepu | `/itemshop` | `NexusCore.Links.itemshop` |
| `/discord` | `dc` | Otwiera link do Discorda | `/discord` | `NexusCore.Links.discord` |
| `/nxmute` | — | Permanentny mute | `/nxmute <gracz> <powód>` | `NexusCore.Mute.mute` |
| `/nxtempmute` | — | Tymczasowy mute | `/nxtempmute <gracz> <czas> <powód>` | `NexusCore.Mute.tempmute` |
| `/nxmutelist` | — | GUI lista mute | `/nxmutelist` | `NexusCore.Mute.mutelist` |
| `/otchlan` | — | Otwiera Otchłań | `/otchlan` | — |
| `/setspawn` | — | Ustaw spawn | `/setspawn` | `NexusCore.SetSpawn.admin` |
| `/spawn` | — | Teleportuj się na spawn | `/spawn` | `NexusCore.SetSpawn.spawn` |
| `/rtp` | — | Losowa teleportacja | `/rtp` | — |
| `/setrtprange` | — | Ustaw zasięg RTP | `/setrtprange` | `NexusCore.RTP.setrtprange` |
| `/security` | — | Security admin | `/security reload` | `NexusCore.Security.admin` |

## Permissions

| Permission | Default | Opis / Moduł                                |
|------------|---------|---------------------------------------------|
| `NexusCore.CustomEnchant.use` | op | **Addons:** Użycie `/edit`                  |
| `NexusCore.CustomEnchant.admin` | op | **Addons:** Funkcje administracyjne         |
| `NexusCore.CustomEnchant.unsafe` | op | **Addons:** Niebezpieczne operacje          |
| `NexusCore.Ban.ban` | op | **Ban:** Nakładanie bana stałego            |
| `NexusCore.Ban.tempban` | op | **Ban:** Nakładanie tymczasowego bana       |
| `NexusCore.Ban.banip` | op | **Ban:** Banowanie IP                       |
| `NexusCore.Ban.unban` | op | **Ban:** Odbanowywanie gracza/IP            |
| `NexusCore.Ban.banlist` | op | **Ban:** Dostęp do GUI listy banów          |
| `NexusCore.Chat.use` | op | **Chat:** Zarządzanie chatem (on/off/cc)    |
| `NexusCore.Chat.antyslow` | op | **Chat:** Bypass antyspam (3s cooldown)     |
| `NexusCore.HelpOp.use` | true | **HelpOp:** Wysyłanie zgłoszeń              |
| `NexusCore.HelpOp.admin` | op | **HelpOp:** Dostęp do listy zgłoszeń        |
| `NexusCore.Portfel.admin.reload` | op | **Portfel:** Admin `/portfel2`              |
| `NexusCore.StrefaAFK.Admin.selector` | op | **StrefaAFK:** Zarządzanie strefami         |
| `NexusCore.Effects.give` | op | **Effekt:** Nadawanie efektów               |
| `NexusCore.Links.itemshop` | true | **Links:** Dostęp do `/itemshop`            |
| `NexusCore.Links.discord` | true | **Links:** Dostęp do `/discord`, `/dc`      |
| `NexusCore.Mute.mute` | op | **Mute:** Nakładanie permanentnego mute     |
| `NexusCore.Mute.tempmute` | op | **Mute:** Nakładanie tymczasowego mute      |
| `NexusCore.Mute.mutelist` | op | **Mute:** Dostęp do GUI listy mute          |
| `NexusCore.EssentialsKit.use` | true | **EssentialsKits:** Otwieranie GUI kitów    |
| `NexusCore.EssentialsKit.admin.reload` | op | **EssentialsKits:** Reload konfiguracji     |
| `NexusCore.Gamma.use` | op | **Gamma:** Włączanie/wyłączanie Night Vision |
| `NexusCore.Security.admin` | op | **Security:** `/security reload`            |
| `NexusCore.Security.AntySpy.bypass` | op | **Security:** Bypass AntySpy                |
