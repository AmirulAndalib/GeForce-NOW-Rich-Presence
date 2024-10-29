# GeForceNOW-Discord-Rich-Presence
![e47fb330-ad6c-4965-8488-600dc8176f86 - Copy](https://github.com/user-attachments/assets/b38445fb-0ae5-4cdc-b553-17e2829158df)

A modular application that updates your Discord Rich Presence with the current game you're playing on GeForce NOW, including fetching the game's Steam AppID.

## Features

- Detects the current game being played on GeForce NOW by monitoring window titles.
- Fetches the Steam AppID for the detected game using the Steam Web API.
- Updates Discord Rich Presence with game information and AppID.
- Caches AppIDs to minimize API calls and improve performance.
- Modular design for easy future enhancements.
- Configurable settings via `config/config.json`.
- Logging for monitoring application activity and errors.

## Requirements

- **Operating System:** Windows (support for macOS and Linux can be added).
- **Python:** 3.11

## Installation

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/luisbrn/GeForceNOW-Discord-Rich-Presence.git
   cd GeForceNOW-Discord-Rich-Presence
   
## License

## This project is licensed under the [Creative Commons Attribution-NonCommercial 4.0 International License](https://creativecommons.org/licenses/by-nc/4.0/).

