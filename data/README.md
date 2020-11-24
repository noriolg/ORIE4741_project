## Data distribution

1. `initial data` contains datasets directly downloaded from the source without any cleaning or treatment.

2. `treated data` contains the datasets that will be used for model development and drawing conclusions. In this directory there are two kinds of .csv files:
	- clean
	- encoded
	They both have the same observations and information. The difference between them is that the encoded one has the corresponding one-hot encoding done for each of the features that need it.
	For better understanding and initial analysis, clean.csv should be chosen. However for model development, encoded.csv will be used.