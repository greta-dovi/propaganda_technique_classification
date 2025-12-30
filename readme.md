##### Structure:
`parse_raw_data.ipynb` - parses raw data into propaganda fragments and corresponding propagnda techniques, creates a new .csv file. 

`eda.ipynb` - performs exploratory data analysis (distribution of propaganda techniques, etc.), evaluates the propaganda technique co-occurence, prepares new .csv file that would contain only single-label propaganda fragments. 

`plm_finetuning.ipynb` - fine-tune all three models and evaluate on test set. Save the predictions of the best model for the XAI analysis. Extract raw litlat embeddings and perform weighted logreg on them. 

`xai.ipynb` - apply xai frameworks to the best model, evaluate its predictions. 

`visualizations.ipynb` - prepare various graphs. 