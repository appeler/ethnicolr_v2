### Ethnicolr 2023 Paper Replication Materials

### Data

* [FL 2022 Voter Registration Data](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/UBIG3F)

### Scripts

1. Data Preprocessing
	* [Full Name](notebooks/0.1_data_preprocessing_FullName.ipynb)
	* [Last Name](notebooks/0.2_data_preprocessing_LastName.ipynb)

2. Random Forest
	* [Full Name Rapids Unigram](notebooks/1.0_rf_rapids_fullname_unigrams.ipynb)
	* [Full Name (with bigram)](notebooks/1.1_rf_fullname.ipynb)
	* [Last Name](notebooks/1.2_rf_lastname.ipynb)

3. Gradient Boosting
	* [Full Name](notebooks/2.1_gb_fullname.ipynb)
	* [Last Name](notebooks/2.2_gb_lastname.ipynb)

4. LSTM
	* [Full Name](notebooks/3.1_lstm_fullname.ipynb)
	* [Last Name](notebooks/3.2_lstm_lastname.ipynb)

5. Transformer
	* [Full Name](notebooks/4.1_transformer_fullname.ipynb)
	* [Last Name](notebooks/4.2_transformer_lastname.ipynb)

6. KNN Cosine Distance
	* [Full Name](notebooks/6.1_knn_fullname.ipynb)
	* [Last Name](notebooks/6.2_knn_lastname.ipynb)
	* See also [Github Repository](https://github.com/appeler/edit_names) for stuff like LSH Minhash implementation.

7. Multi Output Regression
	* [Last Name](notebooks/5.2_multioutput_regressor_lastname.ipynb)

8. LSTM with Synthetic Data Last Name
	* [Synthetic Data](notebooks/8.0_lastname_variations.ipynb). Output [here](data/name_variations.csv)

9. Validation

10. Application

11. Interpretation

12. [Create Tables](notebooks/create_tables.ipynb)

### Models

* [Models](models/)
	- Excludes large RF models. We don't see the point of including models that are not very computationally expensive but have very large model files.

### Tables

* [Tables](tabs/)

### MS

* [Manuscript](ms/)

### History

The 2018 version of the paper and pres. is [here](old_paper_and_pres/).

### Authors

Rajashekar Chintalapati, Suriyan Laohaprapanon, and Gaurav Sood