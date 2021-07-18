# Unscipted SOC Project 
This is my SOC 2021 project "Unscripted" involving NLP, Machine Learning

My learning progress can be accessed via [project report](https://docs.google.com/document/d/10vDvAiZNAJRD1QzleyLwiM3BMXjb-l0cGkvnWBgEKOk/edit?usp=sharing)

## Speech to text library used:
SpeechRecognition in Python

## Objective of this project:
To take an audio(.wav file) as input and transcribe the speech in a text file(transcription.txt). Another additional feature we have added is to get summary of the transcription. The number of lines of summary the user wants is taken as input and the desired summary is written in summary.txt.

## How to use?
- Clone the github repo on your local machine
- Create a virtual environment in project_files and pip install -r requirements.txt to install the necessary files
- To get transcription of an audio file(.wav file), use python3 speech_to_article.py <path_to_audiofile>
- To get summary of the transcription, run python3 summarizer.py and provide the number of lines of summary you want as input 

## Advantages
- Speech to text automated
- Obtain relevant text from the speech
- Obtain any number of lines of summary 
