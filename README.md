# Modern Portfolio Website

This is a responsive portfolio website built using HTML and Sass (SCSS). 
It was originally created as part of a learning project based on a course by Brad Traversy.

## Features
- Fully responsive design
- Written in HTML5 and SCSS
- Custom CSS Grid and Flexbox layouts
- Simple menu overlay animation

## Recent Updates
- **Security Fixes**: Replaced the deprecated `node-sass` library with modern Dart `sass`.
- Updated color functions (`darken()`, `lighten()`, etc.) to conform to the new Dart Sass module system.
- Updated `gh-pages` dependency to resolve security vulnerabilities.

## How to run locally
1. Clone the repository
2. Install dependencies:
   ```bash
   npm install
   ```
3. Compile Sass to CSS:
   ```bash
   npm run sass
   ```
4. Serve the `dist` folder:
   ```bash
   npx serve dist
   ```

## Technologies Used
- HTML5
- SCSS (Dart Sass)
- JavaScript (minimal interaction)

## Deployment
You can deploy this project to GitHub Pages using the built-in deploy script:
```bash
npm run deploy
```
