# Chart Longevity and Stardom Prediction using Spotify Data

This project aims to predict song duration in Spotify's top 200 charts and classify artists as one-hit wonders or stars using data from Spotify's top 200 playlists from 2017 to 2023. The project combines generic variables like artist names and nationalities with engagement metrics like danceability and points accumulated.


## Installation
To run the project, please install the following libraries:

- gdown
- pandas
- numpy
- sklearn
- matplotlib
- seaborn
- statsmodels
- joblib
- imblearn

You can install these libraries using pip:

```
pip install gdown pandas numpy sklearn matplotlib seaborn statsmodels joblib imblearn
```

## Dataset

The dataset used in this project is stored in a public Google Drive file. The notebook is configured to download the dataset automatically.

## Project Structure

The project consists of two main tasks:

1. **Regression Task**: Predicting the longevity of a song in the charts
2. **Classification Task**: Predicting whether an artist will be a star or a one-hit wonder

### Regression Task

The regression task involves the following steps:

1. Data preprocessing
2. Exploratory data analysis
3. Model implementation and evaluation

The best-performing model for the regression task was Linear Regression, with an average error of around 3 days per song duration.

### Classification Task

The classification task involves the following steps:

1. Data preprocessing
2. Exploratory data analysis
3. Model implementation and evaluation

The best-performing model for the classification task was the improved XGBoost classifier, achieving an accuracy of 71% with a balanced target variable.

## Usage

1. Clone the repository
2. Install the required libraries
3. Run the Jupyter notebook

The notebook will download the dataset from the provided Google Drive link and perform the analysis.

## Results

The project demonstrates the effectiveness of machine learning models in predicting song duration and artist stardom using data from Spotify. The insights gained from this analysis can be used by Spotify to identify rising stars and predict the chart durations of their hits, enabling smarter, dual-focused marketing efforts.

## Future Work

Potential areas for expansion include integrating social media metrics and broader market trends to enrich the dataset and explore more complex algorithms.

## License

This project is open-source and available under the [MIT License](LICENSE).

## Acknowledgements

We would like to thank Spotify for providing the dataset used in this project.

## References

The project report includes a list of references that were used in the research and development of this project.

Feel free to contribute to the project by submitting pull requests or opening issues for any bugs or feature requests.
