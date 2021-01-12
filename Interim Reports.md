### Description
 Baseball is the most popular sport in Korean professional sports, and there are so many different records that it can be called the sport of record. As a result, the popularity of professional baseball's data analysis has increased, and the demand for the role of data science in various clubs in Korea is increasing. However, especially in baseball, the performance of certain players is very volatile, making it difficult to predict the performance of next season. I would like to build a model that can predict good enough to overcome this difficulty in prediction.

 Among baseball's numerous records, OPS is the sum of the batter's on-base rate and slugging rate, and is a representative indicator of the batter's score production. Therefore, I would like to predict the OPS of the 2019 season using the records of the past seasons.

### Data
- Regular_Season_Batter.csvPre_Season_Batter.csv : Basic information such as weight, height, and date of birth, including the performance of hitters who have been active in the KBO in the previous regular season
- Regular_Season_Batter_Day_by_Day_b4.csv : Regular season performance by date of batters who played an active part in KBO
- Pre_Season_Batter.csv : The performance of past demonstration games (practice games held just before the regular season) of hitters who played an active part in KBO
- submission.csv : List of batter's name and ID that participants should predict

### Evaluation
1. Data Cleansing
2. Visualization
3. Feature Engineering
4. Model Building
