# 🛠️ SkinPort BlueGem Bot

A **Discord bot integration** that actively monitors the SkinPort marketplace for **Case Hardened and Heat Treated knife and weapon finishes**.

---

## 📚 Overview

This bot connects to the **SkinPort WebSocket** to access the **Sale Feed (Live)** and actively scans for any listings featuring **Case Hardened** or **Heat Treated finishes**. It evaluates the pattern of these items, and if a match is found, it sends a detailed notification directly to a Discord server. 

This makes it an essential tool for traders looking for rare patterns such as **Blue Gems**. The project utilizes `discord.py` for seamless Discord integration.

---

## 🚀 Installation

### Step 1: Set Up the Bot
1. Check out discord.py on how to set up a Discord bot.
2. Copy your **bot token**.

### Step 2: Install Dependencies
Run the following command to install the required library:
```bash
pip install discord.py
```

---
## 🛠️ How to Use
#### 1. Clone this repository:
```bash
git clone https://github.com/your-username/SkinPort-BlueGem-Bot.git
cd SkinPort-BlueGem-Bot
```
#### 2. Open Script.py and replace:
```bash
TOKEN = 'YOUR_BOT_TOKEN_HERE'
```
with your Discord bot token.

#### 3. Run the bot:
```bash
python Script.py
```
4. Invite the bot to your Discord server using its client ID.
---

## 🔧 Example Notification
![SkinPort Bot Example](https://github.com/Sadat41/SkinPort-BlueGem-Bot/blob/main/image.png?raw=true)

---

## 📋 Notes
This bot uses the Skinport.py API wrapper to interact with the SkinPort marketplace.
Ensure your bot has the correct permissions to send messages to your server channels.

Checkout SkinPort API documentation:
```
https://docs.skinport.com/
```

## 🤝 Contributing
Contributions are welcome! To contribute:

1. Fork this repository.
2. Create a feature branch:
```bash
git checkout -b feature-name
```
3. Push your changes and open a pull request.

---
## Contact:
### Email: mdsadat@ualberta.ca
### Discord: sadat41
---
