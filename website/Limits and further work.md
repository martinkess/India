

## 5. What have we learned? ##

As detailed in the introduction, we had an ambitious project of having a detailed description of the links between politics, corruption, and business performance.

The outcome was more modest, but it allowed us to gather quite a lot of information on interesting characteristics of Indian candidates and elected members of parliaments, their asset holdings and other characteristics, and the impact on elections.

We draw a few key lessons from  our exploration:

- There are a lot of interesting patterns in the elections data that we can uncover with the single source of the affidavits. Linking criminality, assets, party, education provides important insights about the Indian political process:
	- Over time, the asset difference between elected MPs and other candidates increased 
	- Education is a factor of difference, but less than one would expect

- Predicting election results is easier than we expected: e reach an accuracy of about .92 in the basic models and raise it to .95 with XXXX model. At worst, it matches the naive prediction that no one wins. (.92)

- Asset increases are related to a variety of factors, but winning the last election is a significant and strong predictor. We estimate a coefficient of .12, which means that assets increase by 12 percentage points more for winners than losers. If there is a correlation between talent (or other non-observable variable) and increase in assets, then this is consistent with the literature which finds lower but significant "pure" causal effect of magnitude of 3-6 percentage points

## 6. What are the next steps?

We see several potential next steps:

 1. Using a more balanced dataset at the local level: we were only able to retrieve one wave of state level elections, which should be even more meaningful. Indeed, it seems, according to journalist reports, that politicians' declarations at the national level became less "truthful" as the affidavits were used by the media. According to researchers, state level politicians are on average less 'savvy', or have less resources and connexion to hide their assets.
 2.  Second, we would like to obtain exact election results data at the constituency level. This would allow to see the margins of win and add another dimension to classify politicians. (Fisman, and coauthors have used this, and other authors as well)
 3. Third, we could link more meaningfully outcomes to demographic characteristics of the constituency. How do predictions change if the politician is "very different" or "very similar" to the voters, on dimensions such as income, education, etc.?
 4. Use more the variation within type of assets and types of crimes. Some cases are political in nature (wrongful assembly) and not necessarily indicative of corruption. Others indicate clearly outright theft, corruption, murder, and link to criminal activities. A machine learning framework could allow to classify in a few factors, group similar types of crimes, and distinguish between various types of corruptions. We could imagine supervised (which variables are most likely to be linked to a "corrupt" politician? Or unsupervised: which crimes "look" like each other and allow politicians to be bundled in similar groups.

> Written with [StackEdit](https://stackedit.io/).