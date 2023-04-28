# Classification of COVID-19 and political misinformation on social media

This is the code base for "Classification of COVID-19 and political misinformation on social
media", the final project of CS7650 Natural Language at Georgia Tech.

## Folder structure

`CS7650_final.ipynb`: contains code for fine-tuning BERT.

`KNN.ipynb`: contains code for kNN.

`data/`: contains the preprocessed train/valid/test splits of the four misinformation datasets we used in our project.

## Datasets

We used four misinformation datasets in our project. The data sources are listed as below:
- LIAR: https://www.cs.ucsb.edu/~william/data/liar_dataset.zip
- Political News: https://github.com/rpitrust/fakenewsdata
- Rumor: https://github.com/MickeysClubhouse/COVID-19-rumor-dataset
- CONSTRAINT: https://constraint-shared-task-2021.github.io/

We have proccessed the raw data provided in the datasets and organized them into `data/`.
