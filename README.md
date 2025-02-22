# Discord Bot - Stable Diffusion AMD

This Discord bot, named "Stable Diffusion AMD," is designed to generate images based on user prompts using deep learning models. It utilizes the `discord.py` library and integrates with Hugging Face's model repository for image generation.

**Please note:** This is a development branch and might contain experimental features or changes.

## System Requirements
+ Python 3.8, 3.9, or 3.10 (https://www.python.org/)
+ Git (https://git-scm.com/downloads)

| Version | Supported          |
| ------- | ------------------ |
| AMD GPU | :white_check_mark: |
| Nvidia GPU  | :x: |
| AMD CPU | :white_check_mark: |
| Intel CPU | ❓ |

## Features

- Generate images based on user-provided prompts.
- Utilize a variety of deep learning models for image generation.
- Interact with images through reactions for regenerating them.
- Check for bot updates using a version comparison mechanism.
- Manage points to use the image generation feature.

## Commands

- `-creatimg [prompt] [negative_prompt]`: Add an image generation request to the queue (Cost: 5 points).
- `-load_model [model_name]`: Load a specific deep learning model for image generation.
- `-download_model [model_name]`: Download a model from Hugging Face's model repository.
- `-points`: Check your available points.
- `-addpoints [user] [amount]`: Add points to a user's balance (Admin only).
- `-resetpoints [user]`: Reset a user's points to 0 (Admin only).
- Reaction "🔄": Regenerate an image based on the original prompt.

## Installation and Usage

1. Clone the repository: `git clone https://github.com/SimolZimol/Discord-Bot-stable-diffusion-AMD.git`
2. Configure the `TOKEN` and `token_huggingface` variables in the `bot.py` file.
3. Open `start.bat` to install required dependencies and start the bot.
4. Customize your bot's features and appearance as needed.

## Credits

- Developed by [SimolZimol](https://github.com/SimolZimol).
- Utilizes the [discord.py library](https://github.com/Rapptz/discord.py) for Discord interaction.
- Integrates with Hugging Face's [model repository](https://huggingface.co/models) for deep learning models.

![2023-08-29 16_27_59-#admin-bot _ SimolZimol's official Discord Server - Discord](https://github.com/SimolZimol/Discord-Bot-stable-diffusion-AMD/assets/70102430/71b8380d-d4ee-4b6f-9ecb-3ad9da322668)
