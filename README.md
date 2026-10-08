# Fast Fix System Management Utilities

A suite of lightweight, high-performance administrative tools designed to help power users troubleshoot, monitor, and clean Windows systems.

These tools are developed and provided entirely **for free** courtesy of **[FastFixItSolutions.com](https://fastfixitsolutions.com)**.

---

## 🛠️ Included Utilities

### 1. Fast Fix Uninstaller (`Uninstaller.exe`)
A surgical force-uninstaller built for scenarios where the native Windows "Apps & Features" control panel fails, or when application uninstallers are corrupted or missing.
* **Full Registry Scans:** Enumerates hidden 32-bit and 64-bit software entries.
* **Instant Search Filter:** Real-time search to pinpoint stubborn programs instantly.
* **Silent Uninstallation Enforcer:** Modifies standard setups (including MSI packages) to run completely silently in the background, suppressing corrupted GUI error blocks.
* **Deep Purge Sequence:** Manually obliterates lingering disk folders and forcefully removes matching registration keys from the system registry cache.

### 2. Fast Fix Resource Monitor (`reasorcemonitor.exe`)
A lightweight, live-updating task management dashboard that tracks software resource footprints and provides targeted process termination controls.
* **Global Telemetry Progress Bars:** Real-time visual tracking of global CPU load and memory usage.
* **Interactive Dynamic Sorting:** Sort processes instantly by PID, Name, CPU utilization, or memory consumption (MB).
* **Live Target-Locked Refreshes:** Refreshes background statistics every 2 seconds without losing your active row selection.
* **Surgical Path Tracking:** Clicking any active process instantly unmasks its absolute directory path on your storage drive.
* **Explorer Bridge Integration:** Includes an option to launch Windows File Explorer and highlight the selected running software package automatically.
* **Forced Task Killer:** Terminates frozen or locked software routines instantly via deep system kernel hooks.

---

## 🚀 Execution & Requirements

To prevent Windows security mechanisms from blocking deep-level registry modifications or file purges, both utilities require administrative privileges.

### Running the Executables (`.exe`)
* If compiled using the recommended `--uac-admin` configuration flag, double-clicking the application will **automatically trigger the Windows User Account Control (UAC) shield prompt**.
* Alternatively, right-click the executable file and select **Run as administrator**.

### Running from Source Code (`.py`)
If running the raw Python scripts within an IDE (such as PyCharm or VS Code) or via a terminal layout, ensure your environment is fully elevated:
1. Close your active IDE environment completely.
2. Right-click the IDE shortcut or terminal icon and select **Run as administrator**.
3. Install dependencies via the terminal before launching:
   ```bash
   pip install psutil
   ```

---

## ⚖️ License & Disclaimer

These utilities are provided "as-is" without express or implied warranties of any kind. 

Because these tools manipulate system memory structures, terminate active background tasks, and drop keys from the Windows Registry, they must be used with care. The developers at FastFixItSolutions.com shall not be held liable for system instability, loss of data, or accidental deletion of critical OS system assets resulting from the use or misuse of this software software suite. Always verify the target application or process PID before authorizing a purge.

---

### 🌐 Need More Support?
For custom troubleshooting scripts, automated deployment workflows, or specialized IT assistance, visit us online at:
👉 **[FastFixItSolutions.com](https://fastfixitsolutions.com)**
