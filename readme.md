# P.A.U.S.E Exploratory data analysis
EDA phase of 2026/1 Artificial intelligence, Machine Learning & Statistics course.
## Dataset used
[Student Social Media Addiction Analysis Dataset](https://www.kaggle.com/datasets/zahranusratt/student-social-media-addiction-analysis-dataset/)

## Preprocessed notebook files
[EDA](notebooks/eda.ipynb)

[t-SNE](notebooks/tsne.ipynb)

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
