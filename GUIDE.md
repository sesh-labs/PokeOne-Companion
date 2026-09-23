# PokeOne Companion — Beta Tester Guide

**Version 0.1.5-beta** · Windows 10 and 11 (64-bit)

Thank you for testing PokeOne Companion. This guide explains what the app does, how to install it, and how to report what you find. You don't need any technical knowledge.

---

## What this application is

PokeOne Companion is a program you keep open next to **PokéOne** while you play. It:

- shows **what lives where you are**: wild Pokémon (with time-of-day rates), items, people and the gym in your current town or route;
- tracks your **badges and Elite Four** progress in Kanto, Johto and Unova;
- keeps a record of **your team** and checks your party's type weaknesses and move coverage;
- has a searchable **Pokédex** of Pokémon, moves, abilities, items, places and NPCs, plus a type-matchup tool;
- keeps your **goals and notes**;
- works **offline**, and saves your progress **on your computer**.

It does not connect to the game, read your game files or need your PokéOne account. You tell it where you are and what you've done, and it helps from there.

Game information comes from the official PokéOne website (pokeonecommunity.com). PokeOne Companion is an **unofficial fan-made tool**. It is not affiliated with PokéOne, Nintendo, Game Freak or The Pokémon Company.

## Beta status

This is a **beta**, an early version for testing. Expect rough edges. Some things may be missing, behave oddly, or be wrong. Finding and reporting those is exactly what you're here for, and it's appreciated.

Your progress is saved carefully, but please keep a backup file (see [Exporting / backing up](#exporting--backing-up)) of any profile you care about.

## System requirements

- **Windows 10 or Windows 11, 64-bit.** This is the only platform this beta supports. It has not been built for macOS, Linux or 32-bit Windows.
- About **550 MB** of free disk space while you still have the download (the zip is about 160 MB; the extracted app about 375 MB).
- No other software is needed. You don't need to install anything else.
- An internet connection is **optional**. It is only used to show Pokémon and item pictures, which load from the official PokéOne website. Everything else works offline.

## Installation

1. Download `PokeOne-Companion-0.1.5-beta-win-x64.zip`.
2. Right-click the zip file and choose **Extract All…**. Pick a folder you'll remember, for example `Documents\PokeOne Companion`.
   - Please extract it. Running the program from inside the zip without extracting will not work properly.
3. That's it. There is no installer. The extracted folder *is* the app.

To remove the app later, delete that folder. Your saved progress is kept separately (see [Where your data is stored](#where-your-data-is-stored)).

## Launching the application

1. Open the extracted folder `PokeOne-Companion-0.1.5-beta-win-x64`.
2. Double-click **`PokeOne Companion.exe`**.
3. **The first time only**, Windows may show a blue box saying *"Windows protected your PC"*. This happens because this beta is not digitally signed yet. It is not a sign of a problem with your computer. Click **More info**, then **Run anyway**.

Tip: right-click `PokeOne Companion.exe` → **Show more options** → **Send to** → **Desktop (create shortcut)** for a desktop shortcut. (On Windows 10, **Send to** is directly in the right-click menu.)

Only one copy of the app runs at a time. Opening it again brings the existing window to the front.

## First-time setup

The first time you open the app, it asks how you'd like to start:

- **I'm new to PokéOne:** for a brand-new playthrough.
- **I'm already playing:** for when you're partway through the game.
- **Restore from a backup:** for when you have a backup file from PokeOne Companion.

Setup takes a minute or less, and everything you choose can be changed later.

A **profile** is one playthrough. Most people only need one. You can add more later (see [Profiles](#profiles-playthroughs)).

## Starting as a new PokéOne player

1. Choose **I'm new to PokéOne**.
2. Give your profile a name (for example "Main run"). Your in-game trainer name is optional.
3. Pick the region you started in. PokéOne lets new players start in **Kanto** or **Johto**. Then click **Start my companion**. If you haven't decided yet, choose **Skip and start**.
4. The app opens on **Current Location** in your starting town: **Pallet Town** for Kanto, **New Bark Town** for Johto. A **Choose your starter** box lists the three starter Pokémon that town gives; click **Add to my team** next to the one you picked in the game. (If you skipped the region, search for the town or route you're in instead.) A **First steps** box above it names your first gym and how to use the app; **Hide this** puts it away for this profile on this computer.

From then on, update the app as you play: change your location when you move, mark badges as you earn them, and add Pokémon to your team.

## Starting when already partway through PokéOne

1. Choose **I'm already playing**.
2. Name your profile.
3. **Where are you right now?** Pick your current region, then search for the place you're standing in. Also tick any other regions you've played in.
4. **Which badges do you have?** Tap each badge you've earned. There's a **Mark all eight** shortcut. If you've beaten that region's Elite Four, tick that box too. Your trainer level there is optional. Each region has its own trainer level in PokéOne, so switch region at the top of this step to enter the others. It's used for the Unova requirement.
5. **Who's in your party?** (optional) Add your current party now, or skip and do it later from the Team page.
6. Choose **Finish setup**.

You don't need to enter your whole history. The companion only needs enough to be useful, and you can fill in more whenever you like.

## Returning to an existing companion profile

Just open the app again. It opens your last profile where you left it; there's no setup the second time.

Everything saves automatically as you go. The bottom-left corner shows **Saved** (green) once your latest change is on disk. You can close the window at any time; any change that hasn't finished saving is saved before the app closes.

## Main features

**Current Location** (home screen)
- Your current place, with its description from the official site.
- **Gym here**, if there is one: the leader's team with levels, and which types hit the whole team super-effectively. You can click **Mark badge earned** right there.
- **Wild Pokémon**, in one table per method (grass, surfing, headbutt…), per fishing rod (**Fishing · Old Rod**, **Good Rod**, **Super Rod**) and per area where a place has several (e.g. **Grass · Kanto Safari East**), just like the official site. Choose a time of day to see rates for morning, day, evening or night. Tick the checkbox to mark a Pokémon as caught, and use **Only ones I haven't caught** to see what's still missing.
- Each wild Pokémon shows its **EV yield**, and each method has an **EV training** line worked out from the official rates, e.g. "Speed from 100% of encounters (about 1.2 per battle)". When rates change through the day, pick a time to see it. Where the site gives no rates, it counts the Pokémon listed instead, and says so.
- Some forms share one encounter slot, although the official site lists each at the full rate (Pumpkaboo's four sizes, Burmy's three cloaks). They're marked **◦** and counted once.
- A few rows appear only on a Pokémon's own page on the official site, not on the place's page. They're listed last, under **Also listed †**, without a rate, so the table's rates add up. Mega forms never show as wild.
- Where the official rates in a table can't all be right (they add up to well over or under 100%), the table is tagged **≈ rough numbers** and its numbers start with ≈. The **Key** under the tables gives the total. Headbutt and Rock Smash tables normally add up to less than 100%; there the numbers are shares of the Pokémon you battle, and a note says so.
- **Items here** (including berry trees) and **People here** (tutors, vendors, trainers and more).
- A side panel with your goals, region progress and the next badge, your party, and tips from the official FAQ. Endgame tips wait under "more tips" until you've beaten the region's Elite Four.
- **Change location** is at the top. Recently visited places appear as quick buttons.

**Progress**
- Badges for Kanto, Johto and Unova, with each leader's team. Click **Mark badge earned** on a leader's card when you win the badge. Johto's badge order isn't given on the official site, so its cards carry no numbers. For some Unova leaders the site also lists a much stronger team; it's folded under **A stronger team is also listed**.
- Elite Four for each region.
- Your **trainer level in each region** (PokéOne keeps a separate one per region).
- The requirements for reaching Unova, and which of them you already meet. The level requirement uses your Kanto or Johto level, whichever is higher.

**Team**
- Your **party** (up to six) and a **bench**: Pokémon you're keeping an eye on but not carrying right now. When your party is full, new Pokémon go to the bench.
- Edit nickname, level, nature, ability, moves, held item and notes. The editor opens with the cursor in **Level**. The move list only offers moves that Pokémon can learn according to the official site, and any of the four slots can be filled first.
- **Stats (IVs and EVs)**, optional and folded away until you open it: IVs (0–31) and EVs (0–252 each, 510 in total), with the nature's raised and lowered stats marked. A short plain-words explanation of IVs, EVs and the EV plan sits at the top. If you type more EVs than fit, it says how many fit.
- **EV plan:** pick a preset spread (e.g. Physical attacker: 252 Attack / 252 Speed / 4 HP) or type your own targets, then press **+1** once for each EV a beaten Pokémon gives (or type the number). Bars show "now / target", also on the Pokémon's card, which has its own quick +1; the app warns when a plan can no longer be finished under the 510 total. **Where to train** lists places whose wild Pokémon mostly give the EVs you still need, with the table to use (e.g. **Fishing · Super Rod**) and about how many battles it takes. Places whose numbers are only approximate come last, marked **≈**.
- **Party type check:** weaknesses your party shares, and which types your moves cover.

**Pokédex**
- Pokémon, moves, abilities, items, places and NPCs, with search and filters (type, region, caught or not, and more). Each Pokédex number has one row; other forms (Pikachu's caps, Rotom's forms, Megas) open under **▸ N more forms**.
- Every entry links to related entries. A Pokémon's page starts with its **evolution strip**: the whole family as pictures, with the condition on each arrow, regional lines (Alolan) on a row of their own and Megas and other forms in a row below; click any of them to open it. Then where to find it and its moves. An item's page shows where to buy or find it.
- **Where to find** on a Pokémon's page has two lists: **Catch in the wild** (place, how, rarity, chance and when) and **Rewards, gifts and trades** (for example "Reward for beating the Kanto Elite Four" or "Hidden item: Helix Fossil"). Long lists keep your current region open and fold the others.
- The **Tutor** moves tab names each tutor and where they are; a move's own page adds what each tutor charges. Prices are written as in the game, e.g. **₽5,000**; **Gold** is a separate currency.
- **Type matchups:** pick one or two types to see what hits them hard.

**Goals & notes**
- A simple goal checklist. You can also add a "catch" goal from any Pokémon's page.
- A free notes area.

**Search anywhere:** the search box at the top finds any Pokémon, place, item, move or NPC. Press **Ctrl+K** to jump to it.

**Zoom:** Ctrl + plus, Ctrl + minus, or Ctrl + 0 to reset.

**Going back:** the **← Back** button at the top, **Alt+Left** or your mouse's back button return to the previous page, tab and scroll position.

### A note on the information shown

- Rates, levels and locations are as listed on the official site. If the game differs, **the game is right**. Please tell us when you notice a difference.
- A small **†** next to a Pokémon on a place's list means the official site lists it on the Pokémon's own page but not on that place's page. The site disagrees with itself there, so treat it as "check in game".
- Some TM/HM rows are marked **verify** because the official site lists a different move for that machine number than it does everywhere else.
- The **Johto** badge order is not published by the official site, so Johto leaders are listed from lowest to highest team level. That is not a confirmed order.

## Profiles (playthroughs)

**Settings → Profiles** lists your profiles.
- **Add a profile** starts a new playthrough without touching your current one.
- **Switch** opens another profile. Your current one is saved first.
- **Rename** or **Delete** the open profile. A deleted profile is not erased: it's moved to the `removed` folder inside your data folder, just in case.

## Saving and persistence

- **Automatic:** every change saves on its own within a moment. You never need to press Save.
- **Automatic backups:** the app also keeps recent backup copies of each profile (one when you first change something in a session, then every 20 minutes while you keep changing things; the newest 20 are kept). The newest 10 are listed under **Settings → Backups**.
- **Your action:** saving a **backup file** is up to you. We recommend doing it now and then, and before any big change.

If the save indicator ever shows **Not saved** in red, the app keeps trying. If it stays red, save a backup file from Settings and report the problem.

## Exporting / backing up

1. Go to **Settings → Backups**.
2. Click **Save a backup file…**.
3. Choose where to save it (your Documents folder is suggested). The file is named like `PokeOne-Companion-Main-run-2026-09-22.json`.

That single file contains the whole profile. You can copy it to a USB stick, cloud storage or another computer.

## Importing / restoring

**From a backup file**
- On the welcome screen choose **Restore from a backup**, or go to **Settings → Backups → Restore from a backup file…**, and pick the `.json` file.
- Restoring always **adds** the profile. It never overwrites the one you have open. If the same profile already exists, the restored copy is added next to it with "(imported)" in its name, and **the app switches to that copy**: check the profile name at the bottom left, and switch back in **Settings → Profiles** if you meant to keep playing in the original.
- Files that aren't valid companion backups are refused with an explanation, and nothing changes.

**From an automatic backup**
- **Settings → Backups** lists recent automatic backups of the open profile. Click **Restore** next to one. The version you're replacing is backed up first, so you can undo it the same way.

## Starting over

To start a fresh playthrough while keeping your current one, go to **Settings → Profiles → Add a profile**.

To get rid of a profile, go to **Settings → Profiles → Delete this profile…**. Consider saving a backup file first. The deleted profile is moved to the `removed` folder rather than erased. If it was the open profile, the app then asks which profile to open (or offers to start a new one).

## Where your data is stored

Your profiles are saved in your Windows user folder:

`%APPDATA%\PokeOne Companion`

(Usually `C:\Users\<your name>\AppData\Roaming\PokeOne Companion`.) **Settings → Feedback & bug reports → Open data folder** opens it for you. Inside you'll find:

- `profiles`: your profiles;
- `backups`: automatic backups;
- `removed` and `quarantine`: profiles you deleted, and damaged files set aside;
- `logs`: a small log of app events for troubleshooting. It contains no notes or team details.
- `settings.json`: your display choices (Light/Dark), the window size and which profile was open last;
- `chromium`: the picture cache and other files the app's built-in browser engine keeps, including small preferences such as a hidden **First steps** box. It also contains your folder path, so share a **backup file** rather than this folder.

Deleting the app folder does **not** delete this data. Please don't edit these files by hand while the app is open.

### Removing everything

To take PokeOne Companion off your computer completely:

1. If you might want your progress later, save a backup file of each profile first (see [Exporting / backing up](#exporting--backing-up)).
2. Close the app.
3. Delete the app folder you extracted.
4. Press **Windows + R**, type `%APPDATA%`, press Enter, and delete the **PokeOne Companion** folder there.

That removes your profiles, backups, logs and picture cache. Nothing is stored anywhere else.

## Troubleshooting

| Problem | What to do |
|---|---|
| "Windows protected your PC" when opening | Expected for this unsigned beta. Click **More info → Run anyway**. |
| The app doesn't start at all | Make sure you extracted the whole zip (see Installation) and are running `PokeOne Companion.exe` from the extracted folder. Try moving the folder somewhere simple like `Documents`. |
| No Pokémon pictures | Pictures load from the official PokéOne website, so check your internet connection. Everything else works without them. You can turn pictures off in **Settings → Display**. |
| "Your profile couldn't be opened" | The profile file was damaged. The screen lists automatic backups; **Restore** the newest. Nothing has been deleted: the damaged file is kept in the `quarantine` folder. |
| The save indicator says **Not saved** | The app keeps retrying. Make sure your disk isn't full. Save a backup file from Settings, then report it. |
| Clicking the app icon again does nothing new | Only one copy runs at a time; it brings the existing window forward. Check your taskbar. If you had just closed the app, it reopens as soon as it has finished saving. |
| Something shown doesn't match the game | Trust the game, and please report it (see below) with the place or Pokémon name. |
| The window is too small or too large | Resize it (it can go down to 640 pixels wide, half a laptop screen beside the game; the left menu then turns into icons with short labels). The app remembers the size. Use Ctrl + plus or minus to zoom. |

## Known limitations

- **Windows 64-bit only** in this beta.
- **The app is not digitally signed**, so Windows shows a warning the first time.
- **No connection to the game.** Location, badges and team are entered by you.
- **Game data is a snapshot** from the official website (the date is in **Settings → About**). Anything changed in PokéOne since then won't be reflected until a later beta.
- **The official site is incomplete or inconsistent in places:**
  - Some Pokémon are listed on their own page but not on a place's page (marked †).
  - A few TM/HM entries conflict (marked "verify").
  - The Johto badge order isn't published.
  - Some "where to find" details, such as the rarity of Elite Four rewards, aren't available.
- **No catch rates.** They aren't shown because the data we have for them is not reliable yet.
- **Where to train doesn't know which places you can reach yet.** It may suggest a late-game place or one that needs an HM or a rod you don't have. Water and fishing spots say what they need. In the Safari Zone, battles are normal but have a step limit and only Safari Balls; that EVs are given there is assumed, not confirmed.
- **Starter help covers Kanto and Johto.** Unova can't be a starting region.
- **No story walkthrough or quest tracking.** The official site doesn't publish a step-by-step story guide we could check against, so the app doesn't guess one. Use Goals for your own objectives.
- **No automatic updates.** New betas are downloaded manually. Your profiles carry over.
- **Pictures need the internet** (they load from the official site).
- **Profile backup files are one profile each.** There's no single "back up everything" button yet (you can copy the whole data folder instead).

## Reporting bugs

**Where to send reports:** https://github.com/sesh-labs/PokeOne-Companion/issues

1. Open that page. It's private: you need the free GitHub account you were invited with.
2. Click **New issue** and pick **Bug report**, **Wrong or missing game information** or **Idea or suggestion**.
3. Give it a short title (for example "Badge doesn't stay ticked after restart"), fill in the form, and click **Submit new issue**. You can follow replies on the same page.

The **Report a problem on GitHub** button in the app's **Settings → Feedback & bug reports** opens the same page. Reports can be seen by the project owner and the other invited testers, so don't paste anything private. The diagnostic information is safe to include.

Please include:

1. **What you were doing**: the screen and the steps you took.
2. **What you expected** to happen.
3. **What actually happened.**
4. **Steps to reproduce**, if you can make it happen again.
5. **A screenshot**, if it helps (Windows + Shift + S takes one).
6. **Diagnostic information:** go to **Settings → Feedback & bug reports → Copy diagnostic information**, then paste it into your report. It contains the app version, your Windows version and recent app events, which can include folder names on your computer. It does **not** include your notes, goals or team.
7. Your **Windows version** and the **companion version** (both are in the diagnostic information).

For wrong game information, name the Pokémon, place, item or NPC and describe what the game actually shows.

If a profile file is involved (for example, one that won't open), you may attach it from the data folder. Only share it if you're comfortable: it contains your goals and notes.

## Feature feedback

Beyond bugs, we'd especially like to hear:

- Was setup quick and clear? Was anything confusing?
- Does **Current Location** show what you actually need while playing? What's missing?
- Which screens do you use the most, and which never?
- Anything that felt slow, cluttered or hard to find.
- Game information that's missing, out of date or wrong.
- What would make you keep the companion open every time you play?

## Data safety

- Your progress is saved on your computer only. Nothing is uploaded anywhere.
- This is beta software. **Keep a backup file** of profiles you care about, especially before installing a newer beta.
- Newer betas will read profiles from this one. If you ever go back to an older version, it will refuse a profile made by a newer version rather than risk damaging it.
- The app never deletes your data on its own. Deleted and damaged profiles are moved aside, not erased.

## Version information

- **Application:** PokeOne Companion **0.1.5-beta**
- **Platform:** Windows 10/11, 64-bit (portable zip)
- **Game data:** from the official PokéOne website. The exact data date is shown in **Settings → About**.
