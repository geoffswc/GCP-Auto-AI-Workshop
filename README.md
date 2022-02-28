# GCP-Machine-Learning-API-Workshop

### Short Description
This tutorial is an introduction to extracting, classifying, and assessing sentiment for text from image and video documents using the Python and the Google Cloud Platform API.

### Long Description
This workshop will review how to use Python, along with the Google AutoML API, to perform common machine learning and natural laanguage processing tasks using pre-trained models and methods. This workshop is designed to get researchers who are comfortable with python programming up and running with google cloud services for machine learning and natural language processing. 

In this workshop, participants will:

1) Set up a google cloud account and enable services from the vision and language AutoML Apis
2) Use AutoML vision and translation APIs to extract text transcripts from image, audio, and video files
3) Use AutoML language APIs to assessing sentiment and category for text documents

### Prerequisites

Participants should have basic introductory level Python programming skills, including the ability to write loops, conditionals, and methods. Familiarity with pandas and JSON is helpful but not required. 

### Setup and Configuration

Note: the free tier on all accounts below is sufficient for this workshop. 

To use the AutoML services for text extraction, categorization, and sentiment analysis, participants will need a Google Cloud Platform account. 

https://cloud.google.com/

Overview on setting up a google project, generate an API key, and connect to the AutoML API servive

https://cloud.google.com/vision/automl/docs/how-to

Quick Start

https://cloud.google.com/vision/docs/setup


## Workbooks

### Extract_Text_From_Image.ipynb

Use the Vision API to extract text from image files. Translate typed text, hand printed text, and cursive text. Review transcription accuracy and confidence levels. 

### Extract_Transcript_From_Flac.ipynb

Use the Speech API to extract a transcript from an audio (flac) file hosted on google cloud strorage. 

### Extract_Transcript_From_MP4.ipynb

Download an MP4 file from a web address. Use ffmpeg to convert the MP4 Upload to flac. Upload flac file to google cloud storage. Extract transcript from flac file. 

### Predict_Text_Sentiment_And_Category.ipynb

Use the Language API to 1) assess the sentiment for a text document, 2) predict the document classification probabilities for a document. 

### Extract_Transcript_From_YouTube.ipynb

Read transcript from video hosted on YouTube using the python youtube_transcript_api module. Note that this approach does not require setting up a google cloud account. It may be a good option for researchers who wish to analyze existing youtube videos or who are willing to upload their material to youtube (as public or unlisted links). 

## External Links

Google AutoML documentation

https://cloud.google.com/automl


