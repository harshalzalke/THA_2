# THA_2

##  **Research Question and Data**

My **research question** is to explore the correlation between the economic freedom, happiness and inflation for a country. I have limited my analysis to the year of 2016.  In order to do that, I have retrieved the data for the three factors  for the year 2016, and have merged them to create a single dataset I can then analyze. The data that I have used is as follows:
 
 a) The Happiness data: **The codebook is titled hap_final**. The data is retrieved from the World Happiness Report (**source**: https://s3.amazonaws.com/happiness-report/2016/Online-data-for-chapter-2-whr-2016.xlsx). The world happiness report is a survey of global happiness. It ranks 156 countries on the basis of their happiness. **The data format is xlsx.**
 
 b) Economic Freedom data: **The codebook is titled eco_free_f**. The data is retrieved from the Fraser Institute.
 **source**: https://www.fraserinstitute.org/sites/default/files/efw-2018-master-index-data-for-researchers.xlsx. The Frasier Institute is a non-profit think tank in Canada. It is a conservative and libertarian think tank. **The data format is xlsx.**
 
 c) Consumer Price Inflation: **The codebook is titled Inflation**. I retreived this data from the world bank open source datasets (**source**: https://data.worldbank.org/indicator/FP.CPI.TOTL.ZG?locations=BR). The World Bank is an International organization that provides loans to countries of the world for capital projects. Since the link to the data was an API, I had trouble improting the data through an API. Hence, I had to download the data and then edit it to **create the required codebook (file name: Inflation.xlsx)** **This file can be found on the repository by the name of Inflation.xlsx.**. **The format is xlsx.**
 
 The final merged file is titled: **final_data**.
 
 Finally, I plotted economic freedom vs happiness score to get an idea of there is any correlation.
 
 The Python code can be found in the repository by the filename - **THA_1_Harshal.ipynb**
 
 ## **Research Purpose**
 
 Milton Friedman, in his seminal work, **Capital and Freedom**, explained the correlation between economic freedom and political freedom. According to his research, economic freedom is a neccessary condition for political freedom and not vice versa. Assuming that there is a direct correlation between political freedom and happiness, I want to test the hypothesis that economic freedom leads to higher happiness index.
 
 ## **Research Progress**
 
 I have collected the required data and created a document merging all the required factors. I ran a preliminary regression to see if there is a correlation between the economic freedom, happiness and consumer price inflation. The initial graph shows a positive correlation between economic freedom and happiness.
 
 The next step is to process the data and perform a meta analysis of these factors to understand th underlying variables that affect our study.
