# ISA 383: Python for Business Analytics

Click a notebook below to open it in Google Colab.
Then select **File > Save a copy in Drive** so your work is saved in your own Google Drive.

| Topic | Open in Colab |
|---|---|
| Variables and statements | [Open](https://colab.research.google.com/github/harshvardhaniimi/isa383-google-colab/blob/main/02_Variables%20and%20Statements.ipynb) |
| Conditional statements | [Open](https://colab.research.google.com/github/harshvardhaniimi/isa383-google-colab/blob/main/03_Conditional_Statements.ipynb) |
| Lists | [Open](https://colab.research.google.com/github/harshvardhaniimi/isa383-google-colab/blob/main/04_Lists.ipynb) |
| Dictionaries | [Open](https://colab.research.google.com/github/harshvardhaniimi/isa383-google-colab/blob/main/05_Dictionaries.ipynb) |
| Functions | [Open](https://colab.research.google.com/github/harshvardhaniimi/isa383-google-colab/blob/main/06_Functions.ipynb) |
| Strings, regex, and files | [Open](https://colab.research.google.com/github/harshvardhaniimi/isa383-google-colab/blob/main/07_Strings_RegEx_Files.ipynb) |
| Iterations | [Open](https://colab.research.google.com/github/harshvardhaniimi/isa383-google-colab/blob/main/08_Iterations.ipynb) |
| Pandas for data wrangling (basic) | [Open](https://colab.research.google.com/github/harshvardhaniimi/isa383-google-colab/blob/main/09_Pandas_Basic.ipynb) |
| Pandas for data wrangling (advanced) | [Open](https://colab.research.google.com/github/harshvardhaniimi/isa383-google-colab/blob/main/10_Pandas_Advanced.ipynb) |
| Data manipulation, cleaning, and imputation | [Open](https://colab.research.google.com/github/harshvardhaniimi/isa383-google-colab/blob/main/11_Data_Cleaning.ipynb) |
| Data visualization with matplotlib and seaborn | [Open](https://colab.research.google.com/github/harshvardhaniimi/isa383-google-colab/blob/main/12_Data_Visualization.ipynb) |
| Web scraping | [Open](https://colab.research.google.com/github/harshvardhaniimi/isa383-google-colab/blob/main/13_Web_Scraping.ipynb) |
| APIs | [Open](https://colab.research.google.com/github/harshvardhaniimi/isa383-google-colab/blob/main/14_APIs.ipynb) |
| Generative AI APIs | [Open](https://colab.research.google.com/github/harshvardhaniimi/isa383-google-colab/blob/main/15_Generative_AI_APIs.ipynb) |
| End-to-end machine learning | [Open](https://colab.research.google.com/github/harshvardhaniimi/isa383-google-colab/blob/main/16_End_to_End_ML.ipynb) |
| Handling big data with Dask | [Open](https://colab.research.google.com/github/harshvardhaniimi/isa383-google-colab/blob/main/17_Big_Data_Dask.ipynb) |

## Data and API keys

Required course data is included in this repository and downloaded automatically by the notebooks.
Larger practice datasets are generated inside Colab.

Notebooks 09 to 12 use the passenger list of the RMS *Titanic*, stored in the `data` folder:

| File | Contents |
|---|---|
| `titanic.csv` | 891 passengers from Kaggle's *Titanic: Machine Learning from Disaster* training set |
| `titanic_extra.xlsx` | The ports the ship called at, and the official 1912 Board of Trade count of all 2,201 people aboard, including crew |
| `titanic_messy.csv` | A teaching copy of `titanic.csv` with deliberately added data-entry problems, used in Notebook 11 |

For Notebook 15, add `GEMINI_API_KEY` in Colab's **Secrets** panel.
Notebook 14 can use the public NASA demo key, or an optional secret named `NASA_API_KEY`.

Never place an API key directly in a notebook.
