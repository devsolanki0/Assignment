# Music Genre Classifier

## Files

- save_model.py
- inference.py
- app.py
- music_genre_model.pkl
- music_features.csv
- requirements.txt

## Dataset

The CSV file should contain audio feature columns and one column named genre.

Example:

danceability,energy,loudness,speechiness,acousticness,instrumentalness,valence,genre

## Run

Install dependencies:

pip install -r requirements.txt

Create the model:

python save_model.py

Run the Streamlit app:

streamlit run app.py

The app supports CSV prediction and single-song prediction with confidence score.

## Streamlit Cloud

Upload the project to GitHub and deploy the repository through Streamlit Community Cloud.
