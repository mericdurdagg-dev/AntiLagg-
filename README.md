![ANTILAGG](https://cdn.modrinth.com/data/cached_images/3862bfe8af2d91039e1a80037c15ecc6c5fb8256.jpeg)
# 🚀 AntiLagg
### Advanced Performance & Server Optimization Plugin

> Keep your Minecraft server fast, stable, and lag-free with intelligent optimization.

---

## ✨ Overview

**AntiLagg** is a modern optimization plugin built for **Paper**, **Purpur**, and **Spigot** servers.

Instead of simply deleting entities every few minutes, AntiLagg continuously monitors your server's health and applies intelligent optimizations to maintain high TPS and smooth gameplay.

Designed for both small communities and large public servers.

---

# ⚡ Features

## 🧠 Smart Optimization Engine
Automatically analyzes server performance and applies optimizations when needed.

## 📊 Live TPS Monitoring
- Beautiful TPS Graph GUI
- Real-time TPS BossBar
- Performance reports
- Server statistics

## 🧹 Automatic Lag Cleanup
Automatically clears unnecessary:

- Dropped Items
- Experience Orbs
- Unused Entities
- Projectiles
- Other lag-causing objects

---

## 🧩 Entity Stacker

Reduce entity count while keeping gameplay natural.

✔ Better performance

✔ Cleaner worlds

✔ Higher TPS

---

## 🎛️ Interactive GUI

Manage everything directly in-game.

- Performance Dashboard
- Optimization Controls
- Statistics
- Settings Menu
- One-click Optimization

---

## ⚙️ Performance Controls

Quickly enable or disable:

- Mob Spawning
- Item Drops
- Redstone Updates
- Hopper Activity
- Other performance settings

---

## 🌐 Live Web Dashboard

Monitor your server anywhere.

Features include:

- Real-time TPS
- Memory Usage
- CPU Usage
- Entity Count
- Player Count
- Server Status

---

# 📈 Performance Focus

AntiLagg intelligently monitors:

- TPS
- Entity Count
- Memory Usage
- Server Load
- World Activity

Then automatically performs optimizations before lag becomes noticeable.

---

# 🛡 Prevents

- TPS Drops
- Lag Spikes
- Entity Overload
- Redstone Lag
- Hopper Lag
- Chunk Performance Issues
- Memory Waste

---

# 💬 Commands

| Command | Description |
|----------|-------------|
| `/antilagg` | Main command |
| `/antilagg reload` | Reload configuration |
| `/antilagg clear` | Clear lag-causing entities |
| `/antilagg stats` | View cleanup statistics |
| `/antilagg tps` | Display current TPS |
| `/antilagg performance` | Detailed performance report |
| `/antilagg optimize` | Run manual optimization |
| `/antilagg gui` | Open the control panel |
| `/antilagg settings` | Toggle optimization settings |
| `/antilagg help` | Display help menu |

---

# ❤️ Why AntiLagg?

Unlike traditional "clear lag" plugins, **AntiLagg** is a complete performance management system.

Instead of reacting to lag after it happens, AntiLagg actively works to prevent it through intelligent monitoring and adaptive optimization.

---

# 🔧 Compatibility

| Software | Supported |
|----------|-----------|
| Paper | ✅ |
| Purpur | ✅ |
| Spigot | ✅ |

### Minecraft Versions

- ✅ 1.20+
- ⭐ Recommended: **1.21.x**

### Java

- Java 21+

---

# 🚀 Built for Real Servers

Whether you're running a small SMP or a large public network, AntiLagg helps deliver:

- Higher TPS
- Better stability
- Reduced lag
- Smoother gameplay
- Easier server management

---

## ⭐ Enjoying AntiLagg?

If AntiLagg improves your server, consider leaving a ⭐ on Modrinth and sharing your feedback. Every review helps make the plugin even better!
# Config
```yaml
############################################################
# +------------------------------------------------------+ #
# |                       Notes                          | #
# +------------------------------------------------------+ #
############################################################
# ALL RIGHTS RESERVED
# This is the config file for AntiLagg.
# This config was generated for version 1.0.0-10.0.0.
############################################################
# +------------------------------------------------------+ #
# |                    AntiLagg Config                   | #
# +------------------------------------------------------+ #
############################################################

# Made by meric9778

settings:

  # Plugin Prefix
  prefix: "&8[&aAntiLagg&8] "

  # =========================
  # CLEANUP SETTINGS
  # =========================
  cleanup:

    # Enable automatic cleanup
    auto: true

    # Cleanup interval in seconds
    interval-seconds: 300

    # Remove dropped items
    remove-items: true

    # Remove XP orbs
    remove-xp-orbs: true

    # Remove arrows
    remove-arrows: true

    # Remove snowballs
    remove-snowballs: true

    # Remove fireballs
    remove-fireballs: true

  # =========================
  # ENTITY LIMITS
  # =========================
  limits:

    # Max entities per world
    entity-limit: 2000

    # Max entities per chunk
    chunk-entity-limit: 120

  # =========================
  # UPDATE CHECKER
  # =========================
  update-check:

    enabled: true

  # =========================
  # TPS PROTECTION
  # =========================
  tps-protection:

    enabled: true

    warning-threshold: 5.0

    danger-threshold: 4.0

    emergency-threshold: 3.0

  # =========================
  # PERFORMANCE
  # =========================
  performance:

    enable-async-cleaner: true

    optimize-chunks: true

  # =========================
  # TOGGLE SETTINGS (NEW SYSTEM)
  # =========================
  mobspawn: true

  itemdrop: true

  redstone: true

  hopper: true
  ############################################################
  # +------------------------------------------------------+ #
  # |                   AntiLagg Messages                  | #
  # +------------------------------------------------------+ #
  ############################################################

  messages:

    # =========================
    # GENERAL
    # =========================
    no-permission: "&cYou don't have permission!"

    reload: "&aConfiguration reloaded successfully!"

    clear: "&cLag cleanup completed!"

    stats: "&7Plugin is running normally."

    unknown-command: "&cUnknown subcommand."

    # =========================
    # TPS
    # =========================
    tps-warning: "&eServer TPS is dropping!"

    tps-danger: "&cDangerous TPS level detected!"

    tps-emergency: "&4Emergency lag mode activated!"

    # =========================
    # CLEANUP
    # =========================
    cleanup-started: "&7Automatic cleanup started."

    cleanup-finished: "&aCleanup finished successfully."

    # =========================
    # UPDATE CHECKER
    # =========================
    update-found: "&eA new update is available!"

    no-update: "&aYou are using the latest version."
```
