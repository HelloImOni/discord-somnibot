# Commands

[← Back to the overview](README.md) · [Features](FEATURES.md) · [The store](STORE.md)

SomniBot has **84 built-in slash commands** and **8 right-click commands**. Switching a
feature off in the dashboard also hides its commands, and `/help` shows each member only
the commands they can use. Each command name counts once; subcommands and server-specific
custom commands are not added to this total.

Four of the 84 are the age-restricted picture commands of **After Dark images**. They
only work in age-restricted channels for members who hold your 18+ role, and they are
not listed below.

Discord allows 100 slash commands per server, so related commands are grouped under one
name. For example, work is `/earn work`, the daily reward is `/claim daily`, and the game
shop is `/shop view`. The tables below show the commands the way members type them.
Anything in brackets is a subcommand. If you remember the old names, see
[where things went](#where-things-went).

## Getting started

| Command | What it does |
|---|---|
| `/help` | See the commands you can use here |
| `/ask` | Ask the server's assistant a question in plain words |
| `/tutorial` | Start or resume the server tutorial |
| `/setup` | Show where to manage installation and server setup |
| `/dashboard` | Open the web dashboard (owner and administrators only) |
| `/status` | Check whether the bot is working normally |
| `/language` | Choose the language SomniBot uses for you, or Automatic to follow Discord |

## Member gate and moderation

| Command | What it does |
|---|---|
| `/verify` | Let a member into the server without the verification steps |
| `/unverify` | Send a member back to the verification steps |
| `/lockdown` | Stop members posting everywhere, and undo it (start, end, status, panic-start, panic-undo) |
| `/warn` | Warn a member (they get a DM with the case number and how to appeal) |
| `/mute` | Time a member out (Discord timeout, up to 28 days) |
| `/kick` | Remove a member from the server (they can rejoin with an invite) |
| `/ban` | Ban a member or user ID from the server |
| `/pardon` | Undo a case: lifts a timeout or ban and tells the member |
| `/infractions` | Show a member's moderation cases |
| `/purge` | Delete recent messages from this channel (logged in the moderation log) |
| `/voice-mod` | Move, mute, deafen or disconnect a member in voice (move, mute, deafen, disconnect) |
| `/appeal` | Ask the moderators to reconsider a warning, timeout, kick or ban (submit, status) |

`/lockdown panic-start` applies the emergency lockdown you set up in advance and opens an
incident report for staff; `/lockdown panic-undo` puts everything back and closes it.

## Real-money store

| Command | What it does |
|---|---|
| `/store` | Buy products with real money. The game shop is `/shop view`. |
| `/portal` | Open your purchases: downloads, activated PCs and orders |

## Tickets

| Command | What it does |
|---|---|
| `/ticket` | Close the ticket you're in (close) |
| `/ticket-staff` | Staff tools for the ticket you're in (claim, unclaim, reopen, add, remove, transcript, buyer, status, bill, reply, priority, assign, rename, move) |

`/ticket-staff reply` inserts a saved reply, `priority` sets how urgent the ticket is (low,
normal, high or urgent) and `move` moves it to another ticket type on the same panel.

## Levels and profiles

| Command | What it does |
|---|---|
| `/rank` | View or customize rank cards (view, customize) |
| `/leaderboard` | See the server leaderboards: XP, messages, voice time, coins, trivia, fish, achievements, quests, wealth and more, for all time, a week, a month or a season |
| `/xp` | Admin XP management commands (add, remove, set, reset) |
| `/profile` | Your profile card, badges and season progress (view, title, bio, customize, fields, badges, collections) |
| `/profile season` | Your season pass (view, tiers, quests, claim, daily, history) |
| `/starboard` | See the most-starred messages and members of this server (top, members, member) |
| `/birthday` | Share your birthday and see the next ones in this server (set, timezone, hide, clear, view, upcoming) |

## Coin economy (play money)

Everything here uses play money, never real money.

**Earning, claiming and banking**

| Command | What it does |
|---|---|
| `/earn` | Earn play money, rob a member or set passive mode (work, crime, beg, search, job, rob, passive) |
| `/claim` | Claim your rewards and role income, or check your timers (daily, weekly, monthly, income, timers) |
| `/bank` | Move play money between your wallet, bank and other members, or see your wallet history (deposit, withdraw, info, loan, pay, history) |
| `/balance` | See your play-money wallet and bank, plus any open loan and your net worth |
| `/economy-leaderboard` | See the richest members (play money) |
| `/prestige` | Reset your wallet and bank to 0 for a permanent earning bonus |
| `/economy-admin` | Staff: give or take play money and items (give-money, take-money, give-item, take-item) |

**Shop, items and crafting**

| Command | What it does |
|---|---|
| `/shop` | Browse the shop, buy and sell, and manage assets (view, buy, sell, prestige) |
| `/inventory` | See the items you own |
| `/use` | Use an item: open a lootbox, heal on an adventure, hatch a pet egg and more |
| `/craft` | Craft items and browse recipes (item, recipes, boosters) |
| `/gather` | Hunt, dig, mine, chop or forage, see your skills and visit the museum (hunt, dig, mine, chop, forage, skills, museum, log) |
| `/market` | Buy and sell items with other members (list, browse, buy, my-listings, cancel, auction, auctions, bid, auction-cancel, trade, wanted-post, wanted, wanted-fill, wanted-cancel, price, stall) |

**Stocks, properties and cards**

| Command | What it does |
|---|---|
| `/shop stocks` | Trade fictional stocks and crypto with play money (market, buy, sell, portfolio, leaderboard, recover) |
| `/shop property` | Buy, improve and collect income from houses and businesses (catalog, portfolio, decorations, buy, claim, upgrade, decorate) |
| `/shop cards` | Roll, claim and trade collectible cards, for play only (roll, claim, collection, sets, trade, trades, accept, decline) |

**Farming, fishing, pets and quests**

| Command | What it does |
|---|---|
| `/farm` | Grow crops and raise farm animals (view, plant, water, harvest, fertilize, upgrade, cook, eat, adopt, barn, feed, collect, autosell, log) |
| `/fish` | Go fishing (cast, sell, collection, leaderboard, records, conditions, autosell, aquarium, display, remove) |
| `/pet` | Raise a pet: feed it, play, train and battle other members' pets; a battle's entry fee is the pot and the winner takes it (view, buy, feed, play, train, rename, battle, prestige, evolve, switch, collection, expedition) |
| `/quests` | View and manage your quests (view, claim, history) |
| `/badges` | View all achievements and your progress |

**Adventures, heists, clans and the RPG**

| Command | What it does |
|---|---|
| `/adventure` | Go on a story adventure for play money and loot, alone or with a party of 2 to 4 (start, log, party-list, party-create, party-join, party-class, party-scene, party-begin, party-vote, party-resolve) |
| `/heist` | Plan and execute heists with your crew (start, join, status, targets, crew-start, crew-role, crew-join, crew-status, crew-cancel, crew-effort, crew-advance) |
| `/raid` | Fight the server's weekly boss (status, leaderboard, claim) |
| `/clan` | Create, join and grow a member clan (create, view, list, join, quests, rally, places, channel, disband, plus member, bank and war groups) |
| `/rpg` | Play the server RPG (profile, class, skill, equip, bestiary, collection, salvage, plus dungeon, arena and boss groups) |

`/clan member` covers invite, accept, leave, kick, promote, demote and transfer.
`/clan bank` covers view, deposit and withdraw. `/clan war` covers challenge, accept,
decline, status and leaderboard. `/rpg dungeon` has start and resume, `/rpg arena` has
challenge, and `/rpg boss` has status and claim.

## Games and Activities

| Command | What it does |
|---|---|
| `/casino` | Play-money games, trivia and the lottery (roulette, crash, race, duel, perks, paytable, records, coinflip, slots, rps, dice, blackjack, highlow, scratch, guess, trivia, lottery) |
| `/casino coinflip` | Flip a coin: double or nothing |
| `/casino slots` | Spin the slots: three of a kind pays 12× to 150×, a pair gives half your bet back, and you can pick a reel theme |
| `/casino dice` | Roll two dice against the house: higher total wins, a tie gives half your bet back |
| `/casino blackjack` | Play blackjack: a blackjack pays 3:2, the dealer wins ties on 17 or 18, and you can split |
| `/casino scratch` | Scratch 9 symbols: 3 of a kind gives half your bet back, 4 pays 2×, 5 or more pays 4× |
| `/casino guess` | Guess a number from 1 to 100: exact pays 25×, within 5 pays 5×, within 10 pays 2× |
| `/casino rps` | Play rock, paper, scissors for play money |
| `/casino highlow` | Call the next number from 1 to 100 higher or lower, climb the ladder up to 12× and cash out any time |
| `/casino roulette` | Bet on a colour, odd or even, low or high, a dozen or one exact number |
| `/casino crash` | Watch the multiplier climb and cash out before it crashes |
| `/casino race` | Back one of five racers: the favourite pays little, the long shot pays a lot |
| `/casino duel` | Challenge a member to an equal-bet duel decided by a fair coin |
| `/casino trivia` | Trivia rounds, daily questions and trivia nights (start, daily, night, join, scoreboard) |
| `/casino lottery` | Buy lottery tickets or view the current drawing (buy, view) |
| `/games` | Multiplayer and board games: blackjack tables, Texas Hold'em, bingo, tic-tac-toe, connect four, chess, hangman, Wordle, word chain, a guess race and a music quiz (create, join, move, status, music-prepare, music-round, music-answer) |
| `/arcade` | Play real-time games inside Discord: a boss raid arena, a dungeon run, a derby, party adventures, blackjack, Texas Hold'em and bingo (play, quick) |
| `/party` | Party games: truth or dare, would you rather, never have I ever (truth, dare, tod, wyr, nhie) |

## Community

| Command | What it does |
|---|---|
| `/giveaway` | Manage giveaways (start, end, reroll, pause, resume, cancel, list) |
| `/poll` | Create and manage polls (create, close, and saved poll templates) |
| `/predict` | Bet play money on what will happen (create, bet, resolve, cancel) |
| `/voice` | Control your temporary voice channel (lock, unlock, limit, name, permit, deny, ban, claim, handover) |
| `/suggest` | Suggest an idea for this server |
| `/confess` | Post a confession anonymously (the reply is private) |
| `/extras` | Voice, pictures and channel games (voice tts, sound and quiz; image avatar, quote, meme and generate; channel status; event status, quests and claim) |

## Social and everyday tools

| Command | What it does |
|---|---|
| `/info` | Look up a member, a picture or this server (user, avatar, server, invites) |
| `/fun` | Little games: 8-ball, choose, ship and rate |
| `/action` | Hug, pat, kiss, slap, cuddle or bonk someone with an anime GIF |
| `/marry` | Marry another member, or end it (propose, divorce, status) |
| `/rep` | Thank a member with a rep point (give, view, top) |
| `/remind` | Reminders: set one, repeat one, list them or cancel one (set, repeat, list, cancel) |
| `/afk` | Let people know you are away (set, clear) |
| `/time` | Set your time zone, or see the time for someone (set, for) |
| `/tag` | Saved snippets: show one, or (staff) create, edit and delete them (show, list, create, edit, delete) |
| `/todo` | Your private to-do list (add, list, done, clear) |
| `/sticky` | A note that stays at the bottom of a channel (set, clear) |

## Music

| Command | What it does |
|---|---|
| `/play` | Play a song or add it to the queue |
| `/skip` | Skip the song (your own skips at once; someone else's needs a listener vote) |
| `/music` | The rest of the music controls (stop, queue, np, volume, loop, shuffle, seek, remove, move, pause, filter, autoplay, previous, skipto, lyrics, search, 24-7, playlist) |
| `/music search` | Search for a song and choose one from a pick list |
| `/music lyrics` | Show lyrics for the song playing now |
| `/music 24-7` | Keep the bot in voice between songs (DJs only) |
| `/music playlist` | Save and play server or personal playlists (save, play, list, delete) |
| `/music previous` | Play the song that played before this one again (DJs, or the member who asked for it) |
| `/music skipto` | Jump ahead to a song in the queue (your own songs at once; others need a listener vote) |
| `/music autoplay` | Keep playing related songs when the queue runs out (DJs only) |
| `/music filter` | Change how the music sounds (DJs only) |
| `/music remove` | Remove a song from the queue (your own, or any if you are a DJ) |
| `/music move` | Move a song you added to another place in the queue |

`/music stop`, `queue`, `np`, `volume`, `loop`, `shuffle`, `seek` and `pause` do what
their names say.

## Privacy

| Command | What it does |
|---|---|
| `/privacy` | What this bot keeps about you, and how to get a copy or erase it |
| `/mydata` | Export all your data from this server as a JSON file |
| `/forgetme` | Erase or anonymize your account data from this server (irreversible) |

## Where things went

| If you remember | Type |
|---|---|
| `/work`, `/crime`, `/beg`, `/search`, `/rob`, `/passive` | `/earn work`, `/earn crime`, `/earn beg`, `/earn search`, `/earn rob`, `/earn passive` |
| `/daily`, `/weekly`, `/monthly`, `/collect-income`, `/timers` | `/claim daily`, `/claim weekly`, `/claim monthly`, `/claim income`, `/claim timers` |
| `/deposit`, `/withdraw`, `/pay` | `/bank deposit`, `/bank withdraw`, `/bank pay` |
| `/shop`, `/buy`, `/sell` | `/shop view`, `/shop buy`, `/shop sell` |
| `/hunt`, `/dig`, `/mine` | `/gather hunt`, `/gather dig`, `/gather mine` |
| `/craft`, `/recipes` | `/craft item`, `/craft recipes` |
| `/coinflip`, `/slots`, `/dice`, `/blackjack`, `/highlow`, `/scratch`, `/guess`, `/rps` | the same names after `/casino` |
| `/trivia`, `/lottery` | `/casino trivia`, `/casino lottery` |
| `/queue`, `/np`, `/volume`, `/loop`, `/pause`, `/stop` and the other music commands | the same names after `/music` (`/play` and `/skip` still work on their own) |
| `/title`, `/bio` | `/profile title`, `/profile bio` |
| `/season` | `/profile season` |

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
| **Translate** | Read a message in your own language (only you see it) |
| **Draft a reply** | Staff, in a ticket: the assistant drafts a reply you can post or edit |
| **Translate my reply** | Staff, in a ticket: post your reply in the member's language |

Server owners can also add their own slash commands with **Custom commands** on the
dashboard.

---

[← Back to the overview](README.md) · [Features](FEATURES.md) · [The store](STORE.md)
