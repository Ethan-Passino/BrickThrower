# 🧱 BrickThrower v2.0.0

**BrickThrower** is a Minecraft plugin that allows players to throw bricks with a right-click. For more advanced information, visit our [Wiki](https://github.com/Twocoolguy/BrickThrower/wiki).

---

## 🚨 Notice

I will **not be adding new content from my own ideas**. Most updates will focus on:

- Updating to support new Minecraft versions
- Fixing bugs/issues
- Updating documentation

Feel free to request new features, and I'll consider adding them if there's enough interest.

---

## 🛠️ Contributing

There is now a **wip** branch dedicated to updates, including bug fixes, Minecraft version support, and documentation improvements. All code changes and accepted pull requests will go to this branch.

Once enough changes are made, the **wip** branch will be merged into the main branch and released after testing. For major updates or suggestions, please join our [Discord](https://discord.gg/TyZM6ePB65).

---

## 📋 Patch Notes

### Version 2.0.0
- Refactored the entire codebase for improved readability and performance.
- Fixed several bugs, including issues with knockback and inventory loss in creative mode.
- Updated native version to 1.20.4 (supports 1.8 to 1.20.4).
- Performance improvements from removing unnecessary code.

> ⚠️ **This update may break some things due to major changes in the codebase.** Please report any issues on GitHub!

### Version 1.3.3
- Added config options: `item-velocity-multiplier` and `item-damage`.
- Removed the ability to repair BrickThrower items in anvils (except for 1.8).

<details>
  <summary>Older Patch Notes</summary>

### Version 1.3.0
- Added damage to thrown bricks against living entities.
- Older Minecraft versions can now use any chosen items.
- Prevented placing or consuming items with BrickThrower NBT data.

### Version 1.2.4
- Added support for Minecraft versions: 1.12, 1.11, 1.10, 1.9, 1.8.
- Refactored code for improved performance and readability.
- Fixed a bug that deleted off-hand items when throwing bricks.

### Version 1.2.3
- Added custom item configuration for `/brickthrower get` command.
- Improved performance and added new command alias (`/brth`).

### Version 1.2.2
- Added nether bricks as a throwable item (`/brickthrower get nether`).
- Switched to NBT tags for storing no-craft data instead of lore.

</details>

---

## 🔧 Known Issues

- Remove ability to use horse armor, arrows, armor/elytras, and heads with BrickThrower (1.8+).
  
*(These may or may not get fixed at some point 🤷‍♂️)*

---

Thanks for using BrickThrower! Feel free to contribute, report issues, or suggest improvements.
