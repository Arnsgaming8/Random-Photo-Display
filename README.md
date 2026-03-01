# Random Photo Display

A simple website that displays a random photo from the web each time you refresh the page. Photos are displayed in a square on a black background.

## Features

- Displays a random photo on each page refresh
- Responsive square container that adapts to screen size
- Multiple photo sources for variety
- Smooth fade-in transitions
- Click or press 'R' to load a new photo without refreshing
- Optimized for GitHub Pages deployment

## How It Works

The website uses multiple free photo APIs to fetch random images:

1. **Lorem Picsum** - Random placeholder images
2. **Unsplash Source** - Random beautiful photos from Unsplash
3. **PlaceIMG** - Random images in various categories

The script randomly selects one of these APIs on each load to provide variety.

## Deployment to GitHub Pages

1. Push all files to your GitHub repository
2. Go to repository Settings
3. Scroll down to "GitHub Pages" section
4. Under "Source", select "Deploy from a branch"
5. Choose the main branch and root folder
6. Click "Save"
7. Your site will be available at `https://yourusername.github.io/repository-name`

## Local Development

Simply open `index.html` in your web browser. No server required for basic functionality.

## File Structure

```
├── index.html      # Main HTML structure
├── styles.css      # Styling for black background and photo display
├── script.js       # JavaScript for fetching random photos
└── README.md       # This file
```

## Customization

- Change photo dimensions by modifying the `800/800` parameters in `script.js`
- Add more photo APIs by extending the `photoApis` array
- Modify colors and styles in `styles.css`
