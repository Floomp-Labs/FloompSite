Floomp Labs Splash Page
A cyberpunk-inspired, retro-futuristic splash page for the Floomp Labs organization featuring immersive animations, a boot sequence terminal, and a spinning 3D cube logo.
Show Image
Features

CHECK IT OUT: https://floompsite.netlify.app/

Interactive terminal boot sequence with typewriter effect
Animated portal entry effect with lightspeed transition
3D spinning cube with glowing neon effects
Cyberpunk-inspired design with scanlines and static overlays
Floating geometric shapes background animation
Responsive design that works on various screen sizes
GitHub link with hover animation

Getting Started
Simply clone the repository and open index.html in your browser. No build steps or dependencies required.
bashCopygit clone https://github.com/floomp-labs/FloompSite.git
cd splash-page
open index.html
Technical Details
The splash page is built using:

HTML5
CSS3 (with animations, 3D transforms, and custom effects)
Vanilla JavaScript

The page consists of two main views:

The boot sequence / terminal screen
The main splash page with 3D cube

All effects are achieved through pure CSS and JavaScript without any external dependencies or libraries.
Customization
Changing Boot Messages
You can modify the boot sequence messages by editing the bootMessages array in the JavaScript section:
javascriptCopyconst bootMessages = [
    "FLOOMP LABS SYSTEM INITIALIZING...",
    "CHECKING SYSTEM INTEGRITY... [OK]",
    // Add or modify messages here
];
Changing Colors
The main color scheme uses cyan (#00ccff) and green (#0f0) for a cyberpunk feel. You can modify these colors in the CSS section to match your branding.
Adding/Removing Effects
Various effects like scanlines, static overlay, and floating shapes can be removed or modified by editing their respective CSS classes.
Browser Compatibility
This splash page works best in modern browsers that support:

CSS 3D transforms
CSS animations
Modern JavaScript (ES6+)

For optimal visual experience, use Chrome, Firefox, Safari, or Edge.
License
MIT
Contact
For questions or contributions, please open an issue on the GitHub repository or contact us through our GitHub organization page.
