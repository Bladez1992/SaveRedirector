# SaveRedirector
A universal Powershell script that can redirect and sync save games for any game, works with local and network drives. Fully configurable via an automatically generated .ini file

**Steam only for now, non-Steam version coming soon**

***Instructions***
 
• Put `SaveRedirector.bat` and `SaveRedirector.ps1` next to the .exe of the game you'd like to use the script with
 
• Run `SaveRedirector.bat` to run the script - alternatively you can manually run `SaveRedirector.ps1` from a Powershell prompt
 
• The script will have you do a first time setup and automatically generate `SaveRedirector.ini` in the same directory as the .bat and .ps1 files, you can edit this file if you need to change anything after the first run
 
• Save games will sync to your selected redirct directory every **10 seconds** and to your selected local backup directory in **Documents** every **60 seconds** - the redirect directory will stay constantly updated while the game is running and do a final sync after the game closes, the **Documents** backup will save up to 100 saves (100 minutes worth of gameplay) and delete anything older than that
