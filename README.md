# Study of the use of API in Data Analysis
### _Done on Jupyter Notebook with Python; unofficial YouTube Music API used_

This repository contains the main notebook, with the API of interest 'YTMusicAPI', an unofficial YouTube Music API that is able to access relevant statistics (views, popularity, explicity, etc.) of a song, given a list of albums or artists to search songs for. The notebook starts with initializing the API and constructing a DataFrame, to be treated as the dataset of interest for the study.

Data preprocessing is done first to remove duplicate songs, as well as identify and address null values depending on the statistic. Then, four questions are proposed to determine the effectiveness of the API. They are as follows:
- Are explicit songs more popular than non-explicit songs?
- Are longer songs more popular than shorter songs?
- Is video game music (VGM) more popular than non-VGM?
- Are pre-2000s songs more popular than post-2000s songs?

Each question is tackled with their appropriate inferential statistics and exploratory data analyses. Alongside the questions above, other smaller-scale questions are tackled. Afterwards, reflections are made on the API and the researchers themselves, going over any limitations and considerations. The notebook concludes with the sentiment that the API can be used for data analysis, if one were willing to deal with its limitations and quirks. Related concluding statements are also made for each proposed question.
