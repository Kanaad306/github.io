# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a simple static personal portfolio website consisting of two files:
- `index.html` - Single-page personal website with biographical content and links
- `style.css` - Responsive CSS styling with mobile-first design

## Development

### Local Development

Open `index.html` directly in a browser or use a simple HTTP server:

```bash
# Python 3
python3 -m http.server 8000

# Python 2
python -m SimpleHTTPServer 8000

# Node.js (if http-server is installed)
npx http-server .
```

Then navigate to `http://localhost:8000`

### Content Customization

The HTML file contains placeholder text that needs to be replaced:
- `[Your Name]` - Replace with actual name
- `[your interests and hobbies]`, `[hobby 1]`, `[hobby 2]` - Personal interests
- `[your role]`, `[Your Company]`, `[technology]`, `[your mission statement]` - Professional information
- `[previous role]`, `[previous company]` - Career history
- Email address and links to be updated with real information

## Architecture

**Simple Static Site**: No build process, no dependencies, no framework. Just vanilla HTML and CSS that can be served from any static hosting provider (GitHub Pages, Netlify, Vercel, etc.).

**Responsive Design**: CSS uses mobile-first approach with breakpoints at 768px and 480px for tablet and mobile devices.

**Styling Philosophy**: Clean, minimal design using system fonts for fast loading. Container max-width of 700px for optimal reading experience.
