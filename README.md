<img src="assets/Bobcats.png" alt="Banner" style="width:100%;"/>

<br>

# BobcatsCoyotesFoxes
A MSOE midterm project that focuses on applying data science techniques by analyzing a dataset from a biology research paper. This project determines the best approach for addressing research questions. 

## Introduction
Understanding the distribution and behavior of various species is fundamental to ecology, as it helps ecologists understand the relationship betweem organsims and their environments. There is a lot ecological signifigance behind tracking such species, as researchers can see precisely when individual animals depart from one location and arrive at another. Such insights reveal a individual animal’s seasonal movements, feeding locations and more. Such information is valuable because the more ecologists know about animals’ seasonal usage of habitats, the more they can protect the areas the animals need to survive.

## The Hypothesis
For the project, we decided to come up with a hypothesis as shown below:

<blockquote>
Given that adult Gray Foxes have a greater average body length than adult Bobcats, and a smaller average body length than adult Coyotes, we hypothesize that Gray Fox scat will exhibit a significantly larger average diameter than Bobcat scat, but a smaller average diameter than Coyote scat.
</blockquote>


## The Research Questions
The purpose is to analyze data to evaluate whether specific morphological or biogeochemical traits of scats can
reliably differentiate species. We also look at biological and ecological factors that explain observed patterns. 
As a result, these are the two research questions we look at:
- Which morphological and biogeochemical traits distinguish between originating species of the scar samples?
- Why do the traits differ across the species?

## Data Visualization Techniques
When it came to performing visualization techniques, we had to set a response variable, which was scat species. Given
that the response variable was categorical, this means we performed our visualizations according to the following rules:
- Categorical vs Numerical: for plotting a categorical feature against numerical features, we explored using either
box plots or violin plots
- Categorical vs Categorical: for plotting a categorical feature against categorical features, we explored using
heat maps
The visualizations were performed as we compared the response variable against features from both morphological and
biogeochemical traits.

## Statistical Testing Techniques
When it came to performing statistical testing, we used our previously set response variable which was categorical against a number of categorical and numerical features, this means we performing our statistical testing according to the following rules:
- Kruskal-Wallis: for comparing a categorical variable with multiple values against a numerical variable, it answers
the question of whether atleast one group defined by the categorical variable differs from at-least one other.
- Chi-Squared Test of Independence: it is a hypothesis test for comparing two categorical variables and measures whether there is a ’dependence’ between them
- Dunn Testing: used as a post-hoc analysis after a Kruskal-Wallis test to identify which specific groups are significantly different from each other.
The statistical tests were performed as we compared the response variables against features from both morphological
and biogeochemical traits. The justification for all statistical tests and visualizations were all dependent on the type of variable we were dealing against the response variabl

## Family Wise Error Rate
When it came to determining the family-wise error rate method for each of the tests, we decided to go with bonferroni
correction. It is a multiple comparision adjustment method that reduces the signifigance level to control for false positives when performing multiple hypothesis tests. The justification behind using it is that we would like to reduce the likelihood of false positives when performing multiple comparisions.

## Conclusions
From our findings, we now know that Gray Fox scats have the lowest mean for scat diameter and scat mass. This may
be directly linked to the gray fox having the lowest mass compared to the Bobcat & Coyote. As a result, our hypothesis
was wrong, as the body length may not have a correlation to the size of the scat itself.

