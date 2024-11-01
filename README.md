# Conditional Circuit Switch

## Description
An interactive web-based circuit simulation that demonstrates conditional switching behavior through a drag-and-drop interface. Users can manipulate circuit nodes and observe how their positions and states affect a central switch mechanism.

## Features
- 5 interactive circuit nodes with drag-and-drop functionality
- Dynamic central switch with three states
- Real-time state management and visual feedback
- Position-based conditional logic
- Responsive design for various screen sizes

## Technologies Used
- HTML5
- CSS3
- Vanilla JavaScript
- DOM Manipulation
- Event Handling System

## Quick Start
1. Clone the repository: 
```
git clone https://github.com/Jimmyu2foru18/Circuit-Switch.git
```
2. Open `Curcit.html` in your preferred web browser
3. Start interacting with the circuits!

## How It Works

### Circuit System
- 5 draggable circuit nodes that can be positioned anywhere on the screen
- Each circuit can be toggled ON/OFF independently
- Position relative to the central switch affects the overall system state

### Switch Logic
The central switch operates based on the following conditions:

- **Green (ON)**
  - 2 or more circuits ON on both sides
  - 3 circuits ON on one side + 2 ON on the other

- **Yellow (Semi-Connected)**
  - Exactly 1 circuit ON on each side

- **Gray (OFF)**
  - Any other configuration

## Browser Compatibility
- Google Chrome (Recommended)
- Mozilla Firefox
- Microsoft Edge
- Safari

## Future Enhancements
- [ ] Add visual connection lines between circuits
- [ ] Implement power flow animations
- [ ] Add sound effects for interactions
- [ ] Create additional circuit types
- [ ] Add save/load functionality for circuit configurations

## Author
James M.

## Acknowledgments
- Inspired by real-world circuit logic systems
- Built for educational purposes

## Documentation
For detailed usage instructions, please refer to the [Instructions](instructions.md) file.

