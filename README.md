# 💕 Romantic Proposal Website

A beautiful, interactive proposal website built with vanilla HTML, CSS, and JavaScript. Perfect for GitHub Pages hosting!

## Features

✨ **Two-Page Experience**
- Page 1: Interactive proposal screen with a playful NO button
- Page 2: Celebration screen with photo and heartfelt message

🎨 **Design Elements**
- Romantic pastel theme (pink, red, blush)
- Floating hearts animation
- Smooth page transitions
- Confetti celebration effect
- Fully responsive (mobile & desktop)

🎵 **Audio Support**
- Optional romantic background music
- Music toggle button (respects browser autoplay policies)

📱 **Mobile Optimized**
- Touch-friendly buttons
- Responsive layout
- Works on all devices

## Project Structure

```
.
├── index.html              # Main file (everything is here!)
├── assets/
│   ├── photo.jpg          # Your personal photo (replace this)
│   └── music.mp3          # Optional background music (replace this)
├── .gitignore             # Ignore personal files
└── README.md              # This file
```

## Setup Instructions

### 1. **Local Testing**
- Open `index.html` directly in your browser
- Or use a local server: `python -m http.server 8000`

### 2. **Add Your Personal Photo**
- Replace `assets/photo.jpg` with your photo
- Supported formats: JPG, PNG, WebP
- Photo will auto-hide if not found (graceful fallback)

### 3. **Add Background Music (Optional)**
- Replace `assets/music.mp3` with your romantic audio
- Supported formats: MP3, WAV, OGG
- Click the 🔊 button to toggle music

### 4. **Customize Text**
Edit in `index.html`:
- Line 312: Proposal text
- Line 318-319: YES/NO button text
- Messages near NO button (line ~380)
- Page 2 message (line 331-334)
- Footer text (line 338)

## Deploy on GitHub Pages

### Step 1: Create Repository
```bash
git init
git add .
git commit -m "Initial commit: romantic proposal website"
```

### Step 2: Create GitHub Repository
1. Go to [github.com/new](https://github.com/new)
2. Create a repository named `username.github.io` OR any name
3. Copy the repository URL

### Step 3: Push to GitHub
```bash
git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO.git
git branch -M main
git push -u origin main
```

### Step 4: Enable GitHub Pages
1. Go to repository Settings
2. Scroll to "Pages" section
3. Set source to "main" branch
4. Your site will be live at `https://username.github.io` or `https://username.github.io/repo-name`

## Customization Guide

### Change Playful Messages
In `index.html`, find the `CONFIG` object and edit:
```javascript
playfulMessages: [
    "Your custom message 😊",
    "Another message 🎉"
]
```

### Change Button Movement Distance
```javascript
moveDistance: 150  // Increase for more distance
```

### Change Colors
Edit the CSS gradient colors (search for `#ff6b9d` or `#c2185b`)

### Change Confetti Type
Search for "emojis =" in JavaScript to change confetti symbols

## Browser Compatibility

✅ Chrome/Edge/Firefox/Safari (latest versions)
✅ Mobile browsers (iOS Safari, Chrome Mobile)
✅ Works offline (except music might need to be pre-cached)

## Notes

- **Music Autoplay**: Most browsers require user interaction before audio plays. The music won't auto-start; click the 🔊 button to play.
- **Relative Paths**: All asset paths use relative URLs (`assets/photo.jpg`) - works perfectly on GitHub Pages
- **No Backend Needed**: Fully static site - no server required
- **Fully Commented Code**: Every feature is documented in the HTML comments

## Troubleshooting

| Issue | Solution |
|-------|----------|
| Photo not showing | Ensure `assets/photo.jpg` exists and is accessible |
| Music not playing | Click the 🔊 button; check browser autoplay settings |
| Layout broken on mobile | Check viewport meta tag; zoom out your browser |
| Buttons not responsive | Ensure JavaScript is enabled |

## Made with 💗 by Devyansh

Enjoy your proposal! Feel free to customize everything to make it personal.

---

**Tips for the best experience:**
1. Use a high-quality photo with good lighting
2. Choose romantic music (see suggestions below)
3. Test on multiple devices before sharing
4. Open it on the day of the proposal! 💕

---

## Music Suggestions (to be added based on your photo)

Share your photo, and I'll suggest the perfect romantic music! Some popular choices:
- "Perfect" by Ed Sheeran
- "Thinking Out Loud" by Ed Sheeran
- "All of Me" by John Legend
- "Marry You" by Bruno Mars
- "I Will Follow You Into The Dark" by Death Cab for Cutie
