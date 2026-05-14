> 日本語のREADMEはこちらです: [README.ja.md](README.ja.md)

# echizenkaigan

A web application that introduces attractive tourist spots along the Echizen Coast. It visualizes data provided by the Echizen Coast Revitalization Squad on an interactive map.

## Demo
https://code4fukui.github.io/echizenkaigan/

## Features
- Displays tourist spots on an interactive map powered by a single CSV file.
- Clickable map markers reveal detailed information, including descriptions, phone numbers, and regular holidays.
- Uses distinct icons for different categories (e.g., `taiken.png` for experiences, `eat.png` for dining) for easy visual identification.
- Built as a simple, static HTML page using the `<csv-map>` web component.

## Usage
Open the [demo page](https://code4fukui.github.io/echizenkaigan/) in any modern web browser. The map and tourist spots will load automatically. Click on any icon on the map to view details for that location.

## Data Source
This project is powered by a CSV file containing tourist spot information.

- **Data URL:** [`echizenkaigan-spot.csv`](https://code4fukui.github.io/echizenkaigan/echizenkaigan-spot.csv)
- **Key Fields:** `名前` (Name), `電話番号` (Phone), `カテゴリー` (Category), `icon`, `概要` (Description), `定休日` (Regular Holiday), and `geo3x3` for location coordinates.

## Contributing Organizations & Attribution
- **Data Provider:** [Echizen Coast Revitalization Squad](https://discoverechizen.com/)
- **Development:** [Fukui National College of Technology](https://www.fukui-nct.ac.jp/)
- **Iconography:** [OpenMoji](https://openmoji.org/) – The open-source emoji and icon project.

## License
MIT License — see [LICENSE](LICENSE).