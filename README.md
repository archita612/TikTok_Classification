<h1>TikTok Classification Capstone Project</h1>

<h2>Overview</h2>

<p>This project aims to develop a binary classification model to distinguish between claims and opinions in TikTok videos, as well as perform sentiment analysis on the textual content within the videos. The goal is to create an accurate model that can assist in content moderation and user trust by classifying TikTok videos as either "claims" or "opinions" based on their content, while also analyzing the sentiment of the text.</p>

<h2>Project Structure</h2>

<ul>
  <li><strong>Data Preparation:</strong> The dataset is preprocessed by encoding categorical variables, removing irrelevant features, and splitting into training, testing, and validation sets. Additionally, features like sentiment and polarity scores are added using natural language processing techniques.</li>
  
  <li><strong>Model Building:</strong> Several classification models are trained, including tree-based ensembles, Gradient Boosting, XGBoost, and Random Forest. Hyperparameter tuning is performed using grid search to optimize model performance.</li>
  
  <li><strong>Model Evaluation:</strong> Each model is evaluated using various performance metrics such as accuracy, recall, precision, and F1 score. Confusion matrices are generated to visualize model performance in classifying TikTok videos. Sentiment analysis results are also assessed for accuracy and relevance.</li>
  
  <li><strong>GitHub Repository:</strong> The project code, including data preprocessing, model building, and evaluation scripts, is available in this GitHub repository.</li>
</ul>

<h2>Results</h2>

<p>The best-performing model achieves high accuracy and recall in classifying TikTok videos. The confusion matrix provides insights into the model's performance in predicting "claims" and "opinions" in TikTok videos. </p>
