# Amazon-Transcribe_Sensitivity-Analysis
Utilize AWS services (SageMaker, S3 Storage Bucket) to conduct Sensitivity Analysis on Amazon Transcribe Machine Learning Model

## Initialization
Run Initialize.ipynb first and follow the instructions for pre-analysis data preparation

## Transcribe
Run Transcribe.ipynb for audio transcription using Amazon Transcribe, and retrieve corresponding lyrics from the lyrics.ovh API. Check here for API (Documentation)[https://lyricsovh.docs.apiary.io/#]

## Sample Data
data.csv, test_copy.csv, and tempo.csv are provided.

------
data.csv - dataframe containing song title, artist, genre, lyrics, and transcribed lyrics

test_copy.csv - processed data.csv, containing transcription accuracy calculated through the Levenshtein Distance

tempo_csv - contains song title, artist, and tempo


