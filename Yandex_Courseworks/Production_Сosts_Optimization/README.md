# Metallurgical Plant Production Costs Optimization

## Project Description

* **EDA**. Processing of anomalies, omissions and generation of new features based on the available data. Compilation of a single dataframe with the key index.
* **Modeling**. Splitting into test and training samples. Drawing up a pipeline and calculating the target on several models.
* **Debugging**. Feature correction, cross-validation and selection of hyperparameters for the best model. Checking on the constant model sklearn.dummy.DummyRegressor.
* **Drawing up a report**. Determination of the main features that affect the temperature.

## Data

* data_arc.csv - electrode data;
* ata_bulk.csv - data on the supply of bulk materials (volume);
* data_bulk_time.csv - data on the supply of bulk materials (time);
* data_gas.csv - data on alloy gas purge;
* data_temp.csv - temperature measurement results;
* data_wire.csv - data on wire materials (volume);
* data_wire_time.csv - data on wire materials (time).

## Libraries used

- pandas
- numpy
- seaborn
- sklearn
- matplotlib
- lightgbm
- catboos
- optuna