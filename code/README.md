## Problem Statement

To compare and study the participation rate and scores of ACT and SAT examinations and to give a better idea to the participants about the ACT and SAT results and competition in recent years across all the states in USA.

## Datasets Used
- act_2018.csv - Gives ACT scores for the year 2018 across all the states in USA.

- act_2019.csv - Gives ACT scores for the year 2019 across all the states in USA.

- sat_2018.csv - Gives SAT scores for the year 2018 across all the states in USA.

- sat_2019.csv - Gives SAT scores for the year 2019 across all the states in USA.


## References
-https://stackabuse.com/calculating-mean-median-and-mode-in-python
-https://www.act.org/content/act/en/products-and-services/the-act/scores/understanding-your-scores.html
-https://www.princetonreview.com/college/sat-sections
-https://www.minotdailynews.com/news/local-news/2017/04/a-brief-history-of-the-sat-and-act/
-https://edition.cnn.com/2020/04/14/us/coronavirus-colleges-sat-act-test-trnd/index.html
-https://wybeaconnews.org/3659/opinions/act-tests-do-not-determine-your-intelligence/

## Data Dictionary


|Feature|Type|Dataset|Description|
|---|---|---|---|
|state|object|final_data|name of the state in USA| 
|act_2018_participation|float|final_data|ACT-2018 participation rate (0.5 represents 50%)| 
|act_2019_participation|float|final_data|ACT-2019 participation rate (0.5 represents 50%)| 
|sat_2018_participation|float|final_data|SAT-2018 participation rate (0.5 represents 50%)| 
|act_2019_participation|float|final_data|SAT-2019 participation rate (0.5 represents 50%)| 
|act_2018_composite|float|final_data|ACT-2018 composite score| 
|act_2019_composite|float|final_data|ACT-2019 composite score| 
|sat_2018_composite|float|final_data|SAT-2018 score| 
|sat_2019_composite|float|final_data|SAT-2019 score| 


## Summary
The work starts with the import of required datasets. The datasets are checked for redundancy and inconsistent data, which is fixed with of help of supporting functions. The unwanted columns are removed. Renaming of remaining columns is done in all the datasets. Then all the datasets are merged into one, which is then exported. The standard deviation for each columns are calculated and necessary observations are done and logged using the cleaned dataset.

Visualization is done With the help of cleaned dataset. The visualizations such as Heatmap, Histograms, Boxplots, Scattered Plots is done to get better understanding of the trends.

## Conclusion 
From the visualization of the data, we can observe the trend in participation rate and scores across the states of USA remains almost the same for the years 2018 and 2019. The standard deviations found previously supports the above. This gives better understanding of the recent trends in ACT and SAT in USA. The final dataset can be used to build a predictive machine learning models.
