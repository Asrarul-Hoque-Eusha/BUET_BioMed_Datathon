# BUET_BioMed_Datathon

**We have participated in BUET BioMed Datathon 2024 and secured 10th position.** 

### Problem Description
The BioMed Datathon challenges participants to develop AI algorithms capable of accurately diagnosing cardiovascular diseases (CVD) from heart sound recordings. Leveraging the BUET Multi-disease Heart Sound (BMD-HS) Dataset, participants must predict the presence of common valvular abnormalities, including **Aortic Stenosis (AS), Aortic Regurgitation (AR), Mitral Stenosis (MS), and Mitral Regurgitation (MR)**, along with identifying **normal cardiac states**. With multi-label annotations, participants are challenged to develop algorithms that can effectively discern between different cardiac conditions solely from audio data. By successfully addressing this problem, participants contribute to advancing automated CVD diagnosis, particularly in underserved regions, and support the development of AI-driven diagnostic tools for improved healthcare outcomes.

### Our Approach
At first, we made all of the audios with the same length of 20 seconds. Then we have extracted features like MFCC and Delta MFCC, along with ZCR, centroid, bandwidth, and the concatenated mean of all these extracted features. Which is further fed into several ML and DL models to predict multilabel common valvular abnormalities. We have explored several ML and DL models to identify the common valvular abnormalities. Such as:

**ML Models:**
1. Decision Tree (DT)
2. Random Forest (RF)
3. Logistic Regression (LR)
4. Extreme Gradient Boosting (XGB) and
5. Ensemble of DT, RF, and LR

**DL Models:**
1. ANN and
2. CNN
