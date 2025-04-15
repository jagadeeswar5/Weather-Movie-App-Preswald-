Weather-Based Movie Recommender 

This app was built using [Preswald](https://app.preswald.com) for a 30-minute coding challenge. It recommends movies based on the current weather using a real-world dataset from Kaggle.

Features

- Uses a historical weather dataset (`weatherHistory.csv`)
- Cleans and processes the data with pandas
- Maps weather summaries (like "Clear" or "Rain") to moods
- Displays popular movies based on detected mood
- Includes a "Feeling Adventurous?" option (via checkbox)
- Plotly chart logic for temperature trends (included, may not render)

Notes

- `get_df()` was attempted but did not load the dataset properly, so `pandas.read_csv()` was used instead
- Some Preswald sessions do not render `plotly()` or `checkbox()` consistently — logic is included with fallback handling

Dataset

- Source: [Kaggle – Weather History](https://www.kaggle.com/datasets/muthuj7/weather-dataset)


Built by Jagadeeswar using the Preswald SDK.
