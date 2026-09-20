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
= Let's gooooo!

## Launcher 1.8.2
- Fix wrong uninstall property: MSIFASTINSTALL never disabled rollback
- Remove the now-unused launcherReleaseManifest task and doc references
