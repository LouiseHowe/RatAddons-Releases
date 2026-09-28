# RatAddons

RatAddons is a Fabric client mod for Hypixel SkyBlock. It provides utilities for Dungeons, Kuudra, fishing, Diana, HUD customization, and rendering.

## Settings

Settings are organized into General, Dungeon, Fishing, Diana, Render, Actionbar, and Kuudra pages.

- Left-click a toggle to enable or disable a feature.
- Right-click features marked with `▸` to open their detailed settings.
- In the HUD editor, left-click and drag to move an element, use the scroll wheel to resize it, and right-click to restore its default position and scale.
- Use `/rataddon` to open settings or `/rataddon hud` to open the HUD editor directly.

## Features

### General

- **AutoExperiment**: Automates Experimentation Table interactions.
- **No Scoreboard Background**: Hides the sidebar scoreboard background.
- **Scoreboard Text Shadow**: Adds shadows to sidebar scoreboard text.
- **Copy Screenshots**: Copies screenshots to the system clipboard on supported platforms (excluding macOS).
- **Focus Player**: Renders invisible players visibly.
- **Sign Enter Key**: Confirms sign editing with Enter; hold left Shift to keep editing.

### Dungeon

- **Ice Spray**
  - Hides Ice Spray particles.
  - Provides ICE Helper.
- **Ice Announce**
  - Detects targets hit by Ice Spray and displays the result in chat.
  - Can be restricted to `The Catacombs`.
  - Can automatically send the same result to party chat.
- **Storm**
  - Provides aiming, item switching, armor switching, automatic movement, and attack timing options for the Storm phase.
  - Supports delay and slot settings for Last Breath, Terminator, Leap, and related actions.

### Kuudra

- **Rend Damage**
  - Reports large Kuudra health drops as damage and elapsed DPS time in local chat.
  - Associates damage with players swinging a bow or bone within a configurable 200–500 ms window.
- **Rend Macro**
  - Provides rotation, movement, item switching, Rend, Hollow Wand, Rod, Bone, Halberd, and Pull settings.
  - Supports area visualization and debug information.
- **Anky Tick**
  - Displays `Anky update in: nt` after the stun ends.
  - Counts down from 20 ticks to 0 and repeats until the run ends.
  - The HUD can be moved freely and scaled from 0.5x to 4.0x.
- **Kuudra Performance**
  - Hides arrows.
  - Hides damage-number ArmorStands.
  - Filters particle packets that spawn large batches of particles.
  - Limits the render distance of mobs, dropped items, and projectiles.
- **Kuudra Hitbox**
  - Renders Kuudra's hitbox through walls with configurable color and line width.
- **Kuudra Direction Alert**
  - Displays a color-coded FRONT, LEFT, RIGHT, or BACK alert when Kuudra's direction changes.
  - Activates during DPS and resets during stun.
  - The alert HUD can be moved and scaled in the HUD editor.
- **Danger Zone Alert**
  - Shows DANGER or JUMP alerts when standing above tentacle danger-zone terracotta.
- **Ability Announce**
  - Announces Spirit Spark, Hollowed Rush, Raging Wind, and Ichor Pool casts in party chat with coordinates.
  - Can announce Mana Drain usage and the number of affected nearby players.
- **Real Tracking**
  - Tracks thrown Bonemerangs and warns when a bone breaks.
- **Kuudra Distance**
  - Shows Kuudra's distance during DPS and alerts when it enters the configured bone-throw range.
- **Supply Helpers**
  - Provides automatic supply pulling and an optional Ender Pearl action when using Elle's Supplies.
- **Build and Utility Automation**
  - Provides Auto Fire Veil, Auto Sneak in Build, Auto Cannon Close, and Auto Croesus.

### Fishing

- **AutoFish**: Provides automatic casting, bite detection, entity checks, Golden Fish, Auto Breath, and Puddle Jumper.
- **Auto Kill**: Automatically switches to a weapon to attack a target and returns to the fishing rod after the configured delay.
- Supports configurable rod and weapon slots, wait times, HYPE behavior, and attack count.

### Diana

- **Rare Mob Hit Counter**: Counts player hits on rare Diana mobs and can display a chat summary after the kill.

### Render

- **Empty ArmorStand Culling**: Skips rendering invisible ArmorStands that have no name or equipment.
- **Short Damage Numbers**: Shortens damage numbers with optional compact formatting and custom colors.
- **Garden Pest ESP**: Displays boxes and tracer lines for Garden Pests.
- **Animation**: Adjusts blocking, item-switching, and swing animations.

### Actionbar

- Parses Actionbar information such as Health, Mana, Defense, Skill XP, Secrets, Term Laser, and Drill Fuel.
- Individual fields can be moved to a separate HUD, hidden from the original Actionbar, or kept visible continuously.
- HUD elements support dragging, scaling, and restoring their default position.
