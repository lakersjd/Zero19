# ZeroX

**ZeroX** is a browser-based anonymous chat platform that lets users connect globally via text and video, inspired by Omegle.

## Features
- 🧭 Onboarding screen for first-time visitors
- 🎨 Light/Dark theme switcher
- 💬 Real-time text chat
- 📹 WebRTC-based video chat
- 🗂 User profile settings (stored locally)
- ⚡ Matchmaking system with Socket.IO

## Getting Started

### 1. Install dependencies

```bash
npm install
```

### 2. Run the server

```bash
npm start
```

Then visit: [http://localhost:3000/onboarding.html](http://localhost:3000/onboarding.html)

## Project Structure

```
/public          # Static HTML/CSS/JS pages
/server          # Matchmaking backend with Socket.IO
firebase/        # (Not used, optional)
```

## Deployment

To deploy on Render:
1. Push this repo to GitHub
2. Go to [https://render.com](https://render.com)
3. Create a new Web Service from your repo
4. Set build command to `npm install` and start command to `npm start`

## License
MIT
