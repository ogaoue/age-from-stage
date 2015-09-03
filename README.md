## Age from Stage Model

This script accompanied Gaoue OG, Horvitz CC, Ticktin T, Steiner U, Tuljapurkar S (2013). Defoliation and bark harvest alter the life history traits of a Tropical tree. Journal of Ecology 101, 1563–1571

The script uses age-from-stage models to estimate life history parameters in constant (PART I) and stochastic (PART II) environments. I created a big function that takes as argument your T matrix (as in A=T + F decomposition) and generate the following output: 

- Life expectancy (stage-specific): mean, variance, sd and cv
- Age specific survivorship curves
- Age specific mortality trajectory
- Mean age at maturity and stage specific reproductve ages
- Sensitivity and Elasticity of life expectancy

