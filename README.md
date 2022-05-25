# pjdsc
Philippine Junior Data Science Challenge 2022, Exploratory Data Analysis Competition, and Data Science studies



## Requirements

- [Poetry](https://python-poetry.org/docs/#installation)
- Dataset
  - `dataset/Elections Dataset/pres_precinct_data_2022.csv`
    - possible sources: [pres](https://figshare.com/articles/dataset/2022_Presidential_Elections_Data/19755469) & [vp](https://figshare.com/articles/dataset/2016_Philippine_vice-presidential_elections_precinct-level_data/3380116/1)
    - validate geographical political units [article](https://psa.gov.ph/classification/psgc/?q=psgc/luzon) [infographic](https://psa.gov.ph/classification/psgc/downloads/Q42021%20PSGC%20Infographics.PNG) 
  - poverty rates
    - [2021 dataset](https://data.humdata.org/dataset/philippines-poverty-statistics) from [psa article](https://psa.gov.ph/poverty-press-releases/nid/165535)



## Setup

1. Run virtual environment: `poetry shell`
2. Install dependencies: `poetry install`
3. Run notebook: `jupyter lab`



## Tasks

- Exploratory Data Analysis
  - Analyze the datasets
    - Extract its primary attributes
    - Provide deeper insight on the factors which may have caused
      certain trends in the data.
  - Create an interesting data visualization
    - Summarize qualities of the datasets
    - Present these qualities in a way in which people can easily understand the information embedded in the data.
  - Descriptive statistics to help make conclusions regarding the given data.
    - Measures of central tendency
    - Measures of variability
- Not about complexity but the actionability of the results



## Resources

- books
  - [python-data-science-handbook](https://jakevdp.github.io/PythonDataScienceHandbook/)
  - [Think Stats 2e](https://greenteapress.com/wp/think-stats-2e/)

- web
  - [awesome-data-science](https://github.com/academic/awesome-datascience)
    - pandas [official-tutorial](https://pandas.pydata.org/docs/getting_started/intro_tutorials/01_table_oriented.html)  [continue](https://pandas.pydata.org/docs/getting_started/intro_tutorials/07_reshape_table_layout.html)

  - [awesome-python-data-science](https://github.com/krzjoa/awesome-python-data-science)

- PJDSC 2021

  - [COVID vs vaccines](https://github.com/bullybutcher/PJDSC/blob/main/pjdscFINAL.pdf)
  - [COVID n twitter](https://github.com/tkmanabat/Philippine-Junior-Data-Science-Challenge)
  - **TODO** watch presentations and see repo of top 3 teams


- stats
  - **TODO**  [Philippine Statistics Authority > Databases > OpenSTAT](https://openstat.psa.gov.ph/)
  - [philippines-voters-choice-for-president-by-location](https://www.statista.com/statistics/1307769/philippines-voters-choice-for-president-by-location/)
  - [philippines-voters-choice-for-president](https://www.statista.com/statistics/1307754/philippines-voters-choice-for-president/)

- master studies


  - [kaggle rankings](https://www.kaggle.com/rankings?group=notebooks&page=1&pageSize=20)

  

## Tools

- Jupyter [cheatsheet](https://blogs.ubc.ca/advancedgis/files/2020/11/Jupyter_Cheatsheet.pdf)
- Pandas [cheatsheet](https://pandas.pydata.org/Pandas_Cheat_Sheet.pdf)
- Pandas Profiling
- Popmon [docs](https://popmon.readthedocs.io/)
- Great Expectations [docs](https://docs.greatexpectations.io/docs/)



## Explore

- `Exploratory data analysis` projects
  - [kaggle search](https://www.kaggle.com/search?q=exploratory+data+analysis)
    - **TODO** [python eda - getting started](https://www.kaggle.com/getting-started/173448)
    - [kashnitsky topic-1 eda](https://www.kaggle.com/code/kashnitsky/topic-1-exploratory-data-analysis-with-pandas)
  - [github search](https://github.com/search?q=exploratory+data+analysis)
  - reddit search **TODO [4](https://www.reddit.com/r/learnmachinelearning/comments/rv50th/exploratory_data_analysis/) ** [2](https://www.reddit.com/r/statistics/comments/m7110t/d_exploratory_data_analytics/) [3](https://www.reddit.com/r/datascience/comments/71g4zg/exploratory_data_analysis_book_recommendations/) 
- `Philippine election` datasets & projects 
  - **DOING** GitHub search [2](https://github.com/gpesleta/elections) [~~3~~](https://github.com/macoymejia/election_returns_philippines_2016) [4](https://github.com/avsolatorio/philippine-elections-2022) [~~5~~](https://github.com/daison12006013/the-2022-philippine-election-data) [~~6~~](https://github.com/mwdavids/2016-Philippines-Presidential-Map) [~~7~~](https://github.com/parkrain21/2022-PH-Elections) [8](https://github.com/oonrezak/election2019) [9](https://github.com/mgbgarcia/ph_vp_projections) [~~10~~](https://github.com/AstroMC98/GMA-Eleksyon-2022-Data)
  - [~~Kaggle search~~](https://www.kaggle.com/search?q=philippine+election), [~~Google dataset search~~](https://datasetsearch.research.google.com/search?src=0&query=philippine%20election&docid=L2cvMTFyczJubHk0NA%3D%3D)
  - Presidential candidates throughout the history of Philippine elections [kaggle dataset](https://www.kaggle.com/datasets/abeperez/ph-presidential-elections) 
    - cited on: [google scholar: celebrity politics](https://scholar.google.com/scholar?q=%22philippine%20presidential%20elections%22) 
- `pandas data cleaning` examples
- text analysis
  - tweet on elections, topic modelling
  - similar to google trend search
- internet access + location
- campaign target
- social media use ? [paper](https://medienorge.uib.no/files/Eksterne_pub/Pew-Research-Center_Global-Tech-Social-Media-Use_2018.06.19.pdf)
  - influencers ? [paper](https://ijoc.org/index.php/ijoc/article/viewFile/9615/2634) 
  - [google dataset search: philippines-leading-social-media-platforms](https://www.statista.com/statistics/1127983/philippines-leading-social-media-platforms/)
- happenings in each region/ province/ city
- poverty rates
  - google dataset search
    - [Philippines: Poverty statistics](https://data.humdata.org/dataset/philippines-poverty-statistics#)
- digital disinformation ? [paper](https://www.academia.edu/40190235/Tracking_Digital_Disinformation_in_the_2019_Philippine_Midterm_Election?from=cover_page)
- election analysis on other countries
