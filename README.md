# 📦 KayoCrates

**Next-Gen Modular Crates, Portable Lootboxes & Progressive Pity Engine for Paper, Purpur & Spigot [1.20.x - 1.21.x].**

[![SpigotMC](https://img.shields.io/badge/SpigotMC-Download%20Free-EE8A19?style=for-the-badge&logo=spigotmc&logoColor=white)](https://www.spigotmc.org/resources/kayocrates.140482/)
[![Releases](https://img.shields.io/badge/GitHub-Official%20Releases-00D26A?style=for-the-badge&logo=github&logoColor=white)](https://github.com/KayoPlugins/KayoCrates/releases)
[![Discord](https://img.shields.io/badge/Discord-Official%20Community-5865F2?style=for-the-badge&logo=discord&logoColor=white)](https://discord.gg/aruHHdsxTG)

---

## 🎥 In-Game Showcase

Watch the full demonstration (GUI Roulette, Virtual Crates, Pity System & 3D Vault Drop):  
👉 **[Watch on YouTube](https://youtu.be/7RzQhKnWfHw)**

---

## ⚖️ Free vs. Premium Comparison

| Feature | 📦 KayoCrates Free (`v1.0.0`) | 💎 KayoCrates Premium (`v1.0.0`) |
| :--- | :--- | :--- |
| **Registered Crates Limit** | Up to **5** physical crates (`crates.db`) | **Unlimited** |
| **3D Cinematic Animations** | ❌ Not included | ✔ **3D Spatial Display** & **Monumental Vault Drop** (`VAULT_DROP`) |
| **Classic GUI Roulette** | ✔ Included (sound, deceleration & anti-close protection) | ✔ Included (+ skip & multi-roll support) |
| **Database & Networks** | Local SQLite (`crates.db`) | SQLite or **MySQL / MariaDB** with HikariCP |
| **Progressive Pity System** | ❌ Disabled | ✔ Guaranteed rare drop after X unlucky openings |
| **Virtual Menu (`/crates`)** | Standard 45-slot layout | 100% customizable via `menus/virtual.yml` (`AUTO`, `27`, `45`, `54`) |
| **White-Label Branding** | Default branding | ✔ Full White-Label (custom titles & lores) |
| **Drop History & Milestones** | ❌ Disabled | ✔ Paginated winner GUI + Milestone rewards |
| **Rewards per Key (`rolls`)** | 1 reward per key | ✔ Dynamic range (`rolls: min: 1, max: 3`) |
| **PlaceholderAPI** | Async cached key & pending placeholders | ✔ Full expansion (`opened_total`, `pity`, `pity_max`) |

---

## 💻 Commands & Permissions

### Player Commands
* `/crates` *(aliases: `/crate`, `/caixas`, `/c`)* — Opens the virtual crates GUI (`kayocrates.use`).
* `/crate balance` — Displays your virtual key balance in chat (`kayocrates.use`).
* `/crate preview <crate>` — Opens the reward preview & drop chance menu (`kayocrates.preview`).
* `/crate claim` — Claims pending rewards stored from a full inventory (`kayocrates.use`).

### Admin Commands (`kayocrates.admin`)
* `/kayocrates setcrate <id>` — Binds the target block as a physical crate.
* `/kayocrates removecrate` — Unlinks and deletes the target physical crate.
* `/kayocrates givekey <player> <crate> <amount> [physical|virtual]` — Gives physical or virtual keys.
* `/kayocrates givebox <player> <crate> <amount>` — Gives portable lootbox capsules *(Premium)*.
* `/kayocrates list` — Lists all registered crates and coordinates.
* `/kayocrates cleardisplays` — Emergency purge of orphan TextDisplay entities.
* `/kayocrates reload` — Reloads configs, translations (`en_US` / `pt_BR`), and crates.

---

## 📊 PlaceholderAPI Variables

* `%kayocrates_keys_<crate>%` — Total keys owned (Virtual + Physical).
* `%kayocrates_keys_virtual_<crate>%` — Virtual database keys for a crate.
* `%kayocrates_keys_physical_<crate>%` — Physical keys in inventory.
* `%kayocrates_pending%` — Unclaimed rewards waiting in `/crate claim`.
* `%kayocrates_opened_total%` — Lifetime crates opened *(Premium)*.
* `%kayocrates_pity_<crate>%` — Current pity counter progress *(Premium)*.
* `%kayocrates_pity_max_<crate>%` — Required openings for guaranteed drop *(Premium)*.

---

## 💎 Upgrade to Premium

Want to unlock **3D Vault Drops**, **Unlimited Crates**, **Progressive Pity**, **MySQL**, and **Full White-Label**?  
Join our **[Official Discord Server](https://discord.gg/aruHHdsxTG)** and open a ticket to get your lifetime license!
