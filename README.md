![Python](https://img.shields.io/badge/python-3.13-blue.svg)
![Black](https://img.shields.io/badge/code%20style-black-000000.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)
![Scikit-learn](https://img.shields.io/badge/ML-scikit--learn-F7931E.svg)
![Pandas](https://img.shields.io/badge/pandas-2.3.3-150458.svg)
![NumPy](https://img.shields.io/badge/numpy-2.2.2-013243.svg)
![Matplotlib](https://img.shields.io/badge/matplotlib-3.10.0-11557c.svg)

## 🎯 Business Context & Goals
### Problem Statement
Pupperoni Pizza is a (fictitious) company specializing in pizza-themed dog accessories. 
Even though traffic has remained steady at 10,000 visits per month on average, sales have declined.
Company leadership thinks that modernzing the website could help.
To assess the impact of the potential update, an AB test is conducted.

## 📌 Project Overview
- **Data**: All data is synthetic and created with algorithms.
- **Methods**: Univariate A/B Testing, Quantitative Analysis.

### Research Questions & Hypotheses
1. Which website layout leads to higher sale conversion?
   <br>a. Null hypothesis: There is no difference in order frequency between the two website versions.
   <br>b. Alternative hypothesis: There is a difference in order frequency between the two website versions.
2. Which website layout is more efficient, in terms of time spent on website, for customers?
   <br>a. Null hypothesis: There is no difference in site navigation time between the two website versions.
   <br>b. Alternative hypothesis: There is a difference in site navigation time between the two website versions.

### Success Metrics
- Primary: Sale conversion rate
- Secondary: Website navigation time

## 🔍 Research Design
### Test Variations
- **Control (A)**: Current layout with single page listing all available products in alphabetical order.
- **Treatment (B)**: 4 tab navigation layout with primary product categories - collars, leashes, beds, and stuffed toys.

### Methodology
- Target sample size from power calculation (0.8) from baseline sale conversion rate = 4000
- Test Duration: 27 days = 4000(N) / (300/day * 0.5)
- Random Assignment: 50/50 split of incoming traffic (2000/2000)
- Confidence Level: 95%

## 📊 Analysis & Findings
### Quantitative Results
- 38.7% increase in sale rate for the treatment condition (p < .001, medium effect)
- Users in treatment condition spend 4.98 less minutes on site on the average (p < .001, medium effect)

### Key Insights
1. Organized tabs led to quicker navigation and product finding.
2. Organized tabs led to more items being added to cart.
3. Organized tabs led to more sales. 

## 💡 Recommendations
1. Roll out new navigation to all users
2. Monitor long-term impact especially during different seasons 
3. Plan follow-up research for edge cases
4. Assess returning user rate post-launch

## 📝 Notes
- All data is synthetic and created for this portfolio example
- Project showcases research process and methodology 
