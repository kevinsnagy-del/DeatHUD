# Changelog

## 1.1.13
- Needs Mod Drive 9000 1.5.0.
- **Co-op:** teammates are no longer counted as enemies in the floor's enemy count.

## 1.1.12
- Needs Mod Drive 9000 1.4.9.
- **Rotate with the player:** choose whether the minimap turns with your fighter or with the camera.
- **New: Map rotation smoothness** -- the minimap eases into a turn instead of snapping (default 50 %, 0 = instant).
- **New: Disable joystick navigation in menus** -- only the D-pad moves the menus.
- The HUD no longer reads the previous floor after a ride.

## 1.1.11
- **Move the boss health bar:** a new HUD setting places the boss bar at the top of the screen where you want it, so the decal box no longer covers it.

## 1.1.10
- Needs Mod Drive 9000 1.4.5.
- **Fixed: the time left under blessings did not show** (it was drawn fully transparent).
- With POSTMORTEM, event enemies, event bosses and the VIP are not counted as floor enemies.

## 1.1.9
- Enemy counts skip a mid boss's hidden spare pawns and enemies that are already gone (the counter could stay above zero after the skeleton summoner died).
- Enemies the game keeps parked out of sight no longer count as defeated.

## 1.1.8
- For the LET IT DIE update of November 2026 (game 5.0.6).
- With Probes / logs on, the log tells why a status effect shows no countdown (to fix the blessings that show none).

## 1.1.7
- The live HUD editor's panel is drawn with the game's own Options rows, arrows and highlight frame.
- The live editor's frame for a weapon hand now covers all three of its slots.

## 1.1.6
- New: **Edit the HUD live.** DeatHUD settings > Edit the HUD live closes the menu and lets you edit the HUD while you see it: L1 / R1 picks the element, L2 / R2 the setting, the D-pad changes it (on an offset it moves the element freely), Y resets the setting, B is done. Keyboard: Q / E, Z / C, arrow keys, R, Backspace. Every change is saved as you go.
- In the live editor the message box shows a frame where messages end up, even when none are on screen (measured from the first messages you see).
- Needs Mod Drive 9000 1.4.0 or newer.

## 1.1.5
- Fixed: the time left under the status-effect icons stayed on screen during loading screens and while the HUD was hidden. It now fades with the HUD.

## 1.1.4
- New option: Time left under the icons. Shows the seconds left under each status effect in the status-effect bar (off by default).
- The run floor / wave and run points on the minimap now follow POSTMORTEM's own settings (Postmortem settings > Minimap run info: on / off, where, offset) from Postmortem 0.9.10-beta on. DeatHUD's two switches only apply with an older Postmortem.

## 1.1.3
- A leftover diagnostic no longer writes thousands of lines to the log each session (it is behind the Probes / logs switch now).

## 1.1.2
- Fixed: the chest counter could start a floor with a chest already counted as opened (an unopened chest of the floor you just left).
- Fixed a hitch every 3 seconds during a session's first 75 seconds (the atlas name search read every object's class name).
- Removed a leftover diagnostic that wrote a large trace file each time the pause menu opened while Probes / logs was switched on (a 75 ms hitch).
- Fixed: the big minimap never darkened unexplored areas (its fog was skipped as too large), so the run floor and run points floated above the map instead of sitting in its corners.

## 1.1.1
- The run floor and run points sit fully inside the minimap's top corners.

## 1.1.0
- **Run info above the minimap** (POSTMORTEM runs): the floor / wave / bosses reached on the top left, the run's points on the top right. Two new minimap options turn each on or off.
- Fixed: the minimap lost its icons (chests, mushrooms, elevators) whenever a treasure-hunter effect was active; only the player arrow was left.

## 1.0.1
- Supports the LET IT DIE update of 2026-10-20 (Steam build 25923506).

## 1.0.0 (first public release)
- Minimap with its own area-map construction.
- Recolourable minimap background, fog and icons.
- Options in the Mod Drive 9000 tab.
