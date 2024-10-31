# GeForceNOW-Discord-Rich-Presence
![nvidia](https://github.com/user-attachments/assets/f01b9e5e-4cf4-4178-b39e-8719590c5f7c)
![icons8-logotipo-de-la-discordia-128](https://github.com/user-attachments/assets/5c3b161c-b062-4430-93c0-4433c472ce87)

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

