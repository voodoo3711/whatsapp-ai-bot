# WhatsApp Bot Using Google Gemini Model

This project is a WhatsApp bot that integrates with the **Google Gemini Model** for generative AI-powered text responses. It is built using **Node.js**, leverages the **whatsapp-web.js** library for interacting with WhatsApp Web, and operates without a frontend.

---

## Features
- **WhatsApp Integration**: Automatically responds to user messages on WhatsApp.
- **Generative AI Responses**: Uses the **Google Gemini Pro** model to generate intelligent and context-aware replies.
- **Event Listeners**: Tracks bot status (authentication, connection, etc.).
- **Command-Based Interaction**: Responds to messages prefixed with `.bot`.

---

## Requirements
- **Node.js** (v14 or later)
- **npm** (Node Package Manager)
- A **Google Generative AI API key**
- A smartphone with WhatsApp installed

---

## Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/voodoo3711/whatsapp-ai-bot
2.  **Creating Node App with the following command**
   npm init -y

4.   **Installing Required Packages**
     npm i whatsapp-web.js @google/generative-ai qrcode-terminal
   
5. **In Non Window System Additional Installation Required**
      npm i puppeteer
      apt-get install gconf-service libasound2 libatk1.0-0 libc6 libcairo2 libcups2 libdbus-1-3 libexpat1 libfontconfig1 libgcc1 libgconf-2-4 libgdk-pixbuf2.0-0 libglib2.0-0 libgtk-3-0 libnspr4 libpango-1.0-0 libpangocairo-1.0-0 libstdc++6 libx11-6 libx11-xcb1 libxcb1 
      libxcomposite1 libxcursor1 libxdamage1 libxext6 libxfixes3 libxi6 libxrandr2 libxrender1 libxss1 libxtst6 ca-certificates fonts-liberation libappindicator1 libnss3 lsb-release xdg-utils wget
      sudo apt-get update
     sudo apt-get install -y gconf-service libasound2 libatk1.0-0 libc6 libcairo2 libcups2 libdbus-1-3 libexpat1 \
    libfontconfig1 libgcc1 libgconf-2-4 libgdk-pixbuf2.0-0 libglib2.0-0 libnspr4 libnss3 libpango-1.0-0 \
    libpangocairo-1.0-0 libstdc++6 libx11-6 libx11-xcb1 libxcb1 libxcomposite1 libxdamage1 libxext6 \
    libxfixes3 libxrandr2 libxrender1 libxss1 libxtst6 ca-certificates fonts-liberation libappindicator1 \
    libnss3 lsb-release xdg-utils wget
6. **The updated dependencies in package.json file will look like:**
    "dependencies": {
    "@google/generative-ai": "^0.2.1",
    "qrcode-terminal": "^0.12.0",
    "whatsapp-web.js": "^1.23.0"
}

7.    Get the API key from the Gemini AI API

8. add the bot.js file  and add your API-key.

9.  start the bot
     node bot.js









