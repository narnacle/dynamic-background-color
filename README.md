# Dynamic Background Color Webpage

A simple HTML page that changes its background color based on URL parameters. Perfect for OBS streaming, presentations, or quick color reference.

## Features

- Changes background color based on URL parameters
- Supports hex color codes (with or without #)
- Supports CSS color names
- Responsive design with clean UI
- OBS-friendly with CSS override option
- Smooth color transition animations

## Usage

### Hex Codes
- Without #: `narnacle.github.io/dynamic-background-color/?c=7e3f14`
- With URL-encoded #: `narnacle.github.io/dynamic-background-color/?c=%237e3f14`

### Color Names
- `narnacle.github.io/dynamic-background-color/?c=blue`
- `narnacle.github.io/dynamic-background-color/?c=darkcyan`

### OBS Integration
To show only the background color in OBS:
1. Add the page as a Browser Source
2. Add this CSS override in the source properties:

```css
   .container { display: none; }
```
## Examples

- [Blue background](https://narnacle.github.io/dynamic-background-color/?c=blue)
- [Red background](https://narnacle.github.io/dynamic-background-color/?c=ff0000)
- [Green background](https://narnacle.github.io/dynamic-background-color/?c=%2300ff00)
- [Dark cyan background](https://narnacle.github.io/dynamic-background-color/?c=darkcyan)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
