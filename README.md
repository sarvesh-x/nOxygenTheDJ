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
Command                  Description
!play <url/song>	      Plays music from YouTube
!pause	                Pauses the song
!resume	                Resumes the song
!skip	                  Skips the current track
!stop	                  Stops playback and clears the queue
!queue	                Shows the current queue
!np	                    Shows the song currently playing
!loop	                  Loops the current song or queue

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
