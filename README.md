# Location Joystick

Location Joystick is an Xposed module designed for location simulation. It provides a joystick overlay and various location-related settings to enhance the simulation experience.

![Screenshot](https://github.com/fzer0x/PokeGoContoleX/blob/main/screenshot.jpg?raw=true)

## Changelog
### 2.0.2
- FIX: Keyboard and Back button now work correctly in all apps while the overlay is running
- Improved overlay focus management (only requests focus when text input is active)

### 2.0.1
- Add Xposed Reload custom interval between "10ms - 1000ms" in Settings
- Add "Walking Algorithm" function to simulate small movements
- Bug fixes

### 2.0.0

- Completely new app design
- Selectable skins for overlay joystick
- hides the overlay joystick in one click on move button under mini-map
- added new settings in drawer
- improve stability
- bug fixes

### 1.1.0

- Fix stability Issues on some devices
- improve anti detection (need activate "system" in LSPosed Scope - Samsung A16 device tested - may work on other devices) 

### 1.0.6

- Fix Update Issue

## Features

- **Joystick Overlay:** Navigate in real-time with a customizable joystick.
- **Location Simulation:** Mock your GPS location with precision.
- **GNSS Mocking:** Full GNSS status simulation (Satellite count, SVID, C/N0, etc.) to bypass advanced detection.
- **Randomization:** Add a randomization radius to your location for a more natural movement profile.
- **Favorites:** Save and manage your favorite locations for quick teleportation.
- **Customizable UI:** 
    - Adjust joystick and minimap transparency (alpha).
    - Configurable joystick speed.
    - Persistent joystick position.

## Requirements

- **Android:** 10+ (Min SDK 30)
- **Root:** Required for Xposed Framework.
- **Xposed Framework:** LSPosed is recommended.

## Installation & LSPosed Scope

1. Install the Location Joystick APK.
2. Open your Xposed Manager (e.g., LSPosed).
3. Enable the **Location Joystick** module.
4. **Important:** Configure the scope in LSPosed:
    - **Android-System** (Must be checked for GNSS & System-wide mocking).
    - **Target App(s)** (e.g., Pokémon GO, Maps).
5. Reboot your device (or force stop the target app and system-ui if using LSPosed).
6. Open Location Joystick and grant the necessary permissions (Overlay, Location).

## Usage

1. Open the app and set your desired starting location on the map.
2. Configure your simulation settings (Speed, Accuracy, etc.).
3. Start the service to show the joystick overlay.
4. Open your target app and use the joystick to move.

## Disclaimer

This tool is for educational and development purposes only. Use at your own risk.

## License

This project is licensed under the GPL-3.0 License - see the [LICENSE](LICENSE) file for details.
