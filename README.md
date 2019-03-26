### General structure of each two-hour session in the workshop series:
* Guided session
* Hands-on exercise
* Project work

Four sessions are planned in the series with the following time allocations:

| Sessions | Guided session (min) | Hands-on exercise (min) | Project work (min) | Total time (min) |
|----------|:----------:|:----------:|:----------:|:----------------:|
| 1 | 60 | 45 | 15 | 120 |
| 2 | 30 | 45 | 45 | 120 |
| 3 | 70 | 30 | 20 | 120 |
| 4 | 30 | 30 | 60 | 120 |

### Independent projects:
Each participant would pick a dataset of their own choice and work on it in subsequent sessions of the workshop. Below is a list of example datasets one can choose from:

* [Reducing Commercial Aviation Fatalities](https://www.kaggle.com/c/reducing-commercial-aviation-fatalities/data)
* [New York City Taxi Fare Prediction](https://www.kaggle.com/c/new-york-city-taxi-fare-prediction)
* [Titanic: Machine Learning from Disaster](https://www.kaggle.com/c/titanic)
* [House Prices: Predict sales prices](https://www.kaggle.com/c/house-prices-advanced-regression-techniques)
* [Predict Future Sales](https://www.kaggle.com/c/competitive-data-science-predict-future-sales)
* [New York City Taxi Trip Duration](https://www.kaggle.com/c/nyc-taxi-trip-duration/data)
* [Bike Sharing Demand](https://www.kaggle.com/c/bike-sharing-demand/data)
* [Instacart Market Basket Analysis](https://www.kaggle.com/c/instacart-market-basket-analysis/data)
* [Mercari Price Suggestion Challenge](https://www.kaggle.com/c/mercari-price-suggestion-challenge/data)


[Kaggle Competitions](https://www.kaggle.com/competitions) (past and current) as well as [Kaggle Datasets](https://www.kaggle.com/datasets) are an excellent resource to find datasets. Below are a few suggestions to note if you want to pick a dataset from outside the above list:
* Data must be in tabular format (csv files). We will cover other data formats in Deep Learning workshop series later on. Please don’t pick tabular data stored in Google BigQuery format as it is usually too  big to work with.
* Prefer past competitions that have a high participation, a lot of shared kernels and many topics in the discussion forum to learn from.
* Main features must not be textual unless you already know or plan to learn some natural language processing concepts within the time frame.
* Data size must be manageable with respect to the computation power you have access to, especially important to check for the recent competitions. You can also run notebooks in [Google Colab](https://research.google.com/colaboratory/faq.html) for free.
* It is better to pick a [competition dataset](https://www.kaggle.com/competitions) than one from the [dataset archive](https://www.kaggle.com/datasets) unless you have an idea about how to formulate the problem and choose evaluation metrics. Must check with a quick baseline model that the performance is not inappreciable for the formulated problem with respect to the decided metrics. 




### Topics covered in the guided sessions and hands-on exercises:  
Session 1: 
- Reading csv files using `read_csv()`
- Slicing and indexing dataframes using conditionals as well as `iloc[]` and `loc[]` methods.
- Statistical summary and exploration using `describe()`, `median()`, `mean()`, `idxmax()`, `corr()`, etc.
- Detecting and filling missing values in the dataset using `isnull()` and `fillna()`
- Dropping columns using `drop()`.
- Basic operations such as `set_index()`, `replace()`, `value_counts()`, `columns`, `index`, etc.
- Regular expressions for data extraction
- Feature engineering such as creating a new feature for titles.
- Some basic plots
- Correlation among features

Session 2:
- Datatypes of features
- One-hot encoding for categorical variables using `get_dummies()`
- Concatentating two dataframes using `concat()`
- Split-apply-combine operations using `groupby()` and `transform()`
- Merging dataframes using `merge()`
- Sorting the rows of the dataframe using `sort_values()`
- Creating a dataframe using `DataFrame()`

Session 3:
- Overfitting and Underfitting
- Train and test split
- Missing values
- Fit and predict model
- Test different models
    - Classification: Logistic, Decision Trees, SVM, Random Forest, GBT, kNN
    - Regression: Linear, Lasso Regression
    
Session 4:
- Test different models: Regression
- Fine tuning to address under and overfitting
- Principal Component Analysis (PCA)
- Visualization of decision boundaries
- Evaluation metrics
- Bootstrapping
- Cross-validation

### Pre-requisites:
* Python programming basics (CS-5 should suffice)
* Some familiarity with common statistical concepts (MATH-35 should suffice)

It will be beyond the scope of the workshop series to cover the theory and mathematics behind the machine learning algorithms and participants are encouraged to learn them on their own and deepen their understanding. A gentle introduction will be covered in the workshop series and resource links will be given for self-study. The focus will be on the practical aspects of machine learning and the concepts like feature engineering, overfitting vs underfitting, cross-validation, etc. that are crucial for all varietes of machine learning algorithms, including deep neural networks that will be covered in a future Deep Learning series.

### Learning materials:
All the learning material will be shared on Kaggle and links will be added here. The material is designed to be self-sufficient and useful, even in case one miss some of the sessions or cannot attend the entire workshop series. You are also welcome to join our google group [HMC Machine Learning]() that we plan to use for the workshop as well as future activities.
