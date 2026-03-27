# SaveRedirector
A universal Powershell script that can redirect and sync save games for any game, works with local and network drives. Fully configurable via an automatically generated .ini file

***Instructions***
 
• Put `SaveRedirector.bat` and `SaveRedirector.ps1` next to the .exe of the game you'd like to use the script with
 
• Run `SaveRedirector.bat` to run the script - alternatively you can manually run `SaveRedirector.ps1` from a Powershell prompt

• The script will have you do a first time setup and automatically generate `SaveRedirector.ini` and `SaveRedirector.log` in the same directory as the .bat and .ps1 files, you can edit the **.ini** file if you need to change anything after the first run - the log file merely logs the actions of the script
 
• Save games will sync to your selected redirct directory every **5 seconds by default (configurable)** and to your selected local backup directory in **Documents** every **60 seconds by default (configurable)** - the redirect directory will stay constantly updated while the game is running, the **Documents** backup will save up to 100 saves (100 minutes worth of gameplay) and delete anything older than that
