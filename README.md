# HVT
My project concerning the Habitual Voter Theorem. Voter data supplied by the [North Carolina State Board of Elections](https://dl.ncsbe.gov/index.html?prefix=data/). US Census data provided by the [United States Census Bureau](https://factfinder.census.gov/faces/nav/jsf/pages/index.xhtml). Completed June 2017.

- The **census** folder contains census data matched by zip codes for each ncid (voter).
- The **voter_data** folder contains cleaned .xlsx files (100 total) containing voting information for all registered voters of North Carolina.
- The **Interactive Model** folder contains a macro-enabled .xlsx file representing the logistic regression output through a user interface (UI). Instructions for the UI can be found in the **HVT_Appendix.PDF**.
- The R code used to run the regression model is located in the **voter_code.R** file.

# Abstract:
The Habitual Voter Theorem (HVT) suggests that voting is habit-forming: when an individual overcomes the initial costs of turning out to vote (e.g. figuring out his or her polling location, learning how to research the candidates & issues, experiencing the time it takes to cast a ballot), (s)he is more likely to turn out to vote in the future as the costs are lower and the process more familiar. Under this theory, I use a logistic regression to model voter turnout in the 2016 presidential election using data (N = 4,951,648) provided by the North Carolina State Board of Elections and the U.S. Census Bureau. Note: while this model suggests that individuals who had turned out to vote in previous elections (especially the 2012 presidential election) were more likely to vote in the 2016 election, it does not definitively prove the occurrence of habitual voting as this kind of regressing is unable to account for 'unobserved heterogeneity': "unobserved factors that caused past voting behaviour might also cause current turnout" [Green and Shachar, 2000: 563](https://www.cambridge.org/core/journals/british-journal-of-political-science/article/habit-formation-and-political-behaviour-evidence-of-consuetude-in-voter-turnout/4F834B816865D4ED0CE7EEB6C0A710CF). Thus, habitual voting is assumed in this model.
