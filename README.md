# 🎮 My Simple Ped Selector (v1.0.0)

A lightweight and efficient desktop tool designed to manage and configure custom Addon Peds for GTA V. Download the official release directly from **GTA5-Mods.com**.

---

## 🛠️ How to Add and Configure Peds

To make your custom characters work correctly in-game and inside the application, follow these precise configuration steps:

### 1. Preparing the Ped Files in OpenIV
Before adding a character, check how its files are structured inside your addon dlc pack's `peds.rpf`:

* **Non-Streamed Peds (Standard):** If your ped consists of only **4 single files** (`.ydd`, `.ytd`, `.yft`, `.ymt`), place them directly inside `peds.rpf`.
  
* **Streamed Peds (Complex):** If your character has a separate folder for textures and high-definition fragments, you **must create a subfolder** with the exact name of the ped inside `peds.rpf` and place all the asset files inside it.

### 2. Configuring the Ped in the Application
1. Open **My Simple Ped Selector**.
2. Go to the top menu and click `Ped -> Create New Ped` (or use the shortcut `Ctrl + N`).
3. **Ped Name:** Enter the exact model name of your character (it must match the filename in OpenIV perfectly).
4. **Ped Gender:** Select whether the model is **Male** or **Female**.
5. **Is Streamed:** * Set to **False** if it is a standard single-file ped.
   * Set to **True** if it requires a dedicated texture subfolder.
6. Click **Save Ped**.
7. Click the **REBUILD!** button in the top panel to compile your changes into the database.
8. Finally, press `Ctrl + G` (or `File -> Save`) to lock in your project.

---

## ❓ Troubleshooting (Common Errors)

#### 🔴 The game crashes instantly when spawning the character
This happens when you exceed the game's internal archive limits. To fix this, make sure you have a custom `gameconfig.xml`, `HeapAdjuster`, and `Packfile Limit Adjuster` installed in your main GTA V directory.

#### 🔴 The character is completely invisible or has broken textures
Double-check the **Is Streamed** option in the app. If a ped has a texture folder in OpenIV but you set it to `False` in the selector, it will render incorrectly or not show up at all. Make sure it matches your OpenIV file structure.

---

## 📞 Support & Contact

If you find any bugs, have questions, or want to suggest new features for future updates, feel free to reach out:

* **Discord Username:** `miguelxd2`
* **Official Download Platform:** GTA5-Mods
