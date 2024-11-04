# GeForceNOW-Discord-Rich-Presence
![nvidia](https://github.com/user-attachments/assets/f01b9e5e-4cf4-4178-b39e-8719590c5f7c)
![icons8-logotipo-de-la-discordia-128](https://github.com/user-attachments/assets/5c3b161c-b062-4430-93c0-4433c472ce87)

This application enhances your Discord experience by updating your status with the current game you're playing on GeForce NOW. The script runs as a background process and clears your Discord status when you stop playing or close GeForce NOW.

Features
--------

-   Automatically detects games running on GeForce NOW and updates Discord Rich Presence.
-   Uses Steam Store to fetch game details and display the game icon.
-   Clears the Discord status when GeForce NOW is inactive.
-   Prevents multiple instances of the script from running simultaneously.

## Requirements

- **Operating System:** Windows (Incoming MAC and LINUX support)
## Screenshots
![image](https://github.com/user-attachments/assets/7a784c98-6da0-4ee2-b6d9-075e4c64e36a)
![Screenshot 2024-10-31 152405](https://github.com/user-attachments/assets/94b507d9-b751-4989-abad-7ebaa087cfb3)

## Installation

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/luisbrn/GeForceNOW-Discord-Rich-Presence.git
   cd GeForceNOW-Discord-Rich-Presence
2. Deactivate Rich Presence on NVIDIA GeForce NOW.
3. Create an application on https://discord.com/developers/applications/
4. Open your new app, go to Rich Presence, upload the images of the "GFN Images" folder, save.
5. Copy the Application ID.
6. Open the Cloned repository folder.
7. Double click on settings and paste the your ID.
8. Save.
9. Run the program "Discord GFNOW" and enjoy your new Rich presence.

   Notes: Use the image_downloader.exe to download images, this program looks at your cache file in config folder for the games already played.
You can find logs for the programs created when the application runs.
If you want it to run at start of windows create a task opening the Task Manager or Task Scheduler.
Windows+R, type shell:startup and paste a shortcut of Discord GFNOW


If you like it and feel is useful for you, support me if possible:

[!["Buy Me A Coffee"](https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png)](https://buymeacoffee.com/luisbrn)

   
## License

This project is licensed under the [Creative Commons Attribution-NonCommercial 4.0 International License](https://creativecommons.org/licenses/by-nc/4.0/).

