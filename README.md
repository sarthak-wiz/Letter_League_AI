# Letter_League_AI

Letter League AI is a project that combines reinforcement learning and a Chrome extension to play Letter League, a game on Discord, and suggest the word with the most points based on the letters available and the board.

## Features

* Reinforcement learning agent that plays Letter League using a policy-based method like PPO or DDPG
* Chrome extension that suggests the word with the most points based on the letters available and the board
* User-friendly interface for the Chrome extension using Next.js, Tailwind CSS, and shadcn/ui
* Discord bot that interacts with the game and communicates with the AI

## Getting Started

1. Clone the repository: `git clone https://github.com/your-username/letter-league-ai.git`
2. Install the dependencies: `pip install -r requirements.txt`
3. Train the reinforcement learning agent: `python ai/train.py`
4. Run the Discord bot: `python discord_bot/bot.py`
5. Run the Chrome extension: `cd chrome_extension && npm install && npm run dev`

## File Structure

etter-league-ai/
├── ai/
│   ├── init.py
│   ├── env.py
│   ├── agent.py
│   └── train.py
├── discord_bot/
│   ├── init.py
│   └── bot.py
├── chrome_extension/
│   ├── public/
│   │   ├── index.html
│   │   └── ...
│   ├── src/
│   │   ├── components/
│   │   │   ├── WordSuggestion.js
│   │   │   └── ...
│   │   ├── pages/
│   │   │   ├── _app.js
│   │   │   ├──_document.js
│   │   │   └── index.js
│   │   ├── styles/
│   │   │   └── globals.css
│   │   └── ...
│   ├── package.json
│   └── ...
├── data/
│   └── words.txt
├── requirements.txt
└── README.md

## Tech Stack

* Python
* OpenAI Gym
* Stable Baselines
* SpaCy
* Discord.py
* Next.js
* Tailwind CSS
* shadcn/ui

## Contributing

Contributions are welcome! Please open an issue or submit a pull request.

## License

This project is licensed under the MIT License. See the LICENSE file for details.
