# Roblox Followers Bot

Roblox Followers Bot is a Discord bot designed to automate interactions with Roblox users. It can send friend requests, follow users, and initiate visits to Roblox games using provided Roblox cookies.

## Features

- **Send Friend Requests**: Automatically send friend requests to a specified Roblox user.
- **Follow Users**: Automatically follow a specified Roblox user.
- **Visit Games**: Initiate visits to a specified Roblox game.

## Installation

1. **Clone the Repository**

   ```bash
   git clone https://github.com/quehole/RobloxFollowers.git
   cd RobloxFollowers
   ```

2. **Install Dependencies**

   Ensure you have Python installed, then install the required packages:

   ```bash
   pip install discord.py requests
   ```

3. **Setup**

   - Create a `cookies.txt` file in the project directory with your Roblox cookies, each on a new line.
   - Open `main.py` and replace `YOUR BOT TOKEN` with your Discord bot token.

4. **Run the Bot**

   ```bash
   python main.py
   ```

## Usage

1. **Commands**:

   - `.rfriend [userId]`: Send 60 friend requests to the specified Roblox user.
   - `.rfollow [userId]`: Follow the specified Roblox user (up to 45 followers).
   - `.rvisit [gameId]`: Initiate visits to the specified Roblox game (up to 100 visits).

2. **Permissions**:

   Ensure the bot has the appropriate permissions in your Discord server to send messages.

## Notes

- Ensure you handle Roblox cookies securely and do not share them publicly.
- This bot interacts with Roblox and may require specific settings or cookies to function correctly.
- Use responsibly and comply with Roblox's [Terms of Service](https://en.help.roblox.com/hc/en-us/articles/115004647846-Roblox-Terms).

## Author

Created by [quehole](https://github.com/quehole). For further assistance or questions, please refer to the GitHub repository.
