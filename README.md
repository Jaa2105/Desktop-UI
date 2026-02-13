# FitOS Desktop UI 🚀

**FitOS** is a fun project that creates a mock fitness desktop in HTML, designed to motivate you to maintain healthy habits. Best of all, it can be launched directly from a custom **interactive Bash shell**.

## 📁 Project Content

- `fitos_desktop_ui.html`: A simulated desktop interface with access to:
  - Workout plans
  - Meditation
  - Daily hydration
  - Nutrition
  - Advanced mode (macro tracking)
  - Daily challenges
- `shell_interactiva.sh`: A Bash script that allows you to:
  - Launch the FitOS interface in your browser (`launch`)
  - Install auxiliary pages (`install`)
  - Uninstall resources (`uninstall`)
  - View current date and time (`time`)
  - Display fitness ASCII art (`fitness`)
  - View wellness pages in text mode (`salud`)
  - Run commands in interactive mode

## 🚀 Installation and Usage

1. **Clone this repository**:
   ```bash
   git clone [https://github.com/your_username/fitos_desktop.git](https://github.com/your_username/fitos_desktop.git)
   cd fitos_desktop
   
Grant execution permissions to the script:
chmod +x shell_interactiva.sh

Run the interactive shell:
./shell_interactiva.sh



Available commands within the shell:

-install → Creates sample HTML files.

-uninstall → Deletes installed files.

-launch → Opens the FitOS desktop in your browser (default: Firefox).

-fitness → Displays motivational ASCII art.

-salud → Opens a wellness guide in text mode (requires lynx).

-time → Shows the current date and time.

-exit → Exit the shell.

## ⚡ Requirements
-Linux or MacOS (easily adaptable to Windows WSL)

-Firefox browser (or modify the script for another browser)

-lynx installed for text-based navigation:
sudo apt install lynx  # On Debian/Ubuntu
## 🎯 Project Goal
-This project is primarily educational and recreational:

-Practice Bash scripting.

-Simulate lightweight desktop environments.

-Have fun creating small motivational apps.

## 📜 License
This project is licensed under the MIT license.
