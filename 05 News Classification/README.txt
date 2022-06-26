05 PROJECT 'News Classification'
Date of completion - June 2022

In this project I classified the news data in various ways. As baseline, I've chosen gradient boosting models trained in embeddings.

I got embeddings using the FastText library from Facebook (it showed the best results compared to Word2Vec). Next, I took advantage of the performance evaluation function from FastText - so I got a model that showed an excellent speed / results ratio.

Of course, in the project I implemented the SOTA approach. With AutoMl, I validated several models for classifying text for the Russian language with HuggingFace. The best results were shown by the model from DeepPavlov.

Next, I trained the same model on own data and selected own hyperparameters. The result was a little worse than AutoMl. There is potential for improvement.

In this project, I encountered imbalanced data, so I made use of the class stratification before the data splitting . Also, before training the Fast Text model, I balanced the data with the Over-Sampling method.

If I analyze various approaches, then the FastText and Transformers models are best suited for production. Files with the AutoML model can be up to 1GB in size.

P.S. You can upload the data for this project here: https://drive.google.com/drive/folders/14DdKuH3L1_dU4MofWq5l5_ovYQBcKXie?usp=sharing

I participated in the Kaggle competition. Here is a link to the leaderboard: https://www.kaggle.com/competitions/scan-classification-challange/leaderboard