## Launcher 1.8.4
- Launcher logs its startup, progress and silently-handled failures

## Launcher 1.8.3
- Launcher trusts the JDK's root certificates as well as Windows'
- Launcher Changelog button opens the public repo's CHANGELOG.md

## 1.5.0
- Focus follows panels, Tarasque spawn timer, scroll and taskbar fixes
- Damage meter row details, scroll fixes, no row hover flicker
- Mission tracker: per-mission bars, run summary, chest fix
- Start each new guide/search page at its top
- Combat UI: resizable HUD elements, show/hide, scroll direction
- WhatBuffs: team buffs, NCU/Level columns, Shade tabs, sort fixes
- Shorter trade posts: family sections and bare nano names
- Post the same item, QL and price once with its total quantity
- Read mission token lines with the combat log parser, not a second feed
- Tell the token bar about changes once per log tick; tighten the thread rule
- Release the mission token chance bar; keep Missions behind its flag
- Show the mission token chance as a movable HUD bar
- Track each character's mission token chance from the chat log
- Keep live inventory updates off the capture and JavaFX threads
- Link a bag received in a trade to its contents the first time it's opened
- Keep the combat log feed running when an online character has no name yet
- Add pattern finder and live inventory tracking for trades, loot, use and credits
- Name the owner of shared ready icons when toons share a screen

## 1.4.0
- Add What's New, a setup prompt, and a shared look for About and Settings
- Improved the player detection and log parser
- Lay out bag contents like the in-game bag window
- Learn player professions from /list and move damage meter data to its own folder
- Never let a failing shutdown step escape Application.stop()
- Draw animated HUD elements in their own small windows
- Cut overlay redraws: 4Hz duration bars, 30 fps cap, stop idle loops
- Show misses, evades, shields and drain perks in scrolling combat text
- Split the combat log feed from the damage meter
- Parse shields hitting you as damage taken and drains as heals
- Widen the anchor bar's hover area to 200px
- Compact, sorted trade scripts and QL-aware matching of them
- Filter script-item records out at import
- Move blocking work to virtual threads and trade writes off the FX thread
- Move all trade data into a gitignored trade/ folder with targeted writes
- Link inventory bags into the trade lists and keep them live-synced
- Chain trade scripts past AO's 4096-byte limit and rework the trade tabs
- Fix the position of the inventory in regards to the bags in inventory
- Move bag sell/buy glyphs above each opened bag box
- Added sell/buy feature in inventory/bank for bulk trading

## 1.3.1
- Add timer interaction open sound
- Added more pet levels
- Improved sounds
- Combat UI checkbox hides everything now
- Fix guide interaction having two prev next sets of buttons
- Added pet level info for engineer, crat & mp
  
## 1.3.0
- Shift+Shift search history: Prev/Next through the last 25 searches
- Perk action level data: Evasive Stance and 35 more actions now carry every level
- Show perk actions' real icons in /p search results
- Give Evasive Stance its ten levels of All Defense and duration
- Fix LazyInitializationException opening nanos that name another nano in a requirement
- Quality slider for WhatBuffs weapons/armor, Setups equip rows and Weapon DPS
- Assert the launch-created AONewbie window is hidden and logged
- Create the AONewbie chat window hidden and automatically at launch
- Place inventory items from the game's own Inventory.xml layout
- Restore the old window format and swap the trade channel in the AONewbie window on switch
- Window setup (work in progress): create-only, no frame, created closed
- Nano List: gray row highlight instead of the red line for FP Agent/Froob
- Clean symbiant duplicates out of the shipped database and on interrupted rebuilds
- Nano List scratches instead of hiding; search matches groups and bag names
- Add shared input controls and use them in WhatBuffs
- Parse the colour-tagged Tarasque System announcements

## 1.2.1
- Create or recreate the AONewbie chat window; drop legacy window support
- Tell players from single-word mobs by evidence, not by spelling

## 1.2.0
- Tail the chat log faster and prune it at launch
- Never attribute a Damage Done row to whoever attacked the tracked player
- Skip a superseded character when auto-resolving screen assignment
- Fast-reject a combat log line before running its full rule set
- Replace per-bar AnimationTimers with one shared tick in DurationTimerView
- Exclude Calm/Mezz pacify nanos from duration-timer tracking
- Split Bureaucrat's Charm Other nanoline into Long/Short/Team Empowered groups
- Fix WhatBuffs profession filtering, require a profession, and redesign it's implants tab
- Verify scheduleAtFixedRate never overlaps a task with itself on the shared pool
- Consolidate the low-frequency character-detection pollers onto one shared scheduler
- Decouple combat text/sounds/trade from the damage meter; one shared log window
- Debounce search-as-you-type across SuggestField and the main item search
- Fix Weapon DPS Calculator special-attack detection + search cap bug
- Add a real "Special:" weapon-attacks field to item details
- Add the "FP Agent" / "Froob" tag and Nano List filter checkboxes
- Fix and extend nano-crystal item linking; add the real crafting chain
- Let charm-line nanos exceed the duration-bar 5-minute cap
- Fix mislabeled/uncategorized Nano List groups in the aogalaxy catalog
  
## 1.1.0
- Combat/Sounds/Anchor settings overhaul, panel default-size sync
- Load Inventory/Setups/Settings data in the background

## 1.0.0
- Let's gooooo!

## Launcher 1.8.2
- Fix wrong uninstall property: MSIFASTINSTALL never disabled rollback
- Remove the now-unused launcherReleaseManifest task and doc references
