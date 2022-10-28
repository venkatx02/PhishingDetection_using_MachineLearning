Check whether an URL is a Phishing URL or a Benign one.
1) Open the 'FeatureExtraction_URL.ipynb' file.
2) In the 'url' variable, Enter the URL you want to check.
3) Run all the cells.
4) In the end, you will get the feature array.
5) Now, go to 'XGBoostClassifier_PhishingDetection.ipynb' file.
6) Copy the feature array and paste it in the 'test_array' in 'XGBoostClassifier_PhishingDetection.ipynb' file.
7) Now, run all the cells.
8) If the output array contains 1, then the URL is phishing or if it contains 0, then the URL is benign and safe.
Thank you!
-Venkat
