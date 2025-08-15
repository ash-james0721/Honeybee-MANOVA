# Honeybee-MANOVA

# Problem Statement
* Honeybee colonies in US have faced significant declines in recent years due to several stressors such as pests, disease, pesticide exposure, and environmental factors.
* Honeybee health is critical for pollination, food production, and maintaining a healthy ecosystem. Continued monitoring the impact of stressors helps inform conservation methods.
* Colony outcomes may be influenced by multiple stressors simultaneously, causing univariate analysis to be insufficient.
* In this project, MANOVA was applied to evaluate the impact of multiple reported stressors on key honeybee colony health outcomes.

# Objective
Cleaning the data and performing EDA (Explorative Data Analysis) and check for normality. The objective is to determine if individual, enviromental stressors (i.e., varroa mites, disease, pesticides, etc) were detrimental to honeybee colonies across all 50 states.

# Research Question(s)
* Which state has more honeybee apiaries?
* How truthfull is the data?
* Should `added` and `lost colonies` be comobined to `total colonies`?
* Which stressor is harming the honeybee colonies the most?
* What does the `other` stand for in the data?
   * Does it include data about global warming or other changes in the weather?
* What other models can be used for the dataset?

# Key Results
* There was no statistical evidence that an individual stressor was detrimental to honeybee colonies. Instead, if all of the environmental stressors occured simultaneously, then the likelihood that honeybee colonies becoming endangered increases exponentially.
  This is important because honeybees, alone, contributes to about $15 billion dollars to the US economy according to the USDA.
* MANOVA determined that there wasn't a singular environmnetal stressor that was detrimental to honeybee colonies in the US. This was further proven by doing a comparision analysis using PCA (Principal Component Analysis).

# Further Statistical Recommendations
* Creating a forecasting time series analysis to predict honeybee population over time.
* Separting the `Other` variable to things like weather, temperature (i.e., either in degress or categorically listing it as `High`, `Med`, `Cold`), predation, etc.


## Reference
https://www.usda.gov/about-usda/general-information/initiatives-and-highlighted-programs/peoples-garden/importance-pollinators/honey-bees
