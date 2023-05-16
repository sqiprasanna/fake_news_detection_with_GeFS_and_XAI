## Fake News Detection using Genetic Algorithm-based feature selection and Explainable AI

#### Problem Definition
* The project focuses on addressing the problem of fake news by developing a comprehensive fake news detection system. Fake news(FN) has become a pervasive issue, especially with the rise of social media and online platforms. It has potential to spread rapidly and influence public opinion, leading to significant consequences such as misinformation, political manipulation, and social unrest.
* The primary objective of this project is to leverage advanced techniques in deep learning, feature selection, and explainable AI to accurately detect fake news articles. The project aims to go beyond traditional fact-checking methods and manual source verification, which may not be sufficient given the scale and speed at which fake news is disseminated in the digital age.
* By leveraging the power of deep learning models, such as LSTM (Long Short-Term Memory) - CNN (Convolutional Neural Network), and BERT (Bidirectional Encoder Representations from Transformers), seeks to analyze various features and metadata associated with news articles. These models have demonstrated remarkable capabilities in natural language processing tasks and can effectively capture the complex patterns and cues that distinguish between real and fake news.
* To further enhance the system's performance and reduce computational complexity, we incorporate genetic algorithm-based feature selection. Genetic algorithms mimic the process of natural selection to identify the most informative features for fake news detection. By selecting the optimal subset of features, the system can improve its accuracy and efficiency.
* Additionally, we aim to provide explainability in the decision-making process of the models. By employing techniques such as SHAP (SHapley Additive exPlanations), the system will provide insights into the relative importance of different features and their impact on the classification of news articles. This explainable AI aspect enhances transparency and helps users understand the reasons behind the system's predictions, fostering trust and credibility.


#### Algorithms used
* ML ALgorithms: Logistic Regression, K-Nearest Neighbors (KNN), Random Forest, and XGBoost
* DL ALgorithms: CNN-LSTM and BERT

#### Packages installed
* tensorflow
* keras
* pandas
* numpy
* gensim
* scikit-learn
* nltk
* seaborn
* xgboost