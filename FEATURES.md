# Everything SomniBot does

[← Back to the overview](README.md) · [The store](STORE.md) · [Commands](COMMANDS.md)

The screenshots on this page come from a real SomniBot install with sample names.

- [Your brand, everywhere](#your-brand-everywhere)
- [Setting up your server](#setting-up-your-server)
- [Server settings and role appearance](#server-settings-and-role-appearance)
- [Events and stages](#events-and-stages)
- [Emoji, stickers and sounds](#emoji-stickers-and-sounds)
- [Linked roles](#linked-roles)
- [Member gate and verification](#member-gate-and-verification)
- [Channel permissions](#channel-permissions)
- [Welcome and goodbye](#welcome-and-goodbye)
- [Moderation](#moderation)
- [Levels and XP](#levels-and-xp)
- [The coin economy](#the-coin-economy)
- [Giveaways, polls and predictions](#giveaways-polls-and-predictions)
- [Tickets](#tickets)
- [Music](#music)
- [Automations](#automations)
- [Channels and messages](#channels-and-messages)
- [Staying in control](#staying-in-control)
- [Owner alerts and the daily digest](#owner-alerts-and-the-daily-digest)
- [Your team](#your-team)
- [Privacy](#privacy)

---

## Your brand, everywhere

SomniBot is white-label. Members talk to the bot application you create, with the name
and picture you give it. The **Branding** page sets:

- your **brand name**, used in the bot's messages, the store and the customer portal;
- a **logo**, a **header image** and a **background** for the customer portal;
- a **primary colour** and an **accent colour**. Errors, warnings and successes always
  stay red, amber and green, so members read them the same way in every server;
- the **voice style** of the bot's stock lines (refusals, errors, welcomes, level-ups and
  giveaway wins). Your own custom messages are never changed;
- the **"Powered by SomniBot"** footer credit, which you can switch off.

A **live preview** shows your saved messages in your brand. The dashboard is for you and
your team only: the bot's messages to members never mention it. Members use the
customer portal for purchases and a separate verification page for Linked roles.

Discord message cards (Components V2) combine branded text, pictures, sections and
buttons across store receipts, verification, moderation, community, economy and
music messages. Saved classic message templates keep their format until edited;
Discord's native polls use Discord's own voting interface.

## Setting up your server

**Server setup** designs the roles and channels SomniBot looks after, in seven steps:

1. **Bot status**: checks the bot is in your server and ranked high enough.
2. **Roles**: in four tiers (Admin, Moderator, Member and Cosmetic), with your names and
   colours.
3. **Channels**: categories and channels, each with who can open it (verified members,
   members before verification, or staff only).
4. **Review**: every change before it happens. By default it only changes roles and
   channels SomniBot made before, and keeps everything you made yourself.
5. **Deploy**: the bot creates everything and the page follows its progress.
6. **Verification**: exactly what to look at in Discord, ideally with a test account.
7. **Go live**.

Run it again any time to change the plan, or start over with an empty plan. Nothing
changes in Discord until you deploy.

The channel editor includes text, announcement, forum, media, voice and stage
channels. Forum settings include tags, default reaction, layout, guidelines and
post slowmode; voice settings include bitrate, region, video quality and member
limits. Community and boost requirements are shown where needed. **Only these roles**
lets you choose channel access using roles from your plan or existing Discord roles,
such as Server Booster. Missing roles appear as Review problems before deployment.
**Load a server template** imports a template into the plan; it changes nothing in
Discord until you deploy. Sync and snapshots include these settings.

![Server setup](images/server-setup.png)

## Server settings and role appearance

**Server settings** controls the server's name and images, description, verification
and media filtering, notifications, AFK channel and timeout, system messages, safety
alerts, welcome screen, boost progress bar, Community, Discovery and widget. It
reads Discord's current values, explains unavailable features and records reversible
changes in **Admin changes**. The widget warns before exposing online members'
names and pictures; vanity URLs are read-only here.

Role appearance includes one emoji or a PNG/JPEG icon up to 256 KB, two-colour
gradients and holographic colours. Icons need boost level 2; enhanced colours need
boost level 3. Unavailable looks are explained while the rest of the role can still
be applied. The saved plan, Sync and snapshots keep the role's icon and colours.

**Give a role to members who wear this server's tag** adds or removes the chosen role
as members change their tag. It only takes back roles the bot gave for that tag;
roles assigned by hand stay in place. Default Member-tier permissions include
Activities and external sounds, applied through a Server setup deploy.

## Events and stages

**Events** creates, edits, starts, ends and cancels Discord scheduled events in voice,
on a stage or at an external location, with images, recurrence and interested counts.
Starting a stage event opens the stage, with a notification choice; ending it closes
the stage. Events made by hand in Discord are listed too and left alone unless you
edit them. Giveaways and scheduled messages can also appear as Discord events.
Automations can respond to an event starting or ending and a member marking interest.

## Emoji, stickers and sounds

**Emoji, stickers & sounds** uploads, renames and deletes the server's expressions,
showing usage against Discord's limits. Deleting asks for confirmation and explains
that it cannot be undone.

## Linked roles

The Launcher's **Linked Roles** check verifies the public verification address,
registered member facts and Discord sign-in redirect. Until the setup is ready, the
page shows what is missing and keeps new facts from being switched on.

On **Linked roles**, choose which facts SomniBot shares: owning any or a specific
product, an active licence, level, verification and days in the server. In Discord's
**Server Settings → Roles → Links**, choose what each role requires, including its
minimum level or days. Members link through Discord and sign in with their account;
the bot refreshes their values as purchases, licences and membership change.

The Launcher also checks **Install to a member's account**. This makes `/portal`,
`/license`, `/privacy` and `/mydata` available in servers and private chats. A private
server picker chooses which shared server an answer concerns when there is more
than one. Every other command stays server-only.

## Member gate and verification

New members get the **Unverified** role when they join and can open only the rules,
verification and support channels. When they finish your steps they get the **Verified**
role and the rest of the server. You choose the steps:

- the rules step: SomniBot's **I accept** button, Discord's Rules Screening, or a role
  members pick;
- roles they must pick from your reaction-role or button-role messages;
- Discord's own onboarding questions, which SomniBot saves to Discord and reads back.
  You can also give a role for an onboarding answer.

New members get a DM with your opening line and numbered steps linking to your real
channels; if their DMs are closed, the note is posted in a channel instead. Members who
leave and come back go through the steps again, and you choose whether they get back the
roles and level rewards they had.

The **Member gate** box shows whether the gate is on, how many members are waiting and
verified, and every problem the bot's last check found, with **Check again** and **Repair
setup**. Turning the gate on or off shows exactly what will happen first, and members
already in the server keep their access.

**Nobody is let in by a timer.** Staff let someone in with `/verify`, or with **Verify** on
the **Members** page.

![The member gate](images/onboarding.png)

## Channel permissions

Every channel has a purpose, and members get exactly what it allows: staff and log
channels are staff-only, age-restricted channels open only to members who turn on 18+,
rules, announcements, welcome and bot channels are read-only, and chat and voice are
normal. Nothing changes until you preview and confirm, and every change can be undone.

- **Looks private: lock it?** lists channels every member can open today that look like
  staff channels.
- The **18+ role** opens age-restricted channels; members turn it on themselves with a
  button in the verification channel.
- **See the server as a role**: pick one or more roles and see, channel by channel, what
  someone holding them can do, with a fix for anything that doesn't match.

## Welcome and goodbye

- A **welcome message** with variables (`{user}`, `{user.name}`, `{server}`,
  `{memberCount}`, `{memberNumber}`, `{level}`) and a **branded welcome card** with the
  member's avatar and name, or message only, or card only.
- A **welcome DM** with a numbered "where to start" list linking your real channels.
- **Automatic roles** for new members, given once they get access.
- A **goodbye message**, with an optional goodbye card and the time they spent in the
  server.

The welcome runs once per member, when they get access: after the member gate if it's
on, or when they join if it's off.

## Moderation

- `/warn`, `/mute` (a Discord timeout), `/kick`, `/ban`, `/purge`, `/infractions` and
  `/pardon`, plus **Warn User** on the right-click menu.
- **Automatic punishments**: what happens as a member collects warnings. Warnings expire
  after the number of days you set, but stay in the history.
- **Cases**: every warning, timeout, kick and ban, with action or pardon.
- **Appeals**: members appeal with `/appeal`; you approve or deny on the dashboard.
- **Punishments and purchases**: a ban suspends a buyer's purchases instead of revoking
  them, and gives them back if the ban is pardoned. After a kick, purchases are kept and
  roles come back when they rejoin.
- **Message logging** of edits and deletes, **auto-moderation** in Watch only or Enforce
  mode, and a **starboard**.
- **Anti-raid**: watches for a flood of joins, acts, and can lift its raid bans
  afterwards.
- **Lockdown**: stops everyone with the Verified role posting, reacting, starting threads
  and speaking in every channel at once. Staff keep posting where their own roles allow,
  and the owner and Administrators are never locked. Optionally pause invites too.
  **Unlock** puts every channel back exactly as it was, even after a restart.
- **Invites**: who invites whom, how many joined, stayed or left, and pause, reopen,
  delete or make invites from the dashboard.

![Moderation settings](images/moderation.png)

**Auto-mod rules** filter words (exact, wildcard or a custom pattern), links, invites,
spam and mass mentions. **Try a rule safely** checks a sample message against your saved
rules: nothing is sent and no case is recorded. A **Translator** rule rewrites words
instead of blocking them: the rewritten message is posted as the member, and it never
warns or punishes anyone.

![Auto-mod rules](images/automod.png)

Staff can also use `/voice-mod` or a member's timeline to move, server-mute, deafen
or disconnect someone in voice. Each action is recorded as a moderation case.

Lockdown can **Also pause new DMs** until its displayed end time, for up to 24 hours.
Unlock removes the pause that lockdown set, preserving any earlier pause that is
still running.

## Levels and XP

- **Message XP** (a random amount between your minimum and maximum, with a cooldown) and
  **voice XP**.
- Channels and roles that never earn XP.
- **XP multipliers** for roles.
- Your own **level curve**.
- **Level-up announcements** with a rank card in your colour.
- **Level rewards**: a Discord role, coins or a game item at any level.
- A server **leaderboard**. Members use `/rank` and `/leaderboard`; staff adjust XP with
  `/xp`.

![Levels & XP](images/levels.png)

## The coin economy

A full play-money game, with its own pages for each part:

- **Earning**: daily, weekly and monthly rewards with streak bonuses; `/work`, `/crime`,
  `/beg` and `/search`; chat income; and **role income**, coins for holding a role.
- **Banking**: wallet and bank, deposits and withdrawals, paying other members,
  robbing, and passive mode.
- **Gathering and making**: hunting, digging, mining, fishing, farming and crafting.
- **Spending and trading**: a game shop with your own items, and a member-to-member
  market.
- **Playing**: story adventures, crew heists, pets that you feed, train and battle,
  quests given at random each day and week, achievements with badges and rewards,
  prestige, trivia, lotteries and predictions.
- **Games**: coinflip, slots, dice, blackjack, scratch cards, guess the number,
  rock-paper-scissors and high-low.
- **A tutorial** that teaches new members how to use the bot.

Over time the games pay back about 95% of what is bet (heists about 95–96%). You set the
biggest bet per kind of game and a **daily loss limit**.

**Coins are play money, kept apart from real money:** no store product gives coins, there
is no way to turn coins into real money, and a role someone paid for never earns coin
income.

![The Economy page](images/economy.png)

## Giveaways, polls and predictions

- **Giveaways** with an entry button, any number of winners, optional role and level
  requirements, a winner announcement and a congratulations DM. A prize can be a
  product from your store, licence keys included. Staff can start, end, reroll, pause,
  resume and list giveaways from Discord.
- **Polls**: members make them with `/poll`. **Use Discord's poll** uses Discord's
  native voting interface, with a duration and multiple-answer choice; the dashboard
  reads the final counts when the poll ends.
- **Predictions**: members bet play money on what will happen, with `/predict`.

![Giveaways](images/giveaways.png)

## Tickets

- **Panels** with buttons or a dropdown. Each ticket opens as a **private thread**.
- **Ticket types**, each with its own category, manager role and opening message.
- An **intake form** of up to five questions, asked before the ticket is created.
- A **staff alert** for each new ticket, with **Join ticket** and **Claim** buttons.
- Limits on open tickets per member, a reminder and auto-close after silence, and
  **feedback** when a ticket closes.
- **Transcripts**: one web page with the whole conversation and its files, with an
  optional copy for the member.
- **Buyer context**: when the member has bought from your store, staff see their orders,
  active licences (the last four characters only) and open portal requests, and can
  **resend a key**, **start a refund** or **remove access** from inside the ticket. A
  refund requested by staff goes to the owner to approve.

![Ticket panels](images/tickets.png)

## Music

Play from **YouTube, SoundCloud, Bandcamp, Twitch and Vimeo** in your voice channels.

- A **DJ role**. Anyone in the bot's voice channel can add songs and skip their own;
  skipping someone else's song needs a vote from the people listening.
- Music voice channels, starting volume, and limits on queue size and songs per member.
- **Audio effects**, loop, shuffle, seek and moving songs in the queue.
- Leaves an empty channel or an idle player on its own.
- A **Music server and YouTube** check that says whether music is working.

![Music](images/music.png)

## Automations

"When this happens, if these conditions hold, do these actions."

- **Triggers**: members (joins, verified, leaves, roles gained or lost, reaching a
  level, an invite that qualifies), the store (purchase completed, order refunded,
  subscription activated, renewal failed, lapsed or expired, a new licence device),
  moderation (a warning, a case opened), messages and activity (messages, reactions,
  buttons, voice channels), tickets, giveaways and Discord events.
- **Conditions**: roles, levels, channels, owning a product, message text, new or
  returning members, a time window or a specific user.
- **Actions**: a message, DM or reply, giving or removing a role, reactions, deleting the
  message, threads, waiting, granting a product, logging, creating a ticket, and banning,
  kicking or muting.

Start from **Templates**, see what ran on **Activity**, and see the automations you must
preview before they can be switched on (**Waiting for approval**). **Custom commands** makes your
own slash commands, and **Webhook relays** gives you an address that a website, store or
GitHub can send updates to.

![Automations](images/automations.png)

## Channels and messages

- **Scheduled messages**: a reminder, a rules link or a daily tip, on any schedule.
- **Embed builder**: make message cards with text, sections, pictures, galleries and
  link buttons, then send them to a supported channel or use them in a scheduled
  message. Saved classic embeds keep sending as before until you edit them.
- **Temp channels**: a hub voice channel that gives each member who joins their own
  voice room, which they can lock, unlock or claim with `/voice`.
- **Stats channels**: a live number, such as your member count, shown as a voice
  channel's name.
- **Reaction roles**: members give themselves roles with reactions or buttons.

## Staying in control

- **Save badges**: after every save, a badge says what the running bot did with it.
- **Admin changes**: changes made from the dashboard and by the bot, each with an undo
  button where it can be undone, saying what it will put back.
- **Sync**: changes made directly in Discord, outside SomniBot, with **Restore SomniBot's
  version** or **Keep Discord's version**. It checks every few minutes and can put things
  back by itself.
- **Snapshots**: saved copies of every role, channel and permission. SomniBot saves one
  before each big change; restoring compares first and can be undone.
- **Members**: everyone, with a timeline per member (joins and leaves, the member gate,
  role changes the bot made, purchases, refunds, tickets, cases, appeals, level-ups and
  game money,
  always labelled as game money).
- **Failed actions**: anything the bot couldn't do, to replay or dismiss.
- **Incidents**: problems being worked on, each with a timeline. SomniBot opens one by
  itself for a critical alert or a burst of fraud signals.
- **Diagnostics**: whether each part of SomniBot is working, and the problems it raised.
- **Audit log**: everything that happened on your server, who did it and when, with
  filters and downloads.
- Switching a feature off also hides its slash commands in Discord.

![Members](images/members.png)

## Owner alerts and the daily digest

When something needs you (music stopped, a lost permission, a channel that's gone, the
bot can't do something it was asked to, the member gate needs a choice), SomniBot sends
you an **owner alert**, by DM or in a channel members can't read. Store alerts have
their own page and channel.

The **Daily digest** sends one message a day, at the time and timezone you choose, to
your DMs or a staff channel. It covers new members, sales, tickets, requests, failed
actions, moderation, and bot and music health. You can preview the next one, and choose
whether quiet days still get a short note.

![Daily digest](images/digest.png)

## Your team

Give other people access to the dashboard with **dashboard roles**. No role is built in:
start from a template (**Admin**, **Moderator**, **Finance**, **Support**) or an empty
role, then choose each permission. Permissions cover server settings, moderation,
tickets, automations, roles and channels, editing products, running the store, handling
orders, customers and licence keys, analytics, the audit log, Diagnostics, incidents,
fraud, failed actions, undo, the team page and the coin economy.

- A team member sees only the pages their permissions cover. A save that would also
  change something outside them is refused whole.
- Someone who manages the team can only hand out roles that rank below their own. If
  they try more, it's refused and you get an alert.
- Some things stay the owner's alone: Settings, the Daily digest, the store's brand
  name, and where owner alerts go.
- By default, invitations are sent by Discord DM and must be accepted; they expire after
  24 hours, 3 days or 7 days.
- Team members sign in with their own Discord account, from any device.

![Team](images/team.png)

## Privacy

Members manage their own data in Discord:

- `/privacy` shows what SomniBot keeps about them in your server, how long each kind of
  record is kept, and how to reach you.
- `/mydata` sends them a file of their data, once a day at most (you can switch it off).
- `/forgetme` erases or anonymizes their data after they confirm, and lists first what is
  erased and what is kept.

You choose how long records are kept, from 30 days to 10 years. Orders, payments and
licence keys are kept as your sales records.

---

[← Back to the overview](README.md) · [The store](STORE.md) · [Commands](COMMANDS.md)
