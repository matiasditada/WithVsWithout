# Time With vs Without — Crossover Calculator

A beautiful, client-side web application that calculates when you will have lived more time with an event than without it. Perfect for tracking milestones like "more time married than not" or "more time working than not."

## Features

- 🎯 **Simple Calculation**: Enter your birth date and event start date to find the crossover point
- 📊 **Visual Timeline**: Interactive timeline showing your journey from birth to crossover
- 💾 **Save Favorites**: Save multiple events and track them in a beautiful table
- 🔒 **Privacy First**: All calculations run entirely in your browser - no data sent to servers
- 📅 **Age Display**: Shows your age at the crossover date

## How It Works

The crossover date is calculated using a simple formula:

**X = 2·S − B**

Where:
- **B** = Birth date
- **S** = Event start date
- **X** = Crossover date (when time with event equals time without it)

## Local Development

To run locally with a simple HTTP server:

```bash
# Using Python 3
python3 -m http.server 8000

# Using Python 2
python -m SimpleHTTPServer 8000

# Using Node.js (with http-server)
npx http-server -p 8000
```

Then open `http://localhost:8000/index.html` in your browser.

## Technical Details

- **Pure HTML/CSS/JavaScript**: No dependencies, no build process
- **UTC Date Math**: All calculations use UTC dates to avoid timezone/DST issues
- **LocalStorage**: Saves your events and form data locally in your browser
- **Shareable Links**: Generate URLs with query parameters to share specific calculations

## Browser Support

Works in all modern browsers that support:
- ES6 JavaScript
- CSS Grid and Flexbox
- LocalStorage API

## Contributing

Contributions are welcome! Please see [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines.

## License

This is free and unencumbered software released into the public domain. For more information, see the [LICENSE](LICENSE) file or visit [unlicense.org](https://unlicense.org/).

## Acknowledgments

Built with vanilla JavaScript, CSS, and HTML. No frameworks, no dependencies, just pure web technologies.

**Note**: This project was 100% built by AI, demonstrating the capabilities of AI-assisted development.

