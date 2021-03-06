# Tray Monitor

<img src="https://raw.githubusercontent.com/strayge/tray-monitor/master/screenshots/tray.png" width=70%>

See your system's loading in tray.  

Different icons for:  
- battery status (with percentage, remaining time and charging status)
- CPU (including color marking for throttling)
- memory
- network I/O
- disk I/O

Single click uppon CPU / Memory icons open balloon with top processes.  
<img src="https://raw.githubusercontent.com/strayge/tray-monitor/master/screenshots/balloon.png" width=50%>

Double clicks opens Task Manager / Resource Monitor.

All colors, update intervals and some other parameters can be changed via GUI settings.  
<img src="https://raw.githubusercontent.com/strayge/tray-monitor/master/screenshots/settings.png" width=70%>

## Installing

* [Download the latest release](https://github.com/strayge/tray-monitor/releases)
* Copy needed icons to any folder (contains `BatteryIcon.exe`, `CpuIcon.exe`, `DiskIcon.exe`, `NetIcon.exe`, `RamIcon.exe`)
  * all settings will be saved to the same folder to `settings.ini`
* To enable autostart just right click uppon icon and check `Autostart`  
<img src="https://raw.githubusercontent.com/strayge/tray-monitor/master/screenshots/menu.png" width=20%>

## Compiling

This project was compiled with Visual Studio 2017.
