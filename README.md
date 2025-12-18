📝 Introduction
This project describes the deployment and results of a machine learning process designed to identify whether news articles are REAL or FAKE. The study combines AI technology with human behavioral science to address four main goals:


Detection and Precision: Building a technical model optimized for accuracy.


User Education: Helping users improve their perception of honesty online.


Vulnerability Analysis: Studying how different demographic groups react to various news forms.


Trust Assessment: Researching human trust in AI versus other humans regarding false news.

⚙️ Methodology

Data Source: A labeled dataset of news articles acquired from Kaggle.


Preprocessing: Included lower-casing, removing URLs, and eliminating stop words.


Model: Utilized a Passive Aggressive Classifier (PAC) for high efficiency in processing sparse text.


Feature Engineering: Applied TF-IDF Vectorizer with bigram extraction.

📊 Performance Analysis
The model achieved high accuracy and reliability in testing:


Accuracy: 94.16%.


Precision (REAL): 0.94 (94% of articles labeled REAL were truly real).


AUC Value: 0.98, ensuring the authenticity of AI trust markers.

🔍 Key Findings (Linguistic Markers)
The model identifies truthfulness based on specific weighted patterns:


REAL News Indicators: Professional attribution words like "said" and "state".


FAKE News Indicators: Sensationalistic or click-to-share terms like "October" and "share".

🚀 Future Work

Deployment: Integrating the model into a web service using the saved .pkl file.


External Surveys: Implementing human studies to further explore Trust and Vulnerability variables.
