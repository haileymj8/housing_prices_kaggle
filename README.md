# housing_prices_kaggle
Kaggle project for DSCI 478 at CSU. 

Group members: Hailey Johnson, Nathan Mitchell, Katie Myers.

For our project, we have two different files for our different models. First is our R file which is named "lasso_and_ridge.Rmd" which contains our LASSO and Ridge Regression approaches, as well as a visualization of home sales prices. In order to run this file, you will need to download "train.csv" and "test.csv" and put them in the same folder as the RMD in order to get it to run in R. Second is our Python file which is named "Housing_Prices.ipynb" which contains our Random Forest and Neural Network approaches. In order to run this file, you will need to move "train.csv" and "test.csv" into your Google Drive (your home drive, no folder necessary) and then run the Google Colab notebook as displayed. Please let us know if you have any issues with the data loading process and we will be happy to help you.

One final thing we wish to note is that the Jupyter Notebook may take a while to run because of the grid search for the optimal parameters. To sidestep this, the notebook has all of our output and final RMSEs printed out for you to view. Because we did not use a seed, these numbers may change should you choose to run the notebook for yourself. We note this, and what the fluctuations mean for our results, in our final paper, which lists our approach and results as well as all of the sources that we used and is attacted in this repository.
