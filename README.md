# Jedha Bootcamp Essentials Project

The initial goal of this project was to predict the next unicorns based on their actual valuation and the total amount of funds raised at a time.

To do so, I've tried to merge two different datasets found on Kaggle (https://www.kaggle.com/datasets/niekvanderzwaag/unicorn-startups-cleaned and https://www.kaggle.com/datasets/chhinna/crunchbase-data).

Unfortunately, after the merge of the two datasets on the company name, the final dataset was very light (only 66 rows). The main problem was that in the first dataset I had the valuation but not the funding total and in the second I had the funding total but not the valuation (the "Fail.ipynb" file).

Finally, I've based my final project on trying to predict how much funds a company would raised (based on the Crunchbase dataset).

Neither of the four models made are functional, I've tried to play with the numeric and categorical features by interchanging columns between both but all results are the same at the end.

My assumptions are towards outliers that false the model results (I didn't get rid of them during the preprocessing) or it's completely impossible to determine how much funds a company would raised in the future (at least not with the actual data contained in the Crunchbase dataset).

A quick test with a Random Forest algorithm shows better results even though the gap between the train set and the test set is still abnormally huge.
