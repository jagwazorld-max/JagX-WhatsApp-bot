# 🤖 JagX WhatsApp Bot

**The unlimited WhatsApp most powerful bot with 50+ features!**

A feature-rich WhatsApp bot built with Node.js and Baileys that provides automated messaging, media handling, message recovery, and much more.

## ✨ Features (50+)

### Core Features
1. **View Once Message Recovery** - See photos and videos sent as view once
2. **Deleted Message Recovery** - Retrieve deleted messages from chats
3. **Message Status Checker** - Check if messages were read/delivered
4. **Auto Reply System** - Automatic replies to specific keywords
5. **Message Scheduler** - Schedule messages to send at specific times
6. **Broadcast Messages** - Send messages to multiple users at once
7. **Message Translator** - Translate messages to different languages
8. **Grammar Checker** - Check and fix grammar in messages
9. **Text Formatter** - Apply bold, italic, strikethrough formatting
10. **QR Code Generator** - Create QR codes from text or URLs

### Media Features
11. **Image to Text (OCR)** - Extract text from images
12. **Image Resize** - Resize images to specific dimensions
13. **Image Converter** - Convert images between formats
14. **GIF Creator** - Create animated GIFs from images
15. **Video Downloader** - Download videos from YouTube, TikTok, Instagram
16. **Audio Extractor** - Extract audio from videos
17. **Audio Converter** - Convert audio formats
18. **Sticker Maker** - Convert images to WhatsApp stickers
19. **PDF Merger** - Combine multiple PDFs
20. **PDF to Image** - Convert PDF pages to images

### Utility Features
21. **Weather Info** - Get weather information for any location
22. **Horoscope** - Daily horoscope readings
23. **Currency Converter** - Convert between currencies
24. **Unit Converter** - Convert units (length, weight, temperature)
25. **Calculator** - Advanced mathematical calculations
26. **Dictionary** - Word definitions and meanings
27. **Synonym Finder** - Find synonyms and antonyms
28. **Code Formatter** - Format code snippets
29. **JSON Formatter** - Format and validate JSON
30. **URL Shortener** - Create short URLs

### Information Features
31. **Wikipedia Search** - Search Wikipedia information
32. **News Fetcher** - Get latest news
33. **COVID-19 Stats** - Current COVID-19 statistics
34. **Stock Market Info** - Real-time stock prices
35. **Crypto Prices** - Cryptocurrency prices and trends
36. **IP Lookup** - Get information from IP address
37. **Website Info** - Extract website metadata
38. **DNS Lookup** - Perform DNS lookups
39. **Port Scanner** - Check open ports on servers
40. **Ping Checker** - Check server connectivity

### Entertainment Features
41. **Jokes** - Random jokes and funny content
42. **Meme Generator** - Create memes from templates
43. **Quote of the Day** - Inspiring quotes
44. **Trivia Questions** - Random trivia with answers
45. **8Ball** - Magic 8-ball fortune telling
46. **Dice Roller** - Roll dice with customizable sides
47. **Coin Flipper** - Flip coins (heads/tails)
48. **Number Guessing Game** - Interactive guessing game
49. **Riddles** - Random riddles with answers
50. **Pokemon Info** - Get information about Pokemon

### Admin Features
51. **Group Statistics** - Group member and activity stats
52. **Admin Panel** - Manage bot settings and commands
53. **User Statistics** - Track user interactions
54. **Command Logging** - Log all command usage
55. **Bot Uptime Checker** - Check bot running time

## 🚀 Quick Start

### Prerequisites
- **Node.js** (v14 or higher)
- **npm** (Node Package Manager)
- **WhatsApp Account**
- **Stable Internet Connection**

### Installation

1. **Clone the Repository**
   \`\`\`bash
   git clone https://github.com/jagwazorld-max/JagX-WhatsApp-bot.git
   cd JagX-WhatsApp-bot
   \`\`\`

2. **Install Dependencies**
   \`\`\`bash
   npm install
   \`\`\`

3. **Configure Environment**
   \`\`\`bash
   cp .env.example .env
   # Edit .env with your settings
   \`\`\`

4. **Start the Bot**
   \`\`\`bash
   npm start
   \`\`\`

## 📱 How to Connect to WhatsApp

### Step-by-Step Connection Guide

1. **Start the Bot**
   - Run \`npm start\`
   - You'll see a QR code in the terminal or a browser window

2. **Scan QR Code with WhatsApp**
   - Open WhatsApp on your phone
   - Go to **Settings** > **Linked Devices** > **Link a Device**
   - Use your phone's camera to scan the QR code from your terminal/browser
   - Click **Link Device**

3. **Wait for Connection**
   - The bot will now sync with your WhatsApp account
   - Once connected, you'll see a confirmation message
   - Your account credentials are saved locally

4. **Using the Bot**
   - Open any WhatsApp chat
   - Type \`.menu\` to see all available commands
   - Start using any command from the menu

### Troubleshooting Connection Issues

- **QR Code not appearing?** - Try restarting the bot
- **Connection timeout?** - Check your internet connection
- **Bot disconnected?** - The bot will reconnect automatically
- **Permission denied?** - Run with proper permissions (not sudo)

## 📋 Command Menu

### Access Menu
Send \`.menu\` in any WhatsApp chat to see all available commands.

## 🔧 Configuration

Edit \`.env\` file to customize settings.

## 📦 Project Structure

\`\`\`
JagX-WhatsApp-bot/
├── src/
│   ├── commands/              # Command handlers
│   ├── handlers/              # Message handlers
│   ├── utils/                 # Helper functions
│   └── index.js               # Main entry point
├── .env.example               # Environment template
├── package.json               # Dependencies
└── README.md                  # This file
\`\`\`

## 🛠️ Installation Requirements

### Prerequisites
- Node.js 14.0+
- npm 6.0+
- 100MB disk space
- Stable internet

## 🚀 Deployment

### Local Deployment
\`\`\`bash
npm start
\`\`\`

### Using PM2
\`\`\`bash
pm2 start src/index.js --name "jagx-bot"
\`\`\`

## 🤝 Contributing

Contributions are welcome! Please follow these steps:
1. Fork the repository
2. Create a feature branch
3. Commit changes
4. Push to branch
5. Open a Pull Request

## 📜 License

MIT License - See LICENSE file for details

## ⚖️ Disclaimer

This bot uses Baileys library. Users are responsible for compliance with WhatsApp's ToS.

---

**Made with ❤️ by Jag World**
