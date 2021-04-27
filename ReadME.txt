Project link: https://archive.ics.uci.edu/ml/datasets/Bank+Marketing
For this project we will try to determine the accuracy of a trained machine in giving bank loans depending on the input datas.
For the input data we will drop the we will select the entities/inputs where the data is not "unkown".
Some categories(columns) contain too many "unknowns"(example: contact) or containing irrelevant information, so they had to be dropped.
Some entities(rows) were missing mandatory information (a good example being the job) and they had to be dropped.
At the end of the data filtering we will try to train our machine to give loans accordin to age, job, marital status, education,default, balance, housing and active loans.
The main algorithm used is knn(k-nearest neighbors algorithm) method alongside distance metrics: Minkowski Distance and Manhattan Distance , in order to obtain different result and more accurate one.
The results will be desplayed in labels and are easy to interpret.



Pro: in order to obtain faster results all the remaining datas after filtering , where mapped in results between 0 and 1 using MinMaxScaler.
https://scikit-learn.org/stable/modules/generated/sklearn.preprocessing.MinMaxScaler.html