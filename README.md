# Zimbabwe DHS Survery: Understanding DHS Clustering

<strong>Github</strong>: <a href="https://github.com/daikiminaki/zimbabwe_analysis/blob/master/zimbabwe_dhs_analysis.ipynb/">https://github.com/daikiminaki/zimbabwe_analysis/blob/master/zimbabwe_dhs_analysis.ipynb/</a><br>
<strong>Blog Post</strong>: <a href="https://www.daikiminaki.com/zimbabwe-dhs-survery-understanding-dhs-clustering/">Zimbabwe DHS Survery: Understanding DHS Clustering</a><br>

## About The Data:
Demographic & Health Surveys Preprocessed Data: <a href="https://www.kaggle.com/taniaj/zimbabwe-preprocessed/home">Source Here</a>

The dataset contains preprocessed data from the DHS for Zimbabwe. There are five main data files:

1. Household data
2. Household Member data
3. Births data
4. Cluster information
5. Geographic information (shapefile)

For this notebook I have summarized all household and household member data by DHS Cluster as this provides the best structure to focus on analysis by DHS Clusters.

## Question: 

Why is the distribution for electricity and cooking fuel deprivation by DHS so polarized? (Clear cut between DHSs that have it and don't. No middle ground.) What factors relate to this? What can be done?
    
(Based on observations made during data exploration)

### Notebook Structure:
1. #### Data Wrangling
    - Summarize Household Data by DHS
    - Calculate Variable Change Variables
2. #### Exploratory Data Analysis (Overall)
    - Understanding Overall Trends by DHS
    - Understanding Relationships between Variables
3. #### Inferential Statistics
    - Answer Question:
        - Question Specific: EDA
        - Question Specific: Test Statistics
        - Question Specific: Hypothesis Testing
        - Question Specific: Conclusion & Suggestions
4. #### Conclusion
    - Final Takeaways/Final Remarks
