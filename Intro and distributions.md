Data
1. Qualitative/Categorical: a) Nominal-Data with no inherent order or ranking. Eg: Eye color (Blue, Brown, Green), Marital status, Country of origin.
   b) Ordinal: Data that has a clear, ordered ranking, but the mathematical distance between the ranks is unmeasurable or inconsistent.Eg: Education level (High School, BS, MS, PhD), Customer satisfaction scales (Poor, Fair, Good, Excellent).
2. Quantitaive/Numerical: a) Discrete: Countable values, often integers. There are distinct "gaps" between values.Examples: Number of children in a family, daily website traffic,
   b) Continuous: Measurable values that can take any infinite value within a given range, Examples: Height, weight, temperature, time taken to run an algorithm.

**Key Foundational Terminology**
Population ($N$):The complete collection of all elements or individuals to be studied.
Sample ($n$): A representative subset of data selected from the population.
Parameter: A numerical characteristic of a population (e.g., population mean, $\mu$).
Statistic: A numerical characteristic of a sample (e.g., sample mean, $\bar{x}$).


**Measures of Dispersion (Spread):**
Variance ($\sigma^2$ or $s^2$): The average squared deviation from the mean.
Standard Deviation ($\sigma$ or $s$): The square root of the variance, bringing the metric back to the original unit of measurement.
Range: The difference between the maximum and minimum values.
Interquartile Range (IQR): $Q_3 - Q_1$, representing the middle 50% of the data. Excellent for spotting outliers.



**Probability**
The 4 Foundational Distributions
1. The Bernoulli Distribution (Discrete- Binary: exactly $0$ or $1$, eg: SNPs )
2. The Binomial Distribution (Discrete, Counts with a fixed ceiling, $0$ to $n$)
3. The Poisson Distribution (Discrete, Counts with no fixed ceiling, $0$ to infinity))
4. The Normal / Gaussian Distribution (Continuous, can take any decimal or fractional value within a range)

Some other imported types of distributions are - 
**Negative Binomial distribution:** When your genomic count data breaks the Poisson rule (Variance $>$ Mean), you mix a Poisson distribution with a Gamma distribution. The result is the Negative Binomial, which allows the variance to stretch.
**Multinomial distribution:** When your Bernoulli trial has more than two outcomes (e.g., instead of just "Success/Failure", you have four alleles: A, C, T, or G), the Binomial distribution turns into the Multinomial distribution.
**Hypergeometric distribution:** f you are drawing samples without replacement (like pulling unique genes out of a genome pool where the pool gets smaller with each draw), the Binomial distribution becomes the Hypergeometric distribution.

<img width="752" height="543" alt="image" src="https://github.com/user-attachments/assets/f8f5568e-27d2-4bb3-a6f0-6240ad376911" />


Bayes theorem comes under, **probability theory:**
Bayes' Theorem is the fundamental formula used to compute and update conditional probabilities when new data becomes available.

<img width="1613" height="917" alt="image" src="https://github.com/user-attachments/assets/5ef6b24a-5412-4f25-851b-df1f1487993f" />

According to Richard, At its core, **Bayesian inference** is a logical method for learning from data. Unlike other statistical frameworks that focus on testing hypotheses with error rates, the Bayesian approach treats parameters (like the proportion of water on a globe) as things we are uncertain about. We represent this uncertainty with probability distributions.

**Bayesian Updating:** The process of taking your existing knowledge (a prior), looking at new evidence (data), and refining your knowledge to reach a new, updated conclusion (a posterior).

1. Generative Model: You start by defining a process that could plausibly create the data you are observing. In this lecture, it is the "globe tossing" model
2. Estimand (The Question): This is the specific thing you want to learn about the world. In the globe example, it is the parameter P, representing the proportion of the globe covered in water
3.  Bayesian Estimator: This is the mathematical "motor" that combines your generative model with the observed data to produce an estimate
4.  Estimate (Posterior Distribution): This is the final product. It is a distribution of relative plausibilities for every possible value of your parameter
5.  Posterior Prediction/Utility: Once you have the estimate, you don't just stop at a number. You use the entire distribution to generate posterior predictions. You push the uncertainty from your posterior back through the generative model to create forecasts, check if your model fits the data, or determine effect sizes

The Estimate is the Distribution: A single number (like a mean) is just a summary for communication. The real "answer" is the whole curve representing your uncertainty 

Probability distribution: Before knowing the estimate, we consider all posible estimates for eg, say finding percentatge of globe covered by water, if we don't have any actual data we consider all 0-100%, these are called pririor probalbilties, as we toss the globe, got some data we will get to know some percentage of water then 0% becaomes impossible, we elimninate 0%, as we get new observation data we remove impossible probabilities- this is called bayesian updating, and the proportions obtained after the calculations are called posterior probablities. 

It is not searching for one "magic" number. You are constantly refining a distribution of possibilities to see where the evidence is pushing you




      
