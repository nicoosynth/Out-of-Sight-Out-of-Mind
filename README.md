Sonic tour of the Grimsel regions hydropower infrastructure using Mapbox GL JS

This project demonstrates how to use Mapbox GL JS to display a 3D model, audio markers, and GPX routes on an interactive map.

Features:

3D Model Rendering:   Visualize 3D models with Three.js within Mapbox.
Audio Integration:    Clickable map markers that play associated audio tracks.
Animated Camera Path: Camera follows a predefined path using GPX data.
Interactive Popups:   Information popups that appear upon marker interaction.

Requirements:

Mapbox GL JS
Three.js
Turf.js
GPX data for path visualization
Audio files (download from google drive: https://drive.google.com/drive/folders/1mQupUcNtlrA7gqVhBo1bGZlJIpF1ROgB?usp=sharing)

Getting Started:

1. Clone the Repository

git clone https://github.com/your-username/your-repo.git
Navigate to the Project Directory:

cd your-repo
Open index.html in your preferred browser.

How to Use:

1. Map Navigation

Zoom in/out and pan to explore the map.
Use the fullscreen button for an enhanced view.

2. Markers and Audio

Click on the markers to play corresponding audio.
Close the popups to stop the audio.

3. 3D Model

A 3D model is rendered on the map, with parts color-coded based on elevation (green for above ground, red for below ground).
Animated Camera Path:

The camera follows a path derived from the provided GPX data, offering a dynamic view of the map.
Configuration

Mapbox Access Token: Replace the access token in the script with your Mapbox access token.
3D Model Path: Update the GLTF model path in the script if necessary.
Audio Files: Ensure audio files are correctly linked in the HTML.

Dependencies

Mapbox GL JS:     For map rendering.
Three.js:         For 3D model rendering.
Turf.js:          For geospatial analysis and animations.


Customization

Modify the GPX data within the script to change the camera path.
Customize the marker coordinates and audio files to create an audio tour in your own city. 

