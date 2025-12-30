##### Structure:
`parse_raw_data.ipynb` - parse raw data into propaganda fragments and corresponding propagnda techniques, create a new updated .csv file. 

`eda.ipynb` - perform exploratory data analysis (distribution of propaganda techniques, etc.), evaluate the propaganda technique co-occurence, prepare new .csv file that would contain only single-label propaganda fragments. 

`plm_finetuning.ipynb` - fine-tune all three models and evaluate on test set. Save the predictions of the best model for the XAI analysis. Extract raw litlat embeddings and perform weighted logreg on them. 

`xai.ipynb` - apply xai frameworks to the best model, evaluate its predictions. 

`visualizations.ipynb` - prepare various graphs. 