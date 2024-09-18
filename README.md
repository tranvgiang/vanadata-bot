# Vana Airdrop Bot

## Setup

### Prerequisites

- [Node.js](https://nodejs.org/) (version 14 or later)
- [npm](https://www.npmjs.com/) (comes with Node.js)
- [Git] (https://git-scm.com/downloads/)
### Installation

1. **Clone the repository:**

    ```bash
    git clone https://github.com/vinhben12/vana-bot.git
    ```

2. **Chuyển đến thư mục bot:**

    ```bash
    cd vana-bot
    ```

3. **Cài package dependencies:**

    ```bash
    npm install
    ```

### Configuration

1. **Tìm query_ID và đặt vapf file `data.txt` 

2. **Ví dụ:

    ```data.txt
    user=%7B%22id%22......
    ```

   - Tìm `QUERY_ID`,
     1. Mở [Web Telegram](https://web.telegram.org) trên trình duyệt.
     2. Mở bot [ ot](https://t.me/VanaDataHeroBot/VanaDataHero?startapp=5217425934).
     3. Mở DevTools (right-click on the page and select "Inspect" or press `F12`).
     4. Chọn "Application" tab, sau đó "Local Storage", and choose `https://telegram.blum.codes`.
     5. Find `QUERY_ID`, copy its value.

   - **Connection Issues?** Cài bypass để vào được game [Ignore X-Frame-Headers](https://chromewebstore.google.com/detail/ignore-x-frame-headers/gleekbfjekiniecknbkamfmkohkpodhe).

### Running the Bot

Chay bot gõ

```bash
node vana.js
```


