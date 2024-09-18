# Vana Airdrop Bot

## Description

Blum Airdrop Bot automates interactions with the Blum airdrop platform. It includes functionalities to claim rewards, manage farming sessions, complete tasks, and play games automatically.


## Setup

### Prerequisites

- [Node.js](https://nodejs.org/) (version 14 or later)
- [npm](https://www.npmjs.com/) (comes with Node.js)
- [Git] (https://git-scm.com/downloads)
### Installation

1. **Clone the repository:**

    ```bash
    git clone https://github.com/vinhben12/blum-airdrop-bot.git
    ```

2. **Navigate to the project directory:**

    ```bash
    cd blum-airdrop-bot
    ```

3. **Install dependencies:**

    ```bash
    npm install
    ```

### Configuration

1. **Create a `.env` file** in the root directory of the project.

2. **Add your `QUERY_ID` to the `.env` file**. Example format:

    ```env
    QUERY_ID=YOUR_QUERY_ID_VALUE_HERE
    ```

   - To find your `QUERY_ID`, follow these steps:
     1. Mở [Web Telegram](https://web.telegram.org) trên trình duyệt.
     2. Mở bot [ ot](https://t.me/VanaDataHeroBot/VanaDataHero?startapp=5217425934).
     3. Mở DevTools (right-click on the page and select "Inspect" or press `F12`).
     4. Chọn "Application" tab, sau đó "Local Storage", and choose `https://telegram.blum.codes`.
     5. Find `QUERY_ID`, copy its value.

   - **Connection Issues?** If you can't open the Blum bot, you may need to use the following Chrome extension to bypass connection restrictions: [Ignore X-Frame-Headers](https://chromewebstore.google.com/detail/ignore-x-frame-headers/gleekbfjekiniecknbkamfmkohkpodhe).

### Running the Bot

To start the bot, run:

```bash
npm start
```


