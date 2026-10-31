# ValheimModPack changelog

Newest pack first.

## ValheimModPack 2026.10.31 (built 2026-10-31 15:52 UTC, Valheim 1.0.21)

Added:

- Local-PortalSnap 1.2.0
  - Add Portal Snap 1.0.0: end portal loading once the arrival has loaded
  - Place arrival zones without the 0.1 s tick in Portal Snap 1.1.0
  - Ignore small object-count churn in Portal Snap 1.2.0

Updated:

- Local-QuickConnectCaseFix 1.0.0 -> 1.1.0
  - Save dedicated servers by address in Quick Connect Case Fix 1.1.0

Removed:

- Local-GemProcBalance 1.0.0

Game:

- Built for Valheim 1.0.21 (was 1.0.20)

Settings changed:

- com.jubaroo.smarterhoe.cfg
- local.valheim.baseareavisuals.cfg
- local.valheim.buildableonly.cfg
- local.valheim.lockstackguard.cfg
- local.valheim.mechasuit.cfg
- seneaL.valheim.ui.cfg

Map data updated:

- IdolMapPins/-4693685.txt
- MemorialCoalPins/-4693685.txt
- WardMapPins/-4693685.txt
- WorldSeedLogger/worlds.txt

## ValheimModPack 2026.10.28 (built 2026-10-28 23:09 UTC, Valheim 1.0.20)

Updated:

- Local-MechaSuit 1.2.0 -> 1.3.0
  - Give the Colossus a longship sea form, a laser impact marker, finned missiles, a rising third swing and a faster boost
- Local-BaseAreaVisuals 1.2.0 -> 1.2.1
  - Show the comfort marks in SeneaL UI's build menu (Base Area Visuals 1.2.1)
- Local-LockStackGuard 2.9.0 -> 2.11.0
  - Lock Stack Guard 2.10.0: reach chests within 20 m for Fill kit and potion top-ups
  - Lock Stack Guard 2.11.0: claim chests another player's game owns before filling the kit

Now optional (the installer asks):

- Local-LagTracer
- Local-WorldSeedLogger
- Local-WorldCapture
- Local-MechaSuit

Settings changed:

- local.valheim.baseareavisuals.cfg
- local.valheim.mechasuit.cfg
- seneaL.valheim.ui.cfg

Map data updated:

- IdolMapPins/-4693685.txt

## ValheimModPack 2026.10.28 (built 2026-10-28 01:25 UTC, Valheim 1.0.20)

Updated:

- Local-BaseAreaVisuals 1.1.1 -> 1.2.0
  - Show what raises comfort in the build menu (Base Area Visuals 1.2.0)
- Local-MechaSuit 1.0.0 -> 1.2.0
  - Add the Colossus to Mecha Suit 1.1.0: a gammeltroll-sized wolf super-robot that transforms in the air
  - Make the Colossus gammeltroll-sized and record its build and binding checks
  - Add a targeting diagnostic and a full-size Colossus view shot list
  - Give the Colossus a laser, missile salvo, sword combo, plane and sea forms
  - Land the Colossus when it rests on a slope, and tidy the flight hints
  - Add a sea test hook and shot list for the Colossus
  - Keep the Colossus flying when it takes off from the sea
  - Splash the Colossus down only when it is back at its floating height
  - Document the Colossus sea shot list
  - Let the Colossus trample through forest and keep its pilot dry at sea
  - Refuse the Wet effect for the Colossus pilot instead of clearing it each frame
  - Give the Colossus a longship sea form, a laser impact marker, finned missiles, a rising third swing and a faster boost

Settings changed:

- local.valheim.baseareavisuals.cfg
- local.valheim.mechasuit.cfg

Map data updated:

- FrozenLakePins/-4693685.txt
- IdolMapPins/-4693685.txt
- IdolMapPins/328449766.txt
- MemorialCoalPins/-4693685.txt
- OatMapPins/-4693685.txt
- WardMapPins/-4693685.txt
- WorldSeedLogger/worlds.txt

## ValheimModPack 2026.10.27 (built 2026-10-27 22:08 UTC, Valheim 1.0.20)

Added:

- Local-MechaSuit 1.0.0
  - Add Mecha Suit 1.0.0: a troll-sized pilotable mech with weapons, jetpack and cockpit HUD

Updated:

- Local-WorldCapture 1.1.0 -> 1.3.0
  - World Capture 1.2.0: keep far-end portals so copies' portals lead somewhere
  - World Capture 1.3.0: ask for every far end and show capture state on portal hover
- Local-BaseAreaVisuals 1.0.0 -> 1.1.1
  - Add comfort map to Base Area Visuals 1.1.0
  - Make Y turn comfort visuals off and work while moving

## ValheimModPack 2026.10.27 (built 2026-10-27 17:42 UTC, Valheim 1.0.20)

Added:

- Local-BaseAreaVisuals 1.0.0
  - Add Base Area Visuals to replace ESP

Updated:

- Local-PerformanceTuner 1.3.0 -> 1.4.0
  - Spread the periodic pin rescan in Performance Tuner 1.4.0
- Local-CameraColliderGuard 1.0.0 -> 1.1.0
- Local-MemorialCoalPins 1.0.0 -> 1.1.0
  - Classify memorial coal sources once in Memorial Coal Pins 1.1.0
- Local-WardMapPins 1.0.0 -> 1.1.0
  - Rebuild ward pins only on change in Ward Map Pins 1.1.0
- Local-FishMapPins 1.0.0 -> 1.1.0
  - Read each fish once in Fish Map Pins 1.1.0
- Local-ScrapMapPins 1.0.0 -> 1.1.0
  - Classify loose items once in Scrap Map Pins 1.1.0
- Local-WorldCapture 1.0.0 -> 1.1.0
  - Spread World Capture 1.1.0 work over frames and a background writer
- Local-OatMapPins 1.2.0 -> 1.3.0
  - Cut Oat Map Pins sweep cost in 1.3.0
- Local-IdolMapPins 1.1.0 -> 1.2.0
  - Cut Idol Map Pins sweep cost in 1.2.0

Removed:

- JereKuusela-ESP 1.40.0

Settings changed:

- com.kimbauer.valheim.cameracull.cfg

## ValheimModPack 2026.10.27 (built 2026-10-27 17:31 UTC, Valheim 1.0.20)

Map data updated:

- WorldSeedLogger/worlds.txt

## ValheimModPack 2026.10.27 (built 2026-10-27 01:30 UTC, Valheim 1.0.20)

Added:

- Local-WorldCapture 1.0.0
  - Add World Capture 1.0.0: rebuild server zones as a local world
- JereKuusela-ESP 1.40.0

Updated:

- Local-LockStackGuard 2.7.2 -> 2.9.0
  - Lock Stack Guard 2.8.0: refill and re-lock potion stacks drunk to empty
  - Lock Stack Guard 2.9.0: color kit and potion refill cells in the inventory
- Local-PerformanceTuner 1.2.0 -> 1.3.0
  - Throttle wandering tames in Performance Tuner 1.3.0

Settings changed:

- com.jubaroo.smarterhoe.cfg
- local.valheim.lockstackguard.cfg
- local.valheim.performancetuner.cfg
- seneaL.valheim.ui.cfg

Map data updated:

- IdolMapPins/-4693685.txt
- WorldSeedLogger/worlds.txt

## ValheimModPack 2026.10.26 (built 2026-10-26 17:14 UTC, Valheim 1.0.20)

Added:

- Local-ScrapMapPins 1.0.0
  - Add Scrap Map Pins that shows loose scrap iron on the minimap
- Local-HoeLineSnap 1.0.0
  - Add Hoe Line Snap: straight-line snapping for SmarterHoe terrain edits
  - Read the placement ghost through FieldInfo for the .NET Framework compiler
  - Draw the Hoe Line Snap guide point by point for the .NET Framework compiler

Updated:

- Local-CaveScanner 1.2.0 -> 1.3.0
  - Cave Scanner 1.3.0: Escape closes the scanner without opening the game menu
- Local-PerformanceTuner 1.1.1 -> 1.2.0
  - Cache the server world map in Performance Tuner 1.2.0
- Local-LockStackGuard 2.7.0 -> 2.7.2
  - Lock Stack Guard 2.7.1: refill potions from a just-closed barrel; log why chests give none
  - Lock Stack Guard 2.7.2: log resolved potion names and every carried potion stack

Settings changed:

- com.jubaroo.smarterhoe.cfg
- local.valheim.buildableonly.cfg
- local.valheim.cavescanner.cfg
- local.valheim.lockstackguard.cfg
- local.valheim.performancetuner.cfg
- xtav1m.BetterMap.cfg

Map data updated:

- IdolMapPins/-4693685.txt
- WorldSeedLogger/worlds.txt

## ValheimModPack 2026.10.26 (built 2026-10-26 01:32 UTC, Valheim 1.0.20)

Settings changed:

- xtav1m.BetterMap.cfg (BetterMap Lingonberry Pins 1.0.0: auto-pin lingonberry bushes in the Deep North)

## ValheimModPack 2026.10.26 (built 2026-10-26 01:30 UTC, Valheim 1.0.20)

Added:

- Local-GammeltrollIcon 1.0.0
  - Add Gammeltroll Icon that gives the Gammeltroll a creature radar icon

Updated:

- Local-PerformanceTuner 1.1.0 -> 1.1.1
  - Add a running off-thread verdict to Performance Tuner's character save lines (1.1.1)

## ValheimModPack 2026.10.26 (built 2026-10-26 00:33 UTC, Valheim 1.0.20)

Added:

- Local-GrowUpTimer 1.0.0
  - Add Grow Up Timer that shows when young creatures grow up
  - Log Grow Up Timer's young creatures, hovers and growth for debugging

## ValheimModPack 2026.10.26 (built 2026-10-26 00:29 UTC, Valheim 1.0.20)

Updated:

- Local-PerformanceTuner 1.0.0 -> 1.1.0
  - Skip the server's duplicate character save request and time each save in Performance Tuner 1.1.0

## ValheimModPack 2026.10.25 (built 2026-10-25 23:04 UTC, Valheim 1.0.20)

Added:

- Local-WorldSeedLogger 1.0.0
  - Add World Seed Logger: record the seed of each world you load or join
- Local-MemorialCoalPins 1.0.0
  - Add Memorial Coal Pins that pins Morkhalla memorial coal sources
- Local-MapPinToggles 1.0.0
  - Add Map Pin Toggles with Fish and Creatures toggles on the large map
- Local-PerformanceTuner 1.0.0
  - Add Performance Tuner and debug plugin cleanup
- Local-IceLakePins 1.0.0
  - Add Ice Lake Pins that pins the Deep North's ice ponds on the map

Updated:

- Local-ChestFit 1.0.0 -> 1.0.1
  - Chest Fit 1.0.1: fold slots before other mods' UpdateGui postfixes
  - Verify Chest Fit 1.0.1 bindings
- Local-LockStackGuard 2.6.0 -> 2.7.0
  - Add Fill kit button that tops the kit corner up from nearby chests
- Local-TrailFinder 1.1.0 -> 1.3.0
  - Trail Finder 1.2.0: clear the destination on arrival
  - Trail Finder 1.3.0: sail round land masses when aboard a boat

Removed:

- Local-GjallSoundTracer 1.0.0
- Local-BetterMapRepairThrottle 1.0.0
- Local-QuickStackAreaTracer 1.0.1

Settings changed:

- com.jubaroo.smarterhoe.cfg
- goldenrevolver.quick_stack_store.cfg
- local.valheim.cavescanner.cfg
- local.valheim.chestfit.cfg
- local.valheim.lockstackguard.cfg
- local.valheim.sortclickrelay.cfg
- local.valheim.trailfinder.cfg
- seneaL.valheim.ui.cfg

Map data updated:

- FrozenLakePins/-4693685.txt
- IdolMapPins/-4693685.txt
- WardMapPins/-4693685.txt

## ValheimModPack 2026.10.24 (built 2026-10-24 20:23 UTC, Valheim 1.0.20)

Added:

- Local-TrashMiddleClick 1.0.0
  - Add Trash Middle Click: middle click an item toggles its Quick Stack trash flag
- Local-WardMapPins 1.0.0
  - Add Ward Map Pins: show wards on the minimap and large map
- Local-GemProcBalance 1.0.0
  - Add Gem Proc Balance: even out Ashlands gem proc rates by attack speed
- Local-SummonClip 1.0.0
  - Add Summon Clip: walk through your summons
- Local-OatMapPins 1.2.0
  - Add Oat Map Pins: pin wild oats on the map
  - Oat Map Pins 1.1.0: pin loot chests and loose stacks holding oat seeds
  - Oat Map Pins 1.2.0: audit every oat seed pickup against the pins in the log
- Local-TrailFinder 1.1.0
  - Add Trail Finder 1.0.0: persistent destination with a planned trail
  - Trail Finder 1.0.1: start the trail at the character, with a leg back when off it
  - Trail Finder 1.1.0: route around Ashlands lava
- Local-ChestFit 1.0.0
  - Add Chest Fit: show the wardrobe without scrolling
- Local-FrozenLakePins 1.0.0
  - Add Frozen Lake Pins: pin frost caves that hold a frozen lake
- Local-FishMapPins 1.0.0
  - Add Fish Map Pins: show the fish near you on the minimap

Updated:

- Local-CaveScanner 1.1.0 -> 1.2.0
  - Cave Scanner 1.2.0: realistic lit view and selectable wireframe levels
- Local-IdolMapPins 1.0.0 -> 1.1.0
  - Idol Map Pins 1.0.2: label idols in buried chests "(buried, dig here)"
  - Idol Map Pins 1.1.0: pin every buried chest that still holds loot
- Local-ForgeForesight 1.0.1 -> 1.1.0
  - ForgeForesight 1.1.0: follow the item's quality across upgrades in the look-ahead
- Local-LockStackGuard 2.2.0 -> 2.6.0
  - Lock Stack Guard 2.3.0: keep locked stacks out of SeneaL smelter feeding
  - Lock Stack Guard 2.4.0: top up locked potion stacks to 4
  - Add Mead of Troll Endurance to Lock Stack Guard potion stacks
  - Lock Stack Guard 2.5.0: refill locked potions from owned nearby chests; Potions carry button
  - Add Off to the Lock Stack Guard Potions button
  - Lock Stack Guard 2.6.0: let a short kit stack take pickups up to its amount with a full bag

Settings changed:

- com.geronimo.valheim.immersivebuildcamera.cfg
- com.kimbauer.valheim.cameracull.cfg
- local.valheim.cavescanner.cfg
- local.valheim.forgeforesight.cfg
- local.valheim.idolmappins.cfg
- local.valheim.lockstackguard.cfg
- seneaL.valheim.ui.cfg

Map data updated:

- IdolMapPins/-4693685.txt
- IdolMapPins/328449766.txt

## ValheimModPack 2026.10.21 (built 2026-10-21 22:25 UTC, Valheim 1.0.20)

Added:

- Local-BallistaFill 1.0.0
  - Add Ballista Fill: Shift+E loads a ballista until it is full
- Local-HookedLeftClickReel 1.0.0
  - Add Hooked Left Click Reel: reel Hooked's bobber bar with left click
- Local-GjallSoundTracer 1.0.0
  - Add Gjall Sound Tracer: log where Gjall-like sounds come from
- Local-ForgeForesight 1.0.1
  - Document Forge of Potential RNG for ForgeForesight (phase 1)
  - Add ForgeForesight RNG harness and three-outcome ForgeRng
  - Add ForgeForesight: Forge of Potential refine predictions
  - Move ForgeForesight label below the refine button
- Local-LagTracer 1.0.0
  - Add Lag Tracer: log which mod or game system causes each hitch
- Local-IdolMapPins 1.0.0
  - Add Idol Map Pins: show Forge of Potential idols on the map
  - Pin dungeon idols at the dungeon entrance
  - Log idol find details and dungeon entrance matching
- Local-BetterMapRepairThrottle 1.0.0
  - Add BetterMap Repair Throttle: stop the once-a-second map pin rescan
- Local-QuickStackAreaTracer 1.0.1
  - Add Quick Stack Area Tracer: check client-side area quick stacking
  - Read QSS area setting lazily so Quick Stack Area Tracer starts
- Local-BuildableOnly 1.1.0
  - Add Buildable Only: Ctrl+H shows only pieces you can build
  - Add a "Can build" switch to SeneaL UI's build menu for Buildable Only
- Local-CaveScanner 1.1.0
  - Add Cave Scanner: a Deep Rock Galactic style terrain scanner for dungeons
  - Cave Scanner 1.1.0: drag to rotate, idol markers, visited floors

Updated:

- Local-SortClickRelay 1.1.0 -> 1.2.0
  - Clear stale split item in Sort Click Relay 1.2.0
  - Bind Sort Click Relay to InventoryGui.m_splitDialog
- Local-LockStackGuard 2.0.1 -> 2.2.0
  - Add Lock Stack Guard kit button to switch wood and stone portal kits
  - Move Lock Stack Guard kit button below the inventory panel
  - Add workbench and stonecutter materials to Lock Stack Guard stone kit
  - Add Off to the Lock Stack Guard kit button
  - Build Lock Stack Guard 2.2.0: 47 stack rule checks

Settings changed:

- advize.PlantEasily.cfg
- com.jubaroo.smarterhoe.cfg
- goldenrevolver.quick_stack_store.cfg
- local.valheim.lockstackguard.cfg
- local.valheim.sortclickrelay.cfg
- seneaL.valheim.ui.cfg

## ValheimModPack 2026.10.16 (built 2026-10-16 20:40 UTC, Valheim 1.0.20)

First pack.
