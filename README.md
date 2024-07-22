# SIFTastic: Unveiling Reality: SIFT Applications for Visual Classification

**Github Repository for CSL7360 Computer Vision Course**

Our project is based on SIFT and how it can be used in multiple ways. Main Target problems are
1.  **SIFT for Visual Classification** : Using bag of visual words classfication technique
2.  **SIFT for Image Retrieval** : Using bag of visual words classfication technique
   
> Note: Save the bag of visual works to be reused again and again.

## Setup

Before running any part of the application, ensure you have Python installed along with the necessary libraries:

```
pip install -r requirements.txt
```
## Running the application

### Visual Classification
To start the visual classification module, run the following script:
```
python3 BOVWC.py
```


## Results 

### Visual Classification
- Feature Detection Algorithm = SIFT
- Clustering Algorithm = KMeans
- Classifier = SVM

**Accuracy**

| k | kernel_type | Accuracy |
|---|-------------|----------|
| 50 | linear | 54.3 |
| 50 | precomputed | 52.4 |
| 100 | linear | 54.3 |
| 100 | precomputed | 56.7 |

