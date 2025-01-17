# NMA-DL-Project
Abstract

As the healthcare industry increasingly relies on artificial intelligence for diagnostic support, this study evaluates the performance of several predictive models—BioBERT, BioGPT, a simple neural network, XGBoost, and K-Nearest Neighbors (KNN)—in diagnosing diseases based on symptoms. The primary focus is the classification accuracy of these models in diagnosing diseases from symptom lists. We aimed to identify the model with the highest diagnostic accuracy, hypothesizing that large language models (LLMs) such as BioBERT and BioGPT would outperform traditional models.

We utilized a dataset encompassing 527 diseases and 21,378 symptoms across 26,349 entries, restricting our analysis to diseases with at least 50 entries and balancing representation by capping each disease at 50 entries. Symptoms and diseases were encoded appropriately for compatibility with each model, and performance was evaluated based on prediction accuracy. BioBERT achieved the highest accuracy at 87%, followed by KNN at 81%, the neural network at 78%, and XGBoost at 79%. Due to computational limitations, BioGPT's accuracy could not be assessed.

The results support our hypothesis, indicating that BioBERT excels in disease prediction. However, the model failed to achieve higher accuracies, possibly due to the dataset's similarity and indistinguishability of symptoms, which contributed to prediction errors. This issue could be mitigated with a more specific symptom list. BioBERT demonstrates superior performance in disease prediction but is constrained by computational limitations and symptom specificity.

