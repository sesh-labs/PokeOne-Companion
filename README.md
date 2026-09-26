# PokeOne Companion

A free, offline companion app to keep open while you play **PokéOne**. It shows the wild Pokémon, items, people and gym where you are, tracks your badges, team and goals, and has a searchable Pokédex. It uses game information from the official PokéOne website.

> **Private beta.** Only invited testers can see this page. This is an early test version. Expect rough edges, and please report what you find.
> PokeOne Companion is an unofficial fan-made tool, not affiliated with PokéOne, Nintendo, Game Freak or The Pokémon Company.

## Download

**First, sign in to GitHub** with the account you were invited with, and accept the invitation (from the invitation email, or at [github.com/sesh-labs/PokeOne-Companion/invitations](https://github.com/sesh-labs/PokeOne-Companion/invitations)). This page and its downloads are private, so they only work while you're signed in.

**[⬇ Download version 0.2.0-beta (testing: a massive update)](https://github.com/sesh-labs/PokeOne-Companion/releases/tag/v0.2.0-beta)**

On that page, under **Assets** (click the word to open the list if the files aren't showing), click **`PokeOne-Companion-0.2.0-beta-win-x64.zip`** (about 160 MB).

**What's new in 0.2.0:** a **Today** page for your dailies and weeklies with reset timers, bosses with "fought it" countdowns and tick boxes for the steps they need, a **Bag** for your TMs, items and money (with what's worth selling), smarter advice before every gym and Elite Four, a Pokédex count per region, favourites, **Copy team**, and a **mini view** that stays on top of the game. The [release notes](https://github.com/sesh-labs/PokeOne-Companion/releases/tag/v0.2.0-beta) list everything.

**Requirements:** Windows 10 or 11, 64-bit, and about 550 MB of free space. Nothing else to install.

Checksum (SHA-256), if you want to check the download: `58d940ab8a9eaef5c32b3a16585b655072b3fc5de07fd9d80dc2de3f4a7ecf38` (also in `SHA256SUMS.txt` on the release page).

**Prefer the steadier version?** 0.2.0 is new, so [**0.1.8-beta**](https://github.com/sesh-labs/PokeOne-Companion/releases/tag/v0.1.8-beta) stays here too: `PokeOne-Companion-0.1.8-beta-win-x64.zip`, checksum `9c336596d20a5bf47282f75df38019bae0e8163edcd5500a1f3c2f04f3bde2ca`. Once 0.2.0 has opened a profile, 0.1.8 can't open that profile any more (see "Updating" below).

Older versions: [all releases](https://github.com/sesh-labs/PokeOne-Companion/releases).

## Install and run

1. Right-click the downloaded zip and choose **Extract All…**. Pick a folder you'll remember, for example `Documents\PokeOne Companion`.
2. Open the extracted folder `PokeOne-Companion-0.2.0-beta-win-x64` and double-click **`PokeOne Companion.exe`**.
3. The first time, Windows may say *"Windows protected your PC"*. This beta isn't digitally signed yet. Click **More info → Run anyway**.
4. Choose **I'm new to PokéOne** or **I'm already playing**, and follow the short setup. New players start in Pallet Town (Kanto) or New Bark Town (Johto), where the app shows the three starters.

Your progress saves automatically on your own computer (in `%APPDATA%\PokeOne Companion`). Nothing is uploaded anywhere.

**Updating from an earlier version:** first save a backup file (**Settings → Backups → Save a backup file…**). Then extract the new zip to a new folder and run it from there. Your profiles carry over: 0.2.0 upgrades each one the first time it opens and keeps a backup of the old file first. You can delete the old folder afterwards.

**Going back to 0.1.8-beta:** 0.1.8 can't open a profile once 0.2.0 has upgraded it. So before updating, save a backup file in 0.1.8; if you go back, restore that file in 0.1.8 (**Restore from a backup file…**). Nothing is ever deleted: the guide's "Updating from 0.1.8-beta" section has the details.

**Removing it:** delete the app's folder, and, if you want your progress gone too, the folder `%APPDATA%\PokeOne Companion` (type that into File Explorer's address bar). The guide's "Removing everything" section has the details.

The full **[Beta Tester Guide](GUIDE.md)** is also inside the zip and attached to the release.

## Play-testing: your first hour

1. Set up a profile the way you really play (or open your 0.1.8 profile): as a new player, or with your real progress (region, badges, trainer level).
2. Play PokéOne with the app open beside the game, or in the **Mini** view (Ctrl+M) on top of it. Press **Change location** whenever you move, and check the wild Pokémon, items and people against what you actually see.
3. On **Team**, add your real party with levels and moves. On **Progress**, mark your badges: does the **Before <leader>** advice make sense for your team?
4. On **Today**, tick a daily you've done. On **Bosses**, press **I fought it just now** after a boss fight: is the countdown right?
5. In the **Bag**, add a few TMs and items you really have. Try **Teach to…** and look at **Worth selling**.
6. In **Settings → Backups**, save a backup file. Close the app, open it again, and check that everything is still there.
7. Tell us what you looked for and didn't find, what confused you, and a score out of 10 for "would I keep this open while playing?".

## Know something the app doesn't?

Some things the official site doesn't say, so the app marks them **check in game**. The **[open questions](OPEN_QUESTIONS.md)** list them by region and place, one line each. If you know one, use the **I know the answer** form under Issues.

## Report a problem or suggest an idea

Use **[Issues](https://github.com/sesh-labs/PokeOne-Companion/issues)** → **New issue**, and pick a form: bug report, wrong game information, an idea, or "I know the answer". You can also use **Settings → Feedback & bug reports → Report a problem on GitHub** inside the app. Please include **Settings → Feedback & bug reports → Copy diagnostic information** (if the app won't open, just say so). For wrong game information, say where it was and what the game showed. Other invited testers can see reports, so don't include anything private, and crop screenshots to the app window.
