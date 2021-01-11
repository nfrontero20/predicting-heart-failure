# predicting-heart-failure

Heart failure is a cardiovascular disease that happens when the heart cannot pump enough blood and oxygen throughout the body [(CDC, 2020)](https://www.cdc.gov/heartdisease/heart_failure.htm).  In the United States alone, about 6.2 million adults have heart failure. When considered on a worldwide scale, heart failure is referred to as a "global pandemic" [(Savarese & Lund, 2017)](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5494150/).  While scientists and doctors are aware of risk factors for developing heart failure [(CDC, 2020)](https://www.cdc.gov/heartdisease/heart_failure.htm), it is difficult at present for doctors to predict the survival of patients who already have heart failure [(Chicco & Jurman, 2020)](https://bmcmedinformdecismak.biomedcentral.com/articles/10.1186/s12911-020-1023-5).  

In their paper titled "[Machine learning can predict survival of patients with heart failure from serum creatinine and ejection fraction alone](https://bmcmedinformdecismak.biomedcentral.com/articles/10.1186/s12911-020-1023-5)," researchers Davide Chicco and Giuseppe Jurman set out to predict the survival of patients with heart failure by performing machine learning techniques on medical records data.  I was interested in extending Chicco and Jurman's work by performing clustering and classification analyses on their data.

Being able to answer the question "Does this individual belong to a particular subgroup of patients, and does that help us predict their survival?" has lasting implications for the field of cardiovascular health.  Understanding individual patients' risk factors will allow physicians to provide personalized medicine that can hopefully increase the chances of a patient's survival.  

I was interested in using clustering techniques because I knew that if I could identify groups of individuals among those with heart failure, I could make group-specific models for predicting survival.  I wanted to use classification techniques so that I could not only predict survival, but also could learn what the most important variables were in this prediction process.

[data.csv](https://github.com/nfrontero20/predicting-heart-failure/blob/master/data.csv)
[report.Rmd](https://github.com/nfrontero20/predicting-heart-failure/blob/master/report.Rmd)
[report.pdf](https://github.com/nfrontero20/predicting-heart-failure/blob/master/report.pdf)
