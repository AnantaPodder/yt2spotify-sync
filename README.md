# yt2spotify-sync

Automatically sync your liked songs on YouTube or YouTube Music to your Spotify account.

## ✨ Features

- 🔗 Sync Liked Songs from YouTube/YouTube Music
- 🔐 OAuth Authentication for Google & Spotify
- 🎯 Custom Spotify Playlist Selection
- ⏳ Sync Interval Control (every X mins/hours)
- 📅 View Sync History and Logs
- ❌ Duplicate Song Prevention
- 🔍 Manual Sync Option via Dashboard or CLI
- 📬 Optional Notifications via Email or Telegram
- 📊 (Optional) Dashboard for status and logs

## 🛠 Tech Stack

- **Backend**: Node.js + Express/NestJS
- **Auth**: OAuth 2.0 with `passport.js`
- **Database**: PostgreSQL or MongoDB
- **Scheduler**: `node-cron` or `agenda`
- **APIs**: YouTube Data API v3, Spotify Web API
- **Deployment**: Docker + Railway/Fly.io/Vercel

## 🚧 Roadmap

- [ ] OAuth setup for Google & Spotify
- [ ] Sync logic for liked songs → Spotify search → Add to playlist
- [ ] Token refresh + background sync
- [ ] Optional front-end dashboard

## 📜 License

MIT
