<div align="center">
    <a href="https://t.me/z_smdbot">
        <kbd>
            <img width="300" src="https://github.com/user-attachments/assets/40c81490-ba9b-445f-9322-997250634a22" alt="ZPOTIFY-FA Logo">
        </kbd>
    </a>

### ***𝒵𝒫𝒪𝒯𝐼𝐹𝒴-𝐹𝒜***

A powerful Telegram bot for downloading music and videos from Spotify and YouTube directly to your device.
</div>

---

## Features

- 🎵 **Spotify Music Downloads**
- 🔎 **Keyword-based Search on Spotify**
- 🎶 **Multiple Audio Formats and Quality Options**
- 🛠️ **SpotDL and YouTubeDL Integration**
- 📢 **Broadcast Messages to Users**
- 📃 **Subscription Management**
- 🎤 **Voice Recognition for Song Search**
- 📸 **Tweet Screenshot Capture**
- 📹 **Twitter Media Downloads**
- 🎥 **Instagram Media Downloads**
- 🔄 **YouTube Media Downloads**

---

## 🔧 Installation

### Step 1: Clone the Repository

```bash
sudo apt install git ffmpeg python3 python3-pip -y
git clone https://github.com/zasasamar2129/zpotify-fa.git
```

### Step 2: Install Dependencies

Navigate to the project directory and install the required Python packages:

```bash
cd zpotify-fa
pip3 install -r requirements.txt
```

### Step 3: Configure Environment Variables

Create a `config.env` file in the root directory and add the following:

```env
SPOTIFY_CLIENT_ID=your_spotify_client_id
SPOTIFY_CLIENT_SECRET=your_spotify_client_secret
BOT_TOKEN=your_telegram_bot_token
API_ID=your_telegram_api_id
API_HASH=your_telegram_api_hash
GENIUS_ACCESS_TOKEN=your_genius_access_token
```

### Step 4: Run the Bot

```bash
python3 main.py
```

---

### 🚀 Docker Deployment

```bash
docker build -t musicfa .
docker run musicfa
```

---

## 📊 Usage

1. Start the bot with `/start`.
2. Send a Spotify link or use `/search <query>` to find songs.
3. Use `/settings` to customize audio quality and format.
4. Access admin features via `/admin` (authorized users only).

---

## 🔧 Commands

### User Commands

- `/start`: Initialize the bot.
- `/search <query>`: Find songs on Spotify.
- `/settings`: Adjust settings like format and quality.
- `/core`: Directly change the downloading core.
- `/quality`: Quickly change audio quality.
- `/subscribe`: Subscribe to updates.
- `/unsubscribe`: Opt-out of updates.
- `/help`: Display usage instructions.
- `/ping`: Check bot response time.
- `/stats`: View bot usage statistics.

### Admin Commands

- `/broadcast <message>`: Send a message to all subscribers.
  - Example: `/broadcast Hello, users!`
  - Example: `/broadcast_to_all Update available!`
- `/stats`: Retrieve bot usage stats.

---

## 🔗 Dependencies

- Python 3.10+
- Telethon
- Spotipy
- Yt-dlp
- SpotDL
- Shazamio
- Pillow
- Dotenv
- AioSQLite
- LyricsGenius
- FastTelethonHelper

---

## 🎨 Contributing

Contributions are welcome! Feel free to submit pull requests or open issues for bugs and enhancements.

---

## 🛡️ License

This project is licensed under the MIT License. See the `LICENSE` file for details.

---

## 📢 Contact

For questions or feedback:
- Telegram: [@Itachi2129](https://t.me/Itachi2129)
- Email: zasasamar2129@gmail.com

---

## ✨ Acknowledgments

- Spotify API for metadata access
- Telegram API for bot functionality
- Shazam API for voice recognition
- YouTubeDL for downloading media

