# Name-Entity-Recognition-
Named EntitiesRecognition (NER) is a basic task of Natural Language Processing (NLP). The purpose is to identify named entities such as person names, place names, and organization names in the corpus. 
Due to the increasing number of these named entities, it is usually impossible to exhaustively list them in the dictionary, and their constituent methods have some regularities. Therefore, the recognition of these words is usually included in the task of morphological processing (such as Chinese segmentation). Independent processing, called named entity recognition. 


Named entity recognition technology is an indispensable part of many natural language processing technologies such as information extraction, information retrieval, machine translation, and question answering systems.

Named entities are the research subjects for named entity recognition. Generally, named entities include 3 categories (entity, time, and number) and 7 categories (person, place, institution, time, date, currency, and percentage). Judging whether a named entity is correctly identified includes two aspects: whether the boundary of the entity is correct; and whether the type of the entity is correctly labeled. 

The main types of errors include correct text, which may be of the wrong type; conversely, text boundaries are incorrect, and the main entity words and part-of-speech tokens it contains may be correct.


TECHNOLOGY USE
Here we will be using  Anaconda Python 3.6 , Pytorch 1.4 with GPU support CUDA 10 with CuDNN 10.



WORKFLOW DIAGRAM


IMPLEMENTATION
1. Project Directory
Here data folder consists of data and out_base folder consists of the BERT models.

2. requirements.txt


requirements.txt file consists of all the packages that we need to run with project.

3. bert.py

This is the most important file in this project which we will be using for training and prediction.
3. clientApp.py

This is the flask server file and the entry point of application.



TESTING IN LOCAL/API
To do the test testing we need to run the clientApp.py and after that web server will start at http://0.0.0.0:5000/

Enter the Text and click on Predict button.


Predictions will be shown in the result box. 

CONCLUSION
Here we successfully performed Named Entity Recognition on the given dataset.
COMPARISION
More data or better larger dataset can be used to build a better model. We can also try out better pre trained model with fine tuning to increase the performance.
