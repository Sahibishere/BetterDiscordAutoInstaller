
<h1 align="center">
    BetterDiscordAutoInstaller
</h1>

<p align="center">
    <img src="https://img.shields.io/badge/python-3.12-green?logo=python&logoColor=white&style=for-the-badge">
    <img src="https://img.shields.io/badge/LICENSE-MIT-green?style=for-the-badge">
    <img src="https://img.shields.io/github/languages/code-size/Zwylair/BetterDiscordAutoInstaller?style=for-the-badge">
</p>

## About

`BetterDiscordAutoInstaller` is a script that works as the official [BetterDiscord installer](https://betterdiscord.app/). This script applies mod on **default** Discord (non canary, etc.). It automatically downloads `betterdiscord.asar` file from the official [BetterDiscord GitHub repo](https://github.com/BetterDiscord/BetterDiscord) and adds into loading modules.

Currently, `BetterDiscordAutoInstaller` is supported for **[Windows](https://github.com/Zwylair/BetterDiscordAutoInstaller/tree/master)** and **[macOS](https://github.com/Zwylair/BetterDiscordAutoInstaller/tree/macos)** platforms.

`BetterDiscordAutoInstaller` also allows you to add/remove it from autostart, without having to run it manually every time. For MacOS, the user can also choose to bind script to a keyboard shortcut to manually update.

## Setup and Dependencies

### Windows

Clone the repository:
```bash
git clone https://github.com/Zwylair/BetterDiscordAutoInstaller
```

Install the dependencies:
```bash
py -m pip install -r requirements.txt
```

Run the script:
```bash
py main.py
```

To add BetterDiscordAutoInstaller to your startup apps:
```bash
py startup_manager.py
```

### MacOS

You need to move to this [README.md](https://github.com/Zwylair/BetterDiscordAutoInstaller/tree/macos?tab=readme-ov-file#setup-and-dependencies)

## Contributing

I will be grateful for any contribution and help given to improve the quality of the project :)

_(especially about adapting the project to other platforms like linux, etc :3)_

### macOS
There is redundant/repetitive code which is seen both in manual-installer-mac.py and auto-installer-mac.py. 

That can be fixed. Just need to make sure to have 2 seperate files to allow for auto, manual install, and auto/manual-mixed functionalities. 

### Fork
Well, just fork it

**But please, don't forget to mention original project in your README**

## Special thanks

**[Ajit Mehrotra](https://github.com/Ajit-Mehrotra)** for adding masOS support

## License
This project is under the [MIT license](./LICENSE).
