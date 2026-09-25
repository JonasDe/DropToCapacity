# Drop to Capacity

A Valheim mod. Over your carry weight? Hold **Left Alt** and click an item in your inventory. The mod drops just enough of that stack to bring you back to your weight limit. Never more.

## How it works

- Open your inventory, hold Left Alt, and left-click an item.
- The mod drops only as many as needed to get you back to your limit. If the whole stack is needed, it drops the whole stack.
- If you are not over your limit, nothing happens.
- Items with no weight are never dropped.
- Works while standing still, walking or running.
- Only affects items in your own inventory. Chests are not touched.

## Install

You need **BepInExPack for Valheim** installed first.

**Download:** get `DropToCapacity-0.1.0.zip` from the [Releases](../../releases) page, or the two files in the `plugins` folder of this repo:

- `DropToCapacity.dll`
- `DropToCapacity.Core.dll`

Both files are needed.

**With a mod manager (Gale, r2modman, Thunderstore Mod Manager):**

1. Open your profile folder. In Gale: the profile menu, then "Open profile folder".
2. Go to `BepInEx/plugins`.
3. Make a folder called `DropToCapacity` and put both DLLs in it.
4. Start the game through the mod manager.

**Manual install:**

1. Go to your Valheim folder (Steam: right-click Valheim, Manage, Browse local files).
2. Go to `BepInEx/plugins`.
3. Make a folder called `DropToCapacity` and put both DLLs in it.

**Uninstall:** delete the `DropToCapacity` folder.

## Settings

After the first launch, a config file appears at `BepInEx/config/com.jonasd.valheim.droptocapacity.cfg`.

- `ModifierKey` (default `LeftAlt`): the key to hold while clicking.

Some keys are not allowed because they break normal game controls: Escape, Shift, Ctrl, mouse buttons, and whatever your Inventory and Use keys are. If you pick one of those, the mod goes back to Left Alt.

## Multiplayer

Only you need it. Other players and the server do not need to install it.

## Compatibility

- Holding the key replaces the normal click on inventory items. Other mods that also use Alt+click in the inventory will clash. Change the key in the settings if that happens.
- Holding Shift and Alt together drops, instead of splitting the stack.
