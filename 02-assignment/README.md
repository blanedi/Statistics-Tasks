
---
title: "Assignment 2 - The backdoor criterion, regression, and matching"
date: "September 19, 2023"
output: html_document
---

## Task 1 - Interpreting a Causal Graph

1. **Reproduce and plot this DAG using ggdag.** Highlight observed vs unobserved traits by node filling.
2. **List all paths (causal and non-causal) in the graph.** There are 10 paths from d->y, with 2 closed paths.
3. **Identify backdoor paths.** There are 6 backdoor paths.
4. **Variables to satisfy the backdoor criterion:** { u, z } and { x, z }
5. **Effect of observing U:** It's necessary to control for "u" to satisfy the backdoor criteria.

## Task 2 - Smoking behavior and infant birth weight

1. **Estimated model:** bwght=β0+β1cigs+β2male
2. **Change in birth weight for 20 more cigarettes/day:** 0.39 ounces more for girls than boys.
3. **Estimated birth weight for baby girl with mother smoking 15 cigarettes/day:** 110.5358 ounces.
4. **Variation in birth weight explained by gender and cigarette consumption:** 27%
5. **Extended model covariates:** Parity and being white are significant.

## Task 3 - Consequences of child soldiering

1. **Covariate balance in unmatched dataset:** Education, age, and certain sub-districts are significant factors.
2. **Naive average treatment effect (NATE) of abduction on education:** -0.595
3. **Exact matched and propensity score models:** Effect of abduction on education is not significant after propensity score matching.

## Task 4 - One more causal graph and simulation

1. **Simulated data:** Grades, motivation, and attendance are related.
2. **Regression results:** Motivation is a significant factor for grades.
3. **Effect of confounder:** Motivation biases the results.
4. **Randomized workshop:** Randomizing workshop attendance can provide a more accurate result.

## Task 5 - Statistics inspired meme

