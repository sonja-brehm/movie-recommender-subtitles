# Content-based movie recommender with subtitles

The aim of this project was to develop a content-based approach to recommending movies based on a dataset of Netflix movies. In a first step, only the movie descriptions were used to create recommendations. Afterwards, other features, namely cast, director and genre, were added. The next step was to expand the dataset to include the subtitles of the films to explore whether using them would improve the recommendations compared to the short descriptions.

This project was created during my postgraduate studies in the course unit "Personalisation and Machine Learning" at UAL in 2023. Unit Tutors: [Louis McCallum](http://louismccallum.com/), [Terence Broad](https://terencebroad.com/), Ulfa Octaviani and Maria Than.

The used dataset is ['Netflix Movies and TV Shows'](https://www.kaggle.com/datasets/shivamb/netflix-shows) from Shivam Bansal, published on Kaggle. To download the corresponding subtitles, the [opensubtitles](https://www.opensubtitles.com/en) API was used.

## Files
### Notebooks
- **01_recommendations-netflix-data**: Exploring the use of the information provided in the dataset to generate content-based recommendations.
- **02_get-subtitles**: The code for downloading the subtitles from [opensubtitles](https://www.opensubtitles.com/en) for a subsample of the Netflix dataset.
- **03_recommendations-subtitles**: Using the downloaded subtitles for recommendations (in combination with other information from the original dataset).

### Data Folder
...includes the datasets that are being used in the notebooks.
- **netflix_titles.csv**: The original dataset downloaded from Kaggle (created by Shivam Bansal), which can also be found [here](https://www.kaggle.com/datasets/shivamb/netflix-shows).
- **netflix_with_subtitles.csv**: Dataset including all downloaded subtitles; it is created at the end of the second notebook.
