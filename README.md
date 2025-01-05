# NFL Kicker Predictor

A sophisticated Python application that provides real-time NFL kicker statistics and performance analysis with an intuitive graphical interface.

## Features

- **Real-time Data**: Scrapes live NFL kicker statistics from ESPN
- **Offline Mode**: Load previously saved kicker data for offline analysis
- **Statistical Analysis**: Track and analyze key performance metrics including:
  - Career & season field goal percentages
  - Average attempts per game
  - Average successful kicks per game
  - Last game performance
- **Visual Performance Indicators**: Color-coded projections comparing historical averages
- **Data Persistence**: Save kicker statistics locally for future reference

## Installation

1. Clone the repository: ```bash git clone https://github.com/yourusername/NFL-Kicker-Predictor.git ```

2. Install required dependencies: ```bash pip install requests beautifulsoup4 tkinter ```

## Usage

1. Run the main application: ```bash python Kicker.py ```

2. Select data source:
   - **From Network**: Fetches real-time data from ESPN
   - **From Save**: Loads previously saved local data

4. Choose league (NFL currently supported)

5. Browse kickers and view their statistics

6. Enter projections to compare against historical performance:
   - Green: Projection below historical average
   - Red: Projection above historical average

## Project Structure

- `Classes/`: Core class definitions
- `Gui/`: User interface implementation
- `Local/`: Local data handling
- `Save/`: Data persistence operations
- `Scrape/`: Web scraping functionality

## Technical Details

- Built with Python 3.x
- Uses BeautifulSoup4 for web scraping
- Tkinter for GUI implementation
- Modular architecture for easy maintenance and expansion

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Data sourced from ESPN's NFL statistics
- Built with inspiration from sports analytics and statistical modeling

--- *Note: This project is for educational and analytical purposes only. All NFL data is property of their respective owners.*
