# Soskoify's spotify-ad-skipper
modded spotify ad skipper from https://github.com/sihooney/spotify-ad-skipper
If they would like me to take this project down I will as I used most of their code to make this possible, make sure to give their repo a star for making this possible!

## Soskoify changes

- **Hidden-screen skipping**: after an ad is detected, Spotify is force-closed and relaunched on an
  off-screen virtual display instead of the main screen, and the Home-press step is skipped, so
  nothing pops up over what you are doing. Toggle it in the app ("Skip ads on a hidden screen").
  If the hidden display can't be created, it falls back to the original behavior automatically.
- Neater ui
- The "How It Works" and "Limitations" sections below describe the original (toggle off) behavior.

## Features

- **Automatic Ad Detection**: Monitors Spotify notifications for "Advertisement"
- **Queue Preservation**: Emulates manual close to preserve Spotify's queue state
- **Reliable Relaunch**: Uses Shizuku to bypass Android 15 background launch restrictions
- **Auto-Play**: Sends play intent after relaunch to resume playback
- **Battery Efficient**: Passive notification listener with zero CPU usage when idle
- **Privacy Focused**: No data collection, storage, or transmission
- **Samsung Optimized**: Tested on Samsung One UI 7.0 (and Samsung One UI 8.5 by soskoify)
