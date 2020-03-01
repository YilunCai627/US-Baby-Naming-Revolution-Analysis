# US-Baby-Naming-Revolution-Analysis
## Intruduction
 What factors make a name suddenly pop—and then die? In fact, social scientists and historians have been puzzling over this for decades.   
 
 In this study, we'll work with open data on [Popular Baby Names](https://www.ssa.gov/oact/babynames/limits.html) made by the United States Social Security Administration (SSA) to find some intriguing clues about the revolution of popular baby names. Besides, we incorporate a dataset from the [US Department of Health and Human Services](https://catalog.data.gov/dataset/births-and-general-fertility-rates-united-states-1909-2013/resource/a4d978b0-3396-4bb9-b967-b3c8c69b03a3?inner_span=True) which records the number of births each year to facilitate our analysis.  

We find a similar naming trend over years — they rise in popularity, enjoy a period of dominance, and then fall. Obviously, nowadays people seem to have a stronger preference for naming diversity. Pop culture and celebrities play important roles in the newer and spiky names. However, following the trend blindly may leave parents later slightly regretting how they hopped on the bandwagon. 

## Data Analytics Outline
### **1. Research Questions**
What are the reasons behind how parents name their babies?Whether it is out of personal preference, aspiration they hold for their children, or to memorialize a loved one or a special event, etc? Choosing a name for a baby is a big commitment. Cultural diversity in the U.S. has led to great variations in names and naming traditions and names have been used to express creativity, personality, cultural identity, and values.  

Do you want to go with an all-time classic name, or something trendy and of-the-moment? Do you want a popular name, or do you want to find something that's truly unique (but not so unique that it's illegal)? And, if it's the latter, how do you know that your unique name isn't one that's going to top all of the baby lists in the next five years? It's time to do some research.

### **2. Data Questions**  
the US Social Security Administration makes available data files, one per year, containing the total number of births for each sex/name combination. [The raw archive (“National data” file)](https://www.ssa.gov/oact/babynames/limits.html) can be obtained from the website of US Social Security Administration.  

While it is impossible to figure out on an individual level how each person names his/her baby, we can at least get some insight of the factors that might affect baby-naming trend over years through data analysis and visualization. The dataset we worked with records the number of babies born with a particular name for each year. Note rhat only popular names (names with at least 5 babies born in the same year and same state) are included in the dataset.  

There are many things we can explore with the dataset:
* Analyze the total births by year of birth and sex
* Visualize popular names and the naming trend given a particular name over time
* Figure out the factors that influence the baby-naming revolution
* Investigate the diversity of baby names over the years
* Characterize the similar trends of spiky names in the history and analyze the potential reasons
### **3. Data Answers**  
#### Popular Names Top10 Countdown
The table below presents the top10 countdown of popular names by gender over the history. We can see that the trend has dramatically changed over the years, with varieties of new names appear in the chart.

![](https://github.com/YilunCai627/US-Baby-Naming-Revolution-Analysis/raw/master/Visualization/Popular%20Names%20Countdown.png)

#### Recent Naming Trend
 Baby Center released its trends list of [the most popular baby names of 2019](https://www.babycenter.com/top-baby-names)—and those two topped the list. For years, “Noah” was in No.1 name for boys, and it took a long climb for “Liam” to knock it off its perch. Similarly, “Sophia” had ruled the roost for girls before “Emma” took the No.1 position.   

 Emma has gained its popularity since the 90s and is still very popular nowadays.  
 ![](https://github.com/YilunCai627/US-Baby-Naming-Revolution-Analysis/raw/master/Visualization/Emma_naming_trend.png)

 Similar to other popular names in the recent decade, Noah also started gaining its popularity since the 90s. It quickly reached the zenith in 1999 and still remains popular nowadays.
![](https://github.com/YilunCai627/US-Baby-Naming-Revolution-Analysis/raw/master/Visualization/Noah_naming_trend.png)


####  Influence of pop culture
Some factors might influence people's decision in naming their babies are explored.  Any part of mass culture can trigger hot new names. There's evidence that parents nowadays prefer more unique names and might also be influenced by celebrities. To verify this idea, I pick some uncommon celebrity names trying to look at the relationship between the naming trend of these uncommon names and the celebrities' defining moments in their career.


* **Athletic star**   
  I explore the influence form the famous basketball player Kobe. We see a similar surge for the name Kobe after he led the Los Angeles Lakers, to NBA championship during 2000–2002.  
  ![](https://github.com/YilunCai627/US-Baby-Naming-Revolution-Analysis/raw/master/Visualization/Celebrity_Kobe.png)
* **Artist**  
  I look into unique names to see if there is some influence from the celebrity. From the naming trend of famous singer Beyonce, we definitely see a potential correlation between naming trend and celebrity's career path.  
  ![](https://github.com/YilunCai627/US-Baby-Naming-Revolution-Analysis/raw/master/Visualization/Celebrity-Beyonce.png)
* **Politician**  
  I try Barack, which is the first name of President Obama. Surprisingly, not a lot of parents named their babies Barack and also the trend didn‘t last. Probably because we seldom refer to politicians with their first name.  
  ![](https://github.com/YilunCai627/US-Baby-Naming-Revolution-Analysis/raw/master/Visualization/Celebrity_Barack.png)

#### Finding fads
What factors make a name suddenly pop—and then die? In fact,  social scientists and historians have been puzzling over this for decades.   

New names rise in popularity, enjoy a period of dominance, and then fall like the below line graph displays. Therefore, following the trend blindly may leave parents later slightly regretting how they hopped on the bandwagon. 

![](https://github.com/YilunCai627/US-Baby-Naming-Revolution-Analysis/raw/master/Visualization/The%20top%20ten%20most%20faddy%20names.png)

### **4. Research Answers**
#### Increase in naming diversity
The naming trend have gotten more diverse as time has gone on. Over the last 100 years, Americans have increasingly embraced novelty. They’ve become less likely to pick already-popular names, and more likely to mint entirely new ones.

For the number of distinct popular names used over time, we are seeing an increasing trend and this increasing trend is not because more babies are born - for example, the number of births in the recent years is comparable to that during the baby boom in the 1960s but the number of distinct popular names used recently is more than double that of the 1960s. Thus, nowadays people seem to have a stronger preference for variations.  

![](https://github.com/YilunCai627/US-Baby-Naming-Revolution-Analysis/raw/master/Visualization/Increase%20in%20naming%20diversity.png)

#### The desire to be different
People's growing desire to be different is also evident when comparing the total number of births from the Department of Health and Human Services and the number of babies born with popular names from the Social Security application data. The colored area represents the number of babies born with unpopular names and we can see that the area gets bigger and bigger over time.   

Back in 1900, for example, 91% of all children of any gender were given a name from the top 1,000 most popular names. But a century later in 2000, only 75% of girls were given a name from the top 1,000 most-popular girl names, and that percentage had dropped for boys too, to 86%. In other words, more kids were getting names that would have been considered unusual or new. (And the trend is more prominent for girls than boys: Americans are more willing to experiment with new names for girls, it seems, than for boys.)

![](https://github.com/YilunCai627/US-Baby-Naming-Revolution-Analysis/raw/master/Visualization/The%20Desire%20to%20be%20Different%20png.png)


#### Future research Directions
* This analysis is limited by the fact that only the data for names with at least 5 babies born in the same year are published.
* It would be helpful if I can get the full set of data for a more accurate picture of the trends and regional differences.
* It would also be interesting to gather some external data from social media sources to look at the correlation with naming trend.


## Data Sources
* [Popular Baby Names--the United States Social Security Administration (SSA)](https://www.ssa.gov/oact/babynames/limits.html)
* [The crude birth rates and general fertility rates in the United States](https://catalog.data.gov/dataset/births-and-general-fertility-rates-united-states-1909-2013/resource/a4d978b0-3396-4bb9-b967-b3c8c69b03a3?inner_span=True)
* [Python Pandas API Reference](https://pandas.pydata.org/pandas-docs/stable/reference/index.html)
* [Jupter Notebook for data analysis and visualization](https://github.com/YilunCai627/US-Baby-Naming-Revolution-Analysis/blob/master/Baby-Naming%20Revolution.ipynb)


