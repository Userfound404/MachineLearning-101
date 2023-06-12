# MachineLearning-101

### This repository is a collection of all end-to-end machine learning projects I'm doing

## Magic-Telescope-Dataset
the data is taken from link(https://archive.ics.uci.edu/dataset/159/magic+gamma+telescope)

The data are MC generated to simulate registration of high energy gamma particles in a ground-based atmospheric Cherenkov gamma telescope using the imaging technique. Our labels are either gamma or hardon, so It's a binary classification.

Here are the results of the different models.

1. **KNN** -        
 |  measure   | precision     | recall  | f1-score  | support |
|---------------|---------|-----------|-----------------|
|           0   |   0.78  |   0.67    | 0.72    |   1338|
|           1   |   0.83  |   0.90    | 0.86    |  2466 |
|     accuracy  |         |           |  0.82   |   3804|
|    macro avg  |    0.81 |   0.78    | 0.79    |  3804 |
| weighted avg   |   0.81  |  0.82    | 0.81   |  3804  |

 2. **Naive bayes** - 
 | measure  | precision     | recall  | f1-score  | support |
|---------------|---------|-----------|-----------------|
|           0   |   0.63 |   0.39   | 0.48   |   1338|
|           1   |   0.73  |   0.88    | 0.79    |  2466 |
|     accuracy  |         |           |  0.71   |   3804|
|    macro avg  |    0.68 |   0.63    | 0.64    |  3804 |
| weighted avg   |   0.69  |  0.71    | 0.68  |  3804  |

3. **Logistic Regression** -
 |measure   | precision     | recall  | f1-score  | support |
|---------------|---------|-----------|-----------------|
|           0   |   0.67 |   0.72   | 0.69   |   1338|
|           1   |   0.84  |   0.81    | 0.83    |  2466 |
|     accuracy  |         |           |  0.78  |   3804|
|    macro avg  |    0.76 |   0.76   | 0.76   |  3804 |
| weighted avg   |   0.78  |  0.78    | 0.78  |  3804  |

4. **SVMs** - 
 |measure    | precision     | recall  | f1-score  | support |
|---------------|---------|-----------|-----------------|
|           0   |   0.81 |   0.79   | 0.80   |   1338|
|           1   |   0.89  |   0.90    | 0.89    |  2466 |
|     accuracy  |         |           |  0.86   |   3804|
|    macro avg  |    0.85 |   0.84    | 0.85    |  3804 |
| weighted avg   |   0.86  |  0.86    | 0.86  |  3804  |

5. **Neural networks** -  
 |  measure   | precision     | recall  | f1-score  | support |
|---------------|---------|-----------|-----------------|
|           0   |   0.85 |   0.75     | 0.80   |   1338|
|           1   |   0.87  |   0.93   | 0.90    |  2466 |
|     accuracy  |         |           |  0.87   |   3804|
|    macro avg  |    0.86 |   0.84    | 0.85    |  3804 |
| weighted avg   |   0.86  |  0.87    | 0.86  |  3804  |

I've provided a brief explanation in the python notebook on how the algorithms work


