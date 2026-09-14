# Dynamic Lean & Crouch

Adds full analog control over leaning and crouch depth on top of Anomaly's vanilla lean and crouch system.

Instead of being limited to a fixed lean angle or three hard stance positions, standing, crouched, and prone, you get **continuous control** over how far you lean and how low you crouch. You can smoothly move between positions rather than simply hitting a hard limit.

## How to Use

**Hold the adjustment key (Left Alt by default)** and move the mouse:

* **Left / Right** → Adjust lean
* **Up / Down** → Adjust crouch depth

Release the adjustment key and everything behaves exactly like vanilla until you use it again.

Don't want to use the mouse? Both leaning and crouching also support a **keybind mode**. Hold the modifier and use dedicated nudge keys to adjust your position, with its own independently configurable sensitivity.

## Dynamic Lean

* **Continuous Lean:** Lean to any angle instead of being restricted to a fixed position.
* **Dynamically Switch Sides:** Push a lean all the way to one side and keep going to transition into the opposite lean.
* **Lean From Nothing:** Start leaning directly from the mouse or keybind controls without pressing the vanilla lean key first.
* **Vanilla Hold / Toggle Support:** Fully respects Anomaly's existing hold-vs-toggle lean setting. In hold mode, releasing the vanilla lean key or adjustment key correctly stops the lean. In toggle mode, releasing the vanilla lean key or adjustment key holds the lean.

## Dynamic Crouch

* **Continuous Crouch:** Adjust smoothly anywhere between standing and prone instead of being locked to a single crouch height.
* **Dynamically Switch Stances:** Push crouch all the way down and keep going to flow into prone. Push back up to transition toward standing. **Stance Commit Firmness** controls how much input is required to commit to the next stance, with prone intentionally requiring a stronger push.
* **Crouch From Nothing:** Start crouching directly from the mouse or keybind controls without pressing the vanilla crouch key first.
* **Weighted Crouch Entry:** Entering crouch—whether from standing or while rising out of prone—starts with some immediate depth instead of snapping into a barely-crouched position.

## Toggles & Options

* **Enable Mod:** Master switch that safely returns you to a normal standing, non-leaning state when disabled.
* **Enable Leaning:** Disable the mod's leaning features completely and return leaning to vanilla behavior.
* **Enable Crouching:** Disable the mod's crouching features completely while leaving leaning active.
* **Sprinting Removes Stance And Lean:** Sprinting automatically returns you to standing and removes any active lean instead of simply preventing you from sprinting.
* **Remember Angle / Height:** Remembers your last lean or crouch position, allowing you to quickly return to it within the configured time window. Zero disables the timer.

## Compatibility

Includes integration with **Liz Inertia Expanded**.
Weapon sway caused by leaning and crouching scales with how far you're actually leaning or crouching, rather than applying at full strength immediately when the stance is engaged.
