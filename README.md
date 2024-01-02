1. Initial Observations:
    - No of Feature 
    - Name of Class
    - Visualizations(seaborne, matplotlib)

 
2. Data Preprocessing:
    - Null handling
    - Encoding
         - Label Encoder
         - One Hot Encoder
         - Ordinal Encoder
         - Imbalance or not -- Sampling (Oversampling, undersampling)
    - Duplicate Removal (Optional)
    - Scaling
        - MinMaxScaler (Normalization)
        - StandardScaler (Z - score)
        - RobustScaler
        - Log Transform (FunctionTransformer)/ Box Cox
        - MaxAbsoluteScaler

Train-Test Split:
    - Cross Validation(Hold Out, K-fold,stratify, LOOCV)





ML LifeCycle:
Feature Selection(Correlation Matrix, PCA, Wrapper, Embedded Methods, Filter Method, Select K best) -> Data Preprocessing -> Split(Train-Test) -> ML model Implement -> Accuracy Matrix -> Imbalance Check(Data Check) -> Sampling Method(Over Sampling, Under Sampling, Resampling) -> Ml Model -> Accuracy Test
