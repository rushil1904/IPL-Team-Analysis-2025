# IPL Team Analysis Dashboard

## Overview
A comprehensive analysis tool for Indian Premier League (IPL) teams that combines web scraping, data analysis, and visualization to provide insights for team building and player evaluation.

## Features
- **Player Statistics Scraping**: Automated data collection from ESPNCricinfo using Python
- **Performance Analytics**: In-depth analysis of batting and bowling metrics
- **Visual Dashboard**: Interactive Tableau visualizations for:
  - Bowling performance metrics (SR, Economy, Average)
  - Batting statistics (Strike Rate, Average, Impact scores)
  - All-rounders' performance comparison
- **Team Composition Analysis**: Excel-based tracking of:
  - Player valuations
  - Role categorization
  - Team balance metrics

## Tech Stack
- **Python**: Data scraping and processing
  - BeautifulSoup4
  - Pandas
  - Requests
  - NumPy
- **Tableau**: Data visualization and dashboarding
- **Excel**: Player categorization and team composition analysis

## Interactive Analysis
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](notebook-link)

The analysis can be run interactively using Google Colab. The notebook includes:
- Web scraping from ESPNCricinfo
- Data cleaning and preprocessing
- Statistical analysis
- Performance metrics calculation
- Data visualization using matplotlib
- Export functionality for Tableau integration

## Project Structure
```
📦 ipl-analysis
 ┣ 📂 data
 ┃ ┣ 📜 player_stats_combined.csv
 ┃ ┗ 📜 team_composition.xlsx
 ┣ 📂 notebooks
 ┃ ┗ 📜 IPL_Analysis.ipynb
 ┣ 📂 visualizations
 ┃ ┗ 📜 team_dashboard.twb
 ┣ 📜 README.md
 ┗ 📜 requirements.txt
```

## Setup and Usage

### Google Colab
1. Click the "Open in Colab" badge above
2. Make a copy of the notebook in your Google Drive
3. Run all cells or execute them step by step
4. Download generated CSV files for further analysis

### Local Setup
1. Clone the repository
```bash
git clone https://github.com/yourusername/ipl-analysis.git
cd ipl-analysis
```

2. Install required Python packages
```bash
pip install -r requirements.txt
```

3. Open and run the Jupyter notebook locally
```bash
jupyter notebook notebooks/IPL_Analysis.ipynb
```

## Data Sources
- Player statistics: ESPNCricinfo
- Player valuations: IPL Auction data
- Team composition metrics: Custom analytics

## Analysis Components
### Python Analysis (Colab Notebook)
- Player statistics web scraping
- Performance metrics calculation
- Statistical analysis of player performance
- Data preprocessing for visualization
- CSV export functionality

### Tableau Dashboard
- Bowling Performance Analysis
- Batting Impact Assessment
- All-rounder Matrix
- Team Composition Insights

### Excel Analysis
- Player valuation tracking
- Role-based categorization
- Team balance metrics
- Budget allocation analysis

## Visualizations
- Bowling Performance Analysis
  - Strike Rate comparisons
  - Economy rate analysis
  - Wicket-taking ability
- Batting Impact Assessment
  - Strike Rate vs Average analysis
  - Situation-based performance
- All-rounder Matrix
  - Combined bowling and batting metrics
  - Role-based clustering

## Future Enhancements
- [ ] Match situation analysis
- [ ] Player form tracker
- [ ] Opposition-specific performance metrics
- [ ] Predictive team performance modeling
- [ ] Integration with live match data
- [ ] Automated data refresh pipeline

## Contributing
Feel free to submit issues and enhancement requests. To contribute:
1. Fork the repository
2. Create a feature branch
3. Submit a pull request

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact
For any queries, please reach out to [rushil1904@gmail.com]
