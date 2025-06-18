# Sowing Taker Bot

An automated farming bot designed to interact with the Taker Sowing Protocol. This bot helps automate daily sign-ins and farming activities to accumulate Taker Points, which may be valuable for future airdrops.

## Installation

### Prerequisites

- Node.js (v16 or higher)
- npm or yarn package manager

### Setup

1. Clone the repository:

```bash
git clone https://github.com/taikoyaki/Sowing-Taker-Protocol-Bot.git
cd Sowing-Taker-Protocol-Bot
```

2. Install dependencies:

```bash
npm install
```

3. Cp  `.env` file in the project root directory and add your private keys:

```bash
cp .env.example .env
```
```
PRIVATE_KEY_1=your_private_key_here
PRIVATE_KEY_2=another_private_key_here
# Add more as needed
```

4. (Optional) If you want to use proxies, create a `proxies.txt` file and add one proxy per line:

```
username:password@host:port
host:port:username:password
http://username:password@host:port
# Add more as needed
```

## Usage

Start the bot with:

```bash
npm start
```

### Controls

- **Q**: Quit the application
- **R**: Refresh authentication tokens
- **←**: Switch to previous wallet
- **→**: Switch to next wallet

Last updated: Wed Jun 18 01:42:39 UTC 2025
