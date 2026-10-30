# حکم پادشاهان | KINGS OF HOKM

A Persian RTL online Hokm prototype built with Node.js, Express and Socket.IO.

## Run locally
1. Install Node.js 18 or newer.
2. Run `npm install`
3. Run `npm start`
4. Open `http://localhost:3000`

## Deploy on Render
Create a **Web Service** from this GitHub repository:
- Runtime: Node
- Build command: `npm install`
- Start command: `npm start`
- Region: Frankfurt (or closest to your players)
- Free plan is fine for a first test.

## Current MVP scope
- Private four-seat rooms with invite code
- Real-time lobby, readiness, chat and card plays
- 52-card deck, trump selection, follow-suit validation and trick winner calculation

## Important limitations
This is an MVP, not a finished competitive game. It does not yet implement a complete hakim-selection/dealing flow, reconnect persistence, anti-cheat/rate limiting, persistent accounts, tournament scoring, or a comprehensive automated test suite. Test with friends before relying on it. Room state is in memory and resets when the server restarts.
