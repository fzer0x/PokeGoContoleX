# PokeGoControle

![PokeGoControle](https://raw.githubusercontent.com/fzer0x/PokeGoContole/main/Image.png)

PokeGoControle is an Xposed module designed for location simulation, specifically tailored for Pokémon GO. It provides a joystick overlay and various location-related settings to enhance the simulation experience.

## Features

- **Joystick Overlay:** Navigate in-real time with a customizable joystick.
- **Location Simulation:** Mock your GPS location with precision.
- **Advanced Parameters:** Simulate:
    - Accuracy & Vertical Accuracy
    - Altitude
    - Speed & Speed Accuracy
    - Mean Sea Level & Accuracy
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

## Installation

1. Install the PokeGoControle APK.
2. Open your Xposed Manager (e.g., LSPosed).
3. Enable the **PokeGoControle** module.
4. Ensure **Pokémon GO** is selected in the module's scope.
5. Reboot your device (or force stop the target app if using LSPosed).
6. Open PokeGoControle and grant the necessary permissions (Overlay, Location).

## Usage

1. Open the app and set your desired starting location on the map.
2. Configure your simulation settings (Speed, Accuracy, etc.).
3. Start the service to show the joystick overlay.
4. Open Pokémon GO and use the joystick to move.

## Disclaimer

This tool is for educational and development purposes only. Using third-party tools with Pokémon GO may violate their Terms of Service and could lead to account suspension or banning. Use at your own risk.

## License

This project is licensed under the GPL-3.0 License - see the [LICENSE](LICENSE) file for details.
