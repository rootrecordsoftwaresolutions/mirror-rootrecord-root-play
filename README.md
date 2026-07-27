# Root-Play

RootMC play progression â€” ranks, rewards, and help

| Field | Value |
|-------|-------|
| **Folder / artifact** | `root-play` |
| **Version** | `1.7.2` |
| **Bukkit name** | `Root-Play` |
| **Paper API** | `26.1` |
| **Author** | Root Record |
| **Website** | https://rootmc.net |
| **Main class** | `com.rootrecord.minecraft.rootplay.RootPlayPlugin` |

## Install

1. Install **[Root-Core](https://github.com/RootRecord/root-core)** first (license/cloud spine for the suite).
2. Download `root-play-1.7.2.jar` from [Releases](https://github.com/RootRecord/root-play/releases) or the [plugin catalog](https://rootmc.net/plugins/).
3. Remove any older `root-play-*.jar` from `plugins/`.
4. Drop the new jar into `plugins/` and restart (or use Root-Core suite updater when this plugin is on the public manifest).
5. Shared config and secrets live under `plugins/RootMC/` (not a per-plugin data folder unless documented otherwise).

### Dependencies

| Type | Plugins |
|------|---------|
| Hard depend | _none_ |
| Soft depend | Root-Core, Root-Economy, Root-Essentials, Root-Perms, Vault, Root-Claims, RootMC, Root-Haste, PlaceholderAPI, NuVotifier, VotifierPlus |

## Configuration

Most RootMC plugins store operator YAML under `plugins/RootMC/`. After first boot, check that folder for new keys. Never commit live `cloud.yml` / database passwords to git.

## Build (monorepo)

Primary compilation is the RootMC Gradle workspace (not this standalone repo alone):

```bat
cd "D:\.1 Work Stations\RootMC\Plugin Building\Minecraft"
.\build-with-server-jdk.bat :plugins:root-play:jar
```

This repository mirrors sources for GitHub browsing and release distribution. It depends on `rootrecord-common` inside the monorepo.

## Commands (summary)

| Command | Description |
|---------|-------------|
| `/rank` | View or buy your player rank |
| `/rootranks` | Admin reload for Root-Ranks |
| `/playtime` | Your playtime, milestones, and leaderboard |
| `/vote` | Server list vote links |
| `/rootrewards` | Admin reload for Root-Rewards |
| `/rules` | Show RootMC server rules |
| `/cmds` | Paginated list of in-game commands |
| `/discord` | RootMC Discord invite and link your game + Discord profile |
| `/map` | Open the RootMC BlueMap in your browser |
| `/feedback` | Send feedback to staff (posted to Discord) |
| `/cmdtest` | Command onboarding â€” test commands, earn up to 1000 G, stop reminders |

Full command and permission tables: [docs/COMMANDS.md](docs/COMMANDS.md).

## Links

| Resource | URL |
|----------|-----|
| Website | https://rootmc.net |
| Plugin catalog | https://rootmc.net/plugins/ |
| This plugin page | https://rootmc.net/plugins/root-play/ |
| Suite wiki | https://rootmc.net/wiki/plugins/ |
| Player wiki | https://rootmc.net/wiki/player/ |
| Constitution | https://rootmc.net/wiki/constitution/ |
| Economy guide | https://rootmc.net/wiki/economy/ |
| Developer keys | https://rootmc.net/developer/keys/ |
| Manifest | https://rootmc.net/plugins/manifest.json |
| Play | `play.rootmc.net` |
| Live map | https://map.rootmc.net |
| API | https://api.rootmc.net |
| Discord | https://discord.gg/rFFQYrNaqS |
| GitHub (this repo) | https://github.com/RootRecord/root-play |
| Releases | https://github.com/RootRecord/root-play/releases |

**Discord:** RootMC community - join for support, announcements, and governance: https://discord.gg/rFFQYrNaqS


## Documentation in this repo

- [docs/COMMANDS.md](docs/COMMANDS.md) - commands and permissions from `plugin.yml`
- [docs/LINKS.md](docs/LINKS.md) - canonical RootMC web and Discord links
- [CHANGELOG.md](CHANGELOG.md) - version history seed

## License

Copyright Root Record. All rights reserved. Source is published for transparency; no license to copy, modify, or redistribute is granted unless Root Record provides written permission.

