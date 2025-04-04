# SafeOn Campus Website

A comprehensive campus safety information portal providing students, faculty, and staff with essential resources and emergency procedures.

## Project Overview

The SafeOn Campus website is designed to be an accessible and informative resource for campus safety. The website includes:

- Critical emergency contact information
- Detailed safety resources and tips
- Step-by-step emergency procedures
- Information about campus safety services

## File Structure

This project uses a single-file approach to ensure maximum compatibility across different hosting environments:

```
safeon-campus/
└── index.html (contains HTML, CSS, and JavaScript)
```

## Features

- **Multi-page design**: Navigation between different sections without page reload
- **Responsive layout**: Works on mobile and desktop devices
- **Emergency information**: Clearly highlighted emergency contacts and procedures
- **Resource directory**: Comprehensive list of campus safety services

## Installation

1. Download the `index.html` file
2. Place it in any directory on your web server
3. Access it through your web browser

## Local Development

You can run this website locally by:

1. Opening the `index.html` file directly in any modern web browser
2. Using a local development server:

   **Using Python's built-in server**:
   ```
   cd /path/to/safeon-campus
   python -m http.server
   ```
   Then visit http://localhost:8000 in your browser

   **Using Node.js http-server**:
   ```
   npm install -g http-server
   cd /path/to/safeon-campus
   http-server
   ```
   Then visit http://localhost:8080 in your browser

## Customization

The website can be easily customized:

- Update emergency contact information with your campus-specific numbers
- Modify the safety resources to reflect available services on your campus
- Add additional emergency procedures relevant to your location
- Change colors and styling by modifying the CSS in the `<style>` section

## Browser Compatibility

This website is compatible with:
- Chrome 60+
- Firefox 60+
- Safari 12+
- Edge 16+
- Opera 50+

## Future Enhancements

Potential improvements for future versions:

- Add a campus map with safety feature locations
- Implement a real-time emergency alert banner
- Include a campus safety event calendar
- Add a contact form for non-emergency safety concerns

## License

This project is available for free use by educational institutions.

