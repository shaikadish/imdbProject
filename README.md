# Movie Review Rating Predictor

After seeing some of the great results modern NLP architectures can achieve when performing sentiment analysis on [text from IMDB film reviews](https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews), I had a question that I wanted to explore to take things a step further: instead of simply classifying reviews based on sentiment, would it be possible to actually predict the review score (on a scale from 1-10) from the text?

This question led to the developement of this tutorial. I broke solving this problem down into 3 steps:
1. [Dataset generation through webscraping](https://github.com/shaikadish/imdbProject/blob/main/web_scraper.ipynb)
2. [Exploratory data analysis](https://github.com/shaikadish/imdbProject/blob/main/EDA_and_preprocessing.ipynb)
3. [Model training and testing](https://github.com/shaikadish/imdbProject/blob/main/model_training_and_testing.ipynb)

Each of these steps is tutorialised as a colabs notebook, and I recommend going through them in order to understand each step fully. As a whole, this tutorial is not designed to explain technical machine learning information (like how BERT works or what encodings are), nor is it designed to explain the use of machine learning libraries (like Hugging Face and PyTorch). Rather, this tutorial aims to walk you through the Data Science process of data aquisiton, analysis, and application. I hope you find it useful!

You can play around with the final Review Rating Predictor generated from this project in this [interactive demo](https://github.com/shaikadish/imdbProject/blob/main/rating_predictor_demo.ipynb).
