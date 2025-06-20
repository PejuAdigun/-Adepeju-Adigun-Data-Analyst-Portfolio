Netflix Movies and TV Shows Analysis ????

This project explores the global Netflix catalogue, analysing key trends in content types, release patterns, and country-level production. Using Python, I performed data cleaning, exploratory data analysis (EDA), text analysis, and data visualisation to discover insights from the Netflix dataset.

 Key Questions Explored
- What is the distribution of Movies vs TV Shows?
- Which countries produce the most Netflix content?
- What genres are most common across the platform?
- How has Netflix's content production changed over the years?
- What are the most frequently used words in title descriptions?

 Tools & Libraries used
- Python (Jupyter Notebook) � Interactive analysis
- Pandas & NumPy
- Matplotlib & Seaborn
- WordCloud - Text visualization  
- Datetime

 Key Steps

- Cleaned and transformed the dataset (handling nulls, duplicates, splitting genres and dates)
- Performed EDA to identify trends in:
  - Content type (TV Show vs Movie)
  - Release year distribution
  - Top genres over time
  - Country distribution
- Created word clouds for movie descriptions
- Filtered and counted titles released per year
- Compared genre popularity between TV shows and movies

  Key Insights

- Netflix has significantly ramped up content production post-2014.
- Most content comes from the United States, followed by India and the UK.
- "International Movies", "Dramas" and �Comedies� are among the top genres.
- Word cloud analysis reveals storytelling themes around love, family, and life.

What I Learned

- Efficient data wrangling with `pandas`
- Generating insights from unstructured text using `wordcloud`
- Visual storytelling using plots
- Managing common data challenges like null values and formatting inconsistencies

Challenges & Solutions

| Challenge | Solution |
| Inconsistent date formats | Used `pd.to_datetime()` with `errors='coerce'` |
| Genre column with multiple values | Used `.str.split()` and `.explode()` to analyse individually |
| Null values in key columns | Dropped or filled based on context |
| Overwhelming initial dataset | Broke tasks into small exploratory questions |

 ?? Dataset

Publicly available Netflix dataset from [Kaggle](https://www.kaggle.com/shivamb/netflix-shows)

Author: Adepeju (PJ) Adigun
Data Analyst  | Storyteller through Data  
[LinkedIn](https://www.linkedin.com/in/adigun-adepeju/)  



