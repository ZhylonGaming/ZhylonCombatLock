# ZhylonCombatLock

ZhylonCombatLock is a plugin made for the Spigot server software.  
It has combat-related features to add to your server.  

## Main Features

- Custom how the plugin works
- Tag players when they attack other players
- Punish players that log out during combat

## Config
- enabled
  - Whether the CombatLock plugin is enabled or not (Needs a Server restart)
- combatlock-enabled
  - Whether the combat lock is enabled or not
- combatlock-timeout
  - The time in seconds before the combat lock is removed
- combatlock-bypass-enabled
  - Whether the combat lock bypass is enabled or not

| Permission           | Beschreibung                                                                       | Standard |
| -------------------- | ---------------------------------------------------------------------------------- | -------- |
| `combatlock.toggle`  | Enables or disables the combat lock (Command `/combatlock`)        | Operator |
| `combatlock.check`   | Checks if a player is in combat lock (Command `/combatlock-check`) | Operator |
| `combatlock.reload`  | Reloads the CombatLock plugin configuration (Command `/combatlock-reload`)        | Operator |
| `combatlock.timeout` | Sets the timeout for the combat lock (Command `/combatlock-timeout <Sekunden>`) | Operator |
| `combatlock.toggle-bypass` | Enables or disables the combat lock bypass | Operator |
| `combatlock.bypass`  | Allows player to bypass the combat lock restrictions | Operator |


## Installation Guide

1. Download the ZhylonCombatLock.zip file from the [Download Section](https://github.com/ZhylonGaming/ZhylonCombatLock/releases).
2. Extract the contents of the ZhylonCombatLock.zip to your PC.
3. Click the stop button on the panel. If your server doesn't use a panel, type `stop` into the console.
4. Upload `ZhylonCombatLock.jar` to your server `/plugins/` folder.
5. Delete the `ZhylonCombatLock.zip` file.
6. Start/Restart your server using the panel or your startup script.
7. Edit the configuration files `config.yml` for the main plugin.
8. Type the command `/clreload` to reload the configuration files.

## Download

Donwload this Plugin from the download section:
[https://github.com/ZhylonGaming/ZhylonCombatLock/releases](https://github.com/ZhylonGaming/ZhylonCombatLock/releases)
    
 
## Commands

#### 1. `/combatlock`

* **Description:** Aktiviert oder deaktiviert den Combat Lock für den Server.
* **Usage:** `/combatlock`
* **Permission:** `combatlock.toggle`
* **Permission Message:** You do not have permission to use this command.
* **Aliase:** `cl`, `combatlocktoggle`

#### 2. `/combatlock-check [<player>]`

* **Description:** Prüft, ob ein Spieler gerade im Combat Lock ist.
* **Usage:** `/combatlock-check <Spielername>`
* **Permission:** `combatlock.check`
* **Permission Message:** You do not have permission to use this command.
* **Aliase:** `clcheck`, `combatlockcheck`

#### 3. `/combatlock-reload`

* **Description:** Lädt die Plugin-Konfiguration neu.
* **Usage:** `/combatlock-reload`
* **Permission:** `combatlock.reload`
* **Permission Message:** You do not have permission to use this command.
* **Aliase:** `clreload`, `combatlockreload`

#### 4. `/combatlock-timeout <seconds>`

* **Description:** Setzt die Dauer (in Sekunden) des Combat Locks.
* **Usage:** `/combatlock-timeout <seconds>`
* **Permission:** `combatlock.timeout`
* **Permission Message:** You do not have permission to use this command.
* **Aliase:** `cltimeout`, `combatlocktimeout`

#### 5. `/combatlock-bypass`

* **Description:** Toggles the combat lock bypass on/off.
* **Usage:** `/combatlock-bypass`
* **Permission:** `combatlock.toggle-bypass`
* **Permission Message:** You do not have permission to use this command.
* **Aliase:** `clbypass`, `combatlockbypass`

## Sponsors

The people or organizations listed below were kind enough to fund my open-source projects!

- Development by [ZhylonGaming](https://github.com/ZhylonGaming).


## Support

Support is provided by creating a new issue, or by chatting with the Support Team on my discord.  
**Discord Link:** <https://discord.gg/9GaJP46WuF>
