Example of usage ML.NET library for spam detection problem. Presented solution categorize comments collected from YouTube into one of two categories: SPAM, OK. Data source is describe in the footer.

Main steps:
- Load data.
- Extract text features using `FeaturizeText` method.
- Train logistic regression classifier.
- Use cross validation for evaluation.

The mean accuracy of presented solution is about 0.95.

---
The YouTube Spam Collection has been created by Tiago A. Almeida and Tulio C. Alberto.
Data taken from: https://archive.ics.uci.edu/ml/datasets/YouTube+Spam+Collection
Also available here: http://dcomp.sor.ufscar.br/talmeida/youtubespamcollection/