# Interactive Navigation Menu

A modern, responsive navigation menu with scroll-based effects and hover interactions. This project demonstrates a fixed navigation bar that changes appearance when scrolling and provides smooth user interactions.

## Features

- **Fixed Position**: Navigation bar stays visible at the top while scrolling
- **Scroll Effect**: Background changes from transparent to dark blue when scrolled
- **Hover Effects**: 
  - Color change to blue (#3498db)
  - Subtle background highlight
  - Animated underline effect
  - Slight upward movement
- **Smooth Scrolling**: Click navigation links to smoothly scroll to sections
- **Active State**: Current section is highlighted in the navigation
- **Responsive Design**: Works seamlessly on mobile devices
- **Modern Styling**: Clean, professional design with gradient backgrounds

## Files

- `index.html` - HTML structure with navigation and sections
- `styles.css` - CSS styling with animations and responsive design
- `script.js` - JavaScript for scroll detection and interactivity
- `server.js` - Node.js server for local development

## Setup

1. Clone the repository:
```bash
git clone https://github.com/Vatsalgoyal7/navigation-menu.git
cd navigation-menu
```

2. Start the local server:
```bash
node server.js
```

3. Open your browser and navigate to:
```
http://localhost:8000
```

## Usage

- **Scroll the page** to see the navigation background change from transparent to dark blue
- **Hover over menu items** to see the interactive hover effects
- **Click menu items** to smoothly scroll to different sections
- **Resize the browser** to test responsive behavior on different screen sizes

## Technologies Used

- HTML5
- CSS3 (Flexbox, transitions, animations)
- Vanilla JavaScript
- Node.js (for local server)

## Customization

You can easily customize the navigation menu by modifying:

- **Colors**: Change color values in `styles.css`
- **Scroll threshold**: Modify the scroll value in `script.js` (currently set to 50px)
- **Animation speed**: Adjust transition timing in CSS
- **Menu items**: Add or remove links in `index.html`

## Browser Support

Works in all modern browsers that support:
- CSS Flexbox
- CSS Transitions
- ES6 JavaScript

## License

This project is open source and available for educational purposes.
