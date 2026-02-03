# CITY-11 Website

## Overview
A static website for CITY-11 displaying doctrines, staff list, and wanted list. The site features a dark theme with orange accents.

## Project Structure
- `index.html` - Main homepage with doctrines, staff list, and Discord embed
- `style.css` - Main stylesheet
- `images/` - Staff member images
- `wanted/` - Wanted list page
- `server.py` - Python HTTP server for serving static files

## Running the Project
The project uses a simple Python HTTP server:
```bash
python server.py
```
Server runs on port 5000.

## Deployment
This is a static website. Deploy using the static deployment type with the root directory (`.`) as the public directory.
