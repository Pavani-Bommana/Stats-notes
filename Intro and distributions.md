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
1. The Bernoulli Distribution (Discrete)
2. The Binomial Distribution (Discrete)
3. The Poisson Distribution (Discrete)
4. The Normal / Gaussian Distribution (Continuous)

Some other imported types of distributions are - 
**Negative Binomial distribution:** When your genomic count data breaks the Poisson rule (Variance $>$ Mean), you mix a Poisson distribution with a Gamma distribution. The result is the Negative Binomial, which allows the variance to stretch.
**Multinomial distribution:** When your Bernoulli trial has more than two outcomes (e.g., instead of just "Success/Failure", you have four alleles: A, C, T, or G), the Binomial distribution turns into the Multinomial distribution.
**Hypergeometric distribution:** f you are drawing samples without replacement (like pulling unique genes out of a genome pool where the pool gets smaller with each draw), the Binomial distribution becomes the Hypergeometric distribution.



      
