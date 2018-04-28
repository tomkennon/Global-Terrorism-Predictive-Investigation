# Global-Terrorism-Predictive-Investigation
Review descriptive statistics and apply supervised learning techniques to predict various outcomes in Global Terrorism trends


## Summary of Findings

We know from our descriptive analysis, that terrorist attacks, as well as number of people killed in terrorist attacks, are increasing worldwide.  Even accounting for the world's growing population, the number of attacks are still rising per capita at an alarming rate.  So thus, there is not just a recency bias as some may have speculated.  We will seek to model and interpret why this could be later in our project.  There have also been a lot of terrorist attacks in the Middle East and South Asia.  This fact is highly known in current events as there is a lot of political turmoil in many of those nations.  We have also seen that there has been a large increase in bombings in recent years, as well as a mild spike in armed assault both of which also have the highest gross total of attacks since 1970.  Since the late 1990’s/early 2000’s, this increase has been seen.  Why is this so?  This is a question we wish to further explore in our predictive analysis in the future; is this increase because terrorist attacks of this type are more successful?  We also observed that terrorist groups like Islamic State of Iraq and the Levant and Al-Shabaab are on the rise recently, while the Taliban has the most successful attacks since 1970.


For predicting if the terrorist group was "ISIL" or not using a Naive Bayes model, our null model showed that if we assume all attacks are committed by ISIL, we are only right about 7.5 percent of the time. However, we were able to correctly determine if an attack was carried out by ISIL with 17.67 percent accuracy in our training set, and with about 17.21 percent accuracy in our testing set.  So we are decently better at predicting by accuracy than the null model.

For predicting if the terrorist attack was a "mass attack" or not using a Decision tree and Random Forest, we could conclude that the Random Forest model was the best predictor of mass terrorism attacks. This said, it is important to note that neither the Decision Tree nor the Random Forest model improved on the null by more than 2% in accuracy.

For predicting if a terrorist attack was a success, we produced 4 different prediction models, including Naive Bayes, Decision Tree, Random Forest, and even a Logistic Regression, with the Random Forest performing the best and all of our models beating the null.  We feel we have accomplished the goals and exploratory questions we originally set out to accomplish in this analysis



## Files
The files in this repository are as follows:
- [RMD](https://github.com/tomkennon/Global-Terrorism-Predictive-Investigation/blob/master/FINAL_writeup.Rmd)
- [PDF](https://github.com/tomkennon/Global-Terrorism-Predictive-Investigation/blob/master/FINAL_writeup.pdf)

## File Types
This {.PDF} paper is generated from an R markdown {.Rmd} file.  The datasets {.csv} and image files {.png} used are included in the repository to allow for reproducible code.
