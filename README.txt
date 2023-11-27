1. The environement used was anaconda on my local 16gb ram laptop

2. All files should reside in one folder

3. Run the codes in the following manner:

	a) 1_BASELINES_Final-HIST.ipynb (approx 5 minutes)-this generates "HIST.csv" file
	b) 1_BASELINES_Final-LGBM.ipynb (approx 3 minutes)-this generates "LGBM.csv" file
	c) ENSEMBLE.ipynb (approx 1 minute)-this generates "LGB_REDUCED_50_-HIST_100_.csv" file

4. This should be able to generate

NB:
	If you would wish to generate the "test_df.csv" and "train_df.csv" used in this work, you may wish to run the "Data Prep.ipynb" 
	This was run on free kaggle GPUP100 because of the challenges the free google colab gpu posed.