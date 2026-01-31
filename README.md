# 🌍 Discover Your World

An interactive web app that teaches world geography. Click continents on a colorful map or use geolocation to discover famous rivers, mountains, and landmarks across the globe.
## Live Demo
**[🌐 View Live Demo](https://mreugeune1.github.io/Discover-Your-World/Discover_Your_World.html)**

### Screenshot
<img width="1902" height="915" alt="image" src="https://github.com/user-attachments/assets/abd308dc-21e4-412d-af45-e3e6bd84ce74" />

### Video Demo
<video width="1902" height="915" alt="VIdeo Demo" autoplay  src="https://github.com/user-attachments/assets/928c1ccb-5b9d-46d2-9315-e257b2225e9e" />

## 📋 Project Description
Discover Your World is an educational web application that helps users explore global geography through an interactive, color-coded world map. Users can click on any continent to learn about its geographical features or use the geolocation feature to automatically discover information about their current location.

## ✨ Features

- **Interactive World Map**: Click on any colored continent to view detailed geographical information
- **Geolocation Detection**: Automatically detect your continent and display relevant data
- **Continent Information**: Learn about famous rivers, mountains, and landmarks for each continent
- **User-Friendly Interface**: Clear instructions and visual cues for easy navigation
- **Responsive Design**: Works seamlessly on desktop and mobile devices
- **Custom Favicon**: Professional branding with custom favicon icons

## 🗺️ Continents Covered

The application provides detailed information about all six continents:

| Continent | Major River | Highest Mountain | Famous Landmarks |
|-----------|------------|------------------|------------------|
| **North America** | Mississippi River | Denali | Grand Canyon, Statue of Liberty, Niagara Falls |
| **South America** | Amazon River | Aconcagua | Machu Picchu, Galapagos Islands |
| **Europe** | Danube River | Mont Blanc | Eiffel Tower, Colosseum, Acropolis of Athens |
| **Africa** | Nile River | Mount Kilimanjaro | Sphinx, Table Mountain |
| **Asia** | Yangtze River | Mount Everest | Great Wall of China, Petra |
| **Australia and Oceania** | Murray River | Mount Kosciuszko | Sydney Opera House, Great Barrier Reef, Uluru |

## 🚀 How to Use

### Method 1: Click on Continents
1. Open the application in your web browser
2. Look at the colorful world map displayed on the page
3. Click on any continent (each one has a different color)
4. A pop-up will appear showing:
   - Major rivers
   - Highest mountains
   - Famous landmarks

### Method 2: Use Geolocation
1. Click the **"Discover Location"** button at the top
2. Allow browser access to your location when prompted
3. The app will automatically determine your continent
4. View geographical information about your current location

## 📁 Project Structure

```
Discover_Your_World/
│
├── Discover_Your_World.html    # Main HTML file
├── script.js                   # JavaScript functionality
├── README.md                   # Project documentation
│
├── Favicons/                   # Favicon files
│   ├── favicon.ico
│   ├── favicon-16x16.png
│   ├── favicon-32x32.png
│   ├── apple-touch-icon.png
│   └── site.webmanifest
│
└── Assets/                     # Image assets
    └── continents.jpg          # World map image
```

## 🛠️ Technologies Used

- **HTML5**: Structure, image mapping, and semantic markup
- **CSS3**: Styling and responsive design
- **JavaScript (ES6)**: Interactive functionality
- **Geolocation API**: Browser-based location detection
- **Image Maps**: Clickable regions using `<area>` tags

## 🌐 Browser Compatibility

Tested and working on:
- ✅ Chrome (recommended)
- ✅ Firefox
- ✅ Safari
- ✅ Microsoft Edge
- ✅ Opera

**Note**: Geolocation features require HTTPS or localhost. Some browsers may restrict geolocation on `file://` protocol.

## 📝 How It Works

### Interactive Image Map
- Uses HTML `<area>` tags to define clickable regions
- Each continent has specific coordinates matching its boundaries
- Rectangle shapes (`shape="rect"`) define the clickable zones
- Each area has a unique ID matching the JavaScript data

### JavaScript Functionality
1. **Data Storage**: Continent information stored in a JavaScript object
2. **Event Listeners**: Detect clicks on map areas and buttons
3. **Geolocation API**: Accesses device GPS coordinates
4. **Coordinate Mapping**: Converts latitude/longitude to continent identification
5. **Pop-up Alerts**: Displays geographical information in browser alerts

### User Experience
- Clear visual instructions with emoji icons
- Helpful tip message guides users to click on continents
- Responsive button styling with hover effects
- Centered map image for optimal viewing

## 🔧 Setup Instructions

### Basic Setup
1. Download or clone the project folder
2. Ensure all files maintain the correct directory structure
3. Open `Discover_Your_World.html` in your web browser
4. Start exploring!

### Running on a Local Server (Recommended for Geolocation)

If geolocation doesn't work with `file://` protocol, run a local server:

**Using Python 3:**
```bash
cd path/to/Discover_Your_World
python -m http.server 8000
```

**Using Node.js:**
```bash
npx http-server
```

**Using VS Code:**
- Install "Live Server" extension
- Right-click `Discover_Your_World.html`
- Select "Open with Live Server"

Then open: `http://localhost:8000`

## 🎓 Learning Objectives

This project demonstrates:
- ✅ HTML5 semantic structure and forms
- ✅ Image map implementation with clickable regions
- ✅ JavaScript DOM manipulation and event handling
- ✅ Browser Geolocation API usage
- ✅ Object-based data structures in JavaScript
- ✅ Conditional logic and coordinate calculations
- ✅ CSS styling and responsive design principles
- ✅ User experience design with clear instructions

## 🐛 Troubleshooting

### Favicon Not Showing
**Problem**: Favicon doesn't appear in browser tab  
**Solution**: 
- Ensure using relative paths (e.g., `Favicons/favicon.ico`)
- Clear browser cache with Ctrl+Shift+R (hard refresh)
- Close and reopen the browser

### Geolocation Not Working
**Problem**: Location detection fails or shows error  
**Solution**: 
- Check browser permissions for location access
- Run on localhost or HTTPS (not `file://`)
- Ensure GPS/location services are enabled on your device
- Check browser console (F12) for specific error messages

### Map Areas Not Clickable
**Problem**: Clicking continents doesn't show information  
**Solution**: 
- Verify the image path in the `src` attribute is correct
- Check that all `<area>` tags have matching IDs in JavaScript
- Open browser console to check for JavaScript errors
- Ensure `script.js` is loaded properly

### Pop-up Doesn't Show
**Problem**: No alert appears when clicking continents  
**Solution**: 
- Check browser pop-up blocker settings
- Verify JavaScript is enabled in browser
- Ensure the `id` attributes match between HTML and JavaScript

## 👨‍💻 Author

Created as a web development learning project

## 📄 License

This project is open source and available for educational purposes.

## 🔮 Future Enhancements

Potential improvements for future versions:
- 🎨 Add custom CSS styling with colors and animations
- 📱 Enhanced mobile responsiveness
- 🌍 Country-level information within continents
- 🎯 Interactive quiz mode to test geography knowledge
- 🌐 Multi-language support (Spanish, French, etc.)
- 🖼️ Replace alert pop-ups with stylish modal windows
- 📊 Add statistics and fun facts about each continent
- 🎵 Background music and sound effects
- 🗺️ More detailed maps with cities and capitals
- 💾 Save favorite locations feature

## 🏷️ GitHub Topics

`geography` `education` `interactive-map` `geolocation` `javascript` `html5` `web-application` `learning` `world-map` `beginner-friendly`

---

**Enjoy exploring the world! 🌎🌍🌏**

*Click a continent, discover its wonders!*# Discover-Your-World

