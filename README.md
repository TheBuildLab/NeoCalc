# NeoCalc

✨ A beautiful and functional web-based calculator with glassmorphism design.

## Features

- 🎨 **Glassmorphism UI**: Modern frosted glass effect with gradient background
- ⚡ **Full Calculator Functionality**: Addition, subtraction, multiplication, and division
- ⌨️ **Keyboard Support**: Complete keyboard support for all operations
- 📱 **Responsive Design**: Works seamlessly on desktop and tablets
- 🎯 **Number Formatting**: Automatic comma-separated formatting for large numbers
- 🔢 **Decimal Support**: Full support for decimal calculations
- ⏱️ **Smooth Animations**: Hover and active state animations for better UX

## Demo

Open `index.html` in your web browser to see NeoCalc in action!

## Usage

### Mouse/Touch
- Click the number buttons to input numbers
- Click operation buttons (+, -, ×, ÷) to perform calculations
- Press "=" to get the result
- Use "AC" to clear all and "DEL" to delete the last digit

### Keyboard
- **Numbers**: 0-9
- **Operations**: 
  - `+` for addition
  - `-` for subtraction
  - `*` for multiplication
  - `/` for division
- **Results**: `Enter` or `=` to calculate
- **Backspace**: Delete the last digit
- **Delete**: Clear everything (AC)
- **Decimal**: `.` for decimal point

## File Structure

```
NeoCalc/
├── index.html       # HTML structure
├── style.css        # Styling with glassmorphism effect
├── script.js        # Calculator logic and event handling
└── README.md        # Documentation
```

## Technical Details

### Technology Stack
- **HTML5**: Semantic markup
- **CSS3**: Glassmorphism design with backdrop filters
- **Vanilla JavaScript**: Pure JS calculator logic with no dependencies

### Calculator Class
The calculator uses a single `Calculator` class that manages:
- Number input and validation
- Operation selection and chaining
- Computation logic
- Display formatting

## Color Scheme

- **Background**: Purple gradient (from #667eea to #764ba2)
- **Primary Button**: Semi-transparent white
- **Operators**: Orange (rgba(255, 165, 0, 0.8))
- **Equals**: Green (rgba(46, 204, 113, 0.8))
- **Clear/Delete**: Red (rgba(231, 76, 60, 0.8))

## Browser Compatibility

- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/TheBuildLab/NeoCalc.git
   ```

2. Navigate to the project directory:
   ```bash
   cd NeoCalc
   ```

3. Open `index.html` in your web browser

## License

MIT License - feel free to use this project for personal or commercial purposes.

## Author

TheBuildLab

---

**Made with ❤️ and a touch of glassmorphism**
