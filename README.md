# Map Radius Tool

A lightweight, interactive map tool for visualizing radius areas and estimating population data within a geographic region.

**[Live Demo](https://ariwoods-vettx.github.io/maps-radius-tool/)**

## Features

- **Interactive Radius Circle** - Draw, drag, and resize a circle on the map
- **Address Search** - Geocode any address with autocomplete
- **Population Estimates** - Real-time population data for US locations using Census Bureau data
- **Private Party Listings** - Estimated vehicle listings based on population density
- **Customizable** - Adjust radius, units (miles/km), and circle color
- **Shareable URLs** - All settings are saved to the URL for easy sharing
- **Responsive Design** - Works on desktop and mobile devices

## Tech Stack

- Vanilla JavaScript (no frameworks)
- Google Maps JavaScript API
- US Census Bureau API (2020 Census data)
- FCC Geo API (county/FIPS lookup)

## Usage

1. Enter an address in the search field
2. Click "Draw Circle" or select from autocomplete
3. Adjust the radius using the slider or input field
4. Drag or resize the circle directly on the map
5. View population estimates in the panel above the map

## URL Parameters

The tool supports the following URL parameters for sharing:

| Parameter | Description | Example |
|-----------|-------------|---------|
| `address` | Location to center the map | `address=Austin, TX` |
| `radius` | Circle radius value | `radius=25` |
| `unit` | Unit of measurement | `unit=miles` or `unit=km` |
| `color` | Circle color (hex) | `color=%230f172a` |

## Development

This is a single-file application. To run locally:

1. Clone the repository
2. Open `index.html` in a browser

No build process required.

## License

MIT
