# P.A.U.S.E Exploratory data analysis
EDA phase of 2026/1 Artificial intelligence, Machine Learning & Statistics course.
## Dataset used
[Student Social Media Addiction Analysis Dataset](https://www.kaggle.com/datasets/zahranusratt/student-social-media-addiction-analysis-dataset/)

Dataset features:

| Column Name                    | Type                 | Description                                                                  |
| ------------------------------ | -------------------- | ---------------------------------------------------------------------------- |
| Age                          | Numerical            | Age of the student (in years)                                                |
| Gender                       | Categorical          | Gender of the student (e.g., Male, Female)                                   |
| Academic_Level               | Categorical          | Education level (e.g., High School, Undergraduate, Postgraduate)             |
| Country                      | Categorical          | Country of residence of the student                                          |
| Avg_Daily_Usage_Hours        | Numerical            | Average number of hours spent on social media per day                        |
| Most_Used_Platform           | Categorical          | Primary social media platform used (e.g., Instagram, TikTok)                 |
| Affects_Academic_Performance | Categorical (Yes/No) | Whether social media usage negatively impacts academic performance           |
| Sleep_Hours_Per_Night        | Numerical            | Average number of hours the student sleeps per night                         |
| Mental_Health_Score          | Numerical (scale)    | Self-reported mental well-being score (typically 1–10 scale)                 |
| Relationship_Status          | Categorical          | Student’s relationship status (e.g., Single, In a relationship, Complicated) |
| Conflicts_Over_Social_Media  | Numerical (ordinal)  | Frequency/intensity of conflicts caused by social media use                  |
| Addicted_Score               | Numerical (1–10)     | Composite addiction score derived from a psychometric scale (BSMAS)          |

## Preprocessed notebook files
[EDA](notebooks/eda.ipynb)

[t-SNE](notebooks/tsne.ipynb)

[Feature selection & model training](notebooks/feature-selection.ipynb)

## Steps to reproduce (VSCode jupyter notebook extension)
### Assumptions:
 1. VSCode is installed;
 2. Python extensions are installed;
 3. Jupyer notebook extensions are installed; and
 4. You have an account on [Kaggle](https://www.kaggle.com/)
### Step-by-step:
1. Clone this repository  
2. Navigate to the root folder  
3. Create an `.env` file in the root folder  
4. Get your **API token and username** from Kaggle  
5. Write the `.env` file like this:  
    5.1.   Write the file like this:
    ```
    KAGGLE_KEY=[YOUR_API_TOKEN]
    KAGGLE_USERNAME=[YOUR_USERNAME]
    ``` 
6. Create a Python virtual environment  
7. Assign the created virtual environment as the kernel for Jupyter Notebook  
8. Activate the virtual environment in your preferred terminal  
9. Run `pip install -r requirements.txt` (or `requirements-lock.txt`)  
10. Wait for the installation to complete  
11. Click on **"Run All"** to execute all the notebook cells

### Resources used during the assignment

[Holz, A. (2025). Introduction to Exploratory Data Analysis](https://www.youtube.com/watch?v=h6UpsLI4Ejg)

[Faraway, J. J. (2005). Exploratory Data Analysis. In Encyclopedia of Statistics in Behavioral Science. SAGE Publications.](https://www.stat.berkeley.edu/~brill/Stat153/EDASage.pdf)

[Bartlein, P. (2021). GEOG 4/595: Geographic Data Analysis](https://pjbartlein.github.io/GeogDataAnalysis/lec01.html)

[t-SNE introduction](https://en.wikipedia.org/wiki/T-distributed_stochastic_neighbor_embedding)

[How to Use t-SNE Effectively](https://distill.pub/2016/misread-tsne/)

[t-SNE scikit implementation](https://scikit-learn.org/stable/modules/generated/sklearn.manifold.TSNE.html)

[An Introduction to Variable and Feature Selection](https://www.jmlr.org/papers/volume3/guyon03a/guyon03a.pdf)

[Feature Ranking](https://geostatsguy.github.io/MachineLearningDemos_Book/MachineLearning_feature_ranking.html)

[05c Machine Learning: Feature Selection](https://www.youtube.com/watch?v=5Q0gemu-h3Q)

[Feature Selection Tutorial with Python Examples ](https://ar5iv.labs.arxiv.org/html/2106.06437)