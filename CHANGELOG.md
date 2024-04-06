# v2.0

- Added "Guiding Principles" section
- Added "Explanation and Details" section
- `T` is always used for targeting
- Function Keys
    - Shifted station keybinding to have Helm be `F1` to match the order of the stations in the UI
        - (Helm appears first, so it's `F1`, etc)
        - Moved "Full Screen" to `F11` to match web browsers' keyboard shortcut
        - Moved "Help" to `F12`
- Engineering
    - Added alternative keybinds for full-sized keyboards
    - Added keybindings to set the power level using a Triplet
    - Added letter keybinds to pick subsystems subsystems
- Helm
    - Added keybinds for Combat Boost
    - Added keybinds for setting impulse
- Relay
    - Added keybinds for alert levels

# v1.0

- Added hotkeys for Weapons console:
    - `1` `2` `3` etc. for loading and firing missiles
    - Use letters for selecting weapon types
        - `H` Homing
        - `L` HVLI - "L" for "Lead"
        - `E` EMP
        - `N` Nuke
        - `M` Mine
- Warning: These will collide with some existing keybindings!
    - e.g. In Tactical/Single Pilot, `6` adjusts Warp but also load/fires missiles

# v0.2

    -  Use Arrow Keys to move Engineering Crew
        -  Avoids keybinding collision in Engineering+, where S moves the Crew down, but also toggles Shields
    -  Use `-` and `=` to increase/decrease coolant
        -  Requires EE greater than Version 20230617 as `-` cannot be read as a keybind due to a SeriousProton bug

# v0.1

-  Fix duplicate default keybind for Science and Relay
        -  `F5` to switch to the Science station
        -  `F6` to switch to the Relay station

# v0.0

- Imported keybindings.json from EmptyEpsilon Version 20230617
