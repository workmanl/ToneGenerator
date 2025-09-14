# Tone Generator

A simple web-based tone generator that allows you to play pure tones at various frequencies using your browser's Web Audio API.

## Features

- **Multiple Waveforms**: Choose from sine, square, sawtooth, and triangle wave shapes
- **Volume Control**: Three preset volume levels (Low, Mid, High)
- **Frequency Ranges**:
  - Bass Frequencies (20-100 Hz)
  - Mid Range (220-2500 Hz)
  - High Range (3500-10000 Hz)
  - Ultrasonic (15000-20000 Hz)
- **Touch-Friendly**: Optimized for mobile devices with pointer events
- **Responsive Design**: Works on desktop and mobile browsers

## How to Use

1. Open `index.html` in any modern web browser
2. Select your desired waveform (sine wave is selected by default)
3. Choose a volume level
4. Tap or click on any frequency button to start playing the tone
5. Release the button to stop the tone

## Technical Details

- Built with vanilla HTML5, CSS3, and JavaScript
- Uses the Web Audio API for audio generation
- No external dependencies or frameworks required
- Single HTML file for easy deployment

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
