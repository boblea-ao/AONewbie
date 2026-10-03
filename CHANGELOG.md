## 2.0.0
- One reader for every data file; boss timers from the kill; default HUD layout; skin flagged
- Inferno dyna bosses linked to their pocket bosses; the data pipeline rule
- Boss kill timers: a killed boss offers its timer; respawns per server
- Timers: no double fire on the due tick; a boss message starts a stopped timer
- WhatBuffs: Spirits scale with quality; Setups: AI level capped by level
- Buff strip: the Meta-Physicist's composites are their own group
- City raid timer, AONewbie Link over Vicinity, one Menu sounds switch
- Settings: scrolling text kinds, per-sound switches, Combat/Track bars, General style
- Mission Log: alien missions list the Alien Invasion quest guides
- Frame colours with our own picker; outline clear of icons; target icon size
- Frames, XP bars, team and mission log batch
- Mission Log: completed grouped by name, delete, blitz no-token fix
- Party frames: buff icons fitted to the bars, bars never move; outline back
- Overlay topmost guard: a real HWND_TOPMOST - its raise never worked
- Tests: look up suggestion popups on the JavaFX thread; no endless poll
- Buff icons as their own strip; one 1 s clock for icons; frame right clicks
- Deleted characters from the game's list; client-read max; per-client close
- Game commands through the hook: zone scripts, Follow; zone-in decoded
- Party frames: a right click always opens the menu
- Wheel over an open dropdown, suggestion list or menu scrolls it
- Follow released: no feature flag; 1.6.2 notes on master
- Right-click menus: one at a time, closed by a press anywhere off it
- What's New: releases oldest first, in the order they came out
- Bank / inventory: a clump's type in cyan on its icon
- Solid clumps: each low/high id pair one QL-range family, clumps named by type
- Weapon special cycles: note the GM-only A.F.D. Twohander row
- Deleted missions no longer count as completed; alien XP per hour in a mission
- Weapon DPS specials as the item panel's rows (SpecialSkillRow)
- Specials from Nadybot / AO-Universe, PRKHelper dropped; missing weapon cycles from aogalaxy
- Hook-first missions and XP, game UI kept in step, Level tags, specials box, Follow (flagged)
- XP bar from the level table, specials calculator, aligned requirements, mission menu, quest info
- Mission Log: type icons, right-click Upload to map / Delete; loot shown as is; hook note removed
- Frames batch: number formats, bar heights, buff icon placement; trade channels and short posts
- Bug batch: notifications font, cast names from capture, chat window and skin kept in step, live XP
- HUD pass: game bars follow our switches, hover-only bars, target info from the client
- Frames on a second screen: Lock/Move places each handle on its own screen
- Notifications: movable HUD cards for timers, trade matches and finished missions
- Over-Equip inline on requirement lines; special-attack caps; init calculator rounding fix
- XP bar: text shrinks onto a thin bar; XP left to regain in blue; dataset counts refreshed
- Over-Equip on weapon, armour and pet-nano panels; SpotBugs / Checkstyle / coverage pass
- Frames pass: range beside the target's bar, short professions, plain party names, party buff icons
- Game windows and range fixed from the first in-game trace; debuff hover shows its modifiers
- HUD out of the way of the game's windows; range to the target
- Team bars: level and profession before the name, as the target frame; leader in forest green
- Bars: XP / SK, alien XP and PvP score bars of our own
- Settings: on/off switches in place of Show checkboxes; Lock/Move sizing and snapping
- Team known right after an AONewbie restart
- Running nanos: icons for icon-less effects; no 'not found' remembered during the import
- Hook: the game's own bars come back when AONewbie goes; team and XP trace; rebuilt binaries
- Damage meter: trimmed frame, no padding of its own, smaller footer controls
- Running perk effects keep their icon
- Target timers move into the target frame; Player timers renamed
- Mission log: keep every finished mission, load files saved before rewards
- Remove trace logging from the app and the hook
- Own level and profession read from the client at start
- Capture scan: every 30 s once a client is hooked, a client closing ends the wait
- WIP: checkpoint before restarting
- Own stats read through the hook; character switch, tabbed-out HUD, real max health
- Overlay: put our windows back on top when the game gets in front of them
- Lock/Move snapping and plain placeholders; Frames renames; AONewbieGUI tag; About credits
- Combat HUD: cast bars block, Frames settings sections, party level/profession, hide on logout
- Combat HUD: hook-side team select, Combat settings tabs, timer start stamps, traces
- AONewbieGUI released; hook, focus and review fixes for 1.7.0
- AONewbieGUI: game timers, con colours, focus-free overlay, frame fixes
- Remove /list entirely
- Damage meter: Shadowknowledge leads the XP tab from level 200
- Implant compare: fix the class doc's wording
- Implant compare: the picked symbiant stays the reference when stepping
- Inventory: replay a real equip-from-backpack through decoder and model
- Setups: a compact share code that fits in one AO chat message
- Fonts: remove a font you added
- Panels: a slight cyan edge on every panel
- AONewbieGUI: the F10 round-bars option switches game bars vs our frames
- AONewbieGUI: right-click menus on the frames run the game's own actions
- AONewbieGUI target frame (JavaFX)
- AONewbieGUI party frames: the team bars restyled like the player frame
- Player frame: touch nothing when nothing changed
- AONewbieGUI: the player frame in JavaFX, the native frame parked
- Revert closing the game's own Team window
- AONewbieGUI unit frame at the reference's sizes, no resizing
- AONewbieGUI: close the game's Team window at most once a second
- AONewbieGUI unit frame replaces the game's own Team window
- AONewbieGUI unit frame: names and numbers as text, sizes from F10
- AONewbieGUI team frame: team rows, cast bars, F10 Frames page
- AONewbieGUI: player frame, hidden game bars, frame commands in the hook
- Nano timers: time left as 45s / mm:ss / hh:mm:ss
- AONewbieGUI: fixes from the code review
- AONewbieGUI: own client skin module and a native game window bridge
- Shadow nano duplicates: clean up after every item-effect import
- Nano timers: one NCU list per character ("Boblea NCU", "Nopet NCU")
- Nano timers from capture, game-hook gating, and the dataset first over bundled files
- Scrolling text: one merge rule for everything; Team view keeps members since Reset
- 
## 1.6.2
- Solid clumps: each low/high id pair one QL-range family, clumps named by type
- Bank / inventory: a clump's type in cyan on its icon
- What's New: releases oldest first

## 1.6.1
- Mission Log: a quest's details list up to 3 guides naming its people and things
- Damage meter learns professions from selecting a player; /list stays as backup
- Mission Log opens minimized at the right edge on a finished quest or mission
- Trade watch: a name inside another item's link is not a mention
- Chat scripts: shared ChatScript (4096-byte chaining, delays, writing); /aodmg posts everyone and chain
- Tarasque timer counts to when he can be attacked
- Perk Planner: points used counted on open, trained lines first and highlighted
- IP's panel: buttons visible again, Revert to the opening state, clearer rows
- IP's panel: buffed value with base and max per ability and skill
- IP's panel (was Character): Save, Revert and Reset all skills, no auto-save
- Perk data: Defensive Stance added, 34 perks.json levels corrected
- Perk ids: the full table, generated from the game client's own perk records
- Import from Character brings the trained perks into the Perk Planner
- Refined (QL 201+) implants in the Implant Designer
- Mission runs as clearable progress, failed/deleted missions, split-family reward QL
- 
## 1.6.0
- Quest completion between list updates, full character removal
- Mission Log shows completed runs and rewards
- Mission Log, quest chains, setup prompt for new toons
- Combat UI options, more ready icons
- Combat UI font picker with bundled and uploaded fonts
- Added UI scaling and fixes
- Inventory: follow the game's Auto arrange order; note on unseen bags
- Pets: tag recolored pets, split pet damage/heals in details; fix HUD-blocked scrolling
- Team: damage meter Team filter, capture-fed team, team health/nano bars (flagged)

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
