# World_Cup_Predictor
Developed binary classification pipeline in order to predict international football matches. I used 3 separate datasets for
this analysis. FIFA.com rankings since 1993, international match data dating back to 1873, as well as FIFA World Cup field data
in order to correctly simulate the stages as well as right teams for each match. I engineered 4 specific features from the 
available data which consisted of meaningfulness of the match (was it a Friendly or Tournament game?), point and rank 
differential, as well as average FIFA ranking.

# Binary Classification + Scoring Metric (AUC)
I used a binary classification model in this predictor which essentially shows whether a team wins or losses. What makes this
prediction algorithm unique is that I used an ROCAUC scoring metric to 'score' or check model performance. 

# Datasets:
https://www.kaggle.com/tadhgfitzgerald/fifa-international-soccer-mens-ranking-1993now
https://www.kaggle.com/martj42/international-football-results-from-1872-to-2017
https://www.kaggle.com/ahmedelnaggar/fifa-worldcup-2018-dataset

Please download the above datasets if you would like to replicate the above study yourself.


