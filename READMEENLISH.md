# **DBC Core Script**

### **Overview**

This script is a **high-performance core for MooMoo.io mods**, designed to replace bloated or broken scripts with a clean, modular base.
It includes:

* WebSocket hooking and packet handling
* Dynamic hotbar item detection
* Autoheal system
* Stacked insta logic
* Breaker system
* G-Spike + Boost system
* Smooth handling for player state and server communication

It **does not include** visuals, bots, menus, or extra UI clutter — just the pure game logic and mechanics needed for a custom MooMoo client.

---

## **Credits**

### **Lead Developer**

**[HaxBountyHunter](https://github.com/)**

* Built the **entire mod engine**, including:

  * WebSocket system
  * Networking codecs
  * Breaker and autoheal logic
  * Stacked insta core
  * G Spike + Boost mechanics
  * Core state handling and packet routing

> *"Every core piece of this script was written by HaX BountyHunter from scratch to make the smoothest, cleanest mod base for MooMoo.io."*

---

### **Mod Menu**

The **ESC toggle menu** used in some builds **was not made by HaX BountyHunter**.
It was created by **Meow???**, who likely used ChatGPT to generate most of the UI logic for:

* ESC Menu display
* Toggleable buttons for features
* Basic styling

> *"The menu was a later addition and isn't part of the core script. The main gameplay logic stands entirely on its own."*

---

## **Why This Script Exists**

The original VN Mod and similar mods had:

* Broken breaker functions
* Laggy or outdated networking hooks
* Overly complicated or messy code
* Unreliable keybind handling

This project was built **from the ground up** to:

* Be **fast and lightweight**
* **Separate UI (menu)** from core gameplay logic
* Give developers a **solid foundation** for building custom MooMoo clients

---

## **Features Included**

* **WebSocket hooking** for packet control
* **Autoheal system** with smart timing
* **Dynamic slot detection** for spikes, boosts, turrets, and food
* **Stacked Insta attack logic**
* **Breaker system** (DBC right-click breaker)
* **G Spike + Boost combo**
* Clean player state management

---

## **Features NOT Included**

* ESC menu UI
* Keybind presets
* Bots or automation scripts
* Custom visuals or theming

---

## **How to Use**

1. Load the script with Tampermonkey or another userscript manager.
2. Open MooMoo.io — the script hooks automatically.
3. Build your own UI and keybind system on top of this clean base.
4. Extend features by attaching to the exposed functions:

   ```js
   performStackInsta();
   performBreaker();
   performGSequence();
   ```

---

## **Final Notes**

* If you want a **pure gameplay mod**, use only HaxBountyHunter’s code.
* If you want an **ESC menu or UI**, you can combine this with Meow???’s menu or create your own.
* **Do not redistribute without credit** to:

  * **HaxBountyHunter** – for all core game logic
  * **Meow???** – for optional ESC menu UI

> *"This mod was built for speed, stability, and clean design — not flashy menus or bloated scripts."*
