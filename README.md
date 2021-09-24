# Pump it Up, Data Mining the Tanzania Water Table

Github link :  https://github.com/Zameelnm96/Pum-it-UP-Zameel

## Data pre-processing and feature engineering

To explore all of the columns in the data I used PandasProfiling. 
- The given data contains large amount of missing datas so I impute with 0 and missing column with mean value. Imputing data  would've altered the data too much. 
- converted boolean columns to strings and categorical columns to integers using LabelEncoder().
- replaced NaN values with explicit 'nan'.
- drop the column with same value.
- I normalized all the data columns using StandardScaler()
- Finally I used  Random forest model for training





# Submission and Ranking


![image](https://user-images.githubusercontent.com/47120059/134738304-0624ebf8-d2bb-4638-802a-47c422428bdb.png)

