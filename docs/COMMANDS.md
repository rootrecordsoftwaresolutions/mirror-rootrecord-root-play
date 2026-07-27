# Commands and permissions

## Commands

| Command | Description | Permission | Usage |
|---------|-------------|------------|-------|
| `/rank` | View or buy your player rank | `` | `/<command> [list/buy/info]` |
| `/rootranks` | Admin reload for Root-Ranks | `rootranks.reload` | `/<command> reload` |
| `/playtime` | Your playtime, milestones, and leaderboard | `` | `/<command> [player/top]` |
| `/vote` | Server list vote links | `` | `/<command>` |
| `/rootrewards` | Admin reload for Root-Rewards | `rootrewards.reload` | `/<command> reload` |
| `/rules` | Show RootMC server rules | `` | `/<command>` |
| `/cmds` | Paginated list of in-game commands | `` | `/<command> [page/next/prev]` |
| `/discord` | RootMC Discord invite and link your game + Discord profile | `` | `/<command>` |
| `/map` | Open the RootMC BlueMap in your browser | `` | `/<command>` |
| `/feedback` | Send feedback to staff (posted to Discord) | `` | `/<command> <message>` |
| `/cmdtest` | Command onboarding â€” test commands, earn up to 1000 G, stop reminders | `` | `/<command> [list/try <key>/report <key> [note]]` |

## Permissions

| Permission | Description | Default |
|------------|-------------|---------|
| `rootranks.use` | View and purchase player ranks | `true` |
| `rootranks.buy` | Purchase the next player rank | `true` |
| `rootranks.reload` | Reload root-ranks.yml | `op` |
| `rootranks.bypass` | Skip gold cost when buying ranks (testing) | `op` |
| `rootrewards.use` | View your playtime and receive milestone rewards | `true` |
| `rootrewards.playtime.others` | View another player's playtime with /playtime <name> | `true` |
| `rootrewards.playtime.top` | View the playtime leaderboard | `true` |
| `rootrewards.vote` | Receive vote gold | `true` |
| `rootrewards.reload` | Reload root-rewards.yml | `op` |
| `roothelp.rules` | Use /rules | `true` |
| `roothelp.commands` | Use /cmds and /commands | `true` |
| `roothelp.discord` | Use /discord | `true` |
| `roothelp.map` | Use /map | `true` |
| `roothelp.feedback` | Use /feedback | `true` |
| `roothelp.cmdtest` | Use /cmdtest command onboarding | `true` |

