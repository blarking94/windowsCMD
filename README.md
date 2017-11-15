# Windows Command Project
## A handy place for common windows commands 

### Creating a new alias and saving them

#### To save alias's on windows and create them when you start the command line

1. Open the registry editor by searching for **regedit** in the search bar 
2. Select HKEY_CURRENT_USER -> SOFTWARE -> MICROSOFT -> Command Processor
3. Add a new String Value with name "AutoRun" and data "%USERPROFILE%\env.cmd

Create and edit this "env.cmd" file under the user profile directory and fill it with your terminal start up commands!

#### Useful doskeys

* doskey notepad++=C:\Windows\System32\cmd.exe /c "SET LANG=en && START /D ^"C:\Users\benjamin.o.larking\Documents\npp.7.2.bin.x64" notepad++.exe"

* doskey sublime=C:\Windows\System32\cmd.exe /c "SET LANG=en && START /D ^"C:\Program Files\Sublime Text 3^" sublime_text.exe"

* doskey ls=dir (because why not!)


