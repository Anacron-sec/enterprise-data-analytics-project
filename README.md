# Apache Spark Pyspark for online predictions
Machine Learning Project for Enterprise data analytics class using PySpark.

## Install dependencies
To install dependencies just create a conda environment from the provided environment.yml like this

```
conda env create -f environment.yml
```

## Structure
The repository has the following structure
  - *data/* : this folder contains the original dataset plus some other intermediary transformations (big files are omitted, you need to recreate them using the notebooks)
  - *notebooks/* : all the notebooks using during experimentation
  - *predictions/* : the final predictions results in csv format
  - *references/* : references about the data
