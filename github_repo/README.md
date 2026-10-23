# System Vitals

**A free health monitor and nightly backup for Windows 10 and 11.**

System Vitals keeps an eye on every part of your PC and warns you in plain words before small problems turn into crashes or lost files. It also backs up your files every night.

## Download

Get the newest **SystemVitals_Setup** file from [Releases](../../releases/latest), double-click it and click **Install**.
It installs for you only (no admin needed) and adds itself to Start. Its first page asks three things: start it with Windows, put an icon on your desktop, and back up your files.

Windows may say "Windows protected your PC" because the app is new: click **More info**, then **Run anyway**.

## What it watches

| Part | What it checks |
| --- | --- |
| CPU | hardware errors the CPU caught and fixed, program crashes, load and speed. Two of these close together is the pattern that comes before many crashes. |
| Graphics | temperature, power, speed, memory and driver errors (full detail for NVIDIA cards) |
| Drives | health, free space and how fast it fills, drive and cable errors |
| Memory | how much is in use, and Windows running low |
| Cooling & power | every temperature, fan and power line, while a free sensor tool runs (HWiNFO, LibreHardwareMonitor or AIDA64) |
| Apps | which programs and games crashed, and how often |
| Backups | your folders, copied to a second drive or a USB drive every night; older versions kept for 30 days |

It lives in the tray by the clock: **green** means all good, **amber** means watch out, **red** means danger.

## Privacy

System Vitals only reads. Nothing it sees leaves your PC: no accounts, no internet, no tracking.
"Copy a report for AI help" in its Settings puts a plain-text summary on your clipboard, and you decide where to paste it.

## Updating and uninstalling

To update, run a newer setup file: your settings and backups stay.
To uninstall, go to Windows Settings > Apps > System Vitals > Uninstall, or use "Uninstall System Vitals" in its own Settings. Your backups stay where they are.

## Licence

Free to use and share, unchanged and free of charge. Not for sale. No warranty. See [LICENSE.txt](LICENSE.txt).
