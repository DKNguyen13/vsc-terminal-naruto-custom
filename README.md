# 🍥 VSCode Terminal Naruto Mod

A lightweight **Visual Studio Code Terminal customization pack** that brings a subtle Naruto-inspired aesthetic into your coding environment using CSS injection.

This mod enhances your terminal with:
- 🍥 Naruto Chibi decoration in terminal panel  
- 🧡 Chakra-inspired orange glow  
- 🌫️ Glassmorphism terminal background  
- ⚡ Lightweight performance (CSS-only)  

---

## 📖 Overview

This project customizes VS Code using **Custom CSS and JS Loader** to inject styling into the workbench UI.

It is designed for developers who want a more **immersive coding experience** without heavy performance cost.

---

## ✨ Features

- Naruto-themed terminal background accent
- Chakra orange terminal text glow
- Glass-style terminal UI
- Minimal performance impact
- Easy customization via CSS paths

---

## 📸 Preview

> Add screenshot here (before / after terminal UI)

---

## 🛠 Installation

### 1. Install Extension
Install:
👉 **Custom CSS and JS Loader**

---

### 2. Open VS Code Settings JSON

Press: Ctrl + Shift + P
Preferences: Open Settings (JSON)

---

### 3. Add CSS Path (General Setup)

Add this into `settings.json`:

```json
"vscode_custom_css.imports": [
    "file:///.../naruto-style.css"
]
```

---

### 4. Restart VS Code (IMPORTANT)

After enabling Custom CSS:

- Fully close VS Code
- Reopen VS Code

---

### 🔹 Use Base64 Image (Portable Setup)

If you want to avoid broken image paths when sharing your project, you can convert your image to Base64 and embed it directly into CSS.

#### Step 1: Convert Image
Use an online tool:
- https://base64.guru/converter/encode/image
- https://www.base64-image.de/

#### Step 2: Copy Base64 Output

You will get something like:

data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAA...

#### Step 3: Paste into CSS
```
:root {
    --team-7-chibi: url("data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAA...");
}```

#### ✅ Result
- No need for local image files
- Easy to share on GitHub

#### ⚠️ Trade-offs
- Bigger CSS file size
- Slightly heavier than local image
