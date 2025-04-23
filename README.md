
# Skript Worldcreator

## Setup
**Step 1:** To setup, you need to download latest version of plugins:
- [Skript](https://www.spigotmc.org/resources/skript.114544/) 
- [SkBee](https://modrinth.com/plugin/skbee/version/3.11.1)

**Step 2:** Put skript file at directory `plugins/Skript/scripts/worldcreator.sk`

**Step 3:** Reload the skript, using `/skript reload worldcreator.sk`

## Command usage
To create world, type command `/worldcreator <WorldName>`

### Command arguments:
#### 1st argument: 
`<WorldName>` - enter name of the world

#### 2st argument:

- #### **Optional world options:**
- - `--flat` - create a flat world

- - `--void` - create a void world

- - `teleport` - teleport to *created* world at location x: 0, y: 0 and z: 0

Usage: `/worldcreator <WorldName> --flat`

## Configuration:
``` sk
options:
    Permission: worldcreator.use # Permission flag
    PermissionMessage: &cNo permissions! # Message if player doesn't have permission
```
