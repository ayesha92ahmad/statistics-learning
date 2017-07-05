
<h1>Descriptive Stats</h1>

### Table of Contents

**[1. Introduction](#introduction)**<br>
**[2. Surveys](#surveys)**<br>
**[3. Visualization Techniques](#visualization-techniques)**<br>
**[4. Central Tendency](#central-tendency)**<br>
**[5. Mode](#mode)**<br>
**[6. Mean](#mean)**<br>
**[7. Median](#median)**<br>
**[8. Variability](#variability)**<br>
**[9. Standardizing](#standardizing)**<br>
**[10. Z score](#z-score)**<br>
**[11. PDF](#pdf)**<br>



## Introduction
Constructs- something for which a way to measure has not been found. Eg. happiness, hunger, etc

Operational definition:
A way of turning constructs into variables we can measure.

Lurking variables
correlation does not prove causation

Show relationships => observational studies surveys

Show causation => controlled experiment
Different kinds of studies:
observational studies
surveys
Experiments


## Surveys
why surveys?
- Easy
- inexpensive
- Can be conducted remotely
- anyone can access and analyze survey results
- timeless

Downfalls:
- Susceptible to untruthful responses
- Biased responses
- Respondents not understanding the question
- Respondents refusing to answer the question

Experiments:
Random sample

Blinding- 
placebo- fake treatment

single blind- participatants
double blind- researcher and participants are unaware

## Visualization Techniques

Google spreadsheet tutorial:

Forulae:
  - SUM(a2:a8)
  - Average(a2:a8)
  - Deviation: distance from the mean: a2-$E$1 (so that it remains constant if we copy paste)
  - Variance: sum of squared deviation divided by number of entries
  - Standard deviation(sigma): square root of variance

---
## Central Tendency

Mode : Value where frequency is highest

Median : Value where frequency is in the middle

Mean : Average value

---

## Mode
Mode of distribution - Range that occured with highest frequency

Mode of negatively skewed distribution - ""

Mode of Uniform distribution - No mode

Multimodal - More than one mode

- The mode occurs on the X-axis, so you are looking for whatever value has the highest frequency
- The mode can be used to describe any kind of data
- All scores do not affect the mode
- There is no equation for the mode
- If we take different samples of the same dataset we will get different modes
- If we take different bin size mode changes
- It can be used to describe categorical data such as gender or country of origin but not mean and mode

## Mean
mean = sum/frequency

Properties:
- All scores in the distribution affect the mean
- Mean from different samples in the population may have similarmeans
- Extreme values will change the mean
- Mean with Outliers are misleading

## Median

- Middle of the data
- Useful info from data is arrange in order.
- In uniform distribution mode=mean=median

## Variability

Range = maximum - minimum 
Quartile

first split the data into half
find the median of th first half -> q1
find the median of the second half ->q3
Interquartile range q3-q1 (IQR)


About 50% of the data fall within te IQR
The IQR is not affected by every value in the data set
The IQR is not affected by outliers

Outliers

Outlier < Q1- 1.5 (IQR)
        > Q3 + 1.5 (IQR)


Boxplots 

Min, Q1,Q2,Q3, Max


Measure variability
Average distance between each data and mean

What is so great about the standard deviation?

Normal distribution
68% data falls between 1 standard deviation
95% data falls between 2 standard deviation

Bessels correction 

When we find standard deviation of a sample it tends to be smaller than the standard deviation of the population to correct this we have bessels correction. 

Standard deviation = sqrt(sum(xi-xbar)^2)/(n-1)) (instead of n) 
variance = sum(xi-xbar)^2)/(n-1)

makes the original standard dev bigger

## Standardizing

Relative frequency
- Relative frequency distribution looks almost the same as absolute frequency distribution

Smaller bin size will help us get more detail

Continuous distribution

Smooth curve of relative frequency

area under the the theoretical continous curve =1
Normal distribution curve
Mean =median = mode

# Z score
Location on x axis is described by using standard deviation. Eg 1 sd, 2sd etc
Z = number of standard deviation away from mean

Negative z score
means that x is less than mean
z=(x-mean)/sigma

average of new z indexes if we convert all data points to z index =0

## PDF

In a normal distribution, area under the curve can be used to calculate the probability

Tails never actually touch the x axis

- infinity to x is x percentile

Z table: Areas under the standard normal curve


[Link to Worksheets](https://docs.google.com/spreadsheets/d/1612-HXV2WVqfWcpHBsPf5uJWuB4CNB1IK-7IBQiBv80/edit?usp=sharing)
