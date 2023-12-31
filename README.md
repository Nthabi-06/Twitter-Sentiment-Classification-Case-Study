# Twitter Case Study: Leveraging Natural Language Processing for Sentiment Analysis on Climate Change-Related Tweets
Please be advised that, in compliance with project confidentiality requirements, I am unable to disclose the code used in this project publicly. However, I am more than willing to discuss the project's methodology, outcomes, and provide general insights without revealing specific code details.

# Context 
In the face of an apparent rise in skepticism surrounding climate change, companies that promote themselves as environmentally friendly or provide eco-conscious products face a challenging situation if they neglect thorough market research. To enhance ongoing market research endeavors, the development of a Machine Learning model becomes imperative. This model should be capable of discerning whether individuals believe in climate change or not, drawing insights from their unique tweet data.

# Dataset
The collection of this data was funded by a Canada Foundation for Innovation JELF Grant to Chris Bauch, University of Waterloo. The dataset aggregates tweets pertaining to climate change collected between Apr 27, 2015 and Feb 21, 2018. In total, 43,943 tweets were collected. Each tweet is labelled as one of 4 classes, which are described below.

Class Description :

- 2 News: the tweet links to factual news about climate change

- 1 Pro: the tweet supports the belief of man-made climate change

- 0 Neutral: the tweet neither supports nor refutes the belief of man-made climate change

- -1 Anti: the tweet does not believe in man-made climate change Variable definitions

# Project Workflow

- Data Loading: The training and test datasets (train.csv and test.csv) are loaded into the notebook using the pandas library.

- Data Preprocessing: The data is preprocessed to clean and prepare it for model training. This includes text cleaning, tokenization, removing stopwords, and optional stemming or lemmatization.

- Feature Engineering: Text data is transformed into numerical features using techniques like TF-IDF (Term Frequency-Inverse Document Frequency) or Count Vectorization.

- Model Training: Various machine learning models such as Logistic Regression, Random Forest, K-Nearest Neighbors, Naive Bayes, and Support Vector Machines are trained on the preprocessed data.

- Model Evaluation: The trained models are evaluated using performance metrics like accuracy, F1 score, and classification report. Cross-validation techniques like GridSearchCV can also be applied to optimize the model hyperparameters.

- Prediction and Deployment: The trained model can be used to predict the sentiment of new, unseen data. Once satisfied with the model performance, it can be deployed in a production environment for real-time sentiment analysis.

# Expected Outcomes
- Analyze Twitter Trends
- Construct a Sentiment Classification Model for Climate Change
- Engineer a User-Friendly Application for Model Deployment
- Deliver Insights to Key Stakeholders

# Dependencies

The following libraries are required to run the notebook successfully:

- pandas
- numpy
- matplotlib
- seaborn
- nltk
- wordcloud
- regex
- scikit-learn
- imbalanced-learn

You can install the required libraries using the following command:
pip install pandas numpy matplotlib seaborn nltk wordcloud regex scikit-learn imbalanced-learn


Note: Make sure you have Python 3.x installed on your system.

# Tools Used
- Python
- Comet
- GitHub
- AWS EC2


# Usage

- Clone the repository or download the notebook and dataset files to your local machine.

- Install the required dependencies mentioned above.

- Open the notebook in Jupyter Notebook, JupyterLab, or any other compatible environment.

- Run the notebook cells sequentially to execute the code and generate the results.

# Output
![tweet_sentiments](https://github.com/Nthabi-06/Twitter-Sentiment-Classification-Case-Study/assets/128138564/9e3d9d98-5efa-465d-bf3a-6334f12316e3)

A wordcloud that is generated from the Tweets of people who believe in climate change.
![Screenshot (333)](https://github.com/Nthabi-06/Twitter-Sentiment-Classification-Case-Study/assets/128138564/83803ea5-c682-499d-8404-7b75c6e298e0)

A wordcloud that is generated from the Tweets of people who do not believe in climate change.
![Screenshot (332)](https://github.com/Nthabi-06/Twitter-Sentiment-Classification-Case-Study/assets/128138564/17ad4e1f-002b-455c-a15d-b6ece52f3546)

The final output is a user-friendly app 
![Screenshot (205)](https://github.com/Nthabi-06/Twitter-Sentiment-Classification-Case-Study/assets/128138564/eb60a5ff-4c6c-422e-a1b2-f46db02dd7af)

On the app there is a make prediction option where you can choose any model on the drop down , write a tweet then the model will do the predictions for you.
![myth](https://github.com/Nthabi-06/Twitter-Sentiment-Classification-Case-Study/assets/128138564/29a75fa6-eecb-432c-9f99-b21625d22d12)

# Conclusions
- Most tweets express support for addressing climate change, and surprisingly, the language used by both climate change proponents and skeptics shows little divergence. This similarity might arise from the fact that many individuals are inclined to engage with trending topics and hashtags, resulting in common frequently used words across a broad time frame
# Recommendations
- To maximize support and retweets on Twitter, it's advisable for companies to tailor their marketing efforts toward individuals who endorse the concept of climate change, as they constitute the majority of Twitter users generating content on this topic.
- Furthermore, the development of a tool capable of automatically distinguishing language patterns between climate change believers and skeptics based on real-time trends seems crucial.
- This innovation would enable marketers to pinpoint specific terms and phrases that resonate with their target audience, adapting to the ever-changing landscape of online discussions
  
# My contributions
- My duties were to update the Trello board.
- Perform data cleaning on the notebook.
- Perform model experiments using Comet.
  
# Acknowledgements
I would like to thank my team members for their contributions:
- Reneilwe Motsamai (Team Lead)
- Mantsho Molepo
- Nhlanhla Mthembu
- Esethu Mpetshwa
- Phelokazi Wessels
