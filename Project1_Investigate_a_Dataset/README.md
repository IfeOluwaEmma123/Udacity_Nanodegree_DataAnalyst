# Project 1 - Investigate a Dataset
## Project Title: Investigate TMDb Movie Database 

<p align="center"><img src="Image.jpg"></p>

----

### Table Of Contents:
- [Introduction](#introduction)<br>
    - [Project Description](#project-description)<br>
    - [Project Objective](#project-objective)<br>
    - [Project Significance](#project-significance)<br>
- [Project Data](#project-data)<br>
    - [Files Used](#files-used)<br>
    - [Dataset File](#dataset-file)<br>
- [Project Loading](#project-loading)<br>
    - [Requirements](#requirements)<br>
    - [Execution](#execution)<br>
- [Conclusion](#conclusion)<br>
    - [Observations](#observations)<br>
    - [Summary](#summary)<br>
    - [Results](#results)

----


### Introduction

#### Project Description

In this project, I am tasked with selecting a dataset for investigation from a pool of four options. You can access a document containing links and information about these datasets by Clicking [here](https://docs.google.com/document/d/e/2PACX-1vTlVmknRRnfy_4eTrjw5hYGaiQim5ctr9naaRd4V9du2B5bxpd8FEH3KtDgp8qVekw7Cj1GLk1IXdZi/pub?embedded=True)

After careful consideration, I have decided to focus my investigation on the TMDb Movie Data dataset for this project.

#### Project Objective

In this project, my objective is to perform an independent data analysis and compile a report to present my findings. To begin, I will thoroughly examine the dataset and generate a list of potential questions that can be addressed using the available information. Using the powerful tools of pandas and NumPy, I will focus on answering the most intriguing questions. It is important to note that this project does not mandate the use of inferential statistics or machine learning techniques; however, I will emphasize that the conclusions drawn from my analysis are provisional in nature. It is worth highlighting that this project encourages an open-ended approach, where there is no definitive correct answer sought.

#### Project Significance

The significance of this project lies in the comprehensive exploration of the data analysis process, examining how various components interconnect. Throughout this endeavor, I will leverage the capabilities of widely-used Python libraries such as NumPy, pandas, and Matplotlib. These libraries significantly simplify the coding process involved in data analysis tasks, making Python an ideal choice for such endeavors. Moreover, proficiency in these tools is highly sought-after by employers, enhancing one's professional skillset and employability.

----

### Project Data

#### Files Used

This project contains 6 files:
- `tmdb-movies.csv` : The dataset file containing 10k+ entries of movies that I have worked on. 
- `Investigate_TMBD_Dataset.ipynb` : The investigation of the dataset has been done in this jupyter notebook file. 
- `Investigate_TMBD_Dataset.html` : Folder containing HTML file of notebook.
- `Udacity Reviews.pdf` : Folder containing the review of an expert from Udacity.

#### Dataset File

Furthermore, the last two columns, denoted by the suffix “_adj", present the budget and revenue figures of each respective movie in terms of 2010 dollars, accounting for inflation adjustments across time.
This data set contains information about 10,000 movies collected from The Movie Database (TMDb). Contains data such as `title, cast, director, runtime, budget, revenue, release year` etc. 
- Certain columns, like `‘cast’` and `‘genres’`, contain multiple values separated by pipe (|) characters.
- There are some odd characters in the `‘cast’` column. Nothing to care much of, I leave them as is.
- The final two columns ending with `“_adj"` show the budget and revenue of the associated movie in terms of 2010 dollars, accounting for inflation over time.

-----

### Project Loading

#### Requirements

This project requires **Python 3** and the following Python libraries installed:

- [Python 3.6.5](https://www.python.org/downloads/release/python-365/)
- [NumPy](http://www.numpy.org/)
- [Pandas](http://pandas.pydata.org)
- [matplotlib](http://matplotlib.org/)
- [seaborn](https://seaborn.pydata.org/installing.html)

You will also need to have software installed to run and execute a [Jupyter Notebook](http://jupyter.org/install)

If you do not have Python installed yet, it is highly recommended that you install the [Anaconda](https://www.anaconda.com/download/) distribution of Python, which already has the above packages and more included. 


#### Execution

In a terminal or command window, navigate to the top-level project directory `Project1_Investigate_a_Dataset/` (that contains this README) and run one of the following commands:

```bash
ipython notebook Investigate_TMBD_Dataset.ipynb
```  
or
```bash
jupyter notebook Investigate_TMBD_Dataset.ipynb
```

or if you have 'Jupyter Lab' installed
```bash
jupyter lab
```

This will open the Jupyter/iPython Notebook software and project file/folder in your browser.

-----

### Conclusion

#### Observations

 - Understand the steps involved in a typical data analysis process, which includes data exploration, data cleaning, data transformation, data analysis, and data visualization.
 - Develop proficiency in formulating relevant questions that can be addressed using a given dataset, and subsequently provide answers to those questions through data analysis.
 - Acquire the skills necessary to identify and resolve issues within a dataset, ensuring that the data is in a usable format for analysis.
 - Practice effective communication of analysis results, translating complex findings into clear and concise reports or presentations.
 - Utilize vectorized operations in NumPy and Pandas to optimize data analysis code, enabling faster and more efficient computations.
 - Gain familiarity with Pandas Series and DataFrame objects, facilitating convenient access and manipulation of data.
 - Lastly, become proficient in utilizing visualization libraries such as Matplotlib and Seaborn to generate informative and visually appealing plots, effectively illustrating the discovered insights.


#### Summary
My project was reviewed by a Udacity reviewer against the **<a href="https://review.udacity.com/#!/projects/3176718735/rubric" target="_blank">Investigating a Dataset rubric</a>**. All criteria found in the rubric must be *meeting specifications* for me to pass.

#### Results
[My Project Review by an Udacity Reviewer](https://review.udacity.com/#!/reviews)

----
