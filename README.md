# Traffic-Congestion-forecasting
this project aims to forecast twelve-hours of traffic flow in a major U.S. metropolitan area. Time, space, and directional features give you the chance to model interactions across a network of roadways.

Files and Field Descriptions
train.csv - the training set, comprising measurements of traffic congestion across 65 roadways from April through September of 1991.
row_id - a unique identifier for this instance
time - the 20-minute period in which each measurement was taken
x - the east-west midpoint coordinate of the roadway
y - the north-south midpoint coordinate of the roadway
direction - the direction of travel of the roadway. EB indicates "eastbound" travel, for example, while SW indicates a "southwest" direction of travel.
congestion - congestion levels for the roadway during each hour; the target. The congestion measurements have been normalized to the range 0 to 100.
test.csv - the test set; you will make hourly predictions for roadways identified by a coordinate location and a direction of travel on the day of 1991-09-30.
sample_submission.csv - a sample submission file in the correct format

https://www.kaggle.com/competitions/tabular-playground-series-mar-2022/data

https://www.kaggle.com/code/ambrosm/tpsmar22-eda-which-makes-sense/notebook
