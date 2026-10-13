# RatAddons

RatAddons is a Fabric client mod for Hypixel SkyBlock. It provides utilities for Dungeons, Kuudra, fishing, Diana, HUD customization, and rendering.

## Settings

Settings are organized into General, Dungeon, Fishing, Diana, Render, A ctionbar, and Kuudra pages.

- Left-click a toggle to enable or disable a feature.
- Right-click features marked with `▸` to open their detailed settings.
- In the HUD editor, left-click and drag to move an element, use the scroll wheel to resize it, and right-click to restore its default position and scale.
- Use `/rataddon` to open settings or `/rataddon hud` to open the HUD editor directly.

## Features

### General

- **Arrow Tracker** reads the quiver item in hotbar slot 9 and updates from low-arrow or empty-quiver chat messages. It shows arrow count and type, with an option to show it only while holding a bow.
- **AutoExperiment**, **Auto Clicker**, and **Chat Macros** provide table automation, configurable left/right clicking, and regex-triggered commands. Manage macros in General or with `/rataddon macros`.
- **Click Through Players** lets the crosshair reach targets behind players. By default it is limited to Dungeons and Kuudra; optional alpha changes make nearby players less visible.
- Display and input tools include scoreboard background/shadow settings, screenshot copying, Focus Player, Enter-to-confirm signs, and Tweaks.

### Dungeon

- **Ice Spray** can hide its particles and enable ICE Helper. **Ice Announce** reports affected targets, optionally to party chat.
- **Storm** handles aiming, item and armor swaps, Last Breath timing, and a configurable swap back armor step.
- **Auto Leap** selects Spirit Leap targets by player name or class and supports phase/position triggers, Fast mode, input blocking, swap back, and presets. Its settings are under Dungeon → Auto Leap.
- **Relics** provides M7 relic and cauldron triggerbots and color-coded spawn boxes.

### Kuudra

- **Phase Display** briefly shows the current phase when it changes. **Anky Tick**, **Direction Alert**, **Rend Damage**, **Danger Zone Alert**, and **Kuudra Distance** provide combat timing and positioning information.
- **Kuudra Display** can highlight Kuudra, show a screen HP label, draw health on Kuudra's body, and hide the matching vanilla damage title. Enable Kuudra Display before using its health options. The body label and title filter have separate switches.
- **Chest Counter** tracks progress toward the 60-chest limit. A completed or failed boss run adds one; a confirmed free or paid reward-chest opening subtracts one. It appears in Kuudra, Dungeon Hub, and Forgotten Skull when the count is above zero, with an Always Show option.
- **Supplies** includes supply ESP/beacons, drop-off markers, pickup and teammate-time HUDs, alerts, and giant indicators. The default supply color is Kitty-style Aqua. Supply Swap selects an Ender Pearl when using Elle's Supplies; the server handles switching back to the supply.
- **Build**, **Stun**, **Crate Priority**, **Pearl Waypoints**, **Etherwarp Waypoints**, **Safe Spots**, and **Fireball** each have their own options for waypoints, previews, progress, or interaction helpers.
- Automation options include **Rend Macro**, **Auto GFS**, **Supply Cheats**, **Auto Fire Veil**, **Auto Sneak in Build**, **Auto Cannon Close**, and **Auto Croesus**. Configure each feature before use.

### Fishing

- **AutoFish** manages casting, bite timing, entity checks, Golden Fish, Auto Breath, and Puddle Jumper.
- **Auto Kill** switches to a chosen weapon for an attack and returns to the rod after a configurable delay. Rod/weapon slots and timing are configurable.

### Diana

- **Diana's Feet** prevents dead entities from blocking shovel targeting while holding an Ancestral, Archaic, or Deific Spade.

### Mineshaft

- **Corpse ESP** outlines recognized loaded Lapis, Umber, Tungsten, and Vanguard corpses and stops highlighting them after they are looted.
- **Shaft Announce** reports the detected shaft and corpses to party chat shortly after entry. Reports can also be sent manually.

### Render and Actionbar

- Render options include empty ArmorStand culling, shorter damage numbers, Garden Pest ESP, and item/blocking/swing animation controls.
- **Actionbar Parser** separates Health, Mana, Defense, Skill XP, Secrets, Term Laser, Drill Fuel, and other fields into configurable HUD elements. Each field can stay in the actionbar, move to a screen HUD, or be hidden.

## Commands

- `/rataddon` — open settings.
- `/rataddon hud` — open the HUD editor.
- `/rataddon macros` — open the chat macro manager.
- `/rataddon leap <player or class>` — manually select a Spirit Leap target.
- `/rataddon chests` — show the saved chest count.
- `/rataddon chests set <0-60>` — align the counter with existing progress.
- `/rataddon chests reset` — reset the counter to zero.
- `/rataddon shaft share` and `/rataddon shaft corpses` — send shaft or corpse information.
- `/rataddon conditionalbox`, `/rataddon boxes`, and `/rataddon reloadboxes` — manage conditional Kuudra boxes.
- `/rataddon autoclicker add|remove|clear left|right` — manage Auto Clicker item lists.
