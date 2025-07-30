# 🌗 Windows Auto Light/Dark Mode Scheduler

A lightweight PowerShell script to automatically switch between Light and Dark mode on Windows — no background apps, no bloat, and no unnecessary resource usage. Just set it and forget it.

## 🛠 Features

- 🌓 Automatically switches between Light and Dark themes based on your schedule
- ⚙️ No background services or apps required
- 🚫 Zero resource usage after setup
- 🧼 Simple, lightweight, and clean PowerShell-only implementation
- 🔒 Safe to use — modifies only theme settings

## 📦 What's Included

- `Auto_LightDarkMode.ps1` – The main PowerShell script
- Optional helper scripts (if any, e.g., for scheduling)

## 🖥️ Requirements

- Windows 10 or 11
- PowerShell 5.1+ or PowerShell 7+

## 🚀 How to Use

1. **Download the script**  
   Clone the repo or download the `.ps1` file directly.

2. **Edit your preferred schedule**  
   Open the script in a text editor and customize the `lightTime` and `darkTime` variables as needed.

3. **Run the script once**  
   It will create two scheduled tasks to switch themes at your desired times.

4. **That's it!**  
   Your system will now automatically switch between Light and Dark modes based on your schedule.

## 📅 Example Schedule (Default)

- Light mode: 7:00 AM
- Dark mode: 7:00 PM

Feel free to change these values in the script.

## 🔧 Optional: Uninstall Scheduled Tasks

To remove the automation, run the script again and choose the option to **remove scheduled tasks**.

## 🧑‍💻 Author

Made with 💻 by [AKSHAT_530](https://github.com/AKSHAT-530)

## 📄 License

MIT License – feel free to use, modify, and share!

