# NLP_PROJECT_CS4650

### ABSTRACT

This paper works through pre-trained BERT model and its application in social media hate speech detection for multiple languages. The paper aims to leverage the lexical similarity between two different languages to solve the problem of unavailability of annotated low re- source data. The experiment is performed on 4 languages - English, French, Spanish and Ger- man. Lexical Similarity Index (SI) is based on literature. In linguistics, lexical similarity is a measure of the degree to which the word sets of two given languages are similar. We here pro- pose that English German with SI 0.6 will per- form better than English French with SI 0.27. Similarly, French Spanish with SI 0.75 should perform better than French-German 0.29 SI. We chose transfer learning as our method to train a pre-trained multilingual BERT from one language to another language. The results are then compared for how lexical similarity af- fects the performance for Hate Speech Detec- tion. The paper will discuss the benefits of our approach and shortcomings that needs to be rectified in future scope. We were able to find that English supported Other languages in sync with the lexical similarity, but French could not. 

### To run the code
Simply put open the colab files in Google Colab https://colab.research.google.com/. Hit Run All Cells. But for this you will need to mount the google drive.
And Make sure that this path exists in Google Drive - /content/gdrive/MyDrive/NLP Project/model_pt (where all the models will be saved and loaded from).
You need to store the dataset in google drive at paths
- French : /content/gdrive/My Drive/NLP Project/data/french_tweets-003.csv
- English : /content/gdrive/My Drive/NLP Project/data/2019/english_dataset/english_dataset_2019.csv
- German : /content/gdrive/My Drive/NLP Project/data/2019/german_dataset/german_dataset_2019.csv
- Spanish : /content/gdrive/My Drive/NLP Project/data/spanish_dataset/spanish_dataset.csv

All the graphs and numbers will be generated in the same manner as shown in the individual notebooks.

Here you can find Baselines in folder ```Baselines```
And all the transfer learning models performed in fodler ```Transfer Learning```

The format of notebook name ```1_French | 2_Sp_Ger``` means - French Based Transfer Learning with Spanish and German as second languages.

Code is an adaption of the work by Radhika Mamidi Suman Dowlagar. 2021. Using bert and multilingual bert models for hate speech detec- tion.
https://github.com/suman101112/hasoc-fire-2020.
