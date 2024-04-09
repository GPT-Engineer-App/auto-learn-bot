# auto-learn-bot

A sophisticated bot designed for Robotic Process Automation (RPA) with advanced observation and learning capabilities. It starts by entering an 'observation mode' upon hearing the trigger word 'observe'. In this mode, the bot uses screen capture and computer vision to learn user actions. After learning, it indicates readiness with a 'ready' signal. The user then triggers task execution by commanding 'do it', prompting the bot to replicate the observed tasks. This system incorporates NLP for command processing, computer vision for action recognition, and scripting for task execution, aiming to automate repetitive tasks efficiently.

## Collaborate with GPT Engineer

This is a [gptengineer.app](https://gptengineer.app)-synced repository 🌟🤖

Changes made via gptengineer.app will be committed to this repo.

If you clone this repo and push changes, you will have them reflected in the GPT Engineer UI.

## Tech stack

This project is built with React and Chakra UI.

- Vite
- React
- Chakra UI

## Setup

```sh
git clone https://github.com/GPT-Engineer-App/auto-learn-bot.git
cd auto-learn-bot
npm i
```

```sh
npm run dev
```

This will run a dev server with auto reloading and an instant preview.

## Requirements

- Node.js & npm - [install with nvm](https://github.com/nvm-sh/nvm#installing-and-updating)
