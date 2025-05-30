# $LOUD Shouting Match 🎤

A viral multiplayer voice-enabled shouting game where players compete by shouting "LOUD" into their microphones. Features real-time voice transmission, live leaderboards, and Twitter integration.

## 🎮 Game Features

- **Real-time Voice Transmission**: Players hear each other's actual voices via WebRTC
- **Speech Recognition**: Detects when players shout "LOUD" and awards points
- **Live Multiplayer**: Up to 10 players per round with queue system
- **Live Leaderboard**: Real-time scoring and rankings
- **Twitter Integration**: Winners can auto-tweet their victory
- **30-second Rounds**: Fast-paced competitive gameplay
- **Chat System**: In-game messaging between players

## 🚀 Technologies Used

- **Frontend**: HTML5, TailwindCSS, Vanilla JavaScript
- **Real-time Sync**: MultiSynq for synchronized game state
- **Voice Transmission**: WebRTC peer-to-peer audio
- **Speech Recognition**: Web Speech API
- **Deployment**: Vercel (static hosting)

## 🎯 How to Play

1. Enter your Twitter handle
2. Click "SHOUT LOUD!" to join
3. When the round starts, shout "LOUD" into your microphone
4. Earn points for each successful shout
5. Compete with up to 9 other players
6. Winner gets bragging rights and can tweet their victory!

## 🛠 Local Development

1. Clone the repository:
```bash
git clone https://github.com/hochangjun/shoutloud.git
cd shoutloud
```

2. Open `loud-shouting-match.html` in your browser
3. Allow microphone permissions when prompted
4. Test with multiple browser tabs/windows

## 🌐 Deployment

### Vercel Setup
1. Connect your GitHub repository to Vercel
2. Set the build command to: `echo "Static site - no build needed"`
3. Set the output directory to: `./`
4. Deploy! The game is a single HTML file, so no build process needed.

### Environment
- No environment variables required
- Uses MultiSynq cloud service for real-time sync
- WebRTC handles peer-to-peer connections

## 🔧 Technical Details

- **Single File**: Entire game contained in one HTML file for easy deployment
- **WebRTC Audio**: Direct peer-to-peer voice transmission
- **Speech Recognition**: Browser-based speech detection
- **MultiSynq Integration**: Synchronized game state across all players
- **Responsive Design**: Works on desktop and mobile browsers

## 🎨 Brand Colors

- **Primary Background**: Cyan gradient (`#06ffa5` to `#0099ff`)
- **Text**: Black for readability
- **Accents**: Blue (`#1e40af`, `#2563eb`)
- **UI Panels**: Semi-transparent white with blue borders

## 🔊 Browser Compatibility

- Chrome/Edge: Full support (recommended)
- Firefox: Full support
- Safari: Partial support (speech recognition limited)
- Mobile: Basic support (WebRTC may vary)

## 📱 Social Media

Built for @stayloudio and @multisynq - a viral game for crypto/audio communities!

## 🏆 Game Strategy

- Shout clearly and loudly for best recognition
- Time your shouts for maximum points
- Use the manual speech restart if detection fails
- Monitor the connection status for optimal performance

## 🐛 Troubleshooting

- **No voice transmission**: Check microphone permissions and connection status
- **Speech not detected**: Use the "Restart Speech" button
- **Connection issues**: Refresh and rejoin the game

---

**Made with ❤️ for the $LOUD community** 