# Irys Testnet Terminal
![Irys Testnet Terminal Screenshot](https://i.ibb.co/TMrys7Zb/IMG-20250918-052532.jpg)
![Version](https://img.shields.io/badge/version-1.0.0-blue.svg)![License](https://img.shields.io/badge/license-MIT-green.svg)![Platform](https://img.shields.io/badge/platform-node.js-lightgrey.svg)  

**Irys Testnet Terminal** is a simple interactive command-line interface (CLI) for playing mini games on the **Irys Testnet**.  
With a clean interface, it lets you connect your wallet and access several game modes directly from the terminal.  

---

## Available Games  

* **SpriteGame**  
* **Snake Game**  
* **Missile Command**  
* **HEX Shooter**  

---

## Prerequisites  

Before starting, make sure you have:  
* [Node.js](https://nodejs.org/) (v18.x or newer)  

---

## Installation & Setup  

Follow these steps to get the Irys Testnet Terminal up and running.  

**1. Clone the Repository**  

```bash
git clone https://github.com/b3l1ya/irys-testnet.git
cd irys-testnet
```

**2. Install Dependencies**

Run the following command to install all the necessary packages.
```bash
npm install
```

**3. Change Environment File (.env)**

Rename file `.env.example` to `.env`in the project's root directory. This file will store your wallet's private key.
```
cp .env.example .env
```

Edit the .env file to add your private key:
```
nano .env
```
Add your private key in the following format:
```
PRIVATE_KEY=your_private_key_here
```
Example:
```
PRIVATE_KEY=0x1234567890abcdef1234567890abcdef1234567890abcdef1234567890abcdef
```

## Usage
To run the terminal, use the following command from the root directory:
```
node index.js
```

Once started, you will see the Irys Testnet header, your wallet address, and balance.
Then you can select from the game menu:
```
1. Play SpriteGame
2. Play Snake Game
3. Play Missile Command
4. Play HEX Shooter
5. Exit
```
Choose any number to start playing.

---

## ⚠️ Security Warning
 * This tool is designed for use in a Testnet environment.
 * Always use a dedicated burner wallet funded by a testnet faucet for all development and testing activities. The developers are not responsible for any loss of assets due to misuse of this tool.
