<div align="center">

```
████████╗██████╗ ██████╗ ██████╗
╚══██╔══╝╚════██╗██╔══██╗██╔══██╗
   ██║    █████╔╝██████╔╝██████╔╝
   ██║   ██╔═══╝ ██╔══██╗██╔═══╝
   ██║   ███████╗██║  ██║██║
   ╚═╝   ╚══════╝╚═╝  ╚═╝╚═╝
```

**Standalone FiveM scripts built for immersion, performance, and plug-and-play simplicity.**

*No bloat. No mandatory frameworks. Just drop it in and go.*

[![GitHub Org](https://img.shields.io/badge/github-T2RP-181717?style=for-the-badge&logo=github)](https://github.com/T2RP)
[![Language](https://img.shields.io/badge/language-Lua-2C2D72?style=for-the-badge&logo=lua)](https://github.com/T2RP)
[![License](https://img.shields.io/badge/license-MIT-green?style=for-the-badge)](https://github.com/T2RP)
[![Framework](https://img.shields.io/badge/frameworks-QBCore%20%7C%20QBox%20%7C%20ESX%20%7C%20Standalone-blue?style=for-the-badge)](https://github.com/T2RP)

</div>

---

## 🗂️ Resources

### 🔫 [gang_aggression](https://github.com/T2RP/gang_aggression)
> *Standalone gang NPC aggression system*

Arm yourself near a gang member and face the consequences. Gang NPCs react with hostility when aimed at or approached while armed, call for backup, and lock into combat mode until the threat is neutralised.

- Aim detection & proximity aggression
- Backup system with configurable ped cap
- Combat attribute locking — peds don't snap back to passive
- Works with **QBCore · QBox · ESX · Vanilla**
- Zero server-side code

---

### 💥 [gang-raid](https://github.com/T2RP/gang-raid)
> *Wave-based gang hideout raid script*

Hit randomized gang hideouts in tense, wave-based gunfights. NPCs are server-synced, loot crates drop on completion, police dispatch fires automatically, and every detail is configurable.

- Server-synced NPC spawns across randomized locations
- Wave-based combat with escalating difficulty
- Loot crate rewards on completion
- Police dispatch integration
- Full support for **QBCore · QBox · qb-target · ox_target · ox_inventory**

---

### 🔧 [t2_repairstation](https://github.com/T2RP/t2_repairstation)
> *Vehicle repair stations for QBox*

Clean, lightweight vehicle repair station script built for QBox. Drop repair points anywhere on the map with minimal configuration.

- Configurable repair station locations
- Built for **QBox**
- Lightweight and dependency-minimal

---

## ⚡ Philosophy

Every script in this org is built around three rules:

**1. Standalone first** — Scripts work without a framework. Framework support is added on top, never as a requirement.

**2. Performance matters** — No `GetGamePool` spam, no unnecessary server calls, no bloated dependencies. Every loop is lean.

**3. Drop-in simplicity** — Copy the folder, add one line to `server.cfg`, done. No SQL migrations, no exports to configure, no framework wrappers to set up.

---

## 🛠️ Framework Compatibility

All public resources in this org support the following out of the box:

| Framework | Supported |
|-----------|:---------:|
| Vanilla FiveM | ✅ |
| QBCore | ✅ |
| QBox | ✅ |
| ESX | ✅ |

---

## 📦 Installation (any resource)

```bash
# 1. Clone or download the resource folder into your resources directory
cd resources
git clone https://github.com/T2RP/<resource-name>

# 2. Add to server.cfg
ensure <resource-name>

# 3. Restart or refresh
refresh
start <resource-name>
```

---

## 🗺️ Roadmap

- [ ] Territory-based gang aggression zones
- [ ] Alliance system — friendly gang logic
- [ ] Additional raid locations and loot tables
- [ ] Configurable wanted-level integration across scripts
- [ ] Blip support for active gang events

---

## 📄 License

All repositories are released under the **MIT License** — free to use, modify, and redistribute. Credit appreciated but not required.

---

<div align="center">

*Built for the FiveM community — contributions, issues, and suggestions always welcome.*

</div>
