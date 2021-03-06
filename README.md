# Credit Risk Analysis
The purpose of this analysis was to apply machine learning to solve the real-world challenge of analyzing credit card risk. In order to do this, I built and evaluated several machine learning models to see which would best predict credit risk. Machine learning algorithms like the ones used here could be used to help predict anomalies, reduce risk cases, monitor portfolios, and provide recommendations on what to do in cases of fraud.

## Results
### Random Over Sampler
- Accuracy: 0.6547
- Precision: 0.99
- Recall: 0.59

### SMOTE
- Accuracy: 0.662
- Precision: 0.99
- Recall: 0.69

### Cluster Centroids
- Accuracy: 0.545
- Precision: 0.99
- Recall: .40

### SMOTEEN
- Accuracy: 0.667
- Precision: 0.99
- Recall: 0.61

### Balanced Random Forest Classifier
- Accuracy: 0.789
- Precision: 0.99
- Recall: 0.87

### Easy Ensemble Classifier
- Accuracy: 0.932
- Precision: 0.99
- Recall: 0.94

|Model   | Accuracy   |Precision   |Recall   |F1   |
|:-:|:-:|:-:|:-:|:-:|
|Random Over Sampling   |0.655   |0.99   |0.59   |0.73   |
|SMOTE   |0.662   |0.99   |0.69   |0.81   |
|Cluster Centroid   |0.545   |0.99   |0.40   |0.56   |
|SMOTEEN   |0.667   |0.99   |0.61   |0.75   |
|Balanced Random Forest   |0.789   |0.99   |0.87   |0.93   |
|Easy Ensemble   |0.932   |0.99   |0.94   |0.97   |

## Summary
Based on the findings above, I would recommend going with the Easy Ensemble Model. It has the highest accuracy, recall, and F1 scores (.932, .94, and .97). All the models had very high precision .99 but the other scores for the models varied. Since this model is looking at credit card risk accuracy is more important than sensitivity. Higher sensitivity is more important when there are concerns about false negatives, such as medical tests. However, becasue the Easy Ensemble Method was the clear stand out and has both high accuracy, recall/sensitivity and F1, we do not need to worry about accuracy vs. sensitivity.
