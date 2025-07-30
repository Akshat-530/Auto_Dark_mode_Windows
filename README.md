# 🌗 Auto Light/Dark Mode Scheduler by AKSHAT_530

A powerful, lightweight PowerShell tool to automate Windows theme switching between **Light** and **Dark** modes at your preferred times — without running any background apps or services.

No bloat. No resource drain. Just smart, scheduled automation.

---

## ✨ Features

- 🔁 Automatically switches between **Light** and **Dark** mode based on your schedule
- 🔐 Requires **no third-party app** or background service
- 🚀 Automatically sets correct theme **at logon**
- 🧠 Fully refreshes all open Windows/Explorer UI elements
- 🕒 Custom 24-hour format scheduling (e.g., 07:00 for Light, 19:00 for Dark)
- 🗑️ Option to **fully remove tasks and reset theme** in one click
- 📝 Logs every theme switch event to a `.txt` file
- 💡 Safe to use — works purely with Windows Registry and Task Scheduler

---

## ⚙️ Requirements

- 🪟 Windows 10 or 11
- 🛠️ PowerShell 5.1 or later (Windows default)
- 🔐 Must be run as **Administrator**

---

## 📦 Included in this Tool

| Script/Component | Description |
|------------------|-------------|
| `Auto_LightDarkScheduler.ps1` | Main automation script |
| `Set-Light-Mode.ps1` | Applies Light theme using registry |
| `Set-Dark-Mode.ps1` | Applies Dark theme using registry |
| `ThemeSwitchChecker.ps1` | Decides Light/Dark mode at logon |
| `ThemeSwitchLog.txt` | Optional log for theme change events |

All helper scripts are saved to your **user profile directory** (e.g., `C:\Users\YourName`).

---

## 📋 What This Script Does

1. **Prompts you to enter two times**:
   - One for switching to **Light mode**
   - One for switching to **Dark mode**
2. **Creates the following scheduled tasks**:
   - `ThemeSwitch_Light`: triggers your Light Mode script daily
   - `ThemeSwitch_Dark`: triggers your Dark Mode script daily
   - `ThemeSwitch_StartupChecker`: checks time and sets correct mode **at logon**
3. **Refreshes all open windows**, so the UI changes take effect immediately
4. **Creates log entries** in a file named `ThemeSwitchLog.txt`

---

## 🚀 How to Use

### 📥 Step 1: Download and Run

1. **Download the latest version** from the [Releases] section.
2. Extract the ZIP file.
3. Run the `RUN_AutoDarkMode.bat` file as **Administrator**.
4. Enter your preferred times for:
   - **Light Mode** (e.g., `07:00`)
   - **Dark Mode** (e.g., `19:00`)
5. That’s it! Your PC will now automatically switch themes at the scheduled times.

