# What to Wear

A single-file client-side web application that helps you decide what to wear based on real-time weather forecasts. It translates data from the MET Norway Weather API and into simple, minimalist dressing recommendations.

## Live demo

https://what-to-wear-2.netlify.app/

## Key Features

- **Dressing Advice**: Recommends appropriate tops, bottoms, and jackets based on active temperature thresholds.
- **Rain Alerts**: Displays a warning to bring an umbrella if precipitation is expected in the next 3 hours.
- **Lightning Warnings**: Scans the upcoming 3 hours and displays an amber alert if thunderstorms are expected.
- **UV Index (2h Max)**: Calculates the 2-hour max UV index and highlights it in orange when sunscreen is needed ($\ge 3.0$).
- **System-Adaptive Theme**: Automatically adapts layout styling to follow your system's light or dark mode.
- **URL Coordinates**: Preserves your location coordinates directly in the browser's URL for seamless page reloads.
- **Weather Simulator**: An interactive drawer to manually override forecast conditions and test recommendations instantly.

## Getting Started

Because the application is serverless and self-contained, no installation or local server setup is required:

1. Locate the `index.html` file.
2. Double-click `index.html` or drag it into any modern web browser.
3. Grant location permissions if prompted (or input coordinates manually inside the coordinates drawer).

## Files

- [index.html](index.html): The complete frontend application containing HTML structure, Vanilla CSS styles, SVG iconography, dressing algorithms, API fetchers, and mock simulators.
- [LICENSE](LICENSE): Project license (MIT).

## Data Sources

- Meteorological data is fetched directly from the [MET Norway Weather API](https://api.met.no/).
