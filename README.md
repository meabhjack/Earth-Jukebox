# Earth Jukebox: by Emergency Exit 

**NASA Space Apps Challenge 2026**

## About the Project

Earth Jukebox is an interactive, accessible Earth science experience that transforms NASA Earth Information Center visualizations into sound, speech, and tactile exploration.

Our goal is to make Earth science more accessible to blind and low-vision individuals, STEM students, and the general public.

## Features

- Interactive Earth science heat maps
- Real-time data-driven musical sonification
- Spoken scientific measurements and explanations
- Keyboard and screen-reader accessibility
- Raspberry Pi Pico hardware integration
- Future tactile globe and thermal-feedback exhibit

## Technologies

- HTML, CSS, JavaScript
- Tone.js and Web Audio
- Python for scientific data processing
- Raspberry Pi Pico and MicroPython
- NASA Scientific Visualization Studio datasets

## Getting Started

1. Download or clone this repository.
2. Open the project in Visual Studio Code.
3. Start a local server with `python -m http.server 8000`.
4. Open `http://localhost:8000` in Chrome.
5. Click Enable Audio and explore using the arrow keys.

The current starter uses synthetic demonstration data; scientifically validated NASA measurements are being integrated.

## Scientific Sources

Our initial target is NASA's [Nighttime Lights visualization (SVS 5313)](https://svs.gsfc.nasa.gov/5313/).

## Future Vision

We envision a museum installation featuring a 3D-printed tactile globe. Visitors could feel geographic relationships, hear patterns in Earth science data, and experience safely controlled thermal signals representing relative brightness.

## Project Status

In active hackathon development. Features under development or not yet tested are not considered complete.

## License

MIT License for our original project code.
