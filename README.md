# Advanced Text-to-Speech Generator

A modern, feature-rich web application that converts text to speech with support for multiple languages, voices, and audio controls. Built with vanilla JavaScript and the Web Speech API.

![Text to Speech Generator](https://raw.githubusercontent.com/sudasun007/TextToSpeech/main/screenshot.png)

## Features

- 🌐 Multi-language support with various voice options
- 🎚️ Adjustable speech parameters:
  - Speed control
  - Pitch modification
  - Volume adjustment
- 🎙️ Audio recording capability
- ⏯️ Playback controls (Play, Pause, Resume, Stop)
- 🌓 Dark mode support
- 📱 Responsive design for all devices
- 💬 Real-time character count
- ✨ Smooth animations and modern UI

## Demo

Try it out here: [Live Demo](https://yourusername.github.io/repo-name)

## Installation

1. Clone the repository:
```bash
git clone https://github.com/sudasun007/TextToSpeech.git
```

2. Navigate to the project directory:
```bash
cd TextToSpeech
```

3. Open `index.html` in your web browser or serve it using a local server.

## Usage

1. Select your preferred language from the dropdown menu
2. Choose an available voice for the selected language
3. Enter or paste your text in the text area
4. Adjust the speech parameters (optional):
   - Speed: 0.5x to 2x
   - Pitch: 0.5 to 2
   - Volume: 0 to 1
5. Click the "Speak" button to start the text-to-speech conversion
6. Use the control buttons to:
   - Pause/Resume the speech
   - Stop the speech
   - Record the audio output
   - Clear the text

## Recording Feature

To record the speech output:
1. Click the "Record" button
2. Grant microphone permissions when prompted
3. The speech will automatically start and be recorded
4. Click "Stop Recording" to save the audio file
5. The recording will be automatically downloaded as 'speech.wav'

## Browser Compatibility

- Chrome (recommended)
- Firefox
- Edge
- Safari
- Opera

Note: Voice selection and features may vary depending on the browser and operating system.

## Technical Details

- Built with vanilla JavaScript
- Uses the Web Speech API for text-to-speech conversion
- Implements the MediaRecorder API for audio recording
- Responsive design using CSS Grid and Flexbox
- Custom CSS variables for easy theming
- Modular JavaScript with clear separation of concerns

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Google Fonts - Poppins font family
- Web Speech API
- MediaRecorder API

## Support

For support, please open an issue in the GitHub repository or contact me at your.email@example.com
