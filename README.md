# Investigating Netflix Movies from the 1990s

A guided DataCamp project using exploratory data analysis to study movies from the 1990s on Netflix.

## Questions answered
1. What is the typical movie duration in the 1990s?
2. How many 1990s action movies are shorter than 90 minutes?

## Key findings
- The dataset holds 4,812 titles; **183** are movies released between 1990 and 1999.
- Durations cluster around **100 minutes**.
- Of **48** action movies from the 1990s, **7** run under 90 minutes.

## Insight
Most 1990s movies on Netflix run for about 100 minutes, and short action films were uncommon (only 7 of 48 were under 90 minutes). A production company making a 1990s-style film would typically aim for around 100 minutes.

## Method
- Filtered by type (Movie), release year and genre.
- Plotted the duration distribution as a histogram with matplotlib.
- Counted short movies with a loop and counter, and noted the vectorised equivalent: `(df["duration"] < 90).sum()`.

## Files
- `netflix_1990s_analysis.ipynb`: the full analysis

## Data
`netflix_data.csv` is provided by DataCamp inside the project. Place it in the same folder as the notebook to re-run the analysis.

## Tools
Python, pandas, matplotlib, Jupyter

*Guided project completed on DataCamp.*
