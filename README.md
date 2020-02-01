# Home Credit Default Risk

## Can you predict how capable each applicant is of repaying a loan?

More information about the competition, its data files, and features can be found on the [competition website](https://www.kaggle.com/c/home-credit-default-risk).

I did not enter this competition. I instead learned a great deal from the various notebooks that 
were shared with the community whilst the competition was ongoing and after it had ended. I 
believe that this competition is a great case study on how to handle a large amount of data (>10000000 rows)
spread across multiple tables and using scalable ML algorthims that work well with large volumes of data.

The feature engineering I performed was heavily inspired by [this notebook](https://www.kaggle.com/willkoehrsen/start-here-a-gentle-introduction) and 
[this one](https://www.kaggle.com/jsaguiar/lightgbm-with-simple-features) but was not exactly replicated as I experimented with the different
aggregation statistics that could be produced when combining the tables. However feature engineering and getting a high LB score was not a priority for this project; I am not a credit expert and my submissions were for knowledge purposes only.
I instead focused on learning and reproducing the techniques for combining the large amounts of data that was available
and using scalable ML algorithms (specifically LightGBM) to make predictions.

I also implemented a form of Automatic Hyperparameter Tuning using the [HyperOpt](https://github.com/hyperopt/hyperopt) library,
the pipeline of which is transferable and can be used to tune any ML algorithm. 
