## Dataset
- File: `spotify_data clean.csv`
- Records: 8,582
- Original columns: 15
- Main information: track details, artist details, album details, popularity, release date, and duration.

## Tools and Libraries
- Python 3
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Tasks Performed
1. Read the CSV file using Pandas.
2. Inspected the dataset using `head()`, `tail()`, `info()`, and `describe()`.
3. Checked duplicate records.
4. Converted album release dates to datetime.
5. Created release year, duration category, and popularity category columns.
6. Dropped identifier columns not needed for the analysis.
7. Identified missing values and handled them. Mean imputation is applied to numerical columns only when numerical nulls exist; missing text values are filled with `Unknown`.
8. Generated insights using grouping, aggregation, and sorting.
9. Created bar charts, histograms, and a line chart.

## Important Note on Missing Values
The supplied CSV has 3 missing values in `artist_name` and 3,361 missing values in `artist_genres`. Its numerical columns have no missing values. Therefore, no numerical mean imputation is required for the current data. The notebook includes mean-imputation code that will run if numerical missing values are present.

## How to Run
1. Install Python and Jupyter Notebook (or use Google Colab).
2. Keep `Spotify_Data_Analysis_Milestone1.ipynb` and `spotify_data clean.csv` in the same folder.
3. Open the notebook.
4. Run all cells from top to bottom.
5. Check that all tables and charts are displayed.

## Files
- `Spotify_Data_Analysis_Milestone1.ipynb` – analysis and visualizations.
- `spotify_data clean.csv` – original dataset.
- `README.md` – project overview and instructions.
