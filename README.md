# 🎧 nOxygenTheDJ — Your Personal Discord Music Bot

**nOxygenTheDJ** is a slick, feature-rich music bot for Discord that brings your voice channels to life with your favorite tunes! Powered by Discord.js and a music streaming library, it supports playlists, streaming from YouTube, and crisp queue control — all with fun and simple commands.

---

 🌟 Features

- 🎶 Play music directly from **YouTube**
- 📃 Create and manage **dynamic queues**
- ⏯️ Control playback: `play`, `pause`, `resume`, `skip`, `stop`
- 🔁 Loop tracks or entire queues
- 🧹 Auto-disconnect after inactivity
- ⚙️ Lightweight and easy to host

---

 🚀 Getting Started

 1. Clone the Repo
```bash
git clone https://github.com/sarvesh-x/nOxygenTheDJ.git
cd nOxygenTheDJ
```
2. Install Dependencies
```bash
npm install
```
3. Set up Environment
Create a `.env` file in the root directory:
```bash
DISCORD_TOKEN=your_discord_bot_token
PREFIX=!
```
4. Start the bot
```bash
node index.js
```
Invite the bot to your server using your OAuth2 bot URL.

##

📜 Commands
| Command Syntax            |  Description                                 |
|---------------------------|----------------------------------------------|
| `!play <url or search>`   | Plays music from a YouTube URL or search term|
| `!pause`                  | Pauses the current track                     |
| `!resume`                 | Resumes the paused track                     |
| `!skip`                   | Skips the current song                       |
| `!stop`                   | Stops playback and clears the queue          |
| `!queue`                  | Displays the current music queue             |
| `!np`                     | Shows the song currently playing             |
| `!loop`                   | Toggles loop mode for the current track      |
| `!loop queue`             | Loops the entire queue                       |
| `!remove <position>`      | Removes a song at a specific position in the queue |
| `!shuffle`                | Shuffles the current queue                  |
| `!volume <0-100>`         | Sets the playback volume                    |
| `!help`                   | Shows the list of available commands        |

##

💻 Tech Stack
- Node.js
- discord.js
- @discordjs/voice
- ytdl-core (YouTube stream handler)
- dotenv (for environment config)

##
📂 Project Structure
```bash
nOxygenTheDJ/
├── commands/        # Command handler files
├── utils/           # Utility functions (e.g., queue manager)
├── index.js         # Bot entry point
├── config.js        # Bot configuration
├── .env             # Environment variables
└── package.json
```

##

🧠 Tips
- Always keep your bot token secret.
- Host the bot on platforms like Heroku, Repl.it, or your local server.
- Ensure YouTube stream limits are respected to avoid throttling.

##

🙌 Credits
- Created with 🎧 by sarvesh-x

📜 License
- This project is licensed under the MIT License. See LICENSE for details.
