# PokeOne Companion — Beta Tester Guide

Version 0.2.4-beta · Windows 10 and 11 (64-bit)

Thanks for testing. This guide covers what the app does, how to install it and how to tell us what you find. No technical knowledge needed.

---

## What this application is

PokeOne Companion is an app you keep open next to PokéOne while you play. It shows the wild Pokémon, items, people and gym where you are, keeps track of your team, badges, dailies and bosses, and checks whether your party is ready for the next fight. It also has a Pokédex you can search, and room for your goals and notes.

It doesn't connect to the game or read your game files, and it never asks for your PokéOne account. You tell it where you are and what you've done, and it helps from there. It works offline and saves everything on your computer.

Game information comes from the official PokéOne website (pokeonecommunity.com). The app is an unofficial fan project, not connected to PokéOne, Nintendo, Game Freak or The Pokémon Company.

## Beta status

This is an early test version, so some things will be missing, odd or wrong. Finding those is exactly what you're here for. Your progress is saved carefully, but keep a backup file of any profile you care about (see [Exporting / backing up](#exporting--backing-up)).

## System requirements

- Windows 10 or 11, 64-bit. There's no Mac, Linux or 32-bit version.
- About 550 MB of free space while you still have the download (the zip is about 160 MB, the app about 375 MB).
- Nothing else to install.
- Internet is optional. It's only used for the Pokémon and item pictures, which load from the official PokéOne website.

## Installation

1. Download `PokeOne-Companion-0.2.4-beta-win-x64.zip`.
2. Right-click it, choose **Extract All…**, and pick a folder you'll remember, for example `Documents\PokeOne Companion`. Running it from inside the zip won't work properly.

There's no installer: the extracted folder is the app. To remove it later, delete that folder. Your progress is kept somewhere else (see [Where your data is stored](#where-your-data-is-stored)).

## Updating from an earlier version

1. In the old version, save a backup file (**Settings → Backups → Save a backup file…**). It's your easy way back.
2. Close the old app and extract the new zip to a new folder, not over the old one.
3. Open the new app. Your profiles come along by themselves.

From 0.2.1, 0.2.2 or 0.2.3 to 0.2.4 nothing is upgraded: they all use the same profiles, so you can switch between them freely. From 0.2.0 or older, the first time each profile opens, 0.2.4 upgrades it (to profile format 5, which makes room for the new 🛠 and ✨ markers) and keeps a copy of the old file first. Settings → Backups lists that copy as "before an update (always kept)". A message says what's new. Profiles from 0.1.8 are upgraded the same way, in one go.

### Going back to an older version

An older version can't open a profile that a newer one has upgraded. It says so and leaves the profile alone.

To go back, open the older version and choose Settings → Backups → Restore from a backup file…, then pick the backup file you saved before updating. What you did in the newer version isn't in it. A backup file saved in a newer version can't be opened in an older one.

If you didn't save a backup file first (going back to 0.1.8 only): 0.1.8 says "Your profile couldn't be opened" and lists its automatic backups. The one marked "(newest)" won't open, so try the ones under it until one does. Nothing is deleted: 0.1.8 keeps the newer profile in its list as one it can't open, or moves it to the `quarantine` folder in your data folder. Back in the newer version you may then have two profiles; switch between them in Settings → Profiles and delete the one you don't want. A quarantined file comes back with Settings → Backups → Restore from a backup file….

## Launching the application

1. Open the extracted folder `PokeOne-Companion-0.2.4-beta-win-x64`.
2. Double-click **`PokeOne Companion.exe`**.
3. **The first time only**, Windows may show a blue box saying *"Windows protected your PC"*. This happens because this beta is not digitally signed yet. It is not a sign of a problem with your computer. Click **More info**, then **Run anyway**.

Tip: right-click `PokeOne Companion.exe` → **Show more options** → **Send to** → **Desktop (create shortcut)** for a desktop shortcut. (On Windows 10, **Send to** is directly in the right-click menu.)

Only one copy of the app runs at a time. Opening it again brings the existing window to the front.

## First-time setup

The first time you open the app, it asks how you'd like to start:

- **I'm new to PokéOne:** for a brand-new playthrough. (Already have your starter? Choose **I'm already playing**.)
- **I'm already playing:** for when you're partway through the game.
- **Restore from a backup:** for when you have a backup file from PokeOne Companion.

Setup takes a minute or less, and everything you choose can be changed later.

A **profile** is one playthrough. Most people only need one. You can add more later (see [Profiles](#profiles-playthroughs)).

## Starting as a new PokéOne player

1. Choose **I'm new to PokéOne**.
2. Give your profile a name (for example "Main run"). Your in-game trainer name is optional.
3. Pick the region you started in. PokéOne lets new players start in **Kanto** or **Johto**. Then click **Start my companion**. If you haven't decided yet, choose **Skip and start**.
4. The app opens on **Current Location** in your starting town: **Pallet Town** for Kanto, **New Bark Town** for Johto. A **Choose your starter** box lists the three starter Pokémon that town gives; click **Add to my team** next to the one you picked in the game. Under each starter, one line says how its type does against your first gym, from the type chart only (e.g. "✓ Strong against Brock's whole team (Water Gun at Lv 7)", "✗ Brock's Rock Pokémon resist Fire, and Rock and Ground hit it hard"). (If you skipped the region, search for the town or route you're in instead.) A **First steps** box above it names your first gym and how to use the app, and links the official **Beginner Guides** (trainer EXP, Rare Candies for your region); **Hide this** puts it away for this profile on this computer.

From then on, update the app as you play: change your location when you move, mark badges as you earn them, and add Pokémon to your team.

## Starting when already partway through PokéOne

1. Choose **I'm already playing**.
2. Name your profile.
3. **Where are you right now?** Pick your current region, then search for the place you're standing in. Also tick any other regions you've played in.
4. **Which badges do you have?** Tap each badge you've earned. There's a **Mark all eight** shortcut. If you've beaten that region's Elite Four, tick that box too. Your trainer level there is optional. Each region has its own trainer level in PokéOne, so switch region at the top of this step to enter the others. It's used for the Unova requirement.
5. **Who's in your party?** (optional) Add your current party now, or skip and do it later from the Team page. You can type each one's level (1–100); a level outside that range says so and isn't saved.
6. Choose **Finish setup**.

You don't need to enter your whole history. The companion only needs enough to be useful, and you can fill in more whenever you like.

## Returning to an existing companion profile

Just open the app again. It opens your last profile where you left it; there's no setup the second time.

Everything saves automatically as you go. The bottom-left corner shows **Saved** (green) once your latest change is on disk. You can close the window at any time; any change that hasn't finished saving is saved before the app closes.

## Main features

**Help where you need it:** a small round **?** beside words like IV, EV, EV yield, nature, catch rate, "depends on time" and ≈ explains them in plain words. Click it (or press Enter), and click anywhere else or press Esc to close it. The **†** and **◦** marks in the wild tables can be clicked the same way.

**Current Location** (home screen)
- Your current place, with its description from the official site.
- **Gym here**, if there is one: the leader's team with levels, and which types hit the whole team super-effectively. You can click **Mark badge earned** right there.
- **Wild Pokémon**, in one table per method (grass, surfing, headbutt…), per fishing rod (**Fishing · Old Rod**, **Good Rod**, **Super Rod**) and per area where a place has several (e.g. **Grass · Kanto Safari East**), just like the official site. Choose a time of day to see rates for morning, day, evening or night. Tick the checkbox to mark a Pokémon as caught, and use **Only ones I haven't caught** to see what's still missing. On a profile set up with **I'm new to PokéOne**, the Headbutt, rod, Surf and Rock Smash tables start folded; click one to open it (the companion remembers).
- Each wild Pokémon shows its **EV yield**, and each method has an **EV training** line worked out from the official rates, e.g. "Speed from 100% of encounters (about 1.2 per battle)". When rates change through the day, pick a time to see it. Where the site gives no rates, it counts the Pokémon listed instead, and says so.
- Some forms share one encounter slot, although the official site lists each at the full rate (Pumpkaboo's four sizes, Burmy's three cloaks). They're marked **◦** and counted once.
- Rewards, prizes, gifts, trades and fossils that the official site names only on a Pokémon's own page are listed under what they are ("Reward for beating Mewtwo", "Prize counter"), like any other row. A wild Pokémon listed only there would be marked †: each table folds such rows behind one line, e.g. **▸ 4 more the official site lists only on Pokémon pages (check in game)**; click it to see them under **Also listed †**, without a rate, so the table's rates add up. Mega forms never show as wild.
- The **?** next to "N of M caught" explains that Pokémon you add to your team count as caught.
- Where the official rates in a table can't all be right (they add up to well over or under 100%), the table is tagged **≈ rough numbers** and its numbers start with ≈. The **Key** under the tables gives the total. Headbutt and Rock Smash tables normally add up to less than 100%; there the numbers are shares of the Pokémon you battle, and a note says so.
- **Items here** (including berry trees) and **People here** (tutors, vendors, trainers and more), grouped by role, each role with a line saying what it does (e.g. Move Deleter: "Makes a Pokémon forget a move, even an HM move."). If the official site lists nothing for a place, the box says so instead of disappearing.
- **Find a service** in the side panel opens the Pokédex's NPC list with a button for each service (Move Reminder, Egg Move Tutor, Move Deleter, PvP shop and more), your current region's NPCs first, then a line **Other regions** and the rest.
- A side panel with your goals, region progress and the next badge (with **Set location: Violet City** to jump to the gym's town), your party, and tips from the official FAQ. Endgame tips wait under "more tips" until you've beaten the region's Elite Four.
- A search box with the cursor in it glows and says **Type to search · Esc to leave**.
- **Change location** is at the top: the cursor goes straight into its search box, places in your current region come first (others show their region), and Esc closes it. Moving to another region says "You're now in Kanto". Recently visited places appear as quick buttons.
- Next to it, **◀ Back to …** sets your location back to the last place you set (e.g. "◀ Back to Viridian Forest"). To see a place's own page, search for it.
- Under the place's name, **On the official list: ◀ Cherrygrove City · Dark Cave ▶** are the places before and after this one in the official site's own page order, inside your region. One click (or **Alt+↑** / **Alt+↓**) sets your location there. That order follows the journey early on but not always (it includes event maps), so it never says "next".

**Suggestions from your save (the Advisor)**
- **Next: <leader>:** what to watch out for in the next gym, from the leader's real moves ("Onix (Lv 14) knows Rock Tomb: 2× on Charmander."), who to lead with, then fixes nearest first: a move your Pokémon learns within 3 levels or can relearn, a TM or HM in your Bag (given to the Pokémon of its own type first), a bench or caught Pokémon, a wild one where you are or nearby. It sits in the gym card in that town, else at the top of the side panel, and on the next gym's card on Progress. When your party's average level is 3 or more above their strongest, only the warnings and the lead line show.
- The box is a short **fight card**: **Win?** (the verdict and the levels), **Lead** (who to lead with and the moves), **Then** or **Gap** (who answers the ones your lead doesn't, or that nothing of yours hits hard), **Watch** (their two worst moves against you) and **Fix** (more fixes fold under "▸ 1 more fix"). Hover a row for the full sentence; **Why?** opens it with the reasons.
- **Win?** starts with a verdict, from the type chart only: **✓ Ready on paper** (you hit their Pokémon hard, few of yours are at risk, and you're not behind), **◐ Nearly**, **⚠ Not ready on paper**, or **✓ Well ahead** when your party averages 10 or more levels above their strongest. When you're 3–9 levels behind, **⚠ Train about N levels first** comes first instead. When your trainer level holds your party 3 or more levels under theirs, the verdict goes one step down and the cap follows: **◐ Nearly ready: trainer level caps you at Lv 38**.
- With all 8 badges of a region, **Next: the <Region> Elite Four** takes the next badge's place in the side panel (and sits on the Elite Four's own page): how your levels compare with their strongest team, a verdict counting the members' teams you hit hard, the worst threats across the five, and fixes. After you've beaten them, it uses their daily rematch teams.
- Next to the next badge, level words: "Lv 14, your strongest Lv 9, behind by 5" ("behind" and "on track" go by your strongest Pokémon; "ahead" by your party's average, 3 or more over, so one high-level Pokémon doesn't make a weak party look ahead).
- **Good to know** starts with lines about this place and your save: Pokémon here you haven't caught and can reach ("In reach here, not caught yet: …": on foot, or with what your Bag and party can use, such as a Bat for Headbutt, a rod or a party Pokémon that knows Surf; † rows left out), a wild Pokémon here that resists your biggest risk, your EV plan here, an evolution item sold or found here (or already in your Bag, and what it costs against the ₽ you have), a Move Reminder here, a new trainer's shop, where to find a Pokémon one of your goals asks for, and a daily or weekly here you haven't done yet (e.g. "Daily here: Cerulean Valley, not done today", with **✓ Done** to tick it).
- **Last time (9 days ago): …** at the top of Current Location when you come back after 6 hours or more: where you were, your badges and your first open goal as the save held them when you opened it (what you change during this visit doesn't alter it).
- Every line has **Why?** (the facts behind it and the official source) and **×** to hide it (the message has **Undo**; several hidden quickly come back together). A hidden line stays hidden, also after a restart, until the facts behind it change; **Settings › Show hidden suggestions again** brings them all back. Type matchups only: no damage or win chances.

**Team**
- Your **party** (up to six) and a **bench**: Pokémon you're keeping an eye on but not carrying right now. When your party is full, new Pokémon go to the bench. Adding a Pokémon (**Add a Pokémon…** here, or **Add to party** / **Add to bench** on its Pokédex page) opens its Edit window for the level, moves and the rest. While it's new, **Done** (or Enter in Nickname or Level) adds it; **Cancel (don't add)**, the **×** or Escape take the add back (the caught mark and goal tick too). The message after Done has **Undo**; after a cancel it has **Add it after all**. Ctrl+Z does the same.
- **Reorder your party:** drag the **⠿** in a party card's corner to a new place, or click it and press ← → (Home and End go to the ends). The mini view and Copy team use the same order.
- **Drag between Party and Bench:** drop a party card's **⠿** on the Bench (a bench card or the Bench box, even folded) to send it there; drop a bench or Utility card's **⠿** on a party card to put it in that place. With a full party the two swap; dropped on the Party box itself, it asks who goes to the bench. Each of these says what happened, with **Undo**. **Move to bench** and **Move to party** do the same from the keyboard, and Enter on a bench card's **⠿** moves it to your party. A bench Pokémon swapped into a full party takes the place of the one it replaces.
- **Remove** asks first, and the message after it has **Undo**, which puts the Pokémon back where it was.
- **▾** beside **Bench** or **🛠 Utility** (or a click on the title) folds that group away, so the party is easier to see; **▸** shows it again. Remembered.
- **Sort by** on the bench: order added, level, name or Pokédex number (favourites stay first). Remembered.
- **The trainer level cap:** a Pokémon above your trainer level for the region fights at that level there (as players report; the official site doesn't say). When your trainer level caps a party Pokémon where you are, its card says so ("fights at Lv 32 in Johto") and the party lists show "Lv 50 → 32". All the advice uses the level it fights at, and when the cap is why you're behind, the line says to raise your trainer level (bounties, bosses and daily quests, as the official FAQ says) instead of "train". It works the same in Kanto, Johto and Unova. With no trainer level entered for a region, nothing is capped, and each box says so once.
- **▲ / ▼** on a card change its level (hold to repeat). When it reaches the level at which it evolves on the official site, the companion asks **Did it evolve?**: "Yes, into Metapod" changes it and keeps its level, moves, nature, stats and notes (the message has **Undo** for 15 seconds, which also takes the new form off your caught list if evolving had ticked it); "No, keep Caterpie" leaves it. Raising the level in **Edit** asks too. A card with no level shows **Set level**.
- **Evolve…** on the card of a Pokémon that evolves another way (a stone, a trade, friendship, a held item): pick the evolution, with the official way beside it and "(in your Bag)" when you have the item. A stone from your Bag is taken out; **Undo** puts it and the old form back. With no stone in your Bag, the message says nothing was taken out.
- **☆** on a card makes that Pokémon a favourite (this one Pokémon, not the species). **★ Favourites** shows only them (remembered), favourites come first on the bench, and the Pokémon's page says "★ Your favourite". In the advice a favourite only breaks ties: when two leads or two fixes are equally good, the favourite's comes first (its Why? says so); it never changes a verdict or a risk.
- **Copy team** puts your party on the clipboard as text, one line per Pokémon with its moves below, ready to paste in a chat.
- A card with no level says why a level helps: the gym and boss checks compare levels.
- Edit nickname, level, ability, nature, moves, held item and notes. A Pokémon whose species has only one ability (Gastly: Levitate) gets it filled in when you add it. The editor opens with the cursor in **Level**. Type a move's name in any of the four move boxes (spaces and hyphens don't matter: "Dragonbreath" finds Dragon Breath), or click a box to see the whole list (level-up moves first, then TM/HM, tutor and egg moves); it only offers moves that Pokémon can learn according to the official site. A move marked **⚠ … · check in game** is one the official site contradicts itself about; pick it and a warning under the moves says why. **Change** next to a picked move opens the box in that spot, so the new move takes the old one's place (Escape keeps the old one); **Clear** empties it and leaves the empty box in its place, with the cursor in it, so the move you pick goes into that slot and the others keep theirs (clear two and both stay empty in place until you pick or close the window). A Team card with no moves has an **Add moves** link: the gym and boss advice needs moves to see who hits hard.
- The nature on a Pokémon's card links to that nature's page.
- **Stats (IVs and EVs)**, optional and folded away until you open it: IVs (0–31) and EVs (0–252 each, 510 in total), with the nature's raised and lowered stats marked. A short plain-words explanation of IVs, EVs and the EV plan sits at the top. If you type more EVs than fit, it says how many fit.
- **EV plan:** pick a preset spread (e.g. Physical attacker: 252 Attack / 252 Speed / 4 HP) or type your own targets, then press **+1** once for each EV a beaten Pokémon gives (hold **+1** or **−1** down to count quickly, or type the number). Bars show "now / target", also on the Pokémon's card, which has its own quick +1; the app warns when a plan can no longer be finished under the 510 total. In a party, EVs count double or triple (official Discord FAQ): pick **×2** or **×3** beside the plan (on the card or in the Edit window, one choice for the whole app, remembered) and the buttons become **+2**/**+3**, while Where to train, the EV line on Current Location and its tips count per battle with it. Set it back to **×1 alone** when you play solo. **Where to train** lists places whose wild Pokémon mostly give the EVs you still need, with the table to use (e.g. **Fishing · Super Rod**) and about how many battles it takes. Places whose numbers are only approximate come last, marked **≈**. A tag says what battling there needs, read from your party's moves, your field tools (Bat, Hammer) and your rods: places you can reach come first ("uses Surf", "uses Headbutt (your Bat)"), the others say why, e.g. "needs Surf (no one in your party knows it)" or "needs Surf (you have the HM: teach it to a Pokémon in your party)". With nothing recorded yet, a hint asks you to record your party's moves and add your rods. Places the official site lists without rates are on their own line; **On foot:** names a place that needs none of those when the top three all need something; "either way" means the official site lists several methods together.
- **Party type check:** folded to a short summary under your party until you open it (▸ beside the title, or click the line; remembered), so the party and bench stay close together. Opened, it shows four short lines first: what to **watch out for**, **your answer** from what you have, **your moves**, and the **next gym**. **Show the full check** opens the rest (the companion remembers whether it's open): your biggest risk in one sentence (e.g. "Ground is your biggest risk: 4 of 6 are weak to it"), then what would help from what you already have: party and bench Pokémon and Pokémon you've caught that resist it, and your moves that hit that type hard (the same Pokémon with the same move once: "Water Gun (Squirtle ×3)"). The **?** beside "biggest risk" explains why one type can rank above another with more weak Pokémon (resisting and immune ones count against it). A move kept on a Pokémon that can't learn it by the official list still counts, marked "(check in game)". It also lists the types your moves don't cover, with level-up moves that would (and whether a Move Reminder can teach them now), and how your party matches the next gym. The full counts are under **Details**.

**Bag**
- Two pockets: **TMs & HMs** and **Items**. Add one by typing its name, number or a move type ("tm26", "earthquake", "ground", "fire stone"); **−** and **+** change the count (up to 999), or click the count to type it; **×** takes it out (with **Undo**). An HM is added once and is **never used up**; its row says who in your party knows the move ("Ferry knows it"), or that no one does yet. Your **₽** and **Gold** go at the top (digits only).
- **Quick update…** is for many at once, such as after a long session: every TM in number order (the HMs as tick boxes), or on the Items tab one pocket at a time (it opens on the pocket where you have the most). Type the counts your bag in the game shows; **Tab** or **Enter** goes to the next box, an empty box means none, and a filter finds a number, name or type (on Items, in every pocket). Changed boxes are shaded. **Review** lists what's new, other counts and what's taken out before anything is saved; after **Save**, one **Undo** takes back the whole batch. Leaving the Bag page keeps the boxes you haven't saved yet, until you close the app.
- Each entry links to its Pokédex page and says where to get it in one line ("Get it: 2 shops · found in 1 place"). Most TMs are also in the reward pool that 17 bosses share ("in 17 bosses' TM pool (67 TMs)"): each of those bosses can give one of them.
- **Teach to…** lists the team Pokémon that can learn that TM or HM (party first). The move goes into a free slot, or you pick which move it replaces. A TM is used up; the message has **Undo** (15 seconds), which takes back that move and gives back one TM.
- TMs and HMs you have also show in the Team editor's move lists (**in your Bag ×2**), on a Pokémon's page (**TMs and HMs in your Bag it can learn**), on each item's page (**In your Bag**, or **Add to Bag**), and in the advice before a gym ("Teach Quilava TM31 Brick Break from your Bag").
- **Worth selling** lists the items in your Bag that an Item Maniac buys: the best buyer and where they are ("Sell to Niomi (Vermilion City); also …, same price"), the price and the total. Items your team still needs to evolve are **Kept** and left out of the total (one stone per Pokémon; a second one is a spare). A fold lists everything the Item Maniacs buy.
- Your party's moves (Surf, Rock Smash, Headbutt), the field tools (Hammer, Bat, Axe, Flashlight, Climbing Boots) and the rods in your Bag tell **Where to train** (on Team) which places you can reach. An HM alone in the Bag isn't enough ("you have the HM: teach it"), and a 🛠 Utility Pokémon outside the party must join it first. The **Field moves** line in Team's 🛠 Utility group lists what your party and tools cover (Headbutt and Rock Climb too), then **not in party** (a dashed chip per mule outside the party, with its moves) and **to teach** (an HM in your Bag nobody in your party knows).
- The companion can't see your game's bag: what you add here is what it knows.

**Today** (Ctrl+4)
- The dailies and weeklies from the official **Daily Guides**, each with its place, what you need, the reward and a link to its guide. At the top: when the daily reset is, in your own time. The countdown itself is at the bottom of the menu on every page (↻ 15 h 59 min · Daily reset · 3:00 AM); it turns amber in the last hour, says "Daily + weekly" on the day the weekly reset comes too, and a click opens Today.
- Tick what you've done. Ticks clear by themselves at the reset: **10:00 UTC** every day for dailies, **Tuesday 10:00 UTC** for weeklies (the times come from the game's own `/reset`). Silph Co. counts 2 days from your tick, as its guide says.
- Each row says whether your profile allows it: **✗ not yet: …** (e.g. "trainer level 80 in Kanto (yours 61)") or **? check in game: …** (something the app can't see). Ones you can do come first; **Hide what I can't do yet** hides the ✗ rows. Guides that don't say how often, or leave something unclear, say "check in game".
- A step a daily needs (a password, a quest before it) can be ticked on its row: it's the same tick as on Bosses.
- A timed one shows **● On now** while it's open, e.g. Lapras in Union Cave from Friday 10:00 to Saturday 10:00 UTC, and otherwise when it next opens.
- **Bosses** at the bottom lists the bosses you logged with **I fought it just now**, each with its countdown or "ready again".
- Tabs at the top pick the region (**Kanto · Johto · Unova · All regions**), like on Bosses; it opens where you are, and a line says which region you're looking at. **All regions**, **Hide done** and **Hide what I can't do yet** are remembered.

**Progress**
- Every gym is a card with the leader's team and the attack types strong against it, with which of those your party's moves have (or "none in your party's moves yet"); earned ones are green. The next gym you haven't earned has a **Next up** frame with its advice.
- Badges for Kanto, Johto and Unova, with each leader's team. Click **Mark badge earned** on a leader's card when you win the badge. Johto's badges are numbered 1 Falkner to 8 Claire, the usual order (the official site gives none; the game lets you take some out of order). Un-marking a badge by mistake? The message that appears has **Undo**. For some Unova leaders the site also lists a much stronger team; it's folded under **A stronger team is also listed**.
- Elite Four for each region: **Mark Elite Four defeated** (un-marking offers **Undo**), with a link to their teams. Their page has your party check under every member's team, as on gyms and bosses. Once marked, the advice uses their stronger **daily rematch** teams instead of the story ones.
- A **<Region> Pokédex** box: how many of the region's wild Pokémon you've caught ("caught in all of Johto"), **Still to catch** with where to find each one (Surf, rods, time of day and so on), and **By place** with each place's count. The companion remembers which of the two you opened.
- Your **trainer level in each region** (PokéOne keeps a separate one per region). Its **?** says what the companion uses it for: reaching Unova, boss requirements, and the level your Pokémon fight at in that region. It starts at 5.
- Until you've been to Unova or hold a Unova badge, its tab reads **Unova · later**, or **Unova · open** once you meet the official rule (an Elite Four and trainer level 80 in Kanto or Johto); it opens on what it takes to get there.
- The requirements for reaching Unova, and which of them you already meet ("(not set)" until you enter a trainer level). The level requirement uses your Kanto or Johto level, whichever is higher.
- On every gym you haven't earned, a folded **Your party** box: their strongest level next to yours, how many of the leader's Pokémon your moves hit super-effectively, how many of yours are at risk, and the best match on paper (or "under-levelled by N" when their strongest is 10 or more levels above yours). Open it for the same fight card as the next gym's: Win?, Lead, Then or Gap, Watch. The next gym's card has the fight card itself, so it has no Your party box (a gym with several teams keeps one per team).

**Bosses**
- Until you've beaten an Elite Four, a line at the top says gym leaders like Brock or Falkner are on **Progress**.
- The page is a short list, one line per boss: its place, its tag, "once a day" when its official guide says so, and its level. Click a line to open the boss's full card (or **Open all**). Above the list: the region tabs, a search over bosses, places and Pokémon, a **Sort** (Can I do it?, Level, Name) and filters with counts (**✓ Can do now**, **⏱ Waiting**, **Needs a step**, **✗ Not yet**, **Once a day**, **Ready again**; some appear only when they apply). The counts follow your search and the other filter. The search ignores spaces and dashes ("hooh" finds Ho-oh) and says when a boss is on another region's tab (**Also found in Unova: Kyurem**, with a button to go there). The companion remembers the region, filter and sort (**Settings › Region tabs** can change which region it opens on). A level from a team with modes reads **Lv 65+ (Normal)**; a boss with two places names the place its tag is for.
- Each boss has a tag: **✓ Can do now**, **Needs 2 steps** (quests, tickets or story steps the app can't see; they're listed under the boss's line as tick boxes, so you can tick them right there), or **✗ Not yet: …** (what's missing, e.g. "the Kanto Elite Four" or "all 8 Johto badges (you have 3)"). The tags check your badges, Elite Four, trainer levels and the steps you've ticked, and compare your party's average level (at your trainer level cap in the boss's region) with the boss's ("a much stronger party"). Bosses you can do now come first, then those needing a step, then "not yet", each from the lowest level up.
- Next to each name, the boss's official category: **Single**, **Mini Boss** or **3 Mode** (you choose Normal, Hard or Champion; Champion-mode Pokémon are Lv 110). Under it, what changes each day, where an official page or the staff say so: **place changes daily** (Volcarona, Wesker, Jeck Spearow), **team changes daily**, **form changes daily** (Mewtwo's Mega, Deoxys). It says what changes, not that you can fight it every day.
- What no official page says, or where two official pages disagree (Coach Matt Han's requirement, Ho-oh's and Lugia's level), is in one quiet line under the list: **Not on any official page yet: …**. A boss whose only open point is one of these shows **✓ Can do now**.
- An opened card reads in the order you play: **Am I ready?**, **How to unlock** (requirement, how to start, the tick boxes), **When** (how often, what changes daily), then the teams and **I fought it just now**.
- **Players say (not official):** a small grey line where players say something the official pages don't (Volcarona every day, the Regis as dailies, Ho-oh at Lv 85), with where and when. The app never decides anything from it. The same line appears on Today (the Ghost). Ho-oh and Lugia appear on both the Kanto and Johto tabs, marked "(also in …)".
- All 26 boss battles, by region: requirement, place, how to start the quest, the teams and their levels (bosses with **Normal**, **Hard** and **Champion** modes show a level for each), and **Your party** against each team.
- **When:** how often, or on which days, a boss can be fought, where the official Boss Guides say so (e.g. Ho-oh at Bell Tower: once per day, again after the reset; Darkrai's dream changes by weekday; N only on Fridays). Where they don't, **How often** says "Not on the official site yet."
- **I fought it just now** on each fight logs the time (with **Undo**). The boss then waits with **⏱ Fought 50 min ago · again in 8 h 30 min**, and reads **✓ Fought … · ready again** once it's back: bosses whose official guide says once a day come back at the daily reset (10:00 UTC), the rest at the weekly boss reset (Tuesday 10:00 UTC). The card says which rule it used and why.
- **Tick what you've done:** the quests, items, tickets and story steps a boss needs are tick boxes on its card. A tick counts for every boss that needs it (tick "the Sevii Islands main story" once and every boss that needs it sees it). Items in your **Bag** (the wings and bells, the Jade Orb…) tick themselves. An HM step (Surf, Flash, Strength) ticks itself when a Pokémon in your party knows the move ("Lapras knows it") or a field item does its job (a Flashlight for Flash). In the game the HM alone isn't enough: with only the HM in your Bag it says "→ You have the HM: teach it to a Pokémon in your party", and a 🛠 Utility Pokémon that knows the move but isn't in your party gets "→ Ferry knows it: put Ferry in your party". A step needed each day, such as a daily ticket or password, clears at the daily reset. With everything ticked, the tag becomes **✓ Can do now**, unless the boss's strongest Pokémon is 20 or more levels above your party's average: then it says **✗ Not yet: Lv 65 vs your 40** (hover for the full reason; a line above the list explains the trainer level cap when it applies). This is the companion's advice, not a game rule: the game lets you try.
- Under a fight you can do (or can once you check in game), the **Your party** box's fight card adds a **Fix** row: the top fix, with "▸ 1 more fix" for the second.
- A team listing more than six Pokémon is a list the boss picks from; the page says so.
- Where the official site lists one Pokémon once per moveset, the card says so: Ho-oh at Bell Tower, Lugia at Whirl Island and Ash's Pikachu are **one Pokémon with one of 3 movesets**. For the Hoenn trio's variations and Volcarona, nothing official says whether you meet one or all, so the card says to check in game.
- If your party has two of the same Pokémon, the boss card says so: the official rule doesn't allow it against bosses.

**Pokédex**
- Pokémon, moves, abilities, items, places and NPCs, with search and filters (type, region, caught or not, and more). Each Pokédex number has one row; other forms (Pikachu's caps, Rotom's forms, Megas) open under **▸ N more forms**. Tick **Caught** right in the list; it works like the Caught box on the Pokémon's page (catch goals tick too, with Undo).
- A Pokémon's page shows its **Abilities** at the top, under EV yield and catch rate (the hidden one marked; point at a name for what it does). The full Abilities box is still further down.
- On a profile set up with **I'm new to PokéOne**, a Pokémon's page folds **Stats, abilities and type defenses** and **Moves** (with how many of each kind) until you open them; the companion remembers which you opened. Other profiles see them open. Places the official site lists only on the Pokémon's own page fold behind a count too (**▸ 38 places listed only on Politoed's page**), unless they're all the page has (Latias).
- Every entry links to related entries. A Pokémon's page starts with its **evolution strip**: the whole family as pictures, with the condition on each arrow, regional lines (Alolan) on a row of their own and Megas and other forms in a row below; click any of them to open it. Then where to find it and its moves. An item's page shows where to buy or find it.
- **Where to find** on a Pokémon's page has two lists: **Catch in the wild** (place, how, rarity, chance and when) and **Rewards, gifts and trades** (for example "Reward for beating the Kanto Elite Four" or "Hidden item: Helix Fossil"). Long lists keep your current region open and fold the others.
- A Pokémon's page shows its **catch rate** from the official site (higher is easier; 255 is the easiest), and a folded **Catch calculator**: pick the ball, HP left (or False Swipe), status and its level, and it shows the chance per ball, how many balls for 50% and 95%, and your own balls ranked. It uses the same rules as the official Catch Rate Calculator on the Pokémon Hunting Guide (rounded to whole percents) and keeps your settings for the next Pokémon.
- **Tabs:** every Pokédex page you open becomes a tab next to the search box, so a few Pokémon can stay open while you farm. Click one to switch, **×** or a middle-click closes it; **Ctrl+click** or a middle-click on a link opens one in the background; **Ctrl+Tab** moves between them and **Ctrl+W** closes the one on screen. Up to 8 are kept, also after a restart; past that the oldest closes, and the app says so.
- The **Tutor** moves tab names each tutor, where they are and what they charge (e.g. **64 BP**, **10× Red Shard**). Prices are written as in the game, e.g. **₽5,000**; **Gold** is a separate currency.
- **Natures:** all 25, with the stat each raises and lowers (by 10%, from the official natures page) and the berry flavours it likes and dislikes. Filter by what it raises or lowers; each nature's page lists your Pokémon that have it.
- **NPCs:** the **Find a service** buttons at the top list, say, every Move Reminder, your region first.
- **Type matchups:** pick one or two types to see what hits them hard.

**Goals & notes**
- A simple goal checklist. You can also add a "catch" goal from any Pokémon's page. Marking that Pokémon caught (or adding it to your team) ticks the goal, and ticking the goal marks it caught; one **Undo** takes back both. A goal typed as "Beat Brock" (or "Beat the Elite Four") ticks itself when you mark that badge (or that Elite Four) on Progress, again with one **Undo**; a rematch goal is left alone. Ticking Lapras caught in Union Cave during its Friday window also ticks the Lapras weekly on Today.
- A free notes area.

**Search anywhere:** the search box at the top finds any Pokémon, place, item, move, NPC or nature ("adamant"). Press **Ctrl+K** to jump to it. **Shift+Enter** on a place sets it as your location straight away, and on an item it adds one to your Bag (with Undo), from any page; the highlighted result says which. Shift+click does the same. Escape clears the box; a second Escape leaves it.

**Beside the game** (Settings › Beside the game)
- **Ctrl+Shift+P** shows or hides the companion and **Ctrl+Shift+F** brings it up ready to search, even while the game is in front. You can pick other keys or turn them off.
- **Keep the companion on top** keeps it over the game window (off at first).
- **Mini**, at the end of the top bar (or **Ctrl+M**), turns the companion into a small window on top of the game (360 × 320 the first time, in the top-right corner): search, where you are, the next badge with two short lines under it (the first line of the Next box, e.g. "⚠ Train about 6 levels first", your top "for you" line, and the timers, e.g. "⏱ Daily reset in 3 h 12 min · 2 bosses ready · Ho-oh again in 8 h"; click one to open it in the full app), then four tabs: **Here** (the Pokémon here with caught ticks, EV yield and rates), **Party** (each Pokémon with **Lv ▲ ▼** and its moves), **Today** (the dailies and weeklies left in your region, to tick off) and **Goals**. It opens on the tab you used last. Move it and resize it where you like; **◐** makes it a little see-through (100%, 90%, 80%). **📌** switches staying on top on or off (lit = on top of the game). **⤢ Full** (or Ctrl+M) puts the app back exactly as it was, and anything you open from the mini view opens there. All of it is kept after a restart.
- In a narrow window, Current Location shows your badges, next badge and goals in one line at the top.
- Keys inside the app (all of them: **Ctrl+/**, or Settings › Keyboard shortcuts): **Ctrl+1 … Ctrl+9** for the menu pages, top to bottom (Team is Ctrl+1, Current Location Ctrl+2, Bag Ctrl+3, Today Ctrl+4, Settings Ctrl+9), **Ctrl+L** for Change location, **Ctrl+H** for "I'm here now" on a place's page, **Alt+↑ / Alt+↓** for the places before and after on Current Location, **Ctrl+Z** for the Undo in the newest message (outside a text box). The full list is in Settings.

**Zoom:** Ctrl + plus, Ctrl + minus, or Ctrl + 0 to go back to your text size.

**Settings › Display** also has **Text size** (Smaller to Largest), **Open on** (the page the companion opens on: Team unless you pick another, or the page you last had open), **Region tabs** (the region Progress and Bosses open on; unless you choose, Progress opens where you are and Bosses on the region you last picked) and **Motion** (Follow Windows or Reduce). All are kept after a restart.

**Going back:** the **←** button at the top (Back), **Alt+Left** or your mouse's back button return to the previous page, tab and scroll position.

### A note on the information shown

- Rates, levels and locations are as listed on the official site. If the game differs, **the game is right**. Please tell us when you notice a difference.
- A small **†** next to a wild Pokémon on a place's list means the official site lists it on the Pokémon's own page but not on that place's page. The site disagrees with itself there, so treat it as "check in game". (On the current data no wild row needs it; rewards, prizes, gifts, trades and fossils never get it.)
- Some TM/HM rows are marked **verify** (and **⚠ … · check in game** in the Team editor) because the official site lists a different move for that machine number than it does everywhere else.
- The **Johto** badge order is not published by the official site. The numbers 1–8 are the usual order, confirmed by a player; the game lets you take some gyms out of order.

## Profiles (playthroughs)

**Settings → Profiles** lists your profiles.
- **Add a profile** starts a new playthrough without touching your current one. Each profile needs its own name (capitals don't make a name different). Leave the name blank and it says the profile will be called "My playthrough"; names stop at 60 characters.
- **Switch** opens another profile on your start page (Team, or what you picked in **Open on**). Your current one is saved first.
- **Rename** or **Delete** the open profile. A deleted profile is not erased: it's moved to the `removed` folder inside your data folder, just in case.

## Saving and persistence

- **Automatic:** every change saves on its own within a moment. You never need to press Save.
- **Automatic backups:** the app also keeps recent backup copies of each profile (one when you first change something in a session, then every 20 minutes while you keep changing things; the newest 20 are kept, or 5, 10 or 50 as set under **Settings → Backups**; older ones move to the `removed` folder). The newest 10 are listed under **Settings → Backups**.
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
- Restoring always **adds** the profile. It never overwrites the one you have open. If the same profile already exists, the restored copy is added next to it with "(imported)" in its name, and **the app switches to that copy** (you stay on Settings): check the profile name at the bottom left, and switch back in **Settings → Profiles** if you meant to keep playing in the original.
- Files that aren't valid companion backups are refused with an explanation, and nothing changes. Badges and natures the game doesn't have (only a hand-edited file could list them) are left out.

**From an automatic backup**
- **Settings → Backups** lists recent automatic backups of the open profile, each as "Data from …" (when that data was saved). Click **Restore** next to one; you stay on Settings. The version you're replacing is backed up first, so you can undo it the same way.

## Starting over

To start a fresh playthrough while keeping your current one, go to **Settings → Profiles → Add a profile**.

To get rid of a profile, go to **Settings → Profiles → Delete this profile…**. Consider saving a backup file first. The deleted profile is moved to the `removed` folder rather than erased. If it was the open profile, the app then asks which profile to open (or offers to start a new one).

## Where your data is stored

Unless you choose another folder, your profiles are saved in your Windows user folder:

`%APPDATA%\PokeOne Companion`

(Usually `C:\Users\<your name>\AppData\Roaming\PokeOne Companion`.) **Settings → Data folder** shows where your data is and has **Open data folder**. Inside you'll find:

- `profiles`: your profiles;
- `backups`: automatic backups;
- `removed` and `quarantine`: profiles you deleted, and damaged files set aside;
- `logs`: a small log of app events for troubleshooting. It contains no notes or team details.
- `settings.json`: your display choices (Light/Dark), the window size and which profile was open last;
- `chromium`: the picture cache and other files the app's built-in browser engine keeps, including small preferences such as a hidden **First steps** box. It also contains your folder path, so share a **backup file** rather than this folder.

Deleting the app folder does **not** delete this data. Please don't edit these files by hand while the app is open.

### Choosing another folder

The first Welcome screen says where your data will be saved; **Change** picks another folder. (If the companion was started with `--data-dir=<folder>`, as test copies are, that folder is fixed: Welcome shows it without **Change**, and Settings says why.) Later, **Settings → Data folder → Move to another folder…** does the same:

1. Choose a folder. An empty folder is used as it is; a folder with other things in it (such as Documents) gets a **PokeOne Companion** folder inside.
2. The companion copies your profiles, backups and settings, checks every file, and restarts using the new folder. If anything doesn't check out, nothing changes.
3. The old folder stays as it was, with a `MOVED-TO.txt` saying where the data went, until you choose **Remove the old copy** (it goes to the Recycle Bin) or **Keep it** in Settings.

**Move back to the default folder** returns it to `%APPDATA%`. If the old copy is still there (you chose **Keep it**), it is first set aside in a folder named **Old copy <date>** inside it, never deleted. A small file there, `location.json`, remembers the folder you chose, so keep the `PokeOne Companion` folder in `%APPDATA%` even when your data lives elsewhere.

If the chosen folder isn't there when the companion starts (a USB stick that isn't plugged in), it asks: **Try again**, **Use the default folder this time**, or **Quit**. With **Use the default folder this time**, a bar on every page reminds you that changes are now saved in the default folder, not in your folder (**Try my folder again** restarts and looks again); moving the data is off until then. At the next normal start, if you changed anything in that session, a box names the profiles and where they are. To bring one over, click **Open that folder**, then use **Settings → Backups → Restore from a backup file…** and pick it from that folder's `profiles` folder (it comes in as a copy). The box comes back at each start until you click **Got it**.

**Advanced:** **Keep my data next to the app** puts it in a **PokeOne Companion Data** folder beside the app, for running the companion itself from a USB stick on any computer. To keep only your data on a stick, use **Move to another folder…** instead.

A cloud-synced folder (OneDrive, Dropbox…) works, but don't open the companion on two computers at the same time: they would overwrite each other's changes.

### Removing everything

**Settings → Delete all my data** removes everything the companion saved on this computer in one go: every profile, the automatic backups, settings, logs and the saved pictures (with the zoom the window remembered), and an old copy you kept after moving your data folder. It first offers **Save backups of all profiles…** (one backup file per profile, in a folder you pick), then asks you to type **DELETE**. Everything goes to the Recycle Bin, and the companion starts fresh at the Welcome screen.

To take PokeOne Companion off your computer completely:

1. If you might want your progress later, save a backup file of each profile first (see [Exporting / backing up](#exporting--backing-up)).
2. Close the app.
3. Delete the app folder you extracted.
4. Press **Windows + R**, type `%APPDATA%`, press Enter, and delete the **PokeOne Companion** folder there.
5. If you moved your data to another folder (Settings → Data folder), delete that folder too.

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
  - A few TM/HM entries conflict (marked "verify", or ⚠ in the Team editor).
  - The Johto badge order isn't published (the app's numbers come from a player).
  - Some "where to find" details, such as the rarity of Elite Four rewards, aren't available.
- **The trainer level cap comes from players, not the official site**; it works the same in Kanto, Johto and Unova. If you see it work differently in game, please tell us.
- **Matchups are by type only.** The party check, **Your party** boxes, the verdicts and "best match on paper" use the official type chart and the moves listed, plus a comparison of levels. Stats, held items and abilities (except Levitate) aren't counted, and there are no damage or win chances.
- **The app can't see your quests, items or story.** On Bosses they're "Needs a step", and on Today "check in game", until you tick them (or add the item to your Bag).
- **Boss timing is only what the official guides say.** Where a guide says once a day, the countdown uses the daily reset; for every other boss it uses the official weekly boss reset (Tuesday). The **How often** line says "Not on the official site yet" where no guide gives a rule; if the game lets you fight sooner, please tell us.
- **Catch chances follow the official calculator.** The Catch calculator uses the official Catch Rate Calculator's rules (Gen 7, as PokéOne). Its "dark grass, double battle" option is the website's own estimate, not a known game rule.
- **Where to train knows only what your Bag and team say.** It reads your party's moves and the rods and field items in your Bag, but not how far you are in the story, so it may still suggest a late-game place. In the Safari Zone, battles are normal but have a step limit and only Safari Balls; that EVs are given there is assumed, not confirmed.
- **Starter help covers Kanto and Johto.** Unova can't be a starting region.
- **No story walkthrough.** The official site doesn't publish a step-by-step story guide we could check against, so the app doesn't guess one. Use Goals for your own objectives.
- **Reset times are the game's `/reset` times** (10:00 UTC daily, Tuesday 10:00 UTC weekly). If the game changes them, ticks and countdowns will be off until a later beta.
- **The show/hide and search keys can't be set to any key you like**, only picked from a short list. If a game or another program already uses one, Settings says so; pick another.
- **No automatic updates.** New betas are downloaded manually. Your profiles carry over.
- **Pictures need the internet** (they load from the official site).
- **Profile backup files are one profile each.** There's no single "back up everything" button yet (you can copy the whole data folder instead).

## Help answer open questions

The official site doesn't say everything, and sometimes contradicts itself. The app marks those things **check in game** rather than guessing. If you can check one while you play, that helps a lot.

- The download page has a list of these open questions, grouped by region and place (`OPEN_QUESTIONS.md`). Each starts with a short id in bold, such as **SEASON-NOW**. A few quick ones anyone can answer come first.
- To answer one, open a **New issue** (see below) and pick **I know the answer**: give the question's id, what you saw in the game and how sure you are. A screenshot is optional; crop it to the game window so no names show.

## Reporting bugs

**Where to send reports:** https://github.com/sesh-labs/PokeOne-Companion/issues

1. Open that page. Anyone can read it; to write a report you need a free GitHub account.
2. Click **New issue** and pick **Bug report**, **Wrong or missing game information**, **Idea or suggestion** or **I know the answer**.
3. Give it a short title (for example "Badge doesn't stay ticked after restart"), fill in the form, and click **Submit new issue**. You can follow replies on the same page.

The **Report a problem on GitHub** button in the app's **Settings → Feedback & bug reports** opens the same page. Reports are public, so don't paste anything private. The diagnostic information is safe to include.

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

- **Application:** PokeOne Companion **0.2.4-beta**
- **Platform:** Windows 10/11, 64-bit (portable zip)
- **Game data:** from the official PokéOne website. The exact data date is shown in **Settings → About**.
