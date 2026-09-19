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
