# Changelog

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
