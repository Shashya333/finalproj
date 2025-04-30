# finalproj
#spotify clone under development
# current state of the project
A responsive web-based Spotify clone that allows users to play music, browse playlists, and control playback. Built with HTML, CSS, and JavaScript.

## Features

- 🎵 Play/pause, next/previous track controls
- 🔊 Volume control with mute option
- 📱 Responsive design for mobile and desktop
- 📁 Browse different music playlists and moods
- ⏳ Real-time progress bar with seek functionality
- 🎨 Dark theme matching Spotify's aesthetics

## Technologies Used

- HTML5
- CSS3
- JavaScript (ES6+)
- SVG Icons
- JSON for playlist metadata

## Project Structure

```
spotify-clone/
│
├── css/
│   ├── style.css      # Main styles
│   └── utility.css    # Utility classes
│
├── img/               # SVG icons and images
│
├── js/
│   └── script.js      # Main JavaScript logic
│
└── songs/            # Music folders and metadata
    ├── Angry_(mood)/
    ├── Bright_(mood)/
    ├── Chill_(mood)/
    └── ...
```

## Setup & run guide 

1. Clone the repository
2. Place your MP3 files in the respective mood/artist folders under `songs/`
3. Update the `info.json` files in each folder with appropriate metadata
4. Open `index.html` in a web browser

## Key Features Implementation

- Dynamic playlist loading using Fetch API
- Real-time audio controls and time updates
- Responsive sidebar with hamburger menu
- Custom audio seekbar and volume controls
- Playlist categorization by moods and artists

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Credits

- Icons from SVG repository
- Font: Roboto from Google Fonts

## License

This project is for educational purposes only. All rights belong to their respective owners.
