# MinorLeagueInjuriesImpactStudy 🏥⚾

![MLB](https://img.shields.io/badge/data-MLB-blue)
![Analysis](https://img.shields.io/badge/type-analysis-green)
![Status](https://img.shields.io/badge/status-complete-brightgreen)

## Overview 📖
This repository contains data and analysis from the STATS 141xp final project, focused on studying the effects of injuries in Minor League Baseball (MiLB) on future Major League Baseball (MLB) performance. The goal is to understand how the largest gaps in game play due to injuries correlate with career Wins Above Replacement (WAR) metrics in MLB.

## Contents 📂
| File                     | Description |
|--------------------------|-------------|
| `2015_2022_pitcher_war.csv` | Contains WAR data for pitchers from 2015 to 2022. |
| `injury_data.csv`        | Details on injuries sustained by players, including types of injuries and the duration of time missed. |
| `pitcher_graph.csv`      | Provides comprehensive analysis of pitchers' performances including metrics like WAR, IP, K/9, ERA, alongside injury analysis. |
| `pitcher_injury_graph.csv` | Included injury type, standardized war metrics, and the number of days of injuries. |
| `pitcher_war.csv`        | WAR data specifically for pitchers. |
| `pitchers_majors.csv`    | Data on pitchers who played in the Major Leagues. |
| `pitchers_minors.csv`    | Data on pitchers during their time in the Minor Leagues. |
| `position_injury_graph.csv` | Similar to pitcher_injury_graph.csv |
| `position_war.csv`       | WAR data for position players. |
| `scrape.ipynb`           | Jupyter notebook containing Python scripts used for scraping and processing the data. |
| `war.ipynb`              | Jupyter notebook used for calculating the WAR and analyzing its implications. |

## Research Findings 🔍
Our analysis indicates that the maximum amount of consecutive games a Minor League position player misses has very little effect, either negative or positive, on his Major League career. Detailed findings and visualizations are provided in the respective CSV files and Jupyter notebooks.

## Technologies Used 💻
- **Python**: Primary programming language.
- **Jupyter Notebook**: Interactive computing and development environment.
  
## Libraries and Tools 🛠️
- **Pandas**: Data manipulation and analysis.
- **NumPy**: Numerical operations.
- **Matplotlib**: Data visualization.
- **Scikit-Learn**: Machine learning library used for calculating WAR and other metrics.
- **BeautifulSoup**: Data scraping from MLB website.
