# Cyrano Musical Production Website

A static website for the Cyrano musical production, set in 19th century France.

## Features

- Responsive design that works on all devices
- Modern, elegant styling inspired by 19th century French aesthetics
- Easy navigation with sticky header
- Pages for cast, orchestra, and synopsis
- Optimized for performance

## Local Development

To run the website locally:

1. Make sure you have Python 3 installed
2. Run the development server:
   ```bash
   python server.py
   ```
3. The website will automatically open in your default browser at http://localhost:8000

## Deployment

### GitHub Pages

1. Create a new repository on GitHub
2. Push this code to the repository
3. Go to repository Settings > Pages
4. Select the main branch as the source
5. Your site will be available at `https://[username].github.io/[repository-name]`

### Docker Deployment

To deploy using Docker:

1. Build the image:
   ```bash
   docker build -t cyrano-website .
   ```

2. Run the container:
   ```bash
   docker run -p 80:80 cyrano-website
   ```

## Project Structure

- `index.html` - Main landing page
- `cast.html` - Cast information
- `orchestra.html` - Orchestra information
- `synopsis.html` - Show synopsis
- `styles.css` - Main stylesheet
- `server.py` - Local development server 