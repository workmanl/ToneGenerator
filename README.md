# Tone Generator

A sleek, web-based tone generator for precision listening, calibration, and sweep testing using the Web Audio API.

## Features

- **Multiple Waveforms**: Sine, square, sawtooth, and triangle
- **Waveform Visualization**: Live signal display
- **Volume Fader**: Vertical output control with max output cap
- **Custom Frequency**: Slider + numeric input with instant play/stop
- **Tone Pads**: Preset frequency banks across key ranges
- **Sweep Generator**: Start, end, and duration controls
- **Playback Safety**: Toggle/lock mode and auto-stop option
- **Settings Panel**: Max output, fade time, auto-stop, repeat sweep
- **Frequency Ranges**:
  - Bass Frequencies (20-100 Hz)
  - Mid Range (220-2500 Hz)
  - High Range (3500-10000 Hz)
  - Ultrasonic (15000-20000 Hz)
- **Touch-Friendly**: Optimized for mobile devices with pointer events
- **Responsive Design**: Works on desktop and mobile browsers

## How to Use

1. Open `index.html` in any modern web browser (or run a local server for full PWA behavior)
2. Select your waveform (sine is default)
3. Set volume with the fader
4. Tap a preset pad or use Custom Frequency + Play
5. Optional: use Sweep, Toggle Mode, or Settings for advanced control

## Technical Details

- Built with vanilla HTML5, CSS3, and JavaScript
- Uses the Web Audio API for audio generation
- No external dependencies or frameworks required
- Single HTML file for easy deployment
## Local Development

You can open the file directly, but a local server is recommended for service worker/PWA testing:

```sh
python3 -m http.server 8000
```

## Browser Compatibility

Works in any browser that supports the Web Audio API:

- Chrome 14+
- Firefox 25+
- Safari 6+
- Edge 12+

## Important Notes

⚠️ **Speaker Limitations**: Most mobile phone speakers cannot accurately reproduce very low bass frequencies or ultrasonic frequencies. Results may vary depending on your device.

🔊 **Hearing Protection**: Please use this tool responsibly and at safe volume levels to protect your hearing and equipment.

## Disclaimer

By using this frequency generator, you acknowledge that you are using it at your own risk. The creators and providers of this tool are not liable for any damage to speakers, hearing, or other equipment that may result from its use.

## License

This project is open source. Feel free to use, modify, and distribute as needed.
