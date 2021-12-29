I create a pareser that scrape data from Flipkart and store it in csv formate and perform analysis.
Normalize rating
4.2    0.458333
4.3    0.347222
4.4    0.097222
4.1    0.083333
5      0.013889

Predicting expected rating for every device according to there specification using RandomForestClassifier
And try to find device which is above 4 star rating 

if ret>4:
pos=(new_df['Product_Name'] +'  Positive')
elif ret<4 and ret >3.5:
avg=(new_df['Product_Name'] +'Average')
else:
neg=(new_df['Product_Name'] +'Not good')
