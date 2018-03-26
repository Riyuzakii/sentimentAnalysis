# sentimentAnalysis
A binary classifier for twitter sentiment analysis.

To test,

  clone the repo: ``` git clone https://github.com/Riyuzakii/sentimentAnalysis ```
  
  run this command: ``` python preprocess.py ./dataset/train.txt ```
  
  The above command prepares the data for training and stores it in a .csv file in the ./dataset directory
  
  For obtaining the stats, run this command: ``` python stats.py ./dataset/train-processed.csv ```

The you can run any classifier, currently there's only SVM but I'll add more. The data was taken from ``` https://www.kaggle.com/c/si650winter11/data ```
  
