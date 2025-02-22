---

JavaScript Obfuscator Bot

A Telegram bot designed to obfuscate JavaScript code using various advanced obfuscation techniques. This bot allows users to upload .js files and receive obfuscated versions of their code, helping developers protect their JavaScript source code from reverse engineering.


---

✨ Features

✅ Multiple Obfuscation Methods – Supports techniques such as variable renaming, dead code injection, and more.
✅ Easy to Use – Upload your .js file, select an obfuscation method, and receive the processed file.
✅ Secure Processing – Ensures your code remains private and secure throughout the obfuscation process.
✅ Customizable – Extend the bot with additional obfuscation techniques or security features.


---

🚀 Getting Started

Prerequisites

Before setting up the bot, ensure you have:

1. Node.js (v18 or higher) installed.


2. A Telegram bot token (see instructions below).




---

🔑 Getting a Telegram Bot Token

1. Open Telegram and search for BotFather.


2. Start a chat with BotFather and use the command:

/newbot


3. Follow the instructions:

Set a name for your bot (e.g., JS Obfuscator Bot).

Choose a unique username (must end with bot, e.g., JSObfuscatorBot).



4. After completing the setup, BotFather will provide you with an API token. Keep it secure.




---

⚙️ Setting Up the Bot

1. Clone this repository:

git clone https://github.com/NyxObscura/javascript-obfuscator-bot.git
cd javascript-obfuscator-bot


2. Install dependencies:

npm install


3. Configure the bot by opening config.js and replacing 'YOUR_TELEGRAM_BOT_TOKEN_HERE' with your actual bot token:

module.exports = {
    TOKEN: 'YOUR_TELEGRAM_BOT_TOKEN_HERE',
};


4. Start the bot:

npm start




---

📡 Deployment

You can deploy the bot locally or on a server.

🌐 Local Deployment

Follow the setup instructions above, then run:

npm start

🖥️ Deployment to a Server

To deploy on a cloud server or VPS:

1. Install Node.js on your server (if not already installed).


2. Clone the repository to your server:

git clone https://github.com/NyxObscura/javascript-obfuscator-bot.git
cd javascript-obfuscator-bot


3. Install dependencies:

npm install


4. Configure the bot token in config.js.


5. Use PM2 to keep the bot running continuously:

npm install -g pm2
pm2 start index.js --name "obfuscator-bot"
pm2 save
pm2 status


6. To restart the bot:

pm2 restart obfuscator-bot




---

⚠️ Important Notes

Obfuscated Code Protection – The main logic file (main.js) is encrypted to protect the obfuscation algorithms. Do not attempt to modify or decrypt it.

Security Reminder – Never share your Telegram bot token publicly. If compromised, regenerate it using BotFather.



---

🛠️ Contributing

Contributions are welcome! To contribute:

1. Fork this repository.


2. Create a new branch for your feature or bug fix.


3. Commit your changes with descriptive messages.


4. Submit a pull request for review.




---

📜 License

This project is licensed under the MIT License. See the LICENSE file for details.


---

📞 Support

If you encounter issues or have questions, please open an issue on the GitHub Issues page.


---

🙌 Acknowledgments

js-confuser library for providing robust obfuscation tools.

Telegram team for their excellent bot platform.


Enjoy using JavaScript Obfuscator Bot! 🚀


---
