# Server Manager for Fivem
This is a tool to easily manage server fivem

## Feature
- Start/Stop Server
- AutoRestart Server by schedule
- Change SystemInfo
- Console Command
- Resource Manager (Enable/Disable, Add/Remove, Start/Stop/Restart Resource in server.cfg)
- Restart Button (Manual Restart)
- AUTO Restart if Server Crash or Force Close
- Disable Close Program if Server Currently Running
- Start Server Without start_server.bat
- PlayerList
- Check For Update (Progam and Server)
- OneSync Support
- Kick All Player Button
- Option to Clear Cache When Restart in Setting menu
- Clear Cache Button (manual Clear Cache)


## ScreenShot



## Download
to download this tool. you can go to [Release](https://github.com/Oky12/FivemServerManager/releases) and download latest version

**Requirement**
- Net. Framework 4.0 or above


**Installation**
1. extract to Server-Data (Config.cfg and the program)
2. add resource tag(#System,  #InESXFolder, #OutESXFolder, #Addons) on server.cfg

Example
```
#System
start mapmanager
start chat
start spawnmanager
start sessionmanager
start fivem
start hardcap
start rconlog
#start scoreboard
#start playernames
start bob74_ipl
start mysql-async
start essentialmode
start esplugin_mysql
start es_admin2
#endSystem

#InESXFolder
start async
start cron
start es_extended
start instance
start es_camera
start skinchanger
start esx_accessories
start esx_addonaccount
#start esx_addoninventory
#start esx_phone
start esx_borrmaskin
#endInESXFolder

#OutESXFolder
#start CalmAI
#start CarRental
start 3dme
start hospital
start BlipsBuilder
start HangOntoAVehicle
start es_ui
start vMenu
#endOutESXFolder

#Addons
start taxi_toyota
start prison-map-addon
start Amarok
start audi
start bmw1000
start bmw_m5
start bmwf8
start bmwi8
start bmwm3
start bmwm4gts
start caferacerducati
start camry2016
#endAddons
```
3. open/run Fivem Server Manager
4. Set Location Fivem Server
