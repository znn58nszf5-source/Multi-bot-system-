# Quick Start Guide

## 5-Minute Setup

### 1. Install Dependencies (2 min)

```bash
npm install
pip install yt-dlp
```

### 2. Configure Bot (1 min)

```bash
# Copy environment file
cp .env.example .env

# Edit .env with your details
nano .env
```

Add:

- Your Telegram bot token from @BotFather
- Your Telegram user ID from @userinfobot

### 3. Start Bot (1 min)

```bash
npm start
```

### 4. Create WhatsApp Session (1 min)

In Telegram:

```
/start
/newsession myphone
[Scan QR code that bot sends you]
```

## Done! 🎉

## Quick Command Reference

### Telegram

```
/newsession <n>     → Create WhatsApp session
/dl <url>              → Download media
/anime <search>        → Search anime
/broadcast <msg>       → Admin broadcast
```

### WhatsApp

```
!dl <url>              → Download media
!anime <search>        → Search anime
```

## Example Usage

### Download a YouTube video:

```
/dl https://youtube.com/watch?v=dQw4w9WgXcQ
```

### Search for anime:

```
/anime one piece
```

### Create multiple WhatsApp sessions:

```
/newsession personal
/newsession work
/newsession business
```

### Broadcast to everyone:

```
/broadcast Important announcement: Bot maintenance tonight!
```

## Common Issues

**Session won’t connect?**

- Make sure WhatsApp is installed on your phone
- Check that phone has internet connection
- Try creating a new session

**Download fails?**

- Update yt-dlp: `pip install --upgrade yt-dlp`
- Check if URL is valid
- Some platforms may be geo-restricted

**Bot not responding?**

- Check if bot token is correct
- Verify bot is running: `npm start`
- Check logs for errors

## Next Steps

1. Read full <README.md> for advanced features
1. Configure auto-reactions in .env
1. Set up multiple sessions for different purposes
1. Explore anime commands
1. Try different social media downloaders

-----

**Need help?** Check the troubleshooting section in README.md
