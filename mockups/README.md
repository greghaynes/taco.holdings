# Alternative Website Mockups for Taco.holdings

This directory contains three simple alternative design mockups for the taco.holdings website. Each mockup is a standalone HTML file that can be opened directly in a browser.

## Mockups

### Mockup 1: Card-Style Layout
**File:** `mockup-1-card-style.html`

A modern centered card design with:
- Gradient background (purple/blue)
- White card container with rounded corners
- Clean typography and spacing
- Centered content with clear hierarchy
- Hover effects on links

**Design Approach:** Friendly and approachable, focuses attention on the content within the card.

### Mockup 2: Split-Screen Layout
**File:** `mockup-2-split-screen.html`

A contemporary two-column split design with:
- Dark left panel with branding and navigation
- Light right panel with content
- Clear visual separation
- Responsive design that stacks on mobile
- Card-based project listings

**Design Approach:** Professional and organized, provides persistent navigation while browsing content.

### Mockup 3: Terminal-Style Layout
**File:** `mockup-3-terminal.html`

A developer-focused terminal interface with:
- Dark background with green terminal text
- Terminal window aesthetics
- Command-line style content presentation
- Blinking cursor animation
- Monospace font throughout

**Design Approach:** Playful and technical, appeals to developer audience with familiar terminal aesthetics.

## How to View

### Option 1: Open Directly in Browser
Simply open any of the HTML files in your web browser:
```bash
# On macOS
open mockup-1-card-style.html

# On Linux
xdg-open mockup-1-card-style.html

# On Windows
start mockup-1-card-style.html
```

### Option 2: Use a Simple Web Server
For the best experience, serve the files with a local web server:

```bash
# Using Python 3
python3 -m http.server 8000

# Using Python 2
python -m SimpleHTTPServer 8000

# Using Node.js (if you have http-server installed)
npx http-server
```

Then open `http://localhost:8000/mockup-1-card-style.html` (or the appropriate port) in your browser.

## Comparison with Current Site

The current site uses the Maverick theme with:
- Minimalist design
- Cream background (#fffdfa)
- Bricolage Grotesque font
- Simple horizontal navigation
- Maximum width of 70 characters

These mockups explore alternative approaches while maintaining simplicity:
1. **Card-Style**: Adds visual interest with gradients and card shadows
2. **Split-Screen**: Provides better content organization with persistent navigation
3. **Terminal-Style**: Creates a unique, memorable developer-centric experience

## Next Steps

To implement any of these designs in the Hugo site:
1. The styles could be adapted to replace the current theme's SCSS
2. The HTML structure could be integrated into Hugo templates
3. Colors, fonts, and spacing can be adjusted to match branding preferences
