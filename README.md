# ZEUSosX_044_Crystal
A premium one-row layout modification for Windows 11 File Explorer featuring symmetrical 2px Crystal glass frames and DPI-safe scaling verification up to 250%. 
# ZEUSosX 044 Crystal - Windows 11 File Explorer Styler Theme

### 100% Verified Universal 44px Single-Row Layout with Unified 2px Glass Borders

An elegant, minimal single-row configuration optimized to completely remove cluttered stock borders and enforce a synchronized 2px 3D Glass linear gradient outline across modern Windows builds (24H2/25H2/26H2).

### 🧬 Behind the Name
* **ZEUSosX:** Represents the creator, bringing a powerful, stylized aesthetic to the desktop environment.
* **044:** Specifies the exact core height of the layout (**44 pixels**), capturing the engineering effort required to compress the multi-row interface into a single line.
* **Crystal:** Derived from the ancient Greek word **"Κρύσταλλος"** (crystal/pure ice), symbolizing the theme's signature glass-like 3D outlines and transparent structural components.

## ✨ Key Features
* **Pure One-Row Geometry:** Collapses the cluttered Windows 11 Explorer interface into a single 44px line for maximum screen real estate.
* **Unified 2px Glass Borders:** Every control element (Back, Forward, Up, Refresh, Address Bar, and Search Box) shares a synchronized 2px 3D Glass linear gradient outline.
* **Mac-Style Symmetrical Radii:** Globally enforces a strict `CornerRadius=16` across all titlebar components and pop-up overflow presenters for a fluid, premium aesthetic.
* **Zero-Flicker Solid Hover Overrides:** Replaces unstable translucent layers with custom, unblocked high-contrast solid blue accents (`#FF057AFD`) on foreground hover states to protect text layers from rendering glitches.
* **Hidden/Clean Tabs Framework:** Features a minimized and locked responsive tab skeleton layout tailored for minimalist setups.

## 🎯 100% Verified Universal Scale
Rigorously tested and verified across high-DPI environments spanning from **125% up to 250%**, despite Windows' internal subpixel anti-aliasing interpolation:
* ✅ 100% (Native Display Scaling Calibration)
* ✅ 125%
* ✅ 150% (Optimized Layout Baseline)
* ✅ 175%
* ✅ 200%
* ✅ 225%
* ✅ 250% (Extreme Resolution Crash-Tested)

## 🚀 Installation Guide
### Prerequisites
* Windhawk installed on your system. Download here: https://windhawk.net/

### Step-by-Step Installation
1. **Install Windhawk:** Download and install from https://windhawk.net/
2. **Install the Windows 11 File Explorer Styler Mod:** Launch the Windhawk app, click the "Explore" button, search for "Windows 11 File Explorer Styler", and click Install.
3. **Open the Mod Settings:** Go to the Windhawk Home page, find "Windows 11 File Explorer Styler", and click the "Settings" tab.
4. **Switch to Textual Mode:** In the settings panel, locate and click "Textual mode".
5. **Clear & Paste YAML Code:** Clear everything in the text editor. Copy the clean YAML code from `ZEUSosX_044_Crystal.yaml` in this repository and paste it into the mod settings' text editor.
6. **Apply Changes:** Click "Save settings". Changes take effect instantly! ✅

## 📋 YAML Configuration Highlights
The complete configuration is available in: `[ZEUSosX_044_Crystal.yaml](https://github.com/ZEUSosX/ZEUSosX_044_Crystal/blob/main/ZEUSosX_044_Crystal.yaml)`
* **Theme Name:** ZEUSosX_044_Crystal
* **Background Effect:** acrylic
* **Core Layout Height:** 44px

## ⚠️ Known Bugs & Limitations
This ultra-compressed 1-row layout achieves its minimalism via negative XAML bounds inside the compiled window chrome. Certain native behaviors require manual handling:

### 🖱️ Window Dragging (Mouse & Touch)
* **Issue:** Cannot click blindly on the top bar to drag the window.
* **Solution:** Target either the Search Box icon area, or the empty gap between Close/Caption buttons and the Search Box.

### 📑 No Tab Strip UI / Context Warning
* **Issue:** Tab strip region is completely collapsed.
* **Warning:** Never select "Open in new tab" from context menus (the new tab is created but remains invisible/inaccessible).
* **Solution:** Always use "Open in new window" instead.

### 🖥️ Desktop Launch Focus Glitch
* **Issue:** Opening a folder directly from the Windows Desktop may trigger a native focus bug, causing the Address Bar background to lock into solid white.
* **Solution:** Launch File Explorer via "This PC" (My PC) or use a standard pinned shortcut.

### 🔤 High-DPI Font Behavior
* **Expected:** Minor UI font shifts (e.g., search text jumping up by 2px at extreme scales like 225% or 250%).
* **Cause:** WinUI accessibility overrides. This is expected and normal behavior.

## 🔒 Terms of Use & Copyright
Copyright © 2026 ZEUSosX. All rights reserved.

### ✅ You CAN:
* Use it for free on your personal system.
* Apply it to your File Explorer.
* Share this repository link with others.

### ❌ You CANNOT:
* Modify, alter, or redistribute this code.
* Re-brand, rename, or take credit for creating it.
* Use it commercially, sell it, or rent it for profit under any circumstances.

**License:** Custom Standard Copyright - All Rights Reserved by ZEUSosX.

## 💬 Feedback & Support
If you encounter issues or have suggestions, verify you are using the latest stable Windows 11 build (24H2/25H2) and that you have cleared your Windhawk code cache by restarting `explorer.exe`.

Made in Greece, by ZEUSosX, June 2026 (Updated October 2026).  
Enjoy your minimalist File Explorer! 🎨

