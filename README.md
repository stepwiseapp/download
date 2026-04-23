# ☁️ Stepwise v2.2.9 – Release Notes

Stepwise 2.2.9 is a minor patch update aimed at enterprise users 🚀

## ⭐ Highlights

- Expanded enterrpise cloud workflows to allow each enterprise user to toggle cloud workflows on/off as needed.
- Allow users to download cloud workflows to their local file system.
- Patched minor bugs.

    - Note: True HIPAA compliance overhaul coming soon to cloud workflows..stay tuned!
    - Also, if non-enteprise, premium users would benefit from cloud workflows, we may shift towards that direction.


# 🏢 Stepwise v2.2.8 – Release Notes

Stepwise 2.2.8 introduces major usability upgrades, enterprise-ready features, and a smoother onboarding experience. This release makes building workflows faster, more intuitive, and more scalable for teams. 🚀

## ⭐ Highlights

- Drag and drop widgets directly from the sidebar into the editor  
- Guided Stepwise tutorial for first-time users  
- Enterprise account support with team-based features  
- Multi-select widgets with bulk actions  
- Stepwise documentation now live on the website  

## 🚀 Improvements

### Drag & Drop Workflow Builder
- You can now drag and drop command widgets from the sidebar directly into the editor for a faster, more intuitive workflow creation experience.

### Guided Onboarding Tutorial
- New users are now guided through Stepwise with a built-in tutorial to quickly understand core functionality and start building workflows.

### Enterprise Support
- Stepwise now supports enterprise accounts, unlocking team-based capabilities:
  - Custom branding so Stepwise fits seamlessly into your organization’s toolbox  
  - Cloud-synced workflows that can be shared across your team  

### Multi-Widget Selection (Power Feature)
- Hold **Shift + Click** to select multiple widgets  
- Use **Backspace** to delete selected widgets in bulk  
- Use **Ctrl + D** to duplicate selected widgets  

### Documentation
- Official Stepwise documentation is now available directly on the website for easier learning and reference.

### General Improvements
- Bug fixes and polish across the app for a smoother experience  

---

<details>

<summary> # 🥳 Stepwise v2.2.7 – Release Notes </summary>

Stepwise 2.2.7 focuses on fixing core issues, improving performance, and adding several requested capabilities. Enjoy!! 🤖

## ⭐ Highlights

- Live command glow — instantly see which workflow step is running

- Detailed Workflow HUD improvements — progress bar now aligns perfectly with execution

- 17 Date/Time formats supported in the Write Current Date widget

- Major performance boost from patched backend memory leaks

- Improved device detection for more reliable device limits

### 🚀 Improvements

Live Command Glow
- Active widgets now glow while executing so you can visually follow workflow progress in real time.

Detailed Workflow HUD
- The progress meter now accurately reflects workflow progress, including wait steps and execution states. (Toggle detailed HUD + Widget glow in Settings)

Write Current Date/Time Widget
- Now supports 17 widely used date and time formats for more flexible timestamp insertion.

Device Session Detection (User Requested)
- Improved identification of unique devices to make device limits more accurate.

### ⚙️ Automation Enhancements

Dropdown Clicking Support
- Improved coordinate selection now allows Stepwise to reliably click dropdown menus.

Raw AutoHotkey Widget Revival
- The Raw AHK widget is back with improved handling and stability.

Stronger Shortcut Toggling
- Hotkeys stay synchronized more reliably when modals or workflows are active.

### 🛠 Fixes & Performance

- Fixed memory leaks that caused duplicate backend processes

- Improved overall runtime performance

- Fixed Ctrl + S not saving in some scenarios

- Fixed Save As duplicating shortcuts when cloning workflows

- Fixed Quick Menu link freezing some PCs

- Restored Quick Menu display script

- Revamped default editor message for clarity

- Mixpanel analytics overhaul (now non-workflow invasive)

</details>

---

<details>
<summary># 🥳 Stepwise v2.2.6 – Release Notes</summary>

Welcome to **Stepwise v2.2.6**!  
We're excited to bring you this latest update, packed with user-requested features, important fixes, and a huge step toward enhanced security and performance.

## 🆕 What's New

### 🔐 Code-Signing Certification (No More Warnings!)
Stepwise is now **code-signed** software, meaning you’ll no longer see the security warnings when downloading or running the app. This change ensures that Stepwise is 100% secure and trustworthy, providing you with a seamless experience every time you install or update.

### 🖥️ Focus Bug Fix
We’ve fixed the issue where Stepwise sometimes required multiple clicks (up to 3) to bring the application back into focus. This bug has been resolved for a smoother user experience.

### 💻 Detailed Workflow Visualizer HUD
We've added a **Workflow Visualizer HUD** to show the workflow name, the current command executing, and a progress bar.  
Toggle it on or off from the settings to keep track of your workflows in real time.

### ⏳ Revamped "Wait for Me to Press Ctrl" Feature
We’ve heard your feedback! Users reported unwanted actions in some programs when needing to press the `Ctrl` key. Now, you have more control:
- You can press the `Ctrl` key or manually click the **blue button** to continue.
- If you want to abort, simply press `Shift + Esc` or click the **red button**.  
Additionally, we've polished the **UI** to make the experience smoother.

### ⚙️ UI Improvements and Bug Fixes
- **Better UI and responsiveness** for various controls and widgets.
- Fixed focus issues when using certain keyboard shortcuts.
- Other minor visual tweaks for a sleeker experience.
</details>

---
<details>
<summary># 🥳 Stepwise v2.2.5 – Release Notes</summary>

## 🆕 What's New

### 💻 Use Stepwise on up to 3 Devices
You can now install and use Stepwise across **three separate devices** under a single account.  
This is a better compromise for individual users who want flexibility to automate across a laptop, desktop, or work machine — without needing a team or enterprise license.  
🛠 _Coming soon_: cross-device syncing of workflows and preferences.

### ⏳ 30-Day Trial System
New users receive a **30-day trial** of Stepwise Premium with access to:
- Unlimited workflows
- The workflow recorder
- Advanced shortcuts
- No credit card required

Our trial detection logic also ensures fair usage across devices.

### 🔴 Automatic Workflow Recorder
Create workflows by example — just hit record and perform your tasks. Stepwise will generate the workflow in real-time.  
Perfect for users who want automation without the drag-and-drop editor.

### 🧠 Smart Features in Development
This update lays groundwork for upcoming AI-powered tools:
- Natural language → automation translation
- Automation suggestions based on repeated activity

📣 _Stay tuned — these are coming soon to premium users._

### ⚙️ Settings Menu Overhaul
The new **Settings Menu** gives you full control over:
- Global shortcut toggle
- Implicit wait timing between steps
- Hotkey/hotstring detection during recording
- Raw AutoHotkey code widget toggle
- Delete all workflows (wipe)
- _Coming soon_: Gaming Mode, Sound FX on widget drop

### ▶️ Animated Workflow/Recorder Icon
A sleek animated icon now appears when workflows are running or being recorded.  
Easily track background automations at a glance.

### ⛔ Abort Workflows Instantly (Shift + Esc)
Press `Shift + Esc` to immediately stop:
- Any running workflow
- Active workflow recording

Useful in emergencies or testing scenarios.

### 🖱️ Multidrag Widgets (Shift + Click)
You can now select and move **multiple widgets** at once in the editor using `Shift + Click`.  
Massively improves productivity and layout control.

### 🤖 Raw AutoHotkey Code Support (Advanced Users)
Insert **raw AutoHotkey code** as part of your workflows for full scripting power.  
Stepwise passes it through without formatting or interference.
</details>

---

<details> 
<summary>🥳 Stepwise v2.2.4 – Release Notes</summary>

## 🆕 What's New

### 🔤 Hotstring Shortcuts
- Workflows can now be triggered using hotstrings
- Ex: typing `asap` → expands to "as soon as possible"

### 👤 User Authentication + First Launch
- Google Sign-in enabled
- Confetti animation on first login 🎉

### 🪟 Open Existing Window Widget Revamp
- Fully redesigned for cross-Windows compatibility

### ⚙️ Misc Improvements
- Live-updating tray context menu
- New “write today’s date” widget
- Abort key (Shift + Esc)
- “About” screen via start menu
- Create Text Shortcut modal

### 🐛 Bug Fixes
- Crashes when deleting current workflow
- Crash in “Open Existing Window” fixed by better dropdown
- Crash in “Wait for Existing Window” fixed similarly
- Crashes now logged to our database
- Write-prompt widget supports longer prompts

</details>

---

## 📦 Download

- [🔧 Installer (Stepwise.Setup.exe)](https://github.com/stepwiseapp/download/releases/latest/download/Stepwise.Setup.exe)  
- [📦 Portable (Stepwise.zip)](https://github.com/stepwiseapp/download/releases/latest/download/Stepwise.zip)

---

## 📣 Stay Connected

- 🌐 [Stepwise Forum](https://www.hellostepwise.com/forums) – Ask questions, share automations, and connect with other users
- 💻 [GitHub](https://github.com/stepwiseapp) – Track development, submit issues, and follow updates
- 🔎 [LinkedIn](https://www.linkedin.com/company/hellostepwise) – Check us out on LinkedIn!
