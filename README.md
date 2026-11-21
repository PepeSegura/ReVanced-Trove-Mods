<p align="center">
  <a href="README.md"><img src="https://img.shields.io/badge/lang-English-2b7cff?style=for-the-badge" alt="English"></a>
  <a href="README.es.md"><img src="https://img.shields.io/badge/idioma-Español-555?style=for-the-badge" alt="Español"></a>
</p>

# ReVanced Trove Mods

UI mods for Trove, installed and updated by [ReVanced Trove Launcher](https://github.com/PepeSegura/ReVanced-TroveLauncher)
(Mods tab). You can also copy a `.tmod` from `mods/` into `Trove\Live\mods` by hand.

| Mod | Changes | What it does |
|---|---|---|
| ReVanced Inventory | Inventory and chests | Card-style inventory and chests. Sort button in chests too, a search (type in the chat) that jumps to the right tab, and right click to store items in the chest. |
| ReVanced Chat | Chat | Chat with emojis and tabs. With the inventory or friend list search open, what you type in the chat filters that window (or /bus text). |
| ReVanced Tooltip | Item tooltips | Item tooltips as a clear card: stats, ability, item icon and comparison with what you wear, in the game language. Allies show their XP. |
| ReVanced Loot Collector | Loot collector | “Keep new” button: items not in your collection yet are locked so Collect All leaves them. |
| ReVanced Tiny Quest | Tiny Quest | The quest table and the Tiny Quest panel show the XP each ally gets from a quest and whether it levels up. |
| ReVanced Auto Tome Swap | Tome bar, menu and Collections | When the equipped tome fills up, the next one is equipped by itself: legendary tomes first, your favourites in the Collections order. It also re-equips your mount, wings and ship on every new world (fixes mount mods that stay bugged). |
| ReVanced Auto Accept | Game prompts and settings | Accepts or declines game prompts (party, club, trade invites…) by your rules, using the friend list locks. Redesigned settings window. |
| ReVanced Loot Tooltips | Floor loot | Hides the tooltips of gear on the floor, except items you do not have in your collection yet. Crystal loot effect. |
| ReVanced Hotbar | Bottom bar | Redesigned bottom bar: health and energy with their numbers, cooldown seconds on each slot and rarity under each item. Sends the item icon to the tooltip. |
| ReVanced Charsheet | Character sheet and gems | All your stats at once and the coefficient the game hides; on gems, how good each roll is. Saves name, PR and mastery for the launcher cards. |
| ReVanced Player HUD | Player bar | Player bar with a pink/red gradient: PR, class level and next prime level. Saves your PR and class for the launcher cards. |

`pack.json` lists every mod with its SHA1: the launcher downloads a mod only when it is missing or changed.

`cfgs/` has clean default settings for the mods that use them (copy to `%APPDATA%\Trove\ModCfgs` with Trove closed if you install by hand; the launcher does it for you and never replaces a cfg you already have). The game only passes a setting to a mod when its key already exists in that file.
