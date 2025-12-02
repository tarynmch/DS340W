# A Comparative Study of Machine Learning Models on Predicting Academic Outcomes 
The goal of this study is to understand the impact of open learning environment (OLE's) on student's academic success. Predicting academic success is crucial for improving student retention, providing early support, and allowing effective academic planning. We plan to compare the baseline data provided by the parent paper to an augmented version of the OULAD dataset. The datasets will be tested on three different machine learning models (Decision Tree, Random Forest Classifier, and XGBoost) to further our comparative analysis. Finally, feature importance will be analyzed as part of the comparative analysis for a more cohesive picture. 

## Installation Instructions
1. Download the assessments, studentAssessment, studentInfo, studentRegistration, and vle csv files. Additionally, download FinalCode.ipynb
2. Go to this website: https://analyse.kmi.open.ac.uk/open-dataset. Download the OULAD dataset and extract studentVle, placing it where you placed the previous csv files.
  (The data file was too large to upload to Github, so you need to do it individually. When you download the dataset from that website, it downloads all the data in a ZIP file. So you can use all the data from there rather than the files in GitHub or just extract the studentVle data).
3. Upload all data to Google drive (do not place it in any files).
4. Open a new notebook in Google Colab and import FinalCode.ipynb.
5. Run all the code, the provided code should ask to connect to your Google Drive. 

## How to Use Project
This project contains importing & cleansing data, data merging & EDA, creating an augmented dataset, machine learning methods on baseline data, and machine learning methods on augmented data. The code file is titled and sectioned appropriately to walk you through the findings. You can find a full analysis in our final paper. 

## Credits
The files Enhance Education Using Big Data-checkpoint.ipynb is the original code. The pdf ParentPaper is the paper that the code is based on. 
