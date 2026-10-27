# ❄️ FrostBot V2

**A multipurpose Discord bot developed by FrostedWeFall.**

FrostBot is the second version of my original Discord bot, Frost. Originally developed using JavaScript and Discord.js, the project includes moderation, an economy system, user experience and levelling, and a custom command system.

> 🚧 **Project Status: Under Development**
>
> FrostBot V2 is being revisited and prepared for modernisation. Updates to the codebase, dependencies and features are planned.

## ✨ Features

- 🛡️ **Moderation** — foundations for server moderation features.
- 💰 **Economy** — a coin system with rewards for chatting.
- 📈 **Experience and Levels** — users earn XP and level up through activity.
- ⚙️ **Custom Commands** — a command handler for organising bot functionality.
- 🏠 **Multi-server Support** — configurable command prefixes for individual servers.
- 🔧 **Event System** — separate event handlers to keep the code organised.

*Features and compatibility are subject to change during modernisation.*

## 🛠️ Built With

- [Node.js](https://nodejs.org/)
- [Discord.js](https://discord.js.org/)
- JavaScript
- JSON-based data storage

## 📁 Project Structure

```text
FrostBotV2/
├── Website/       # Website files
├── commands/      # Bot commands
├── events/        # Discord event handlers
├── index.js       # Main bot entry point
├── botconfig.json # Bot configuration (not committed)
├── coins.json     # Economy data
├── prefixes.json  # Server prefixes
├── xp.json        # Experience and level data
├── package.json   # Dependencies and scripts
├── LICENSE        # MIT License
└── README.md
```

## 🚀 Getting Started

FrostBot currently uses an older version of Discord.js. Setup instructions may change as the project is modernised.

### Prerequisites

- Node.js
- A Discord application and bot account
- The required configuration and data files

### Installation

1. Clone this repository.
2. Install the project dependencies using `npm install`.
3. Configure your bot credentials locally.
4. Start the bot with `npm start`.

**Important:** The current codebase has not yet been fully updated for modern Discord.js versions.

## 🔒 Configuration and Security

- Keep your Discord bot token private.
- Never commit bot tokens, passwords or other secrets.
- Back up
