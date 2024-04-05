# EmptyEpsilon Remapped Keybindings

## Changelog
- v0.0
  - Imported keybindings.json from EmptyEpsilon Version 20230617
- v0.1
  -  Fix duplicate default keybind for Science and Relay
     -  `F5` to switch to the Science station
     -  `F6` to switch to the Relay station
- v0.2
   -  Use Arrow Keys to move Engineering Crew
      -  Avoids keybinding collision in Engineering+, where S moves the Crew down, but also toggles Shields
   -  Use `-` and `=` to increase/decrease coolant
      -  Requires EE greater than Version 20230617 as `-` cannot be read as a keybind due to a SeriousProton bug
- v1.0
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