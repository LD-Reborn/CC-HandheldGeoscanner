# CC-handheldGeoscanner
Computercraft-Tweaked script to scan for ores using an `Advanced Geo Pocket Computer` and a `Player Detector`
It displays the ores (with height indication) on the display using the Player Detector as a self-orientation method.
Allows for custom allow-listing of ores.

## Setup
To install CC-handheldGeoscanner, enter this command in the pocket computer CLI or download the `handheldGeoscanner.lua` file from the list above:
```
wget https://raw.githubusercontent.com/LD-Reborn/CC-GUI/refs/heads/main/GUI.lua
```

## Usage
1. Craft an `Advanced Geo Pocket Computer` (using an `Advanced Pocket Computer` and a `Geo Scanner`)
2. Craft a `Player Detector` and keep it in your inventory
3. Run `handheldGeoscanner` in the pocket computer CLI
4. Press the "scan" button. Once it turns green, it's running.

## FAQ
### The monitor bobs up and down in my hand all the time
If you have a `Player Detector` in your inventory, it switches between it and the `Geo Scanner`. The game interprets this as if you are now holding a new item in your hand, triggering the fade-out and fade-in animations.

If you know a better solution, feel free to reach out or create a pull request.