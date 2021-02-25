
# Projects Overview

This repository holds some of the projects I've done during my studies at **"Yandex.Practicum Data Analysis"** professional program.

[Tableau visualizations](#tableau)
 - [Trending YouTube Videos](#yb)

[Jupyter notebook](#jn)
 - [Mobile app conversion](#mobile)
 - [Online store A/B testing](#online_store)
 - [Marketing expenses research](#marketing)
 - [Food market research](#food)
 
[Course Overview](#course)

# Tableau visualizations<a id='tableau'></a>
## [Trending YouTube Videos](https://public.tableau.com/profile/elizaveta.gorbunova#!/)<a id='yb'></a>
Dashboard shows trending YouTube videos per country and category over time.
<img src="images/tableau_yb.png" alt="drawing" width="800"/>

# Jupyter notebook<a id='jn'></a>

## [Mobile app conversion](https://nbviewer.jupyter.org/github/artefazosya/yandex-practicum/blob/bf518d04cd31bf8bb81d7a34cd361fb2e9eb54bf/09_Mobile_app_conversion/09_Mobile_app_conversion.ipynb)<a id='mobile'></a>
 
 In this project I've analysed mobile app logs:
 * Determined how many logs are there per each date, chose a suitable date interval for analysis
 * Created event funnel to understand when users leave the app
 * Developed recommendations on conversion improvement
 * Checked whether new design was beneficial using the results of A/A/B test
 
**Key words**: sales funnel, conversion, A/B test, user behaviour. 

**Libraries used**: pandas, plotly, seaborn, scipy.

<img src="images/events%20per%20date.png" alt="drawing" width="400"/>
<img src="images/funnel.png" alt="drawing" width="400"/>

## [Online store A/B testing](https://github.com/artefazosya/Elizaveta_Gorbunova_Portfolio/blob/main/07_Online_store_AB_testing/07_Online_store_AB_testing.ipynb)<a id='online_store'></a>
 
 In this project I've worked with online store orders and visits:
 * Prioritised list of hypotheses to test using ICE and RICE scores
 * Analysed results of A/B test: compared cumulative revenue, order size, conversion rate for each group
 * Detected anomalies in data
 * Checked whether there was statistical significance between groups using data with and without anomalies
 * Provided recommendations whether to stop or continue A/B test
 
**Key words**: hypotheses prioritization, hypotheses testing, A/B testing

**Libraries used**: pandas, matplotlib, scipy, seaborn

<img src="images/07_conversion_dif.png" alt="drawing" width="400"/>
<img src="images/07_difference.png" alt="drawing" width="400"/>

## [Marketing expenses research](https://github.com/artefazosya/Elizaveta_Gorbunova_Portfolio/blob/main/06_Marketing_expenses_research/06_Marketing_expenses_research.ipynb)<a id='marketing'></a>
 
 For this project I've analysed data on marketing costs, visits and orders for Yandex.Afisha:
 * Described how clients used the product and when they made purchases
 * Calculated retention rates
 * Performed cohort analysis
 * Explained which marketing costs were worthwhile
 * Came up with product and marketing campaign improvements
 
**Key words**: LTV, CAC, ROMI, retention, cohort analysis. 

**Libraries used**: pandas, matplotlib, seaborn, scipy.

<img src="images/06_area_plot.png" alt="drawing" width="400"/>
<img src="images/06_romi.png" alt="drawing" width="400"/>

## [Food market research](https://github.com/artefazosya/yandex-practicum/blob/main/08_Food_market_research/08_Food_market_research.ipynb)<a id='food'></a>
 
 Here I've worked with data on food market in LA to provide recommendations to investors:
 * Counted various establishment types
 * Found dependencies between type of establishment and belonging to a chain
 * Visualised number of seats distribution
 * Investigated LA streets with a lot of restaurants
 * Described strategies for successful restaurant opening
 
**Key words**: pie chart, bar plot, scatter plot, distribution plot. 

**Libraries used**: pandas, matplotlib, numpy, plotly, seaborn.

<img src="images/08_seats.png" alt="drawing" width="400"/>
<img src="images/08_barplot.png" alt="drawing" width="400"/>

# Course Overview<a id='course'></a>
This is a brief list of topics I've studied:
1. Data Preprocessing (**Python, numpy**)
2. Exploratory Data Analysis (**pandas, scipy, matplotlib**)
3. Statistical Data Analysis (**probability theory, statistics, hypotheses testing**)
4. Data Collection and Storage (**HTML, SQL, web scraping**)
5. Business Analytics (**LTV, CAC, ROMI, cohort analysis**)
6. Making Business Decisions Based on Data (**hypotheses prioritization, A/B testing**)
7. Tell story using data (**plotly, seaborn**)
8. Automation (**ETL, DASH, Tableau**)
9. Forecasts and Predictions (**Machine Learning**)
