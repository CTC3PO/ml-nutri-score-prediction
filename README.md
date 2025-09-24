# Predicting Nutri-Score and Global Applicability
a machine learning project that combines Open Food Facts and World bank data to assess and recommend nutri-score system adoption globally


For this project, we utilize the Open Food Facts database as our primary dataset, with the goal of predicting the Nutri-Score — a simplified food labeling system that reflects the nutritional quality of food products. Nutri-Score was first introduced in France and is now recommended by several European Union countries. It assigns a grade from A (healthiest) to E (least healthy) based on nutrient composition.

- ## Project Objectives:

    Build a supervised classification model to predict Nutri-Score using nutritional features from the dataset.
    Identify suitable countries for Nutri-Score adoption by analyzing external datasets from the World Bank.

- ## Nutri-Score Prediction:
  We developed and evaluated multiple classification models. The best performance was achieved by XGBoost, which reached a test accuracy of 97.84%. This model can be used to assign recommended Nutri-Scores to unlabeled food products.

- ## Global Applicability:
  To assess international applicability, we conducted a complementary analysis using World Bank data. Based on this, we identified the United States as a suitable candidate for Nutri-Score implementation — The 96.8/100 suitability score for the US exemplifies how data integration reveals non-obvious opportunities - despite being wealthy, the US shows concerning health metrics (high obesity, low food quality scores) that justify intervention, while its 173k analyzed products represent the largest potential market impact globally.

- ##Impact:
  With a high-performing model and evidence-based global insights, this project supports the extension of Nutri-Score to new markets, helping consumers make healthier dietary choices worldwide.
