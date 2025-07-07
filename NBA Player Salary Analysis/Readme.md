# NBA Player Data Analysis Dashboard

This project explores player data from the NBA using Python, featuring interactive visualizations and unsupervised machine learning techniques. The analysis aims to uncover patterns in player salaries, physical attributes, and college background, as well as segment players into meaningful clusters.

## Dataset

- Source: `nba.csv` (457 NBA players)
- Features include: Name, Team, Position, Age, Height, Weight, College, and Salary

## Key Objectives

- Clean and preprocess the dataset for analysis
- Visualize salary distributions, positional trends, and college background
- Explore physical attributes (height, weight) in relation to salary
- Segment players using KMeans clustering
- Build an interactive dashboard using Plotly and ipywidgets

## Tools and Libraries

- Python 3
- Pandas
- Plotly (plotly.graph_objects, plotly.subplots)
- Scikit-learn (KMeans)
- ipywidgets
- Google Colab / Jupyter Notebook

## Highlights

- Missing values in `Salary` and `College` handled using imputation
- `Height` column converted from string (e.g., "6-7") to numeric feet
- Interactive dashboard featuring six plots:
  - Salary distribution
  - Average salary by position
  - Average salary by college background
  - Age vs. Salary bubble chart
  - Salary by KMeans cluster
  - Height vs. Weight scatter plot (cluster-colored)

## Clustering Insight

Using KMeans clustering on age, height, weight, and salary, players were grouped into three clusters:

- Cluster 0: Younger players with lower salaries and average physical profiles
- Cluster 1: Taller, heavier players with moderate salaries
- Cluster 2: Older, higher-paid players — often veterans or stars

These clusters help identify player archetypes beyond traditional positions.

## Known Limitations

- ipywidgets may not render correctly in Google Colab; full interactivity is best experienced in a local Jupyter environment
- Salary data may be from a single season and doesn't reflect contract length or bonuses
- The "Unknown" college category includes international players and missing values

## How to Use

1. Clone this repository
2. Open the notebook in Jupyter or Colab
3. Ensure required packages are installed
4. Adjust sliders and dropdowns to explore the data

**Note:** For best widget interactivity, running the notebook in a local Jupyter environment is recommended.

## Future Work

- Incorporate performance statistics (e.g., points per game, assists)
- Include experience level, draft position, or contract details
- Add regression models to better predict player salary
- Explore web deployment using Streamlit or Dash

## License

This project is for educational and analytical purposes.
