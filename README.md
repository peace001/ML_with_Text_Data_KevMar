# ML_with_Text_Data_KevMar
Jupyter Notebooks that shows how to build a predictive model from their own text-based data, including feature extraction, model building and model evaluation.

Presented by [Kevin Markham](http://www.dataschool.io/about/) at PyCon on May 28, 2016. Watch the complete [tutorial video](https://www.youtube.com/watch?v=ZiKMIuYidY0&list=PL5-da3qGB5ICeMbQuqbbCOQWcS6OYBr5A&index=10) on YouTube.

[![Watch the complete tutorial video on YouTube](youtube.jpg)](https://www.youtube.com/watch?v=ZiKMIuYidY0&list=PL5-da3qGB5ICeMbQuqbbCOQWcS6OYBr5A&index=10 "Machine Learning with Text in scikit-learn - PyCon 2016")

### Description

Although numeric data is easy to work with in Python, most knowledge created by humans is actually raw, unstructured text. By learning how to transform text into data that is usable by machine learning models, you drastically increase the amount of data that your models can learn from. In this tutorial, we'll build and evaluate predictive models from real-world text using scikit-learn.

### Objectives

By the end of this tutorial, attendees will be able to confidently build a predictive model from their own text-based data, including feature extraction, model building and model evaluation.

### Required Software

Attendees will need to bring a laptop with [scikit-learn](http://scikit-learn.org/stable/install.html) and [pandas](http://pandas.pydata.org/pandas-docs/stable/install.html) (and their dependencies) already installed. Installing the [Anaconda distribution of Python](https://www.continuum.io/downloads) is an easy way to accomplish this. Both Python 2 and 3 are welcome.

I will be leading the tutorial using the IPython/Jupyter notebook, and have added a pre-written notebook to this repository. I have also created a Python script that is identical to the notebook, which you can use in the Python environment of your choice.

### Tutorial Files

* IPython/Jupyter notebooks: [tutorial.ipynb](tutorial.ipynb), [tutorial_with_output.ipynb](tutorial_with_output.ipynb), [exercise.ipynb](exercise.ipynb), [exercise_solution.ipynb](exercise_solution.ipynb)
* Python scripts: [tutorial.py](tutorial.py), [exercise.py](exercise.py), [exercise_solution.py](exercise_solution.py)
* Datasets: [data/sms.tsv](data/sms.tsv), [data/yelp.csv](data/yelp.csv)

### Prerequisite Knowledge

Attendees to this tutorial should be comfortable working in Python, should understand the basic principles of machine learning, and should have at least basic experience with both pandas and scikit-learn. However, no knowledge of advanced mathematics is required.

- If you need a refresher on scikit-learn or machine learning, I recommend reviewing the notebooks and/or videos from my [scikit-learn video series](https://github.com/justmarkham/scikit-learn-videos), focusing on videos 1-5 as well as video 9. Alternatively, you may prefer reading the [tutorials](http://scikit-learn.org/stable/tutorial/index.html) from the scikit-learn documentation.
- If you need a refresher on pandas, I recommend reviewing the notebook and/or videos from my [pandas video series](https://github.com/justmarkham/pandas-videos). Alternatively, you may prefer reading this 3-part [tutorial](http://www.gregreda.com/2013/10/26/intro-to-pandas-data-structures/).

### Abstract

It can be difficult to figure out how to work with text in scikit-learn, even if you're already comfortable with the scikit-learn API. Many questions immediately come up: Which vectorizer should I use, and why? What's the difference between a "fit" and a "transform"? What's a document-term matrix, and why is it so sparse? Is it okay for my training data to have more features than observations? What's the appropriate machine learning model to use? And so on...

In this tutorial, we'll answer all of those questions, and more! We'll start by walking through the vectorization process in order to understand the input and output formats. Then we'll read a simple dataset into pandas, and immediately apply what we've learned about vectorization. We'll move on to the model building process, including a discussion of which model is most appropriate for the task. We'll evaluate our model a few different ways, and then examine the model for greater insight into how the text is influencing its predictions. Finally, we'll practice this entire workflow on a new dataset, and end with a discussion of which parts of the process are worth tuning for improved performance.

### Detailed Outline

1. Model building in scikit-learn (refresher)
2. Representing text as numerical data
3. Reading a text-based dataset into pandas
4. Vectorizing our dataset
5. Building and evaluating a model
6. Comparing models
7. Examining a model for further insight
8. Practicing this workflow on another dataset
