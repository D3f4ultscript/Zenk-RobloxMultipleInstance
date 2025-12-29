# Zenk Multiple Instances in Roblox

A simple and efficient tool that allows you to run multiple Roblox instances simultaneously on a single PC with different accounts.

## Features

- Run unlimited Roblox instances on one computer
- Simple command-line interface
- Real-time instance counter
- Prevents accidental closure
- Lightweight and fast

## How to Use

1. Download and run `ZenkMultiInstance.exe`
2. Keep the program running in the background
3. Open Roblox with your first account
4. Open Roblox again with another account
5. Repeat for as many instances as you need

## Commands

- `count` - Display the number of active Roblox instances
- `exit` - Close the program

## Requirements

- Windows OS
- .NET 8.0 Runtime (usually pre-installed)
- Roblox installed

## Important Notes

⚠️ **Do NOT close the program while using multiple Roblox instances** - it will prevent new instances from opening.

## Technical Details

This tool works by capturing the `ROBLOX_singletonMutex` that Roblox uses to prevent multiple instances [web:30][web:33]. The program maintains ownership of this mutex, allowing multiple Roblox clients to run simultaneously [web:30].

## License

Free to use and modify.

---

**Created by Zenk**
