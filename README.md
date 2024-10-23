# Image Analyzer

Desktop application for analyzing image files and their properties.

## Features
- Analysis of image properties (dimensions, resolution, color depth, etc.)
- Support for JPG, JPEG, PNG, GIF, BMP, TIFF, PCX
- Image preview
- Three themes (Hacker, Dark, Light)

## Requirements
- Python 3.x
- PyQt6
- Pillow
- piexif

## Installation
```bash
pip install PyQt6 Pillow piexif
```

## Usage
1. Run the application:
   - Download "main.exe" and run

2. Use buttons to:
   - "Select Files" - analyze specific images
   - "Select Folder" - analyze all images in folder
   - Use theme selector to change appearance

3. Results show:
   - Image dimensions
   - Resolution
   - Color depth
   - File format
   - File size
   - Creation/modification times
   - MD5 hash
