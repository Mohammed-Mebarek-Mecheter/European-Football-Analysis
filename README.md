# European Football Data Analysis

This project involves the analysis of European football match results and related statistics using a provided SQLite database containing data from 2005 to the present. The goal is to gain insights into match outcomes, team performance, goal statistics, and trends over the years. The project is conducted using Python and SQL.

## Dataset Description

The [dataset](https://www.kaggle.com/datasets/groleo/european-football-database) is stored in an SQLite database file named `european_database.sqlite`. It consists of two main tables:

1. `matchs` table: Contains detailed information about football matches, including match date, teams, season, and more.
2. `divisions` table: Contains information about football divisions, including division, names, and countries.

## Project Tasks

The project involves the following tasks:

### 1. Data Preparation

- [x] Load the dataset from the SQLite database.
- [x] Explore the 'matchs' table to understand its structure and columns.

### 2. Data Cleaning

- [x] Check for missing values in relevant columns.
- [x] Ensure the 'FTR' (Final-time results) column contains valid values (H for Home win, A for Away win, D for Draw).

### 3. Data Analysis

- [x] Create a pivot table or use SQL queries to aggregate the data.
- [x] Identify patterns or trends in match outcomes over the years.

### 4. Team Performance Analysis

- [x] Create a ranking of teams based on their overall performance (e.g., points earned, goal differences).
- [x] Visualize the top-ranking teams.

### 5. Home Advantage Analysis

- [x] Analyze the presence of a "home advantage" in football matches.
- [x] Identify leagues or teams with the strongest home advantage.

### 6. Country Comparison

- [x] Compare teams from different countries/leagues in terms of match outcomes and goal statistics.

### 7. Seasonal Trends

- [x] Analyze how team performance and match outcomes vary by season.
- [x] Visualize seasonal trends.

### 8. Long-Term Trends

- [x] Identify any long-term trends or patterns in match outcomes or goal statistics over the years.
- [ ] Visualize long-term trends (in progress).

### 9. Competitive Leagues

- [x] Identify leagues that consistently have more competitive matches.

## Installation and Setup

1. Clone this repository to your local machine:
git clone https://github.com/Mohammed-Mebarek-Mecheter/European-Football-Analysis.git

2. Install the required Python libraries:

3. Ensure you have the `european_database.sqlite` file in the project directory.

## Usage

Run the Python scripts for each task in the project. Modify and customize the scripts as needed for specific analyses and visualizations.

## Contributing

Contributions to this project are welcome! Please follow the standard GitHub workflow:

1. Fork the project.
2. Create a new branch.
3. Make your changes and commit them.
4. Create a pull request.

## License

This project is licensed under the MIT License

## Author

- Name: [Mohammed Mebarek Mecheter](https://www.linkedin.com/in/mohammed-mebarek-mecheter/)
- Email: mohammedmecheter@gmail.com
- Portfolio: [Mebarek](https://mebarek.pages.dev/european-football-match/)

Feel free to contact me for any questions or additional information about this project.