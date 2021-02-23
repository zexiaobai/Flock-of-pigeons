## [1.0.0] - 2021-1-31
- first verson
 
## [1.0.1] - 2021-1-31
### Changed
- change the IP adress
- change the server
- delete all the data

## [1.0.2] - 2021-1-31
### Added
#### Plugin
- MobTransporter-2.2
- KeepChunks-1.6.7
- HyperSleep-1.0.1
- ImageOnMap-4.0
- AutoReplant-1.0

## [1.0.3] - 2021-2-1
### Removed
#### Plugin
- AutoReplant-1.0

## [1.0.4] - 2021-2-5
### Changed
- Allow using "copy bug by baby piglin"
- Allow using "deuplication carpet"
- Allow using "break bedroak"

## [2.0.0] - 2021-2-6
### Changed
-**changed server's core from "Paper" to "Fabric"** 
### Removed
#### Plugin
- MobTransporter-2.2
- KeepChunks-1.6.7
- HyperSleep-1.0.1
- ImageOnMap-4.0
### Added
#### Mod
- **Carpte**

## [2.1.0] - 2021-2-14
### Added
- MCDReforged
>MCDReforged (abbreviated as MCDR) is a tool which provides the management ability of the Minecraft server using custom plugin system.
### Changed
- server now base on MCDR

## [2.1.1] - 2021-2-17
### Added
#### Plugin
- AIchat
- Deep
- Daycount
- JsonDataAPI
- Seen and Liver
- Permantent Backip
- Quick Backup Multi > need debug
- Timed QBM
### Changed
- accident setback

## [2.1.2] - 2021.2.18
### Added
#### Plugin
- diepos
- gamemode > need to debug
- MinecraftDataAPI
- SimpleOP

## [2.1.3] - 2021.2.18
### Added
#### Plugin
- Hat > need debug
- PlayerDropS Kill > need debug

### bug report
- [MCDR] [07:15:40] [TaskExecutor/ERROR]: Error invoking listener EventListener[plugin=gamemode@0.0.0,priority=1000,callback=<function on_info at 0x039676E8>]
Traceback (most recent call last):
  File "C:\Users\Administrator\AppData\Local\Programs\Python\Python38-32\lib\site-packages\mcdreforged\plugin\plugin_manager.py", line 447, in trigger_listener
    listener.execute(self.mcdr_server.server_interface, *args)
  File "C:\Users\Administrator\AppData\Local\Programs\Python\Python38-32\lib\site-packages\mcdreforged\plugin\plugin_event.py", line 79, in execute
    return self.callback(*args, **kwargs)
  File "plugins\gamemode.py", line 20, in on_info
    per = server.get_permission_level(info)
  File "C:\Users\Administrator\AppData\Local\Programs\Python\Python38-32\lib\site-packages\mcdreforged\plugin\server_interface.py", line 38, in wrap
    return func(self, *args, **kwargs)
  File "C:\Users\Administrator\AppData\Local\Programs\Python\Python38-32\lib\site-packages\mcdreforged\plugin\server_interface.py", line 448, in get_permission_level
    raise TypeError('The Info instance is not from a user')
TypeError: The Info instance is not from a user

## [2.1.3] - 2021.2.23
### Unload
- Hat
- PlayerDropS kill
