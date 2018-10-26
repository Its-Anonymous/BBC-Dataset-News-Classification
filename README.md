Machine Learning Task By Mohammad Hunain
# BBC-Dataset-News-Classification
Consists of 2225 documents from the BBC news website corresponding to stories in five topical areas from 2004-2005.
Class Labels: 5 (business, entertainment, politics, sport, tech)
# FILE DESCRIPTION 
•	dataset/data_files: Data folders each containing several news txt files
•	dataset/dataset.csv: csv file containing "news" and "type" as columns. 
"news" column represent news article and "type" column represents news category among (business, entertainment, politics, sport, tech).
•	model/get_data.py: To gather all txt files into one csv file contianing two columns("news","type"). After successfull execution it will create dataset.csv file in dataset folder.
•	model/model.py: preprocessing, tf-idf feature extraction and model building and evaluation stuff.
•	model/test.ipynb: jupyter notebook
# INSTRUCTION TO RUN CODE
1.	Open Terminal
2.	Change the current working directory to "model" directory. for eg "BBC-Dataset-News-Classification-master/model"
3.	Run => python get_data.py
It will create "dataset.csv" csv file in dataset folder
4.	Run => python model.py

