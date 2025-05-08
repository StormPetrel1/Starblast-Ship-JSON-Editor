# Starblast Ship JSON Editor

A simple, highly customizable tool for editing [Starblast](https://starblast.io/) [Modding](https://starblast.io/modding.html) JSON ship strings.

Offers significant improvements over the [official ship editor](https://starblast.io/shipeditor/) by removing the need to download or maintain intermediate files. You need only paste the mod export, fill in blanks, apply changes, and the new ship export will be automatically copied to your clipboard.

The Ship JSON Editor also provides features that the official ship editor does not expose, such as explicit control over laser position/mirroring and other stats.

All of the code sits in one .html file. Simply download/copy-paste and double-click to open with your default browser.

Instructions:
- Paste in any mod export.
- Use the text boxes and effect buttons (e.g. "Apply repairs") to manipulate stats.
- Each effect button will copy the updated ship export to your clipboard.
- Press "View stats" to see your mod export in a more readable format.
- Changing "size" automatically changes hitbox and laser positions for you.
- "code" = level * 100 + model (i.e. where the ship is in the ship tree)
- You don't need to fill in all of the text boxes, only the stats that you intend to modify. The exception is adding a new part to the ship, like a laser, in which case you should fill in the laser stats.

![\[screenshot\]](https://raw.github.com/StormPetrel1/Starblast-Ship-JSON-Editor/master/screenshot.png?raw=true)
