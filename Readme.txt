PROJECT: Mood Classification Using Music 🎵

Created by Simranjeet Singh  
Guru Nanak Dev Engineering College, Ludhiana  
Summer School Training & Internship Programme, IIT Jammu
Course: Data Science & Artificial Intelligence (DS&AI)

Project Summary:
This project uses machine learning to classify songs as either "happy" or "sad" based on their audio features. It uses Python, the `librosa` library for audio processing, and a Random Forest model for classification.

FILES:
- extract_features.py: Pulls audio features from songs and stores them in a CSV file.
- train_model.py: Trains a random forest model using those features.
- predict.py: Takes a test song and predicts its mood (e.g., happy/sad).
- music_features.csv: Generated file containing features for all songs.
- genre_model.pkl: Trained model file saved after training.
- Test song : For testing the project.

FOLDER STRUCTURE:(used for training model)
- data/
   ├── happy/
   └── sad/
Each folder should have .mp3 or .wav songs before running the code.
I couldnt upload data folder on git due to restrictions so please make the folder and upload some songs to train the model altho the model needs atleast 5 songs of each genre to train.

STEPS TO RUN:
1. Put songs into their genre folder inside `data/` for training the model.
2. Run `extract_features.py`.
3. Run `train_model.py`.
4. Run `predict.py` to test a new song.

Made with basic Python, sklearn, pandas, and librosa.

