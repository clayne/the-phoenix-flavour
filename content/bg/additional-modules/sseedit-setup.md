---
title: "SSEEdit Setup"
weight:
type: docs
description: >
  How to set up SSEEdit.
---

{{< alert color="info" title="Summary" >}}
> This module covers the installation of SSEEdit for Mod Organizer 2.<p>
> **Prerequisite(s):** [MO2 Setup](/bg/additional-modules/mo2-setup/){{< /alert >}}

## About SSEEdit

xEdit is a tool for viewing and modifying Bethesda plugins.

Versions of it exist for most Bethesda games, not only Skyrim SE, and its name changes depending on the game: For example, xEdit for Skyrim SE is known as **SSEEdit** while xEdit for Skyrim LE was called **TES5Edit** and **FO4Edit** is used in Fallout 4 modding.

Once you have installed the programme, you can use it for any game that is supported by either changing the name of the executable, or starting it with a specific argument such as `-sse` for Skyrim SE.

{{< alert color="info">}}You will see the tool referred to as SSEEdit or xEdit interchangeably. Both mean the same thing.{{< /alert >}}

## Installation

SSEEdit is hosted on the Nexus:

- Download the latest version of [SSEEdit](https://www.nexusmods.com/skyrimspecialedition/mods/164).

### Installation Directory

{{< alert color="warning">}}The instructions below are *mostly* intended for those following the Core Module.{{< /alert >}}

I recommend keeping all your modding tools in one **Tools** folder

When it comes to picking an installation directory for tools, you can either create a folder inside the MO2 directory, i.e., `\Mod Organizer 2\Tools\`, or in a different location <u>on the same drive</u>.

{{< alert color="info">}}While tool authors often warn against running tools from within the MO2 directory, Wabbajack list authors have done just that for years with no issues that I am aware of. If you want to be on the safe side, pick a directory outside of your MO2 installation.{{< /alert >}}

- Create a **Tools** folder <u>on the same drive</u> as your Mod Organizer 2 installation.
- Inside your **Tools** folder, create a **SSEEdit** folder\*.

<font size=2>\**I like to append the version number to my tool folders (SSEEdit 4.0.4) so I am better able to track which version of my tools I have installed.*</font>

## MO2 Integration

Plugins are data folder files which means **SSEEdit** must be run through Mod Organizer 2 in order to access its virtual data folder.

- In Mod Organizer 2, click the [gears icon](/Pictures/bg/mo2-executables-settings.png) in the Toolbar to open the **Executables** settings.
- Click the small blue plus icon and select **Add from file**.
- Navigate to `\Tools\SSEEdit\` and double-click **SSEEdit.exe**.
- Click **OK** to add the executable to Mod Organizer 2.

![Add xEdit](/Pictures/bg/additional-modules/add-sseedit-to-mo2.png)

### Toolbar

SSEEdit should be automatically selected in the executables drop-down (if not, select it).

For maximum convenience, I recommend clicking the **Shortcut** drop-down below the **Run** button and selecting **Toolbar and Menu**.

{{<alert color="info">}} Click the SSEEdit icon in the Toolbar has the same effect as selecting it from the executables drop-down and clicking **Run**, except it is obviously faster. I recommend doing this for every tool.{{< /alert >}}

![Shortcut](/Pictures/bg/additional-modules/mo2-xedit-shortcut.png)

## SSEEdit Ref Cache

When loading up your plugins in SSEEdit, the tool will spend a considerable amount of time processing all records. To cut down on the loading time, SSEEdit creates a **ref cache** (caching reference records for each plugin) which reduces the startup time from several minutes to twenty seconds or less.

I recommend saving the cache files into the **SSEEdit** folder.

- In Mod Organizer 2, click the [gears icon](/Pictures/bg/mo2-executables-settings.png) in the Toolbar to open the **Executables** settings.
- Select **SSEEdit** in the list of executables.
- Under **Arguments** add the `-c:"filepath"` argument along with the file path.

Your file path will, of course, depend on where you installed SSEEdit. It must end in a `\cache\` folder. This folder does not have to exist, it will be created by SSEEdit upon generating the first cache files. <u>The file path must end on a trailing backslash.</u> 

For me, the argument looks like this:

```
-c:"G:\Modding Tools\SSEEdit\cache\"
```

![xEdit Refcache](/Pictures/bg/additional-modules/sseedit-refcache-argument.png)

### Generating Ref Cache

Launch SSEEdit through Mod Organizer 2 and click **OK** in the **Plugin Selection Window** to load all your currently installed plugins. This will take a moment as SSEEdit builds the cache files.

You can quit once the log at the bottom returns `Background loader: finished` or once you are prompted to activate ModGroups.

Check your `\Tools\SSEEdit\cache\` folder to make sure the files were saved to the correct location.

---

#### If you are currently working through the Core Module, return to [Step 3](/bg/core-module/step3).