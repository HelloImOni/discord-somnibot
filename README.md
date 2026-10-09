<p align="center">
  <img src="images/logo.png" alt="SomniBot" width="120">
</p>

<h1 align="center">SomniBot for Discord</h1>

<p align="center">
  <b>One Discord bot for your whole server: member gate, moderation, levels, a coin economy, giveaways, tickets, music, automations, and a real-money store with licence keys and a customer portal.</b><br>
  All of it is run from one web dashboard, under your own bot's name and brand.
</p>

<p align="center">
  <a href="FEATURES.md">Features</a> ·
  <a href="STORE.md">The store</a> ·
  <a href="COMMANDS.md">Commands</a> ·
  <a href="#how-it-runs">How it runs</a> ·
  <a href="#contact">Contact</a>
</p>

---

![The SomniBot dashboard Home page](images/home.png)

> This repository is a showcase. It describes what SomniBot does and contains no code,
> downloads or install files. The screenshots come from a real SomniBot install on a
> test server, with **sample names**: the server, members and products have been renamed.

## Why SomniBot

- **Your bot, your brand.** SomniBot is white-label. Members talk to the bot *you* create
  in the Discord Developer Portal, with your name and picture. The bot's messages, the
  store and the customer portal use your brand name, logo, colours and voice. The only
  mention of SomniBot members see is a small "Powered by SomniBot" footer, and you can
  switch that off.
- **One dashboard for everything.** More than 60 dashboard pages, grouped into Overview,
  Real-money store, Server, Moderation, Community, Channels & messages, Coin economy,
  Automation, Problems & history and System. A search box finds any page.
- **You always know what happened.** After every save, a badge says what the running bot
  did with it: Saved, Applying…, Applied, Not applied (with the reason), or "Bot offline,
  applies when it starts". **Admin changes** lists changes made from the dashboard and by
  the bot, with an undo button that says what it will put back.
- **It never surprises you.** The bot never makes a role or channel nobody asked for.
  Big changes are previewed before anything happens in Discord, and SomniBot saves a
  snapshot of every role, channel and permission before each big change it makes.
- **Real money and play money never mix.** The coin economy is a game. No store product
  gives coins, coins can't be turned into real money, and a role someone paid for never
  earns coin income.
- **A team, not just you.** Give staff dashboard roles built from templates (Admin,
  Moderator, Finance, Support) or from scratch, permission by permission. Each person
  sees exactly the pages their permissions cover.

## A tour

### Build your whole server in seven steps

**Server setup** designs your roles (in Admin, Moderator, Member and Cosmetic tiers) and
your categories and channels, shows every change before it happens, then creates them in
Discord. The deploy is safe by default: it only touches roles and channels SomniBot made,
and keeps everything you made yourself. A last step lists exactly what to check with a
test account.

![Server setup at the Verification step](images/server-setup.png)

### More of Discord in one dashboard

Plan forum, media and stage channels, choose access for specific roles and load a
server template. Manage **Server settings**, role icons and gradients, **Events**,
**Emoji, stickers & sounds**, voice moderation and Discord's own polls. The pages
explain Community, boost and other Discord requirements before unavailable choices
can be applied.

**Linked roles** shares product ownership, active licences, verification, level and
days in the server for requirements you choose in Discord. The Launcher checks the
verification setup first. Members can also install the app to their own accounts for
`/portal`, `/license`, `/privacy` and `/mydata` in servers and private chats.

Branded Discord message cards (Components V2) combine text, pictures and controls.
See [all features](FEATURES.md) and the [command list](COMMANDS.md).

![Linked roles: what members can prove, such as owning one specific product](images/linked-roles.png)

![Events: voice, stage and external events listed in Discord](images/events.png)

![Emoji, stickers & sounds: upload, rename and delete, with the slots left](images/expressions.png)

![Server settings: the server's name, pictures, safety settings and welcome screen](images/server-settings.png)

### A member gate that lets the right people in

New members get an Unverified role the moment they join and can only open the rules,
verification and support channels. When they finish your steps (accept the rules, pick
roles, answer Discord's onboarding questions if you want), they get the Verified role
and the rest of the server. Nobody is let in by a timer, and staff can verify or
unverify anyone from Discord or the dashboard.

Every channel gets a purpose (staff-only, 18+, read-only, normal chat), and **See the
server as a role** shows, channel by channel, what someone holding any set of roles can
do, with a fix for anything that doesn't match.

![The member gate on the Onboarding page](images/onboarding.png)

### Moderation, auto-mod and one-click lockdown

Warnings, timeouts, kicks and bans with automatic punishment steps, cases, appeals,
message logging, anti-raid and a starboard. **Lockdown** stops members posting, reacting
and speaking everywhere at once during a raid, and **Unlock** puts every channel back
exactly as it was, even after a restart.

![Moderation settings with Lockdown](images/moderation.png)

Auto-mod rules filter words, links, invites, spam and mass mentions, and **Try a rule
safely** tests a sample message without acting on it. A **Translator** rule rewrites
words instead of blocking them, and never punishes anyone.

![Auto-mod rules](images/automod.png)

### Levels, a full coin economy and giveaways

Message and voice XP, level rewards (roles, coins or items), XP multipliers, rank cards
and leaderboards.

![Levels & XP](images/levels.png)

A whole play-money game: daily, weekly and monthly rewards, work and crime, banks and
robbing, role income, a game shop, a member-to-member market, crafting, farming,
fishing, hunting, digging and mining, adventures, heists, pets, quests, achievements,
trivia, lotteries, predictions and casino-style games. The games pay back about 95% of
what is bet over time, and you can cap bets and daily losses.

![The Economy page](images/economy.png)

Giveaways with a button to enter, optional role and level requirements, and prizes that
can be products from your store.

![Giveaways](images/giveaways.png)

### Tickets with buyer context

Ticket panels with buttons or a dropdown, private threads, intake questions, ticket
types, claim buttons, reminders, auto-close, feedback and transcripts. When a buyer opens
a ticket, staff see their orders and licences right there, and can resend a key or
start a refund from Discord.

![Ticket panels](images/tickets.png)

### A real-money store inside Discord

Sell digital products from `/store`: licence keys, downloadable files, roles and
channels, service tickets, subscriptions and free products. Buyers pay through **your
own PayPal**, or **your own way** (crypto, Cash App, a bank transfer) and you confirm
the payment. Every product passes a Sandbox test purchase before it can go on sale.
Buyers get a branded customer portal for their licences, downloads and orders.

![The Store page](images/store.png)

Read the full tour in **[STORE.md](STORE.md)**.

### Automations

"When this happens, if these conditions hold, do these actions." Triggers cover members,
the store, moderation, messages and activity, tickets and giveaways; actions include
messages and DMs, roles, threads, tickets, granting a product and moderation.

![Automations](images/automations.png)

### Music

Music in your voice channels from YouTube, SoundCloud, Bandcamp, Twitch and Vimeo, with
a DJ role, vote-to-skip, queue limits, audio filters and auto-leave.

![Music](images/music.png)

### Your morning briefing

The **Daily digest** sends you one message a day about everything since the last one:
new members, sales, tickets, requests, failed actions, moderation, bot and music health,
and anything that needs you. Urgent alerts and money alerts still reach you at once.

![Daily digest](images/digest.png)

### Every member's story in one place

**Members** lists everyone with their level, coins and access. Open a member to see
their timeline: joins and leaves, the member gate, role changes the bot made, purchases,
refunds, tickets, moderation cases and appeals, and level-ups.

![Members](images/members.png)

### Your team

![Team](images/team.png)

See everything in **[FEATURES.md](FEATURES.md)**, and every command in
**[COMMANDS.md](COMMANDS.md)**.

## How it runs

SomniBot is self-hosted: it runs on a server (VPS) or on your own PC, and your data stays
in your own database. The **SomniBot Launcher** (Windows and Linux) installs it,
checks everything it needs from Discord, the database, your web address and PayPal,
starts and stops it, updates it, and rolls back to the version before.

![The SomniBot Launcher Home screen](images/launcher-home.png)

- **Safe updates.** Before every install and update the Launcher backs up the database.
  Checks, the download, the backup and database changes happen before anything running
  is touched. If the new version doesn't pass its health check, the Launcher switches
  back on its own.
- **Updates in one step.** When a new version arrives, point the Launcher at its files
  and press **Update**: it checks every file, backs up the database and switches over,
  and the full guide comes with the Launcher, readable offline.
- **Your data, portable.** Export everything (every table and every uploaded file) to
  one file, and import it on another machine or database.
- **Your database, your choice.** A Supabase project, your own Supabase, or a database
  the Launcher runs for you on the same machine.
- **Reachable from anywhere.** The Launcher gives the dashboard a public web address
  with Tailscale Funnel, or you use your own domain. You and your team sign in with
  Discord from any device.

![The Launcher's Updates screen, with rollback](images/launcher-updates.png)

## Contact

Interested in SomniBot, or have a question? Message me on Discord: **@helloimoni**

---

<p align="center"><sub>Discord is a trademark of Discord Inc. SomniBot is not affiliated with or endorsed by Discord.</sub></p>
