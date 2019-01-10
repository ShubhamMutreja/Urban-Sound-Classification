# Urban-Sound-Classification
Context
The automatic classification of environmental sound is a growing research field with multiple applications to largescale, content-based multimedia indexing and retrieval. In particular, the sonic analysis of urban environments is the subject of increased interest, partly enabled by multimedia sensor networks, as well as by large quantities of online multimedia content depicting urban scenes.

However, while there is a large body of research in related areas such as speech, music and bioacoustics, work on the analysis of urban acoustic environments is relatively scarce.Furthermore, when existent, it mostly focuses on the classification of auditory scene type, e.g. street, park, as opposed to the identification of sound sources in those scenes, e.g.car horn, engine idling, bird tweet.

There are primarily two major challenges with urban sound research namely

Lack of labeled audio data. Previous work has focused on audio from carefully produced movies or television tracks from specific environments such as elevators or office spaces and on commercial or proprietary datasets . The large effort involved in manually annotating real-world data means datasets based on field recordings tend to be relatively small (e.g. the event detection dataset of the IEEE AASP Challenge consists of 24 recordings per each of 17 classes).

Lack of common vocabulary when working on urban sounds.This means the classification of sounds into semantic groups may vary from study to study, making it hard to compare results so the objective of this notebook is to address the above two mentioned challenges.

Content
The dataset is called UrbanSound and contains 8732 labeled sound excerpts (<=4s) of urban sounds from 10 classes: - The dataset contains 8732 sound excerpts (<=4s) of urban sounds from 10 classes, namely: Air Conditioner Car Horn Children Playing Dog bark Drilling Engine Idling Gun Shot Jackhammer Siren Street Music The attributes of data are as follows: ID – Unique ID of sound excerpt Class – type of sound

Acknowledgements
Source of the dataset : https://drive.google.com/drive/folders/0By0bAi7hOBAFUHVXd1JCN3MwTEU
