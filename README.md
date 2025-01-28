# truest-north-compass
# Compass Programming Interface

A web-based tool for programming digital compasses using screen flashing patterns. This interface allows users to set destination coordinates for compatible digital compasses through a simple, browser-based interface.

## Features

- **Simple Coordinate Input**: Directly enter latitude and longitude coordinates
- **Sequence Programming**: Program up to 10 sequential destinations
- **Visual Programming**: Uses screen flashing patterns to transfer coordinate data
- **Mobile Optimized**: Designed for use on mobile devices
- **Screen Wake Lock**: Prevents screen from sleeping during programming
- **Interactive UI**: Includes countdown timer and visual feedback
- **Built-in Instructions**: Contains a how-to modal for new users

## How It Works

The interface converts geographic coordinates into binary data and transmits this data to compatible compasses using a series of white and black screen flashes. The compass's light sensor reads these flashes and programs the destination coordinates.

### Programming Process

1. Enter the target coordinates (single destination or sequence)
2. Click "Start Programming"
3. Place the compass face-down on the screen during the countdown
4. Wait for the flashing sequence to complete
5. The compass will confirm successful programming with spinning hands

## Usage

### Single Destination

1. Enter the latitude and longitude in the input fields
2. Click "Start Programming"
3. Follow the on-screen instructions

### Multiple Destinations

1. Click "Program multiple destinations instead"
2. Enter up to 10 coordinate pairs (one per line) in the format:
   ```
   latitude,longitude
   42.41413,-71.00782
   33.61546,-81.10347
   ```
3. Optionally check "Reset to first destination when compass is turned off"
4. Click "Start Programming"
5. Follow the on-screen instructions

## Technical Details

- Built with vanilla JavaScript and HTML5
- Uses the NoSleep.js library to prevent screen timeout
- Converts coordinates to 53-bit binary strings for transmission
- Supports both single and multi-destination programming
- Implements precise timing for flash patterns
- Mobile-responsive design

## Setup

1. Download the HTML file
2. Open it in a modern web browser
3. That's it! No server or additional setup required

## Compatibility

- Works with most modern web browsers
- Designed for mobile devices with brightness control
- Compatible with digital compasses that use light-based programming
- Best used with screen brightness at maximum

## Best Practices

- Ensure your screen brightness is at maximum
- Clean both your phone screen and compass sensor
- Keep the compass steady during programming
- Use in a well-lit environment for best results
- Double-check coordinates before programming

## Contributing

Feel free to submit issues and enhancement requests!

## License

This project is licensed under the MIT License - see the LICENSE file for details.
