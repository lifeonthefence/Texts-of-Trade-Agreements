# Texts of Trade Agreements
This project looked at texts of trade agreements to determine if the way the texts are written have any impact on trade flows.
We used natural language processing to extract features from the text, such as K-means and ULMFiT. This included length, unique words, proportion of text written about specific topics, and how nice the language was.
We ran regression to establish causal links between features of the text and trade flows, which found that there were limited effects of features from the text on trade flows. These were robust to the addition of controls.
We also ran prediction to see how well the variables from the gravity dataset and features from the text predicted change in trade flows. We used Shapley values to interpret the results. Some features, such as proportion of text written about rules of origins had a small, but positive influence on trade. These results were not robust, and there were concerns of overfittiing.

### Data sources:
Texts of Trade Agreements: https://github.com/mappingtreaties/tota
CEPII Gravity Dataset: http://www.cepii.fr/CEPII/en/bdd_modele/presentation.asp?id=8

### Authors:
David Chen
Will Lau
Jiwoo Bae
Shanjun Zhu
