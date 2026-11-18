# Project Proposal

To the BST 260 Teaching Team, Fall 2026,

I’m interested in using NHANES data to understand the effects of
socioeconomic factors on disease onset time for diabetes patients. The
exposures include household annual income, education, physical
activeness, and alcohol consumption. Adjusting for confounding
introduced by variables like age, BMI, gender, and race, I am mainly
interested in the age, in years, when participants were diagnosed with
Diabetes (continuous).

The analysis will focus on all participants diagnosed with diabetes and
have reported the age of disease onset. Diabetes patients without a
reported age of onset will be dropped from the analysis. Similarly,
patients without information on HHincome, education, physical
activeness, and alcohol consumption will be dropped from the
current-stage of our analysis.

To examine alcohol consumption, we will use “Alcohol12PlusYr” as a proxy
for a binary variable, where $`X_i = 1`$ for individuals who reported
with smoking history of 12+ years, and $`0`$ otherwise. Education and
household income will be examined as categorical variables. Physical
activeness is a self-reported binary variable coded as “yes” or “no” and
will remain a binary variable in our analysis. I am hoping to build a
regression model to explore potential effects of socioeconomic factors
on the time when people develop diabetes. If time allows, I would like
to examine if there’s any significant difference in these risk factors,
between diabetes and non-diabetes patients.

Another question that I’m interested in will be based on the waterborne
data set. Out of all confirmed waterborne pathogens collected from 2020
to 2023 in Florida, does water exposure have an effect on the number of
cases in outbreak? The outcome will be number of cases and I plan to
include confounding variables like “setting” and water type, which are
both categorical variables.
