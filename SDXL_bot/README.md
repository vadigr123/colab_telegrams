# Telegram Stable Diffusion XL Bot 🤖🎨

A Telegram bot for generating AI images using Stable Diffusion XL with LoRA support. This bot allows users to create custom images via text prompts directly in Telegram.

## Features ✨
- Generate high-quality images from text prompts
- Support for LoRA models (`<lora:model_name>`)
- Multiple image size presets (square/wide/tall)
- Queue system with ETA display
- Image upscaling and regeneration options
- Detailed generation metadata

## Setup 🛠️
1. **Requirements:**
   - Google Colab (GPU recommended)
   - Telegram bot token from [@BotFather](https://t.me/BotFather)

2. **Run the bot:**
   - Open the [Colab Notebook](https://colab.research.google.com/github/your-repo/notebook.ipynb)
   - Enter your Telegram bot token
   - Click "Run all" (Runtime → Run all)

## Commands 💻

- `/start` - Initialize the bot
- `/models` - Select voice conversion model
- `/settings` - Adjust processing parameters
- `/status` - Check current configuration
- `/debug` - Toggle debug output display
- `/help` - Show help information


## LoRA Support 🧩
Add custom models using:
- `/lora https://civitai.com/models/...`
- Use in prompts: `<lora:model_name>` or `<lora:model_name:0.8>`

## Social Profiles 🌐
Connect with the creator:
- 🤗 [Hugging Face](https://huggingface.co/vadigr123)
- 🐦 [Twitter / X](https://x.com/vadigr123)
- 💬 [Discord](https://discord.gg/UtYvGwFfvx)
- 📱 [Telegram Channel](https://t.me/ai_mikus)

---

*This project contains code generated with AI assistance.*
