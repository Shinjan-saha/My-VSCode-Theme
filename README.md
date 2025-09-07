# My VSCode Theme 🎨

Welcome to **My VSCode Theme** repository!  
This project contains both my **old theme setup** and my **new customized theme**, built using [Code Aura](https://codeaura.godutta.tech) and enhanced with my own personal touches.  

---

## 📌 Overview
- **Old Theme** → My initial VSCode setup and styling.  
- **New Theme** → Based on **Carbon Steel Theme** generated using **Code Aura**, with additional customization.  

I’ve added **personal background styling** and some tweaks to make the editor truly feel like *mine*.  

---

## ✨ Features
- **Carbon Steel Base** – A clean, modern theme foundation from Code Aura.  
- **Personal Touch** – Custom background (`vscode-background-cover`) and visual adjustments.  
- **Two Versions** – Compare my old theme with the newly designed one.  
- **Consistent UI** – Minimal yet aesthetic, designed for long coding sessions.  

---

## ⚙️ Setup

   
1. Choosing File Locations

Windows:
```json
%APPDATA%\Code\User\settings.json
```
Mac:
```json
~/Library/Application Support/Code/User/settings.json
```

Linux:
```json
~/.config/Code/User/settings.json*.
```

2. change this part generated from the CodeAura Last Part for your own device specifictation settings find in the intial default settings .json :

   - Install [vscode-background-cover](https://marketplace.visualstudio.com/items?itemName=shalldie.background) extension.


```json
{
  "files.autoSave": "afterDelay",
  "C_Cpp.default.compilerPath": "/usr/bin/clang",
  "workbench.editor.empty.hint": "hidden",
  "sqldeveloper.sqlHistory.historyLimit": 500,
  "kotlin.languageServer.enabled": false,
  "kotlin.debugAdapter.enabled": false,
  "security.workspace.trust.untrustedFiles": "open",
  "github.copilot.nextEditSuggestions.enabled": true,
  "python.createEnvironment.trigger": "off",
  "backgroundCover.imagePath": "/Users/shinjansaha/Documents/background.png"
}
```




---

## 🔗 Resources
- [Code Aura Theme Generator](https://codeaura.godutta.tech)   
- [vscode-background-cover Extension](https://marketplace.visualstudio.com/items?itemName=shalldie.background)  

---

## 📜 License
This project is for **personal use**. Feel free to get inspired and make your own tweaks!  

---
💡 *Made with love for coding & design ✨*
