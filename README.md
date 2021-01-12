# Frequentist Inference: 

**Frequentist inference** is the process of deriving conclusions about an underlying distribution via the observation of data. In particular, you'll practice writing Python code to apply the following statistical concepts:

   * The z-statistic
   * The t-statistic
   * The difference and relationship between the two
   * The Central Limit Theorem, including its assumptions and consequences
   * How to estimate the population mean and standard deviation from a sample
   * The concept of a sampling distribution of a test statistic, particularly for the mean
   * how to combine these concepts to calculate a confidence interval
   * Calculating confidence intervals and p-values
   * Hypothesis testing
    

There are two parts to the case study: 
   * In part A, we’ll highlight the Pythonic implementation of the concepts underlying frequentist inference. 
   * In Part B, we’ll apply those implementations to a real-world scenario.    
   
   
### Sample & population:    

In general, the sample mean we calculate will not be equal to the population mean (as we saw above). A consequence of this is that the sum of squares of the deviations from the population mean will be bigger than the sum of squares of the deviations from the sample mean. In other words, the sum of squares of the deviations from the sample mean is too small to give an unbiased estimate of the population variance. An example of this effect is given here. Scaling our estimate of the variance by the factor  𝑛/(𝑛−1)  gives an unbiased estimator of the population variance. This factor is known as Bessel's correction. The consequence of this is that the  𝑛  in the denominator is replaced by  𝑛−1 .

[\sqrt{\frac{\sum_i(x_i - \bar{x})^2}{n-1}}]

\frac{\sigma}{\mu}

%5Csqrt%7B%5Cfrac%7B%5Csum_i%28x_i+-+%5Cbar%7Bx%7D%29%5E2%7D%7Bn-1%7D%7D
