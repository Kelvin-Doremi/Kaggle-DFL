# Kaggle-DFL

## Note:

There is an idea to complete the task of the competition which this code will show to you. The idea is that first, extract the position informations of footballs and persons by YOLO, and then use these data to predict events by a LSTM model. So far, the effect of this method is not good, but I think this method will be effective. So, I put it here and find another time to improve it in the future.



## Direction:

1. Download the **input** file from the follow web: https://www.kaggle.com/competitions/dfl-bundesliga-data-shootout/data
2. Run the **generate.sh** to generate all the csv files which contains position informations of footballs and persons in the videos.
3. Then open the **working** document, you can use the **LSTM_train.ipynb** to train your model and use the **test.ipynb** to test your model.
