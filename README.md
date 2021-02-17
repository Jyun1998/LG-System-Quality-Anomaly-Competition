# LG-System-Quality-Anomaly-Competition

## Topic
- Analyzed 16M unidentified system log records Jan 2021
- Predicted inconvenience of users from system quality changes

## Summerization
- EDA
  - PCA - elbow / silhouette method
  - t-SNE with litsm 
  - scaling - box-cox, minmax/standard scaler
  - memory reduction using pandas datatype byte-size 
  - Null processing
- Feature selection
  - filter method
   -   correlation with target
   -   pairwise correlation
   -   variance threshold
  - warpper method
   -   feature importance via permutation importance
   -   adversarial validation
  - embedded method
   -   decision tree embedded feature importance - lightgbm
- feature extraction
  - label encoding
  - onehot encoding
  - frequency encoding
  - cyclic encoding
  - pandas statistical aggregation
- modelling
  - AutoML
  - OOF Meta Modelling 

## Comment
- Lacks several codes since this repository only include code from me, not teammate's
