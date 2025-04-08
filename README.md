# Dummy Data for Data Science Classes

## User Knowledge Modeling Dataset

`1-user_knowledge.csv`: This dataset has 403 rows and 6 columns. This dataset
relates to learning efforts and knowledge levels of participants in a
corporate training course.

| #  | Name | Refined Definition                                                                                                                        | Data Type    |
|----|------|-------------------------------------------------------------------------------------------------------------------------------------------|--------------|
| 1  | STG  | **Study Time on Goal Material** – How much time a participant spends studying the test material.                                          | Quantitative |
| 2  | SCG  | **Study Count on Goal Material** – How often a participant reviews or repeats the test material.                                          | Quantitative |
| 3  | STR  | **Study Time on Related Material** – How much time a participant spends learning content related to, but not  part of, the test material. | Quantitative |
| 4  | LPR  | **Performance on Related Practice** – How well a participant performs on quizzes related to the subject but not on the main goal content. | Quantitative |
| 5  | PEG  | **Performance on Exam Goals** – How well a participant scores on questions that assess the main learning objectives.                      | Quantitative |
| 6  | UNS  | **User Knowledge Level** – A label that reflects the participant's overall understanding.                                                 | Qualitative  |

## Car Evaluation Dataset

`2-car_acceptance.csv`: The data set has 1728 rows and 7 columns in which car
attributes such as price and technology are described across 6 attributes such
as *Buying Price*, *Maintenance*, and *Safety* etc.

| #  | Name     | Definition                                                       | Data Type    |
|----|----------|------------------------------------------------------------------|--------------|
| 1  | buying   | Buying price of the car (thousand USD)                           | Quantitative |
| 2  | maint    | Price of the maintenance of car (thousand USD)                   | Quantitative |
| 3  | doors    | Number of doors (2, 3, 4, 5-more)                                | Qualitative  |
| 4  | persons  | Capacity in terms of persons to carry (2, 4, more)               | Qualitative  |
| 5  | lug_boot | Indicator whether the car has a large luggage boot (TRUE, FALSE) | Qualitative  |
| 6  | safety   | Estimated safety of the car (low, med, high)                     | Qualitative  |
| 7  | class    | Car acceptability (0: unacceptible, 10: very good)               | Quantitative |

## Online News Popularity Dataset

`3-online_news_popularity.csv`: This dataset has 39644 rows and 61 columns. This
dataset summarizes a heterogeneous set of features about articles published by
Mashable in a period of two years.

| #  | Name                         | Definition                                                                | Data Type    |
|----|------------------------------|---------------------------------------------------------------------------|--------------|
| 1  | URL                          | URL of the Article                                                        | Qualitative  |
| 2  | Timedelta                    | Days Between the Article Publication and the Dataset Acquisition          | Quantitative |
| 3  | N_Tokens_Title               | Number of Words in the Title                                              | Quantitative |
| 4  | N_Tokens_Content             | Number of Words in the Content                                            | Quantitative |
| 5  | N_Unique_Tokens              | Rate of Unique Words in the Content                                       | Quantitative |
| 6  | N_Non_Stop_Words             | Rate of Non-Stop Words in the Content                                     | Quantitative |
| 7  | N_Non_Stop_Unique_Tokens     | Rate of Unique Non-Stop Words in the Content                              | Quantitative |
| 8  | Num_Hrefs                    | Number of Links                                                           | Quantitative |
| 9  | Num_Self_Hrefs               | Number of Links to Other Articles Published by Mashable                   | Quantitative |
| 10 | Num_Imgs                     | Number of Images                                                          | Quantitative |
| 11 | Num_Videos                   | Number of Videos                                                          | Quantitative |
| 12 | Average_Token_Length         | Average Length of the Words in the Content                                | Quantitative |
| 13 | Num_Keywords                 | Number of Keywords in the Metadata                                        | Quantitative |
| 14 | Data_Channel_Is_Lifestyle    | Is Data Channel 'Lifestyle'?                                              | Quantitative |
| 15 | Data_Channel_Is_Entertainment| Is Data Channel 'Entertainment'?                                          | Quantitative |
| 16 | Data_Channel_Is_Bus          | Is Data Channel 'Business'?                                               | Quantitative |
| 17 | Data_Channel_Is_Socmed       | Is Data Channel 'Social Media'?                                           | Quantitative |
| 18 | Data_Channel_Is_Tech         | Is Data Channel 'Tech'?                                                   | Quantitative |
| 19 | Data_Channel_Is_World        | Is Data Channel 'World'?                                                  | Quantitative |
| 20 | Kw_Min_Min                   | Worst Keyword (Min. Shares)                                               | Quantitative |
| 21 | Kw_Max_Min                   | Worst Keyword (Max. Shares)                                               | Quantitative |
| 22 | Kw_Avg_Min                   | Worst Keyword (Avg. Shares)                                               | Quantitative |
| 23 | Kw_Min_Max                   | Best Keyword (Min. Shares)                                                | Quantitative |
| 24 | Kw_Max_Max                   | Best Keyword (Max. Shares)                                                | Quantitative |
| 25 | Kw_Avg_Max                   | Best Keyword (Avg. Shares)                                                | Quantitative |
| 26 | Kw_Min_Avg                   | Avg. Keyword (Min. Shares)                                                | Quantitative |
| 27 | Kw_Max_Avg                   | Avg. Keyword (Max. Shares)                                                | Quantitative |
| 28 | Kw_Avg_Avg                   | Avg. Keyword (Avg. Shares)                                                | Quantitative |
| 29 | Self_Reference_Min_Shares    | Min. Shares of Referenced Articles in Mashable                            | Quantitative |
| 30 | Self_Reference_Max_Shares    | Max. Shares of Referenced Articles in Mashable                            | Quantitative |
| 31 | Self_Reference_Avg_Sharess   | Avg. Shares of Referenced Articles in Mashable                            | Quantitative |
| 32 | Weekday_Is_Monday            | Was the Article Published on a Monday?                                    | Quantitative |
| 33 | Weekday_Is_Tuesday           | Was the Article Published on a Tuesday?                                   | Quantitative |
| 34 | Weekday_Is_Wednesday         | Was the Article Published on a Wednesday?                                 | Quantitative |
| 35 | Weekday_Is_Thursday          | Was the Article Published on a Thursday?                                  | Quantitative |
| 36 | Weekday_Is_Friday            | Was the Article Published on a Friday?                                    | Quantitative |
| 37 | Weekday_Is_Saturday          | Was the Article Published on a Saturday?                                  | Quantitative |
| 38 | Weekday_Is_Sunday            | Was the Article Published on a Sunday?                                    | Quantitative |
| 39 | Is_Weekend                   | Was the Article Published on the Weekend?                                 | Quantitative |
| 40 | Lda_00                       | Closeness to Lda Topic 0                                                  | Quantitative |
| 41 | Lda_01                       | Closeness to Lda Topic 1                                                  | Quantitative |
| 42 | Lda_02                       | Closeness to Lda Topic 2                                                  | Quantitative |
| 43 | Lda_03                       | Closeness to Lda Topic 3                                                  | Quantitative |
| 44 | Lda_04                       | Closeness to Lda Topic 4                                                  | Quantitative |
| 45 | Global_Subjectivity          | Text Subjectivity                                                         | Quantitative |
| 46 | Global_Sentiment_Polarity    | Text Sentiment Polarity                                                   | Quantitative |
| 47 | Global_Rate_Positive_Words   | Rate of Positive Words in the Content                                     | Quantitative |
| 48 | Global_Rate_Negative_Words   | Rate of Negative Words in the Content                                     | Quantitative |
| 49 | Rate_Positive_Words          | Rate of Positive Words Among Non-Neutral Tokens                           | Quantitative |
| 50 | Rate_Negative_Words          | Rate of Negative Words Among Non-Neutral Tokens                           | Quantitative |
| 51 | Avg_Positive_Polarity        | Avg. Polarity of Positive Words                                           | Quantitative |
| 52 | Min_Positive_Polarity        | Min. Polarity of Positive Words                                           | Quantitative |
| 53 | Max_Positive_Polarity        | Max. Polarity of Positive Words                                           | Quantitative |
| 54 | Avg_Negative_Polarity        | Avg. Polarity of Negative Words                                           | Quantitative |
| 55 | Min_Negative_Polarity        | Min. Polarity of Negative Words                                           | Quantitative |
| 56 | Max_Negative_Polarity        | Max. Polarity of Negative Words                                           | Quantitative |
| 57 | Title_Subjectivity           | Title Subjectivity                                                        | Quantitative |
| 58 | Title_Sentiment_Polarity     | Title Polarity                                                            | Quantitative |
| 59 | Abs_Title_Subjectivity       | Absolute Subjectivity Level                                               | Quantitative |
| 60 | Abs_Title_Sentiment_Polarity | Absolute Polarity Level                                                   | Quantitative |
| 61 | Shares                       | Number of Shares                                                          | Quantitative |
| 62 | High_Shares                  | Dummy indicator whether the article has been highly shared                | Qualitative  |

## Acknowledgements

All datasets were sourced from [Data Science Dojo](https://code.datasciencedojo.com/datasciencedojo/datasets).

### User Knowledge Data

This data set has been originally sourced from the Machine Learning Repository
of the University of California, Irvine [User Knowledge Modeling Data Set (UC Irvine)](https://archive.ics.uci.edu/ml/datasets/User+Knowledge+Modeling).
The UCI page mentions the following publication as the original
source of the data set: H. T. Kahraman, Sagiroglu, S., Colak, I., Developing
intuitive knowledge classifier and modeling of users' domain dependent data in
web, Knowledge Based Systems, vol. 37, pp. 283-295, 2013.

### Car Acceptance Data

This data set has been sourced from the Machine Learning Repository of
University of California, Irvine [Car Evaluation Data Set (UC Irvine)](https://archive.ics.uci.edu/ml/datasets/Car+Evaluation).
The UCI page mentions following as the donors of the dataset: Marko Bohanec
(marko.bohanec '@' ijs.si) and Blaz Zupan (blaz.zupan '@' ijs.si).

### Online News Popularity

This data set has been sourced from the Machine Learning Repository of
University of California, Irvine [Online News Popularity Data Set (UC Irvine)](https://archive.ics.uci.edu/ml/datasets/Online+News+Popularity).
The UCI page mentions the following publication as the original source of the
data set: K. Fernandes, P. Vinagre and P. Cortez. a Proactive Intelligent
Decision Support System for Predicting the Popularity of Online News.
Proceedings of the 17th EPIA 2015 - Portuguese Conference on Artificial
Intelligence, September, Coimbra, Portugal.
