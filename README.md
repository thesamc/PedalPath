# PedalPath - Guitar Pedalboard Design Tool

An interactive web application built with vanilla JavaScript that helps guitarists design, plan, and learn about guitar effect pedal configurations. This tool allows users to experiment with different pedal arrangements while receiving real-time feedback about power requirements, board size needs, and signal chain optimization.

## Features
- Drag-and-drop pedal arrangement interface
- Real-time chain statistics (power draw, board size, total cost)
- Intelligent signal chain recommendations
- Famous guitarist presets (The Edge, David Gilmour, Jimi Hendrix)
- Pedal filtering by effect type
- Interactive pedal tooltips
- Local storage for saving configurations
- Mobile-responsive design
- High contrast theme support

## Built With
- HTML5
- CSS3 (Custom Properties)
- Vanilla JavaScript
- No external frameworks or libraries

## Project Structure
The application includes several key components:
- Pedal database with detailed specifications
- Drag-and-drop interface
- Interactive signal chain
- Statistics panel
- Preset system
- Filter system
- Save/load functionality

## Design System
Core styles managed through CSS variables:
```css
:root {
  --primary-bg: #1a1a1a;
  --secondary-bg: #252525;
  --accent: #4dabf7;
  --text: #ffffff;
  --warning: #ff6b6b;
  --success: #51cf66;
}
```

## Setup
1. Clone the repository
   ```bash
   git clone https://github.com/thesamc/PedalPath.git
   ```
2. Open index.html in your browser

No build process required as this is a static website.

## Features in Development
- Additional famous presets
- Advanced power supply recommendations
- Audio samples for each pedal
- Custom chain sharing
- Extended pedal database
- Visual signal path display

## Usage Tips
- Drag pedals from the bank to your chain
- Rearrange pedals by dragging within the chain
- Watch for chain order recommendations
- Use presets to learn from famous tones
- Save your configurations for later use

## Contact
- GitHub: [@thesamc](https://github.com/thesamc)
- LinkedIn: [Samuel Chutter](https://www.linkedin.com/in/samuel-chutter/)
- Email: samcwebdev@gmail.com

## License
This project is open source and available under the MIT License.
