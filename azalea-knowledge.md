# Azalea — Knowledge Base

> This is the single source of truth for the Azalea Field Guide and the Discord ticket assistant.
> Edit any section and the bots pick up changes within ~1 hour.
> Keep server status, update announcements, and access info current. Last reviewed: 2026-10-03.

---

## About Azalea

Azalea is a custom modded DayZ map set on São Miguel island in the Azores — a volcanic Atlantic island in Portugal. It is an independent project built by OlipollyZ, a solo developer working alongside a day job. The map is not affiliated with Bohemia Interactive.

The map focuses on atmosphere, realism, and the natural beauty of the Azores. Every building, spawn point, vehicle, and loot tier has been placed deliberately over three years.

Key facts:
- Based on São Miguel, the largest island of the Azores archipelago
- Map size: approximately 161 km² (9.6km × 16.8km)
- Completely free to play — not a DLC
- Dense POIs, short rotations, never truly safe
- 19,000+ Steam Workshop subscriptions to date
- Inspiration: the Azores, LOST, Dark, Silo

Portuguese players have messaged saying they recognise their hometown in the design.

---

## The Developer

- **Name:** OlipollyZ
- **Model:** Solo project alongside a day job, helped by volunteer staff on Discord
- **Support:** https://ko-fi.com/olipollyz
- **Do not DM the developer or staff directly** — open a ticket in Discord `#🎟️│create-a-ticket` for support.

---

## Access & Early Access

Azalea is in early access. The official server runs 24/7 and is open to the public. The map is updated regularly; the current server version is shown in Discord `#📻│server-info`, and the next update's ETA is in `#⏳│next-update`.

The mod is listed on Steam Workshop. You can subscribe and join the server at any time.

You cannot run your own Azalea server until full release — this keeps the experience consistent and prevents unfinished builds from circulating. Downloading, repacking, or modifying the mod is not allowed.

Full release target: 2027.

---

## Servers

- **AZALEA EU** — open now. 1PP, no bases, adventure style. 60 player slots.
- **AZALEA US** — coming soon, launching alongside Update 0.4. Not joinable yet.
- There is no PvE server and no third-person server.
- Connection details, live status and the BattleMetrics link are always in Discord `#📻│server-info`. Downtime and "back online" notices go in `#💓│server-status`.

---

## How to Join

**Easiest method:** Search for "Azalea" in the Community tab of the DayZ Launcher. Click Join and select "Setup DLCs and Mods and Join" for automatic mod sync.

**Manual steps:**
1. Subscribe to the Azalea mod on Steam Workshop
2. Launch DayZ
3. Open the Community Server Browser
4. Search "Azalea" and connect to AZALEA EU
5. The mod downloads and loads automatically on connect

**Direct connection (AZALEA EU):**
- Address: `45.151.81.211:2502`
- If it ever changes, `#📻│server-info` in Discord has the current address.

Free to play. No whitelist required.

---

## Server Info

- **Restarts:** Every 4 hours
- **Bases:** None. Building and base storage are not part of Azalea's style; it is an adventure server.
- **Wipes:** Rare — only during major DayZ engine updates or critical terrain overhauls that would cause item glitches. Map persistence is currently stable.
- **Max players:** 60 on AZALEA EU

---

## Gameplay — Loot & Economy

Loot is tiered by region:
- **Spawn towns (Tier 1):** Intentionally sparse — basic clothing and tools only. This is by design to push players inland and explore.
- **Inland and northern zones:** Higher-tier gear, military loot, and weapons.
- **Sonar Bunkers:** High-risk, high-reward loot concentration.

---

## Gameplay — The Sonar System

The Sonar is a unique Azalea mechanic. Understanding it is essential for survival.

**Warning signs — retreat immediately if you see either:**
- Screen turns grey
- Distinct pulse/trumpet audio cue

**How to survive:**
- Wear a **Sonar Helmet** (Tanker Helmet style) for protection
- Find a **Sonar Keycard** in nearby mini-bunkers to deactivate the pylons
- Passage is only safe when pylon lights are **green**

**Punchcards:**
- Spawn in high-tier military locations in the north, or as rare drops
- Have limited durability — they will eventually ruin

---

## Gameplay — Navigation

Azalea uses custom technical coordinates. Compasses and GPS may feel "off", particularly in the extreme south of the map. Use the **sun** as your primary navigation anchor if your compass seems wrong.

---

## Troubleshooting

**Name showing as "Survivor"**
You must set your profile name in the DayZ Launcher before joining.
Fix: Close the game → Open Launcher → Settings → enter your name in the Profile Name field.

**Buildings missing / doors not opening**
Usually caused by an outdated mod version.
Fix: Close DayZ and the launcher, unsubscribe from the Azalea mod on Steam Workshop, then re-subscribe to force a fresh download.

**Game crashes on join / "Modified Data" error (Ghost Mod)**
1. Unsubscribe from all Azalea mods
2. Delete the hidden `!Workshop` folder in your DayZ installation directory
3. Verify integrity of game files via Steam
4. Re-join

**Kicked immediately at Position 0 in queue**
- First attempt: simply re-join — the second attempt often succeeds once data is cached
- If persistent: delete your character profile folder at `%UserProfile%\Documents\DayZ` (note: resets settings and keybinds)

**Kicked for VPN / proxy when you are not using one**
Some home and mobile internet providers (and some IPv6 connections) get flagged by mistake. Try these first:
1. Fully close browsers with a built-in VPN (for example Opera or Brave), and turn off iCloud Private Relay, Cloudflare WARP and "ping booster" apps
2. Restart your router to get a new address, or try another network such as a phone hotspot
3. Try joining again
If it still happens, say in your ticket which country and internet provider you use and roughly when it happened (with timezone). A volunteer checks these by hand; the bot cannot change it.

**Server not showing in the launcher**
Use Direct Connect with the address in `#📻│server-info`, or join through the DZSA Launcher. The official launcher's server list is sometimes unreliable.

**Stuck in a bunker, a hole, or under the map**
If a bunker door seems stuck, wait until it has fully finished opening or closing, then try again. If you are really trapped, say in your ticket where you are (coordinates from [P]) and when you will be online. A volunteer can move you when one is available; there is no set time.

**Got a fresh character after joining during a restart**
This is a known DayZ bug (since 1.29), not an Azalea one: during a restart your character can stay loaded in the world for a moment and be killed there. Wait until the server is fully back up before joining.

**Dropped items disappearing**
Items left on the ground despawn after some hours, and hiding them does not stop the timer. Use a stash, barrel or container if you want to keep something.

**Game crashed**
Post the crash in Discord `#⚠️│crash-logs`, or use the crash form at azaleamap.com/report-crash. Include what you were doing and the time. DayZ keeps crash logs (.RPT and .mdmp files) in `%LocalAppData%\DayZ`; attach the newest ones.

**Lost gear, died to a bug, or fell through the map**
Open a ticket with the time (with timezone), where it happened (coordinates from [P]), and a screenshot or clip if you have one. Gear lost to DayZ itself (disconnects and rollbacks, items stuck in walls or the floor, vehicle physics, normal deaths) is not restored. Gear lost to a bug in Azalea's own content can be restored if you open a ticket within 48 hours and the server logs confirm it; an admin decides, and nothing is promised before the logs are checked.

**Server offline or not showing in the browser**
Check `#💓│server-status` and the BattleMetrics link in `#📻│server-info`. Restarts every 4 hours take a few minutes. If it is down outside a restart, open a ticket.

If a technical issue is unresolved after trying the steps above, open a ticket in Discord `#🎟️│create-a-ticket`. Do not DM the developer or staff.

---

## Priority Queue (Ko-fi Tier 2)

Priority Queue is a perk of the Azalea Supporter (Tier 2) membership on Ko-fi. It is not given out for crashes, streaming or events, and DayZ has no "rejoin after crash" queue skip. It cannot be switched on by hand; it activates automatically once all three steps are done:

1. **Connect Discord on Ko-fi:** log in to Ko-fi with the email you paid with and use "Connect to Discord" so you get the Tier 2 supporter role in the Azalea Discord. Check that the role shows on your profile. If the web page does not work, try it from your phone.
2. **Link your Steam ID:** use `/link-steam` (or the "Link your Steam ID" button) with your 17-digit Steam64 ID. If you linked before you paid, link again.
3. **Wait and rejoin:** it syncs automatically within a few minutes (allow up to about 20).

If it still does not skip the queue after 24 hours, open a ticket and say which of the three steps you have done and what the `/link-steam` reply said. Refunds and payment problems are handled by staff in a ticket.

---

## Bug Reports & Suggestions

The source of truth for bugs and suggestions is **azaleamap.com/support**. Every report there gets a ref like R-123 with a status (open, fixed, and so on) and the version it was fixed in.

**How to report:**
- Go to **azaleamap.com/support** — no Discord needed
- Or use the buttons in Discord `#🐞│report-bugs-ideas`; they post straight to the same list
- Search the list first: if your bug is already there, vote on it instead of posting a new one

**What to include:**
- What happened, and how often (every time, sometimes, once)
- Where: press **[P]** in-game to show coordinates, and take a screenshot
- Steps to reproduce, if you know them

Use a ticket instead of a bug report for anything about your own account, a ban, another player, or a server outage.

---

## Roadmap

**Currently in progress:**
- **Monte Palace Hotel** — a huge abandoned hotel inspired by the real Monte Palace on São Miguel, built from scratch
- Update 0.4, which also opens the AZALEA US server
- Performance and loot balance tuning from player feedback
- Bug fixes from the azaleamap.com/support list

**Under consideration (not committed):**
- Dynamic weather events — storms, rolling Atlantic fog, heavy rain
- Boats and naval travel between coastal areas
- Wildlife expansion — tropical birds, boars, island fauna
- Underground cave system

**Custom Buildings, Music & Performance** is an ongoing goal across all updates. Dates are announced in `#⏳│next-update` and `#📣│announcements`, never in tickets.

---

## Community & Links

- **Discord:** https://discord.gg/azalea-dayz-map-951758529201569842
- **Steam Workshop:** https://steamcommunity.com/sharedfiles/filedetails/?id=2977981023
- **Website:** https://azaleamap.com
- **Bugs & suggestions:** https://azaleamap.com/support
- **Changelog:** https://azaleamap.com/changelog
- **Ko-fi (support the project):** https://ko-fi.com/olipollyz
- **Twitch (dev streams):** https://www.twitch.tv/olipollyz

---

## Credits

**Integrated mods:**
- Fishy's Buildings — by Fishy / onexs
- CS Item Pack — by CanadianSniper
- Tony's UK Assets (windmill) — by Tony

**Special thanks:**
AutistixLIVE, Basshi, Bitteroot Dev (Matty), British, ChimneyLIVE, Co_Co, DanceofJesus, DayZnChill, Hella Plays, Holliedayz, JemmyB00, JonssonRS, KNEXEM, Lad, Mazmaz, MikeDocherty, MissMoody, MR-PMB77, Nate_lapT, SalvaeniDayZ, SCLOWTONEZ, SeniMJ, SmokeTV, Sumrak, Waldemar, and the entire DayZ community.

---

## FAQ

**Is Azalea free?**
Yes. Workshop subscription is free, the server is free to join.

**Is this an official DayZ DLC?**
No. Azalea is an independent project, not affiliated with Bohemia Interactive.

**Can I run my own Azalea server?**
Not currently. The map runs only on the official servers until full public release (1.0); it will be announced when that changes. Repacking or redistributing the mod files is not allowed. If you want a server closer to your region, post it in `#🐞│report-bugs-ideas` as an idea.

**Where is the best loot / where do I find item X?**
Finding things is part of the game, so staff do not give out loot locations. The Sonar and navigation sections above cover the mechanics.

**When are the restarts?**
Every 4 hours. Unplanned downtime and "back online" notices go in `#💓│server-status`.

**When is full release?**
Targeting 2027. Currently in early access with the EU server running 24/7.

**When does the US server open?**
Alongside Update 0.4. Watch `#📻│server-info` and `#⏳│next-update`.

**Can I build a base?**
No. Azalea servers have no bases; it is an adventure server.

**How do I get notified about major updates?**
Join the Discord — announcements go to `#📣│announcements` first. You can also leave your email at azaleamap.com.

**How can I support the project?**
Ko-fi at https://ko-fi.com/olipollyz — helps cover hosting and hardware costs. Questions about Ko-fi perks or payments go in a ticket; staff handle them.

**I found a bug / have an idea.**
Use azaleamap.com/support or the buttons in `#🐞│report-bugs-ideas`. Press [P] in-game for coordinates and add a screenshot.

**Is there wildlife on the map?**
Yes — crocodiles are in the map. More wildlife is under consideration for future updates.

**Why is my compass wrong?**
Azalea uses custom coordinates. Use the sun for navigation, especially in the far south.
