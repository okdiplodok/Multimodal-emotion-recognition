# Multimodal-emotion-recognition
This repository contains the pipeline of my master thesis project "Multimodal emotion recognition in video content".

The structure of my project is as follows:

1. Preprocessing steps: cutting the video into shots -> deleting the repeating shots (intro, recap, sneak peek) -> aligning a shot with a subtitle
2. Handing out the shot data to the annotators.
3. Analysing the results of the annotation sessions:
    1. Fine-tuning [BERT](https://github.com/google-research/bert) on the subtitle data.
    2. Overviewing the annotation statistics, the predictions of facial emotion recognition network, the predictions of BERT,
    and joining the textual and facial emotion classifiers for multimodal emotion recognition.

All these steps are presented in the following Jupyter notebooks (repositories):

Step # | Task
------------ | -------------
1. | Preprocessing
2. | [Instructions for annotators](https://github.com/okdiplodok/Annotator-instructions)
3.1 | Fine-tuning BERT
3.2 | Results: annotation, models' predictions
