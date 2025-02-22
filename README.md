# JavaScript Obfuscator Bot

A Telegram bot designed to obfuscate JavaScript code using various obfuscation techniques. This bot allows users to upload `.js` files and receive obfuscated versions of their code. The bot supports multiple obfuscation methods, making it a versatile tool for developers who want to protect their JavaScript code.

---

## Features

- **Multiple Obfuscation Methods**: Choose from a variety of obfuscation techniques, including variable renaming, dead code injection, and more.
- **Easy to Use**: Simply upload your `.js` file and select the desired obfuscation method.
- **Secure**: The bot ensures that your code is processed securely and privately.
- **Customizable**: The bot can be extended with additional obfuscation methods or features.

---

## How to Get Started

### Prerequisites

1. **Node.js**: Ensure you have Node.js installed (version 18 or higher).
2. **Telegram Bot Token**: You need a Telegram bot token. Follow the steps below to get one.

### Getting Your Telegram Bot Token

1. Open Telegram and search for **BotFather**.
2. Start a chat with BotFather and use the `/newbot` command.
3. Follow the instructions:
   - Choose a name for your bot (e.g., `MyObfuscatorBot`).
   - Choose a username for your bot (must end with `bot`, e.g., `MyObfuscatorBot_bot`).
4. After completing the steps, BotFather will provide you with a token. Copy this token.

### Setting Up the Bot

1. Clone this repository:
   ```bash
   git clone https://github.com/NyxObscura/javascript-obfuscator-bot.git
   cd javascript-obfuscator-bot
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Open the `config.js` file and replace `'PUT_YOUR_TELEGRAM_BOT_TOKEN_HERE'` with your actual bot token:
   ```javascript
   module.exports = {
       TOKEN: 'YOUR_TELEGRAM_BOT_TOKEN_HERE',
   };
   ```
4. Start the bot:
   ```bash
   npm start
   ```

---

## Deployment

### Local Deployment

1. Follow the setup instructions above.
2. Run the bot locally using:
   ```bash
   npm start
   ```

### Deployment to a Server

1. **Install Node.js** on your server (if not already installed).
2. Clone the repository to your server:
   ```bash
   git clone https://github.com/NyxObscura/javascript-obfuscator-bot.git
   cd javascript-obfuscator-bot
   ```
3. Install dependencies:
   ```bash
   npm install
   ```
4. Set up environment variables:
   - Replace the `TOKEN` in `config.js` with your bot token.
5. Use a process manager like **PM2** to keep the bot running:
   ```bash
   npm install -g pm2
   pm2 start index.js --name "obfuscator-bot"
   ```
6. Ensure the bot is running:
   ```bash
   pm2 status
   ```

---

## Important Notes

- **Encrypted Main File**: The main logic file (`main.js`) in this project is encrypted to protect the obfuscation algorithms and ensure the security of the bot. Do not attempt to modify or decrypt this file.
- **Security**: Keep your bot token secure and do not share it publicly. If your token is compromised, regenerate it using BotFather.

---

## Contributing

Contributions are welcome! If you'd like to contribute to this project, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bugfix.
3. Commit your changes.
4. Submit a pull request.

---

## License

This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for details.

---

## Support

If you encounter any issues or have questions, please open an issue on the [GitHub Issues page](https://github.com/NyxObscura/javascript-obfuscator-bot/issues).

---

## Acknowledgments

- Thanks to the creators of the `js-confuser` library for providing powerful obfuscation tools.
- Special thanks to the Telegram team for their excellent bot platform.

---

Enjoy using the **JavaScript Obfuscator Bot**! 🚀

---
