# 🖥️ node-plane - Control secure nodes from Telegram

[![Download node-plane](https://img.shields.io/badge/Download%20node-plane-4CAF50?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Reesheaded250/node-plane)

## 📌 What this is

node-plane is a control plane for secure self-hosted nodes. It uses Telegram so you can manage access, check node status, and handle basic control tasks from your phone or desktop.

It is made for people who run their own network services and want a simple way to manage them without opening a full admin panel each time.

## ⚙️ What you can do

- Add and remove users
- Check if a node is online
- Manage access from Telegram
- Work with secure connectivity tools
- Run it on your own server
- Keep control in one place
- Use it with common self-hosted setups

## 🪟 Windows setup

node-plane is designed for self-hosted use. On Windows, the simplest path is to download the project from the link below and run it in a supported local setup.

### ⬇️ Download

Visit this page to download and set up node-plane:

https://github.com/Reesheaded250/node-plane

### 🧩 Before you start

You will need:

- A Windows PC
- Internet access
- A Telegram account
- A GitHub account or browser access to the download page
- A local environment that can run Python apps or Docker apps

If you are not sure which setup to use, start with the Docker path if you already use Docker Desktop. Use the Python path if you prefer a direct local run.

## 🚀 Quick start

1. Open the download page:
   https://github.com/Reesheaded250/node-plane

2. Download or clone the project files.

3. Choose one way to run it:
   - Docker
   - Python

4. Set up your Telegram bot token.

5. Add your node and access settings.

6. Start the app and open Telegram.

7. Send a command to confirm that it works.

## 🐳 Option 1: Run with Docker

Use this path if you already have Docker Desktop on Windows.

### What to do

1. Install Docker Desktop if you do not have it.
2. Open PowerShell or Command Prompt.
3. Go to the folder where you saved node-plane.
4. Build or start the app with the files in the project.
5. Set the needed Telegram and node settings in the config file or environment variables.
6. Start the container.
7. Check Telegram to make sure the bot responds.

### Why this helps

Docker keeps the app in one place. It also makes it easier to move the same setup between machines.

## 🐍 Option 2: Run with Python

Use this path if you want to run the app directly on Windows.

### What to do

1. Install Python 3.11 or newer.
2. Download the project from:
   https://github.com/Reesheaded250/node-plane
3. Open the project folder in File Explorer.
4. Open PowerShell in that folder.
5. Create a virtual environment.
6. Install the required packages.
7. Set your Telegram bot token and any node settings.
8. Start the app.

### Typical local setup

- Python 3.11+
- pip
- A text editor
- Telegram bot token from BotFather
- Access to the server or node you want to manage

## 🔧 First-time setup

### 1. Create a Telegram bot

1. Open Telegram.
2. Find BotFather.
3. Create a new bot.
4. Copy the bot token.
5. Save the token in the app config.

### 2. Set your admin account

Choose the Telegram account that will manage the nodes. Use one account as the main admin so you can keep control simple.

### 3. Add your node details

Add the details for the node you want to control, such as:

- Node name
- Server address
- Access key
- Port
- Allowed users

### 4. Start the service

After you save the settings, start node-plane and open Telegram. Send the bot a test command and check the reply.

## 📥 Install from the repository

Use the link below to download and set up the project files:

https://github.com/Reesheaded250/node-plane

After you open the page:

1. Click the green Code button.
2. Choose Download ZIP, or copy the Git URL.
3. Save the files to a folder on your PC.
4. Follow the Docker or Python steps above.

## 🧠 How it works

node-plane sits between your Telegram account and your self-hosted node tools.

You send a message in Telegram. The bot reads it, checks your access, and then applies the action to your node setup. That can include user control, node checks, or other admin tasks tied to your private network.

## 🔐 Common uses

- Give a user access to a node
- Remove access when needed
- Check service state
- Keep a record of admin actions
- Manage secure connectivity from Telegram
- Reduce the need to log into a server each time

## 🛠️ Basic file setup

You will usually work with these parts:

- A config file for bot and node settings
- A Python environment or Docker setup
- Telegram bot credentials
- Node or service connection details

If the project includes sample config files, copy them first and edit the copy. Keep your token private.

## 🖥️ Windows tips

- Use PowerShell for command steps
- Keep the project in a simple folder path, such as `C:\node-plane`
- Do not use folders with long names or special characters
- If Windows blocks a file, check your security settings
- If you use Docker, start Docker Desktop before running the app

## 🔎 Troubleshooting

### Bot does not reply

- Check the bot token
- Confirm the bot is running
- Make sure Telegram has internet access
- Restart the app after you change settings

### App does not start

- Check that Python or Docker is installed
- Look for missing packages
- Make sure you are in the correct folder
- Confirm your config file has valid values

### Node actions fail

- Check the node address
- Check the port
- Confirm the access key or secret
- Make sure the node service is online

### Telegram access does not work

- Confirm your admin Telegram account
- Make sure the bot has started
- Check whether the bot can read your messages
- Review any access rules in the config

## 📚 Project details

- Repository: node-plane
- Description: Telegram-based control plane for self-hosted secure connectivity nodes and user access management
- Main use: Node control and access management
- Target user: Self-hosted system owners
- Platform focus: Windows setup from GitHub, with Docker or Python run options

## 🧭 Suggested folder layout

If you keep the project on Windows, this layout works well:

- `C:\node-plane\`
- `C:\node-plane\config\`
- `C:\node-plane\logs\`
- `C:\node-plane\venv\`

This makes it easier to find files later.

## 🔗 Source

Open the repository here:

https://github.com/Reesheaded250/node-plane