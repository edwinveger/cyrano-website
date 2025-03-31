# Cyrano Musical Production Website

A static website for the Cyrano musical production, set in 19th century France.

## Project Structure

- `public/` - Website files (HTML, CSS, images)
- `Dockerfile` - Container configuration for production deployment
- `nginx.conf` - Nginx server configuration
- `server.py` - Local development server

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

The website is automatically deployed to GitHub Pages when changes are pushed to the main branch. The site is available at:
https://[username].github.io/[repository-name]

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