Hypothesis testing(HT) uses sample data to evaluate the plausibility of a specific claim about a population parameter. In biological research, it allows us to distinguish between random experimental noise and true biological signal.
Steps involved in hypothesis testing
1. State the hypothesis
2. Compute the test statistic
3. Determine p-value
4. Conclusions

Null Hypothesis (H₀): The default assumption that there is no effect, no difference, or no relationship.

Alternative Hypothesis (H₁ or \(H_{A}\)): Your research claim; the statement that there is a difference or effect

p-value helps to quantify uncertainity

p- value ranges from 0-1, quantify the difference between the effect of event 1 and event 2. 

smaller the p -value close to 0, more confident to say both are different and reject null hypothesis. 

Smaller means how much smaller, to say reject null hypothesis confidently- It should be less than or equal to the significance level, alpha

Most of the time, alpha is 0.05, which means out of 100% the decision is wrong 5% of the time. To make it stricter, sometimes it could be 0.01%, meaning only a 1% chance for errors. 

Conclusions based on p- value and alpha
Compare the p-value to your significance level $\alpha$:

If $p \le \alpha \rightarrow$ Reject $H_0$ (Statistically significant result).

If $p > \alpha \rightarrow$ Fail to Reject $H_0$ (Inconclusive result).




**Errors in hypothesis testing:** two types of errors, type 1 and type 2
Type 1 error: Rejecting the true null hypothesis; the significance level, alpha, sets the probability of committing the type 1 error, it can be reduced by decreasing the alpha value, e.g., from 0.05 to 0.01, but this increases the type 2 error chances
Type 2 error: Failing to reject the false null hypothesis

### Summary: Error Severity Comparison

* **Type I Error ($\alpha$ / False Positive):** Rejecting a true $H_0$.
  * *Impact:* Wasted resources, unnecessary follow-ups, false leads.
* **Type II Error ($\beta$ / False Negative):** Failing to reject a false $H_0$.
  * *Impact:* Missed diagnoses, discarded discoveries, unmitigated risks.
* **Rule of Thumb:** In biological and clinical sciences, **Type II errors are generally considered more dangerous** due to the fatal risk of missed detection.
* **Mitigation:** Increase sample size ($n$) to boost Statistical Power ($1 - \beta$) without inflating $\alpha$.

Power of the test: probability of random sample will lead to rejection of false null hypothesis, that is reducing type 2 error. 
test’s ability to detect a true biological effect when one actually exists.

