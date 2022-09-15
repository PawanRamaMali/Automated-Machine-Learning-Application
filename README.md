# Automated-Machine-Learning-Application


Objective - To automate end to end machine learning process.
----------------------------------------------

Automated Artificial Intelligence and Machine Learning (AutoAI / AutoML) can now automate every step of the end-to-end AI Lifecycle, from data cleaning, to algorithm selection, and to model deployment and monitoring in the machine learning workflow. AutoAI technologies, initially aimed to save data scientists from the low level coding tasks, also has great potential to serve non-technical users such as domain experts and business users to build and deploy machine learning models. Researchers coined it as "democratizing AI", where non-technical users are empowered by AutoAI technologies to create and adopt AI models. To realize such promise, AutoAI needs to translate and incorporate the real-world business logic and requirements into the automation.


What Is AutoML?
----------------
Automated machine learning (AutoML) is a process that automatically performs many of the time-consuming and repetitive tasks involved in model development. It was developed to increase the productivity of data scientists, analysts, and developers and to make machine learning more accessible to those with less data expertise.

Challenges & The Need for AutoML
----------------------------------
In ML, data scientists first start with a problem statement and a dataset. The data is analysed and cleaned, a metric of performance is decided on and then a few models which might work on the dataset, according to the human intuition, are experimented with. There is a lot of feature engineering and fine tuning involved before we finally reach an acceptable model.

A recent Gartner survey reported that it takes on average four years to get an AI project live. For 58% of businesses it takes two years to get to the piloting stage. Furthermore, these big investments in data and AI projects are successful only 15% of the time. As a result, for many readers, delivering an effective AI app in one day sounds like an impossible pipedream.

Apart from math, data analysis is the essential skill for machine learning. The ability to crunch data to derive useful insights and patterns form the foundation of ML. Like math, not every developer has the knack to play with data. Loading a large dataset, cleansing it to fill missing data, slicing and dicing the dataset to find patterns and correlation are the critical steps in data analysis.

Why is Automated Machine Learning Important?
-------------------------------------------
Machine learning automation is important because it enables organizations to significantly reduce the knowledge-based resources required to train and implement machine learning models. It can be used effectively by organizations with less domain knowledge, fewer computer science skills, and less mathematical expertise. This reduces the pressure on individual data scientists as well as on organizations to find and retain those scientists.

AutoML can also help organizations improve model accuracy and insights by reducing opportunities for bias or error. This is because machine learning automation is developed with best practices determined by expert data scientists. AutoML models do not rely on organizations or developers to individually implement best practices.

Machine learning automation lowers the requirements for entry to model development, allowing industries that were previously unable to leverage machine learning to do so. This creates opportunities for innovation and strengthens the competitiveness of markets, driving advancement.

What Tasks can be Automated?
--------------------------------

While not everything in machine learning can be automated, many processes and steps that are iterative, especially in model training. These iterative steps are ideal for automation.

Hyperparameter optimization
---------------------
Hyperparameters are values that are defined before a model is trained. These values govern model training and impact the end accuracy of the model. Example hyperparameters include learning rate, activations functions, number of hidden units and layers, and the number of epochs.

To improve models, you need to optimize your hyperparameters. This is typically done through the application of search algorithms, such as random search, grid search, or Bayesian optimization. This application is what can be automated. There are multiple individual tools available for this, including SigOpt, Katib, Eclipse Arbiter, Tensorflow Vizier, and Spearmint.

Model selection
--------------------
In machine learning, model selection is the process of selecting the right candidate model for your machine learning implementations. It is based on model performance, complexity and maintainability, as well as what resources you have available. The model selection process is what determines the structure of your model development pipeline.

Automating model selection is done in much the same way hyperparameter optimization is. This is because both are essentially seeking the same end goal. The difference is that model selection may also include more extensive filtering through methods like Akaike Information Criterion (AIC) or Bayesian Information Criterion (BIC).

Feature selection
-----------------------
Machine learning feature selection is a process that refines how many predictor variables are used in a machine learning model. The number of features that your model includes directly affects how difficult it is to train, understand, and run.

When automating feature selection testing is scripted to use one or more of a variety of algorithmic methods, such as wrapper, filter, or embedded. After performing your feature selection tests, the one with the lowest error rate or proxy measure is selected.

Data preprocessing
-----------------------
Data preprocessing involves cleaning, encoding, and verifying data before use. Automated tasks can perform basic data preprocessing before performing hyperparameter and model optimization steps. This type of machine learning automation typically includes the detection of column types, transformation into numerical data, and handling missing values.

Advanced preprocessing can also be performed. This includes automation of feature selection, target encoding, data compression, text content processing, feature generation or creation, and data cleaning.

Transfer learning and pre-trained models
--------------------------------------------------

In machine learning, transfer learning involves taking models that have already been trained on a similar data set and using it for your machine learning initiative. Generally, this model is used as a base and then further trained to match your exact needs.

In terms of machine learning automation, this initial model can be trained in the same way as your end model while you are collecting or preparing datasets for the final model. This can save significant time, especially if you do not need a highly accurate model.
