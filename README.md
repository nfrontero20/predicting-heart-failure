# predicting-heart-failure

## Background

Heart failure is a cardiovascular disease that happens when the heart cannot pump enough blood and oxygen throughout the body [(CDC, 2020)](https://www.cdc.gov/heartdisease/heart_failure.htm).  In the United States alone, about 6.2 million adults have heart failure. When considered on a worldwide scale, heart failure is referred to as a "global pandemic" [(Savarese & Lund, 2017)](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5494150/).  While scientists and doctors are aware of risk factors for developing heart failure [(CDC, 2020)](https://www.cdc.gov/heartdisease/heart_failure.htm), it is difficult at present for doctors to predict the survival of patients who already have heart failure [(Chicco & Jurman, 2020)](https://bmcmedinformdecismak.biomedcentral.com/articles/10.1186/s12911-020-1023-5). 

## My goals

In their paper titled "[Machine learning can predict survival of patients with heart failure from serum creatinine and ejection fraction alone](https://bmcmedinformdecismak.biomedcentral.com/articles/10.1186/s12911-020-1023-5)," researchers Davide Chicco and Giuseppe Jurman set out to predict the survival of patients with heart failure by performing machine learning techniques on medical records data.  I was interested in **extending Chicco and Jurman's work by performing clustering and classification analyses on their data**.

I was interested in using clustering techniques because I knew that if I could identify groups of individuals among those with heart failure, I could make group-specific models for predicting survival.  I wanted to use classification techniques so that I could not only predict survival, but also could learn what the most important variables were in this prediction process.

Ultimately, being able to answer the question "Does this individual belong to a particular subgroup of patients, and does that help us predict their survival?" has lasting implications for the field of cardiovascular health.  Understanding individual patients' risk factors will allow physicians to provide personalized medicine that can hopefully increase the chances of a patient's survival. 

## Report

I created a **report of my analyses**, which can be found in [report.pdf](https://github.com/nfrontero20/predicting-heart-failure/blob/master/report.pdf).  The Rmd of the report is [report.Rmd](https://github.com/nfrontero20/predicting-heart-failure/blob/master/report.Rmd), and [data.csv](https://github.com/nfrontero20/predicting-heart-failure/blob/master/data.csv) contains Chicco & Jurman's data.

The report has multiple sections, which can be summarized as follows: 

**1. Introduction:** motivation, overview of report

**2. Preliminary analysis:** description of data, data wrangling, univariate analysis, bivariate analysis, outliers

**3. Methods:** brief review of clustering and classification methods, discussion of how I implemented these methods

**4. Results:** creation of three clustering models, creation of two classification models, reporting of results, choice of best model

**5. Conclusion:** review of report, limitations, future directions
