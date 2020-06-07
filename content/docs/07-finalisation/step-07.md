---
title: "First Launch"
weight: 7
type: docs
description: >
  Ingame testing and final steps.
---

## 7.1 The Final Step

All mods are installed. Your ENB preset is configured correctly. DynDOLOD is generated. Now comes the moment of truth.

Once arrived at this point it is important to thoroughly test your setup in order to make sure your game looks beautiful, performs well and runs stable so that you can finally start a new playthrough without a high risk for nasty surprises.

## 7.2 Start a test game

* In Mod Organizer 2, select **SKSE** in the exectuables drop-down and hit **Run**.
* In the main menu, select **New** to start your test save.
* After the initial loading screen you will find yourself in the AS LAL cell where you can customise your (testing) character.
* When you’re done, talk to the Statue of Mara and select the **I am camping in the woods** option.
* Go to the bed in the back in the cell and interact with it to "sleep".

## 7.3 Configuration

### 7.3.1 Immersive HUD

**Both of these changes are completely optional but recommended.**

Changes to MCM settings do not carry over across save games so it would be a waste of time to configure all MCMs for a test run. There are merely two changes in the Immersive HUD MCM that I recommend for now.

- Press **ESCAPE** and select the **MCM** Option.
- Scroll down and click on **Immersive HUD** to open the mod's MCM.
- In the **Activation** tab, select the following two options:
  - Key press toggles
  - Link ALL SkyUI Widgets
- You can also change the hotkey to a different one if its inconvenient for you (default is X).

> This will make it so that the clock widget from A Matter of Time is toggled along with iHUD (and therefore hidden most of the time). Pressing the hotkey once to toggle is more convenient than having to keep pressing it in my opinion.

### 7.3.2 Depth of Field

While the default Depth of Field effect is fairly ugly, you will have noticed that we specifically left it turned on while configuring INI settings way back during the Setup section. This is because the DoF effect is tied to the underwater blur effect - turn off DoF and going underwater you will be able to see as clearly as above the surface. The solution to this is leaving the effect on but turning it down all the way so that the DoF doesn't actually show up.

* Press **ESCAPE** and go into **Settings** > **Display**.
* Turn down **Depth of Field** all the way.

![Turn down DoF](/Pictures/finalisation/turn_down_dof.jpg)

## 7.4 Testing Suggestions

* You will spawn near Helgen in an area you likely know well. Take some time to look around.
* Activate the ENBSeries FPS counter if you installed ENB (default hotkey: Numpad *). Otherwise use the Steam overlay or something similar.
* Travel around Skyrim and visit your favourite locations (open the console and type `tmm` to enable all map markers).
* Especially intense areas where you frame rate might drop are:
  * the southern forest, especially when looking down at Falkreath
  * the swamp surrounding Morthal
  * the bridge looking at Riverwood
  * the Rift, particularly when approaching Riften from the south

I recommend spending at least 10 to 20 minutes ingame. Enjoy the improved graphics and take some screenshots! Once you have quit the game, proceed with the next step.

## 7.5 Overwrite Cleanup

### 7.5.1 About the Overwrite

As mentioned before, the ***Overwrite*** folder in Mod Organizer 2 catches all files generated by mods or applications that would normally land in your **root** folder. After the first launch, you will find quite a few files in your ***Overwrite*** that were generated by mods.

Now if you delete these, they’ll just be regenerated when you next launch the game, but we don’t want them to clutter up the ***Overwrite*** either. The best solution is to keep these files with the mods they belong, inside their mod folders. This way they will also be removed and regenerated when the mod is updated.

### 7.5.2 Open in Explorer

* Right-click the ***Overwrite*** and select **Open in Explorer**.
* Navigate to `SKSE\Plugins` which may contain files for Simply Knock, Keyboard Shortcuts Fix, and Fuz Ro D’oh.
* Drag the window to the side or your second monitor.

### 7.5.3 Keyboard Shortcuts Fix

> Skip this step if you did not install Keyboard Shortcuts Fix.

* Find **Keyboard Shortcuts Fix** in your mod order, right-click it and select **Open in Explorer**.
* Navigate to `Keyboard Shortcuts Fix\SKSE\Plugins`.
* Drag the **KeyboardShortcutsFix.log** file from the ***Overwrite*** into that folder.
* The resulting file path should be:
  * `Mod Organizer 2\mods\Keyboard Shortcuts Fix\SKSE\Plugins\KeyboardShortcutsFix.log`

### 7.5.4 Fuz Ro D-oh

* Find **Fuz Ro D-oh** in your mod order, right-click it and select **Open in Explorer**.
* Navigate to `Fuz Ro D-oh\SKSE\Plugins`.
* Drag the **Fuz Ro D’oh.ini** file from the ***Overwrite*** into that folder.
* The resulting file path should be:
  * `Mod Organizer 2\mods\Fuz Ro D-oh\SKSE\Plugins\Fuz Ro D'oh.ini`

### 7.5.5 Simply Knock

> Skip this step if you did not install Simply Knock.

* Find **Simply Knock** in your mod order, right-click it and select **Open in Explorer**.
* Return to the root of the ***Overwrite*** – `Mod Organizer 2\overwrite`.
* Move the entire **SKSE** folder into the **Simply Knock** mod folder.
* The resulting file path should be:
  * `Mod Organizer 2\mods\Simply Knock\SKSE\`

### 7.5.6 Clean-up

* Close all Explorer windows and return to Mod Organizer 2.
* Double-click the ***Overwrite*** and delete any left-over files (there probably aren't any).

## 7.6 What now?

**Congratulations, you have completed The Phoenix Flavour!**

I hope you had a great time, found the instructions easy to follow, and didn’t run into any frustrating issues. Your game is now thoroughly overhauled and you learned plenty about modding in the meantime.

You will notice two additional sections following this one: In the **Customisation**, you may find many options to expand or tweak your current setup. This includes changes to improve performance so don’t be discouraged if you find your game running at less than 60FPS upon your first launch!

The final section, **New Game**, will help you get started with your next playthrough. It contains recommended changes to the Mod Configuration Menus.

So you see - your journey is not over yet.

**Happy modding!**