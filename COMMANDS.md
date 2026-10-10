# Commands

[← Back to the overview](README.md) · [Features](FEATURES.md) · [The store](STORE.md)

SomniBot has **91 built-in slash commands** and **5 right-click commands**. Switching a feature
off in the dashboard also hides its commands, and `/help` shows each member only the
commands they can use. Each command name counts once; subcommands and server-specific
custom commands are not added to this total.

## Getting started

| Command | What it does |
|---|---|
| `/help` | See the commands you can use here |
| `/tutorial` | Start or resume the server tutorial |
| `/setup` | Show where to manage installation and server setup |

## Member gate and moderation

| Command | What it does |
|---|---|
| `/verify` | Let a member into the server without the verification steps |
| `/unverify` | Send a member back to the verification steps |
| `/lockdown` | Stop members posting everywhere, and undo it (start, end, status) |
| `/warn` | Warn a member (they get a DM with the case number and how to appeal) |
| `/mute` | Time a member out (Discord timeout, up to 28 days) |
| `/kick` | Remove a member from the server (they can rejoin with an invite) |
| `/ban` | Ban a member or user ID from the server |
| `/pardon` | Undo a case: lifts a timeout or ban and tells the member |
| `/infractions` | Show a member's moderation cases |
| `/purge` | Delete recent messages from this channel (logged in the moderation log) |
| `/voice-mod` | Move, mute, deafen or disconnect a member in voice |
| `/appeal` | Ask the moderators to reconsider a warning, timeout, kick or ban (submit, status) |

## Real-money store

| Command | What it does |
|---|---|
| `/store` | Buy products with real money. The game shop is /shop. |
| `/portal` | Open your purchases: downloads, activated PCs and orders |

## Tickets

| Command | What it does |
|---|---|
| `/ticket` | Close the ticket you're in |
| `/ticket-staff` | Staff tools for the ticket you're in (claim, add, remove, transcript, buyer) |

## Levels and profiles

| Command | What it does |
|---|---|
| `/rank` | View or customize rank cards |
| `/leaderboard` | View the server XP leaderboard |
| `/xp` | Admin XP management commands (add, remove, set, reset) |
| `/profile` | See your profile, or another member's |
| `/title` | Set your display title |
| `/bio` | Set your profile bio |
| `/badges` | View all achievements and your progress |

## Coin economy (play money)

| Command | What it does |
|---|---|
| `/balance` | See your play-money wallet and bank |
| `/daily` | Claim your daily play-money reward |
| `/weekly` | Claim your weekly play-money reward |
| `/monthly` | Claim your monthly play-money reward |
| `/work` | Work a shift to earn play money |
| `/crime` | Try a crime for a big payout, or pay a fine if caught |
| `/beg` | Beg for a little spare play money |
| `/search` | Search around for dropped play money |
| `/collect-income` | Collect the play money your roles earn |
| `/deposit` | Move play money from your wallet into your bank (safe from robbers) |
| `/withdraw` | Move play money from your bank into your wallet |
| `/pay` | Send play money to another member |
| `/rob` | Try to steal from another member's wallet |
| `/passive` | Turn passive mode on or off (nobody can rob you, and you can't rob anyone) |
| `/timers` | See which play-money cooldowns are running and when they are ready |
| `/shop` | Spend play money on game items (not real money). The real-money store is /store. |
| `/buy` | Buy an item from the shop with play money |
| `/sell` | Sell items from your inventory to the shop for play money |
| `/inventory` | See the items you own |
| `/use` | Use an item: open a lootbox, heal on an adventure, and more |
| `/market` | Buy and sell items with other members (list, browse, buy, my-listings, cancel) |
| `/craft` | Craft an item from the materials in your inventory |
| `/recipes` | See every crafting recipe and which ones you can make now |
| `/hunt` | Go hunting for meat, hides and rare finds (a hunting tool finds rarer ones) |
| `/dig` | Dig for clay, fossils and buried treasure (a shovel finds rarer ones) |
| `/mine` | Mine for stone, ore and gems (a pickaxe finds rarer ones) |
| `/fish` | Go fishing (bare hands work; a rod catches rarer fish) (cast, sell, collection, leaderboard) |
| `/farm` | Grow crops from seeds and sell the harvest (play money) (view, plant, water, harvest, fertilize) |
| `/adventure` | Go on a story adventure for play money and loot |
| `/heist` | Plan and execute heists with your crew (start, join, status) |
| `/pet` | Raise a pet: feed it, play, train and battle (view, buy, feed, play, train, rename, battle, prestige) |
| `/quests` | View and manage your quests (view, claim) |
| `/prestige` | Reset your wallet and bank to 0 for a permanent earning bonus |
| `/lottery` | Buy lottery tickets or view the current drawing |
| `/economy-leaderboard` | See the richest members (play money) |
| `/economy-admin` | Staff: give or take play money and items (give-money, take-money, give-item, take-item) |

## Games

| Command | What it does |
|---|---|
| `/coinflip` | Flip a coin: double or nothing |
| `/slots` | Spin the slots: three of a kind pays 12× to 150×, a pair gives half your bet back |
| `/dice` | Roll two dice against the house: higher total wins, a tie gives half your bet back |
| `/blackjack` | Play blackjack: a blackjack pays 3:2, the dealer wins ties on 17 or 18 |
| `/scratch` | Scratch 9 symbols: 3 of a kind gives half your bet back, 4 pays 2×, 5 or more pays 4× |
| `/guess` | Guess a number from 1 to 100: exact pays 25×, within 5 pays 5×, within 10 pays 2× |
| `/rps` | Play rock, paper, scissors for play money |
| `/highlow` | Guess if the next number is higher or lower (free) |
| `/trivia` | Start a trivia round |

## Community

| Command | What it does |
|---|---|
| `/giveaway` | Manage giveaways (start, end, reroll, pause, resume, list) |
| `/poll` | Create and manage polls (create, close) |
| `/predict` | Bet play money on what will happen (create, bet, resolve) |
| `/voice` | Control your temporary voice channel (lock, unlock, limit, name, permit, deny, ban, claim) |

## Music

| Command | What it does |
|---|---|
| `/play` | Play a song or add it to the queue |
| `/np` | Show the song that is playing |
| `/queue` | View the current music queue |
| `/skip` | Skip the song (your own skips at once; someone else's needs a listener vote) |
| `/pause` | Pause or resume playback |
| `/stop` | Stop playback, clear the queue, and leave voice |
| `/volume` | Set the playback volume |
| `/loop` | Set loop mode |
| `/shuffle` | Shuffle the songs coming up in the queue |
| `/seek` | Jump to a point in the song that is playing |
| `/remove` | Remove a song from the queue |
| `/move` | Move a song you added to another place in the queue |
| `/filter` | Change how the music sounds (DJs only) |

## Privacy

| Command | What it does |
|---|---|
| `/privacy` | What this bot keeps about you, and how to get a copy or erase it |
| `/mydata` | Export all your data from this server as a JSON file |
| `/forgetme` | Erase or anonymize your account data from this server (irreversible) |

## Commands on your own account

After the Launcher's **Install to a member's account** check, install the app to your
Discord account to use `/portal`, `/privacy` and `/mydata` in servers,
DMs with the bot and other private chats. Answers concern a server you belong to
that the bot looks after; when there is more than one, a private server picker
chooses which one. All other commands stay server-only.

## Right-click commands

| Command | What it does |
|---|---|
| **View Profile** | Staff: a member's level, messages, join date, roles and moderation cases |
| **View Purchases** | Admins: a member's purchases and total spent |
| **Warn User** | Staff: warn a member |
| **Create Ticket** | Open a ticket from a message |
| **Report Message** | Report a message, with a reason only the staff team sees |

Server owners can also add their own slash commands with **Custom commands** on the
dashboard.

---

[← Back to the overview](README.md) · [Features](FEATURES.md) · [The store](STORE.md)
