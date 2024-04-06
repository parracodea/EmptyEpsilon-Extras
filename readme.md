# EmptyEpsilon Remapped Keybindings

_Note: These keybinds are for version of EmptyEpsilon greater than Version 20230617, as `-` cannot be read as a keybind due to a SeriousProton bug. EmptyEpsilon deletes keybinds that it cannot read from the `keybindings.json` file. After downloading the newer version of EmptyEpsilon, so you will need to re-download [this `keybindings.json` file](./keybindings.json) instead of copy-pasting from the previous version._

## Guiding Principles

- The letter of the keybind should match the name of the action
  - Example: `E` in Weapons will select the EMPs since "EMP" starts with the letter "E"
- Keybinds should be consistent across stations as best possible.
  - Example: `T` in Weapons selects the next target, `T` in Science selects the next (scannable) target, and `T` in Cinematic moves to the next player ship
- Keys that appear in "Pairs" or "Triplets" should have related actions
  - Examples of Pairs:
    - `Home` and `End`
    - `Insert` and `Delete` (`Delete`, not `Backspace`; `Insert` and `Delete` are above/below each other on a full-sized keyboard)
    - `-` and `=` (`-` and `+`)
    - `9` and `0` (`(` and `)`)
  - Examples of Triplets: 
    - `,` and `.` and `/` (`<` and `>` and `/`)
    - `[` and `]` and `\`
- If a pair of actions is mapped to a letter, preference is given to the "up"/"forward"/"increase" action, and the "down"/"reverse"/"decrease" action is mapped to the key that's left of it (due to English being read from left to right)
  - Example: In Helm, setting warp levels is mapped to `W` since "Warp" starts with "W".
    - `W` increase warp level
    - `Q` decrease warp level
  - However, consider whether a Pair or Triplet might make more sense.
- If possible, allow the use of both hands by placing certain actions on opposite sides of the keyboard
  - Example: In Engineering, systems are selected by pressing the numbers or letters with the left hand, while adjusting the power/coolant levels is done by pressing `< > /` or `- =` with the right hand
  - Example: In Relay, players are primarily using the mouse with (most likely) their right hand. If a keybind for "Open Comms" is added, the default binding should be on the left side of the keyboard, so they can press it with their left hand and keep their right hand on the mouse. 
    - Bonus points if the keybind can be on the left-hand's home row. This allows for:
      1. Reduced strain from moving back and forth from the keybind to the home row
      2. Their hand is already in the position to start typing

## Explanation and Details

- `Space` is reserved as a `Push-To-Talk` key, due to being a large key that can be comfortably pressed by either hand.
- **Main Screen**
  - `R` - Set view screen to "Radar"
  - `T` - Set view screen to "Target"
  - `Y` - Set view screen to "Long Range Radar" (`Y` was chosen as it is adjacent to `R` and `T`)
- **Helm**
  - Combat Boost
    - `I` - Forward
    - `J` - Left
    - `L` - Right
    - This uses the same "spacing" as `W A S D`
      - The player's left-hand ring-finger goes on `J` where most keyboards have a bump to indicate the home row
      - The player's right hand stays on the arrow keys to adjust impulse and turning
  - Setting Impulse
    - `C` - Set Impulse to -100% (Full Reverse)
    - `V` - Set Impulse to 0% (Full Stop). (`V` is chosen since it looks like a down arrow)
    - `B` - Set Impulse to 100% (Full Forward)
- **Weapons**
  - Targeting
    - `T` - Next hostile target
    - `Y` - Next target any (hostile or friendly) - `Y` for the "Y" in "any"
  - Beam Weapons
    - All keybinds for beam-related actions are next to each other: `9 0 - =`
    - `(` - Target previous subsystem
    - `)` - Target next subsystem
    - `-` - Decrease beam frequency
    - `=` - Increase beam frequency
  - Missiles
    - `H` - HVLI
    - `G` - Guided Missile/Homing Missile
    - `E` - EMP
    - `N` - Nuke
    - `M` - Mine
    - `1`-`8` - Load/Fire Tube #
  - Shields
    - `[` - Decrease shield frequency
    - `]` - Increase shield frequency
    - `\` - ~~Start shield calibration~~ (removed to prevent players from accidentally pressing the key)
- **Engineering**
  - Select the system using the numbers or letters with left hand
    - Selecting Sub-System
      - `R` - Reactor
      - `B` - Beam Weapons
      - `N` or `H` - Missile System ("N" for "Nuke", "H" for "HVLI")
      - `M` or `O` - Maneuvering ("O" because it looks like a steering wheel, which matches the icon for Maneuvering. `O` is also adjacent to the `I` keybind for Impulse)
      - `I` - Impulse Engines
      - `W` - Warp Drive
      - `J` - Jump Drive
      - `F` - Front Shield Generator ("F" for "Front")
      - `D` or `G` - Rear Shield Generator (`D` is left of `F` for "Front Shield Generator")
  - Adjust the power/coolant levels with the right hand
    - Coolant
      - `-` decrease coolant
      - `=` increase coolant
    - Power
      - Increase/Decrease
        - `[` decrease power
        - `]` increase power
        - `\` reset power level to 100%
      - Low/Medium/High
        - `,` set power to low (30%)
        - `.` reset power to 100%
        - `/` set power to high (150%)