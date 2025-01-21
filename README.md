# Simple Discord Auto VC Bot

This is a Discord bot designed to easily and fast create temporary voice channals for your discord server.

## How it works!
Just simply create a voice channel that has the text "create" in it and your done. Example: "Create-GermanVC", "Englisch-Create", ....

## Features

- Automatically creates a temporary voice channel when a user joins a "Create" channel.
- Moves users to the newly created "Temp" voice channel.
- Monitors and deletes empty "Temp" channels.
- Provides logging for actions such as user movements and channel creations/deletions.
- Works with multible create voice channels.
- Copies the provisions from the corresponding create channel.

## Requirements

- Node.js version 16 or higher.
- A Discord bot token (set in `token.env` file).

## Installation

1. Clone this repository to your local machine:
   ```bash
   git clone https://github.com/TheGgito/SimpleDiscordAutoVCBot.git
   cd SimpleDiscordAutoVCBot
2. Install npm
   ```bash 
   npm install
3. DISCORD_BOT_TOKEN=your-bot-token-here
   
4. Start the bot.
- Just start the `start-bot.exe` if u are on windows OR on linux `start-bot.sh`.
   ```bash
   node bot-start.js

## Questions?
Add me on Discord @gigto

## Wanna have a even simpler way? Add my bot ^^
[Invite my Bot](https://discord.com/oauth2/authorize?client_id=1200573679738830868&permissions=277083450689&scope=bot%20applications.commands)

## License
This project is licensed under the Creative Commons Attribution-NonCommercial 4.0 International License (CC BY-NC 4.0).

You are free to:

Share — copy and redistribute the material in any medium or format
Adapt — remix, transform, and build upon the material for non-commercial purposes
Under the following terms:

You must give appropriate credit, provide a link to the license and project page on github, and indicate if changes were made. You may do so in any reasonable manner, but not in any way that suggests the licensor endorses you or your use.
You may not use the material for commercial purposes.
For more information, visit Creative Commons - CC BY-NC 4.0.
