# Sparrow Dataset Analysis

![](images/song_sparrow_1.jpg)

Reproductive success in bird populations is influenced by a variety of factors, including fitness, age, competition, nesting site quality, and environmental conditions. This study analyzes a 19-year observational dataset of song sparrows on a Pacific Northwest island to investigate these factors. These sparrows are monogamous, with females beginning to mate at one year old and often reusing the same nesting sites due to their territorial nature, even under suboptimal conditions. The dataset includes detailed information on individual sparrows, such as their age, nesting location, the year they were tagged, and the number of offspring produced. It also captures broader variables, such as the year of the study and population density, offering a comprehensive view of factors influencing reproductive success.


The primary objective of this analysis is to understand the ecological and biological sources of variability in reproductive success among song sparrows. Specifically, this study addresses the following questions:

- How do individual-level factors, such as age or nesting location, and population-level variables, such as competition (population density), influence reproductive success?

- Are there observable trends or patterns in reproductive success across different years or cohorts of sparrows?

- How do individual characteristics and environmental factors interact to influence variability in reproductive outcomes?

To address these questions, this analysis uses a **linear mixed-effects model** (Bates et al. (2014)) with fixed effects for female population density, spatial location, and age, and a random intercept for year. Moreover, it incorporates an AR(1) (Box et al. (1994)) **correlation structure** to account for temporal autocorrelation. The results show that population and nesting location significantly affect reproductive success, while age has no statistically significant impact. Temporal variability is effectively captured by the random intercept and the AR(1) structure, highlighting year-to-year differences in reproductive outcomes. This study highlights the need to account for both fixed and random effects to understand ecological processes and suggests future model improvements, such as exploring non-linear patterns and additional ecological variables.
