# Kaggle x Spotify
-------------------------
**Project description:** A **160k** lines of data from Kaggle x Spotify can provide some necessary resources in order to improve one's ability to improve in this Data Science World. The main porpuse of this article is to show a visualization tool capable to improve your knowledge of your data.

When coding with Python there is no **"best"** tool (library) for all cases. That being said, I believe that are some key tools that you should have in your toolbox.

## 1. Jupyter Notebook
I always start my projects with a Jupyter, I prefer the **JupyterLab** from Anaconda.

Basically, Jupyter Notebook is an application that allows documents containing Python code and rich text elements (paragraphs, equations, figures, links, etc). Notebook documents are both human-readable documents containing the analysis description and the results as well as excutable documents which can be run to perform data analysis.

## 2. Bokeh
Bokeh is a package capable of integrate both a way to visualize the data and interact. This interactions mainly consists on **"widgets"** and **"tools"**. I am going to show you for ease of understanding.


The first step is to have some kind of dataset and in this case a DataFrame from Kaggle x Spotify is available, so lets explore together.
```
df = pd.read_csv('data.csv', parse_dates=['release_date'])
```
