netman is EXTREMELY heavy handed script to self reboot if networking is lost, for headless installs where all else fails.
sys wifi power management fixes some (now older) versions of raspbian that would not disable power saving correctly, and kept resetting it on boot.


message to the poor lad that found this: if you still have issues after checking local wifi power management, look at your modems WMM power saving, that turned out to be my issue - turned it off and not had issues since.
