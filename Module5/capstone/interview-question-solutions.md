# Module 5 - Applied Statistics

## Capstone -- End Course Summative Assignment

**Problem Statement: Write the Solutions to the Top 50 Interview Questions and Explain any 5 Questions in a Video**

### 1. What is a vector in mathematics?

A vector in mathematics is like an arrow that has both a direction and a length (magnitude). Imagine you're playing a video game and your character can move up, down, left, or right. Each move can be represented by a vector.

**Example:**  
If you move 3 steps to the right and 2 steps up, this can be represented as the vector (3, 2).

### 2. How is a vector different from a scalar?

A scalar is just a single number that represents a quantity, like temperature or weight. It has no direction, only magnitude.

A vector, on the other hand, has both magnitude and direction.

**Example:**

- Scalar: The temperature is 30°C.
- Vector: The wind is blowing 30 km/h to the north.

### 3. What are the different operations that can be performed on vectors?

Here are some common operations on vectors:

- **Addition:** Adding two vectors together.
- **Subtraction:** Subtracting one vector from another.
- **Scalar Multiplication:** Multiplying a vector by a scalar (a single number).
- **Dot Product:** A way to multiply two vectors that results in a scalar.
- **Cross Product:** A way to multiply two vectors that results in another vector (only in 3D space).

**Example:**  
If vector A = (2, 3) and vector B = (1, 4):

- Addition: A + B = (2 + 1, 3 + 4) = (3, 7)
- Subtraction: A - B = (2 - 1, 3 - 4) = (1, -1)

### 4. How can vectors be multiplied by a scalar?

When you multiply a vector by a scalar, you multiply each component of the vector by that scalar.

**Example:**  
If vector A = (2, 3) and the scalar is 4:

4 _ A = 4 _ (2, 3) = (4 _ 2, 4 _ 3) = (8, 12)

### 5. What is the magnitude of a vector?

The magnitude of a vector is its length. You can find it using the Pythagorean theorem.

**Example:**  
For vector A = (3, 4), the magnitude is calculated as:

$$ \text{Magnitude} = \sqrt{3^2 + 4^2} = \sqrt{9 + 16} = \sqrt{25} = 5 $$

### 6. How can the direction of a vector be determined?

The direction of a vector can be found using the angle it makes with a reference axis (like the x-axis). This is often calculated using trigonometry.

**Example:**  
For vector A = (3, 4), the direction (angle θ) can be found using:

$$ \theta = \tan^{-1}\left(\frac{4}{3}\right) \approx 53.13^\circ $$

### 7. What is the difference between a square matrix and a rectangular matrix?

A square matrix has the same number of rows and columns, while a rectangular matrix has a different number of rows and columns.

**Example:**

- Square Matrix: $`\begin{pmatrix} 1 & 2 \\ 3 & 4 \end{pmatrix}`$
- Rectangular Matrix: $`\begin{pmatrix} 1 & 2 & 3 \\ 4 & 5 & 6 \end{pmatrix}`$

### 8. What is a basis in linear algebra?

A basis is a set of vectors that, when combined (through addition and scalar multiplication), can produce any vector in a given space. These vectors are linearly independent and span the space.

**Example:**  
In 2D space, the vectors (1, 0) and (0, 1) form a basis because you can create any vector in 2D space by combining these two vectors.

### 9. What is a linear transformation in linear algebra?

A linear transformation is a function that takes a vector and maps it to another vector in a way that preserves vector addition and scalar multiplication.

**Example:**  
If T is a linear transformation that doubles the components of a vector, then T(2, 3) = (4, 6).

### 10. What is an eigenvector in linear algebra?

An eigenvector of a matrix is a vector that, when the matrix is applied to it, only gets scaled by a certain factor (the eigenvalue) and does not change direction.

**Example:**  
For the matrix $`\begin{pmatrix} 2 & 0 \\ 0 & 3 \end{pmatrix}`$, the vector (1, 0) is an eigenvector with eigenvalue 2, because:

$`\begin{pmatrix} 2 & 0 \\ 0 & 3 \end{pmatrix} \begin{pmatrix} 1 \\ 0 \end{pmatrix} = \begin{pmatrix} 2 \\ 0 \end{pmatrix} = 2 \begin{pmatrix} 1 \\ 0 \end{pmatrix}`$

### 11. What is the gradient in machine learning?

The gradient is a vector that points in the direction of the steepest increase of a function. In machine learning, we often use it to find the minimum value of a loss function (a measure of how bad our model is).

**Example:**  
If you think of a hill, the gradient at any point shows the direction to climb to reach the top fastest. In machine learning, we usually want to go in the opposite direction (downhill) to minimize errors.

### 12. What is backpropagation in machine learning?

Backpropagation is a method used to train neural networks. It works by calculating the gradient of the loss function with respect to each weight by using the chain rule of calculus, and then updating the weights to reduce the loss.

**Example:**  
Imagine you are adjusting the aim in a video game to hit a target. You first shoot (forward pass), see where you missed (calculate error), and then adjust your aim (update weights) to get closer next time.

### 13. What is the concept of a derivative in calculus?

A derivative measures how a function changes as its input changes. It represents the slope of the function at any given point.

**Example:**  
If you are driving a car and you look at how your speed changes with time, the derivative of your position with respect to time is your speed.

### 14. How are partial derivatives used in machine learning?

Partial derivatives measure how a function changes as one of its inputs changes, keeping the other inputs constant. In machine learning, they help in understanding how changing each weight affects the loss function.

**Example:**  
If you are baking a cake, and you want to know how changing the amount of sugar affects the taste while keeping all other ingredients the same, you're looking at a partial derivative.

### 15. What is probability theory?

Probability theory is the branch of mathematics that deals with the likelihood of events happening. It provides tools to quantify uncertainty.

**Example:**  
If you flip a coin, probability theory helps you calculate that there is a 50% chance it will land on heads and a 50% chance it will land on tails.

### 16. What are the primary components of probability theory?

The primary components include:

- **Random Experiments:** Actions with uncertain outcomes (e.g., rolling a dice).
- **Sample Space:** All possible outcomes of a random experiment (e.g., {1, 2, 3, 4, 5, 6} for a dice roll).
- **Events:** A subset of the sample space (e.g., rolling an even number).
- **Probability Measure:** A function that assigns a probability to each event.

### 17. What is conditional probability, and how is it calculated?

Conditional probability is the probability of an event occurring given that another event has already occurred. It's calculated using the formula:

$$ P(A|B) = \frac{P(A \cap B)}{P(B)} $$

**Example:**  
If you have a deck of cards and you want to know the probability of drawing an Ace given that you've already drawn a King, you use conditional probability.

### 18. What is Bayes' theorem, and how is it used?

Bayes' theorem relates the conditional probability of two events. It is expressed as:

$$ P(A|B) = \frac{P(B|A) \cdot P(A)}{P(B)} $$

It is used to update the probability of a hypothesis based on new evidence.

**Example:**  
If a doctor knows the probability of a patient having a disease and the probability of a test result given the disease, Bayes' theorem helps the doctor update the probability of the disease based on the test result.

### 19. What is a random variable, and how is it different from a regular variable?

A random variable is a variable that takes on different values based on the outcome of a random event. Unlike a regular variable that has a fixed value, a random variable has a set of possible values and a probability distribution.

**Example:**  
Rolling a dice and recording the result is a random variable because the outcome can be any number from 1 to 6, each with a probability.

### 20. What is the law of large numbers, and how does it relate to probability theory?

The law of large numbers states that as the number of trials in a random experiment increases, the average of the results will get closer to the expected value.

**Example:**  
If you flip a coin many times, the proportion of heads will get closer to 50% as the number of flips increases.

### 21. What is the central limit theorem, and how is it used?

The central limit theorem (CLT) states that the distribution of the sample mean of a large number of independent, identically distributed variables will be approximately normally distributed, regardless of the original distribution of the variables. This is incredibly useful because it allows us to make inferences about population parameters using the normal distribution.

**Example:**
If you measure the heights of 30 people from different schools, their average height will form a normal distribution, even if the heights themselves do not follow a normal distribution.

### 22. What is the difference between discrete and continuous probability distributions?

- **Discrete Probability Distribution:** Deals with variables that can take on distinct, separate values. The probabilities are associated with individual points.

  - **Example:** Rolling a six-sided die. The possible outcomes are 1, 2, 3, 4, 5, and 6.

- **Continuous Probability Distribution:** Deals with variables that can take on any value within a range. The probabilities are associated with intervals rather than individual points.
  - **Example:** The height of students in a class. Heights can be any value within a range, like 150.5 cm, 150.55 cm, etc.

### 23. What are some common measures of central tendency, and how are they calculated?

- **Mean:** The average of all the data points.

  $$\text{Mean} = \frac{\sum x_i}{n}$$

  **Example:** For data points 2, 3, 4, the mean is $`\frac{2+3+4}{3} = 3`$.

- **Median:** The middle value when the data points are arranged in order.
  **Example:** For data points 2, 3, 4, the median is 3. If the data points are 2, 3, 4, 5, the median is $`\frac{3+4}{2} = 3.5`$.

- **Mode:** The most frequent value in the dataset.
  **Example:** For data points 2, 2, 3, 4, the mode is 2.

### 24. What is the purpose of using percentiles and quartiles in data summarization?

Percentiles and quartiles help summarize and understand the distribution of data. They indicate the relative standing of a data point within a dataset.

- **Percentiles:** Indicate the value below which a given percentage of observations fall.
  **Example:** The 90th percentile is the value below which 90% of the data points lie.

- **Quartiles:** Divide data into four equal parts.
  - **Q1 (1st Quartile):** 25th percentile.
  - **Q2 (2nd Quartile/Median):** 50th percentile.
  - **Q3 (3rd Quartile):** 75th percentile.

### 25. How do you detect and treat outliers in a dataset?

**Detection:**

- **Visual Methods:** Box plots, scatter plots.
- **Statistical Methods:** Z-scores (values more than 3 standard deviations from the mean), IQR method (values outside 1.5 \* IQR from Q1 or Q3).

**Treatment:**

- **Remove Outliers:** If they are errors or irrelevant.
- **Cap Outliers:** Limit their values to a certain threshold.
- **Transform Data:** Apply log transformation or other methods to reduce the impact of outliers.

**Example:** If most of your data points are between 10 and 20, but you have one point at 100, that's likely an outlier.

### 26. How do you use the central limit theorem to approximate a discrete probability distribution?

When dealing with a large sample size from a discrete probability distribution, the central limit theorem allows you to approximate the distribution of the sample mean as a normal distribution.

**Example:** If you roll a die 30 times and calculate the average roll, the distribution of these averages will be approximately normal, even though the roll outcomes are discrete.

### 27. How do you test the goodness of fit of a discrete probability distribution?

**Chi-Square Test:**

- Compare observed frequencies with expected frequencies.
- Calculate the chi-square statistic:

  $$\chi^2 = \sum \frac{(O_i - E_i)^2}{E_i}$$

  Where $`O_i`$ is the observed frequency and $`E_i`$ is the expected frequency.

- Compare the calculated chi-square value with the critical value from the chi-square distribution table.

**Example:** If you want to see if a die is fair, you roll it 60 times and compare the observed frequencies of each outcome to the expected frequency (10 for each number).

### 28. What is a joint probability distribution?

A joint probability distribution gives the probability of two or more events happening at the same time. It shows the probability of different combinations of outcomes for multiple random variables.

**Example:** If you roll two dice, the joint probability distribution would show the probability of getting each possible pair of outcomes (e.g., (1,1), (1,2), etc.).

### 29. How do you calculate the joint probability distribution?

To calculate the joint probability distribution, you need to determine the probability of each combination of outcomes for the random variables.

**Example:**
If you roll two dice:

- Probability of (1,1) is $` \frac{1}{36} `$ (since there are 6 sides on each die and 36 possible outcomes in total).

### 30. What is the difference between a joint probability distribution and a marginal probability distribution?

- **Joint Probability Distribution:** Gives the probability of different combinations of outcomes for multiple random variables.

  - **Example:** Probability of rolling a 1 on the first die and a 2 on the second die.

- **Marginal Probability Distribution:** Gives the probability of a single event happening, irrespective of other events.
  - **Example:** Probability of rolling a 1 on the first die, regardless of what happens on the second die.

### 31. What is the covariance of a joint probability distribution?

Covariance measures how much two random variables change together. If they tend to increase and decrease together, the covariance is positive. If one increases while the other decreases, the covariance is negative.

**Example:**
If students' study hours and their exam scores both increase together, the covariance is positive.

Mathematically:

$$ \text{Cov}(X, Y) = \sum (x_i - \mu_X)(y_i - \mu_Y)P(x_i, y_i) $$

### 32. How do you determine if two random variables are independent based on their joint probability distribution?

Two random variables are independent if the joint probability distribution is the product of the marginal probabilities of each variable.

$$ P(X = x, Y = y) = P(X = x) \times P(Y = y) $$

**Example:**
If the probability of rolling a 3 on the first die is 1/6 and rolling a 5 on the second die is 1/6, then the joint probability of both events occurring together is:

$$ P(X = 3, Y = 5) = \frac{1}{6} \times \frac{1}{6} = \frac{1}{36} $$

### 33. What is the relationship between the correlation coefficient and the covariance of a joint probability distribution?

The correlation coefficient (ρ) is a normalized version of covariance, showing the strength and direction of the linear relationship between two variables. It ranges from -1 to 1.

$$ \rho\_{XY} = \frac{\text{Cov}(X, Y)}{\sigma_X \sigma_Y} $$

**Example:**
If the covariance between study hours and exam scores is 10, and the standard deviations of study hours and exam scores are 2 and 5 respectively, then:

$$ \rho\_{XY} = \frac{10}{2 \times 5} = 1 $$

This indicates a perfect positive linear relationship.

### 34. What is sampling in statistics, and why is it important?

Sampling is the process of selecting a subset of individuals from a population to estimate characteristics of the whole population. It is important because it is often impractical or impossible to study an entire population.

**Example:**
To estimate the average height of students in a school, you might measure the height of 50 students instead of all 500 students.

### 35. What are the different sampling methods commonly used in statistical inference?

Common sampling methods include:

- **Simple Random Sampling:** Every individual has an equal chance of being selected.
- **Stratified Sampling:** The population is divided into subgroups (strata) and random samples are taken from each stratum.
- **Cluster Sampling:** The population is divided into clusters, and some clusters are randomly selected for sampling.
- **Systematic Sampling:** Every nth individual is selected from a list.

**Example:**
For stratified sampling, if a school has 60% boys and 40% girls, you could ensure your sample reflects this proportion by randomly selecting students accordingly.

### 36. What is the central limit theorem, and why is it important in statistical inference?

The central limit theorem (CLT) states that the sampling distribution of the sample mean will be approximately normally distributed, regardless of the population distribution, given a sufficiently large sample size. This is important because it allows us to use normal distribution techniques for inference.

**Example:**
If you repeatedly measure the average height of samples of 30 students from a school, the distribution of these averages will be normal, even if individual heights are not normally distributed.

### 37. What is the difference between parameter estimation and hypothesis testing?

- **Parameter Estimation:** Involves estimating the value of a population parameter (e.g., mean, proportion) using sample data.

  - **Example:** Estimating the average height of students in a school based on a sample.

- **Hypothesis Testing:** Involves making a decision about a population parameter based on sample data, typically by testing a null hypothesis.
  - **Example:** Testing if the average height of students in a school is greater than 150 cm.

### 38. What is the p-value in hypothesis testing?

The p-value is the probability of obtaining a test statistic at least as extreme as the one observed, assuming the null hypothesis is true. It helps determine the statistical significance of the test.

**Example:**
If you test whether a coin is fair, and you get a p-value of 0.03, it means there's a 3% chance of getting the observed results (or more extreme) if the coin is fair.

### 39. What is confidence interval estimation?

A confidence interval is a range of values, derived from the sample, that is likely to contain the population parameter with a certain level of confidence (e.g., 95%).

**Example:**
If you estimate the average height of students to be 160 cm with a 95% confidence interval of [158 cm, 162 cm], you are 95% confident that the true average height is between 158 cm and 162 cm.

### 40. What are Type I and Type II errors in hypothesis testing?

- **Type I Error (False Positive):** Rejecting the null hypothesis when it is actually true.

  - **Example:** Concluding that a coin is biased when it is actually fair.

- **Type II Error (False Negative):** Failing to reject the null hypothesis when it is actually false.
  - **Example:** Concluding that a coin is fair when it is actually biased.

### 41. What is the difference between correlation and causation?

- **Correlation:** Indicates that two variables are related, meaning they change together, but it does not imply that one variable causes the other to change.

  - **Example:** Ice cream sales and drowning incidents are correlated because both increase during the summer, but buying ice cream doesn't cause drowning incidents.

- **Causation:** Indicates that one variable directly affects the other.
  - **Example:** Smoking causes lung cancer. Here, smoking is the cause, and lung cancer is the effect.

### 42. How is a confidence interval defined in statistics?

A confidence interval is a range of values, derived from the sample data, that is likely to contain the true population parameter. It is defined by the sample estimate plus or minus a margin of error.

**Example:**
If you estimate the average height of students to be 160 cm with a 95% confidence interval of [158 cm, 162 cm], you are saying that you are 95% confident that the true average height is between 158 cm and 162 cm.

### 43. What does the confidence level represent in a confidence interval?

The confidence level represents the percentage of all possible samples that can be expected to include the true population parameter. Common confidence levels are 90%, 95%, and 99%.

**Example:**
A 95% confidence level means that if you took 100 different samples and calculated a confidence interval for each, about 95 of those intervals would contain the true population parameter.

### 44. What is hypothesis testing in statistics?

Hypothesis testing is a method used to make decisions or inferences about population parameters based on sample data. It involves testing an assumption (hypothesis) about a population parameter.

**Example:**
Testing whether a new drug is more effective than the existing drug involves hypothesis testing.

### 45. What is the purpose of a null hypothesis in hypothesis testing?

The null hypothesis (H0) is a statement that there is no effect or no difference, and it serves as the default assumption that we aim to test against. The purpose is to provide a baseline for comparison.

**Example:**
If you're testing whether a new teaching method is effective, the null hypothesis might be that the new method has no effect on student performance.

### 46. What is the difference between a one-tailed and a two-tailed test?

- **One-Tailed Test:** Tests for an effect in one direction (either greater than or less than a certain value).

  - **Example:** Testing if a new drug is better than the current one (only looking for improvement).

- **Two-Tailed Test:** Tests for an effect in both directions (both greater than and less than a certain value).
  - **Example:** Testing if a new drug is different from the current one (could be better or worse).

### 47. What is experiment design, and why is it important?

Experiment design is the process of planning an experiment to ensure that it can accurately test hypotheses and answer research questions. It is important because a well-designed experiment minimizes biases, controls for variables, and ensures the results are valid and reliable.

**Example:**
In a clinical trial, designing the experiment to randomly assign participants to the treatment and control groups helps ensure that any differences in outcomes are due to the treatment itself, not other factors.

### 48. What are the key elements to consider when designing an experiment?

- **Hypothesis:** Clear and testable statements.
- **Variables:** Define independent (manipulated) and dependent (measured) variables.
- **Control Group:** A group that does not receive the treatment, used for comparison.
- **Randomization:** Randomly assign subjects to control and experimental groups.
- **Replication:** Repeat the experiment to ensure results are consistent.

**Example:**
In testing a new fertilizer, consider the type of plants (dependent variable), the amount of fertilizer (independent variable), a group of plants without fertilizer (control group), and randomly assigning plants to each group.

### 49. How can sample size determination affect experiment design?

The sample size affects the experiment's power and the reliability of the results. A larger sample size generally provides more accurate estimates of population parameters and increases the likelihood of detecting a true effect.

**Example:**
If you're testing a new drug, a larger sample size will give you more confidence that the observed effects are real and not due to random chance.

### 50. What are some strategies to mitigate potential sources of bias in experiment design?

- **Randomization:** Randomly assign participants to groups to reduce selection bias.
- **Blinding:** Use single-blind or double-blind designs to prevent participants and researchers from knowing group assignments.
- **Control Groups:** Include control groups to compare with the experimental group.
- **Replication:** Repeat the experiment to ensure the results are consistent.
- **Standardization:** Use consistent procedures for all participants.

**Example:**
In a clinical trial, randomizing participants and using a double-blind design (where neither participants nor researchers know who is receiving the treatment) helps reduce biases.

### 51. What is the geometric interpretation of the dot product?

The dot product of two vectors measures the extent to which the vectors point in the same direction. Geometrically, it is the product of the magnitudes of the two vectors and the cosine of the angle between them.

$$ \mathbf{a} \cdot \mathbf{b} = \|\mathbf{a}\| \|\mathbf{b}\| \cos \theta $$

**Example:**
If $`\mathbf{a}`$ and $`\mathbf{b}`$ are two vectors, and the angle between them is 90 degrees (they are perpendicular), the dot product is 0 because $`\cos 90^\circ = 0`$.

### 52. What is the geometric interpretation of the cross-product?

The cross product of two vectors in three-dimensional space produces a third vector that is perpendicular to the plane formed by the first two vectors. The magnitude of the cross product vector is equal to the area of the parallelogram formed by the two original vectors.

$$ \mathbf{a} \times \mathbf{b} = \|\mathbf{a}\| \|\mathbf{b}\| \sin \theta \mathbf{n} $$

where $`\mathbf{n}`$ is the unit vector perpendicular to the plane containing $`\mathbf{a}`$ and $`\mathbf{b}`$.

**Example:**
If $`\mathbf{a}`$ and $`\mathbf{b}`$ are vectors in the xy-plane, their cross product will be a vector pointing in the z-direction.

### 53. How are optimization algorithms with calculus used in training deep learning models?

Optimization algorithms in deep learning use calculus to minimize the loss function, which measures how well the model's predictions match the actual outcomes. Calculus helps in finding the gradient (the direction of the steepest ascent) of the loss function. By iteratively adjusting the model parameters in the direction opposite to the gradient (using techniques like gradient descent), the algorithm reduces the loss, improving the model's performance.

**Example:**
Gradient Descent Algorithm adjusts the weights of a neural network to minimize the error in predictions.

### 54. What are observational and experimental data in statistics?

- **Observational Data:** Collected without manipulating the study environment. Observers record information as it naturally occurs.

  - **Example:** Recording the heights of students in a class.

- **Experimental Data:** Collected by manipulating the study environment and observing the effects. Involves controlled experiments.
  - **Example:** Testing a new drug by giving it to one group and a placebo to another.

### 55. How are confidence tests and hypothesis tests similar? How are they different?

**Similarities:**

- Both use sample data to make inferences about a population.
- Both involve statistical calculations and the concept of sampling distribution.

**Differences:**

- **Confidence Interval:** Provides a range of values within which the population parameter is likely to fall, along with a confidence level (e.g., 95%).

  - **Example:** Estimating the average height of students with a 95% confidence interval of [158 cm, 162 cm].

- **Hypothesis Test:** Tests a specific hypothesis about a population parameter. It involves a null hypothesis (H0) and an alternative hypothesis (H1) and uses a p-value to determine statistical significance.
  - **Example:** Testing if the average height of students is greater than 160 cm.

### 56. What is the left-skewed distribution and the right-skewed distribution?

- **Left-Skewed (Negative Skew):** The tail on the left side of the distribution is longer or fatter than the right side. The mean is less than the median.

  - **Example:** Scores on a very easy exam where most students score high, but a few score very low.

- **Right-Skewed (Positive Skew):** The tail on the right side of the distribution is longer or fatter than the left side. The mean is greater than the median.
  - **Example:** Income distribution where most people earn lower salaries, but a few earn very high salaries.

### 57. What is Bessel’s correction?

Bessel’s correction is used when calculating the sample variance to provide an unbiased estimate of the population variance. It involves dividing by $`n-1`$ instead of $`n`$, where $`n`$ is the sample size.

**Example:**
If the sample size is 5, you divide by 4 instead of 5 when calculating the sample variance.

### 58. What is kurtosis?

Kurtosis measures the "tailedness" of the probability distribution of a real-valued random variable. High kurtosis means more of the variance is due to infrequent extreme deviations, while low kurtosis indicates fewer and less extreme outliers.

- **Leptokurtic:** High kurtosis, sharp peak, heavy tails.
- **Mesokurtic:** Normal distribution, moderate tails.
- **Platykurtic:** Low kurtosis, flat peak, light tails.

**Example:**
A distribution of test scores with a few very high and very low scores (outliers) will have high kurtosis.

### 59. What is the probability of throwing two fair dice when the sum is 5 and 8?

To find the probabilities, count the favorable outcomes and divide by the total number of possible outcomes (36).

- **Sum of 5:** Possible pairs: (1,4), (2,3), (3,2), (4,1) → 4 outcomes.

  $$ P(\text{sum} = 5) = \frac{4}{36} = \frac{1}{9} $$

- **Sum of 8:** Possible pairs: (2,6), (3,5), (4,4), (5,3), (6,2) → 5 outcomes.

  $$ P(\text{sum} = 8) = \frac{5}{36} $$

### 60. What is the difference between Descriptive and Inferential Statistics?

- **Descriptive Statistics:** Summarize and describe the features of a dataset. They provide simple summaries about the sample and the measures.

  - **Example:** Calculating the mean, median, and mode of test scores.

- **Inferential Statistics:** Make inferences and predictions about a population based on a sample of data. They involve hypothesis testing, confidence intervals, and regression analysis.
  - **Example:** Estimating the average height of all students in a school based on a sample.

### 61. Imagine that Jeremy took part in an examination. The test has a mean score of 160, and it has a standard deviation of 15. If Jeremy’s z-score is 1.20, what would be his score on the test?

A z-score tells us how many standard deviations an element is from the mean. The formula to find the score from a z-score is:

$$ \text{Score} = \mu + (z \times \sigma) $$

where $`\mu`$ is the mean, $`z`$ is the z-score, and $`\sigma`$ is the standard deviation.

Given:

$$ \mu = 160, \quad z = 1.20, \quad \sigma = 15 $$

$$ \text{Score} = 160 + (1.20 \times 15) $$

$$ \text{Score} = 160 + 18 $$

$$ \text{Score} = 178 $$

Jeremy’s score on the test is 178.

### 62. In an observation, there is a high correlation between the time a person sleeps and the amount of productive work he does. What can be inferred from this?

A high correlation indicates a strong relationship between two variables, but it does not imply causation. In this case, it means that as the time a person sleeps increases, the amount of productive work they do also increases, or vice versa. However, this does not mean that more sleep directly causes more productivity.

**Example:**
Other factors, like overall health, stress levels, or work environment, might also influence productivity.

### 63. What is the meaning of degrees of freedom (DF) in statistics?

Degrees of freedom (DF) refer to the number of independent values or quantities which can be assigned to a statistical distribution. It is the number of values in the final calculation of a statistic that are free to vary.

**Example:**
In a sample of size $` n `$, the degrees of freedom for estimating the population variance is $` n-1 `$. This is because one degree of freedom is used to estimate the mean, leaving $` n-1 `$ values that can vary independently.

### 64. If there is a 30 percent probability that you will see a supercar in any 20-minute time interval, what is the probability that you see at least one supercar in the period of an hour (60 minutes)?

First, we find the probability of not seeing a supercar in a 20-minute interval, which is $` 1 - 0.30 = 0.70 `$.

Next, the probability of not seeing a supercar in three consecutive 20-minute intervals (which makes an hour) is:

$$ 0.70 \times 0.70 \times 0.70 = 0.70^3 = 0.343 $$

So, the probability of seeing at least one supercar in an hour is:

$$ 1 - 0.343 = 0.657 $$

Therefore, there is a 65.7% probability of seeing at least one supercar in an hour.

### 65. What is the empirical rule in Statistics?

The empirical rule states that for a normal distribution:

- About 68% of the data falls within one standard deviation of the mean.
- About 95% of the data falls within two standard deviations of the mean.
- About 99.7% of the data falls within three standard deviations of the mean.

**Example:**
If the average score on a test is 100 with a standard deviation of 10, then:

- 68% of students scored between 90 and 110.
- 95% of students scored between 80 and 120.
- 99.7% of students scored between 70 and 130.

### 66. What is the relationship between sample size and power in hypothesis testing?

The power of a hypothesis test is the probability that the test correctly rejects the null hypothesis when it is false. Larger sample sizes increase the power of the test because they provide more accurate estimates of the population parameters, making it easier to detect true effects.

**Example:**
If you’re testing the effect of a new drug, a larger sample size would give you a higher chance of detecting a real difference in outcomes between the treatment and control groups.

### 67. Can you perform hypothesis testing with non-parametric methods?

Yes, non-parametric methods can be used for hypothesis testing, especially when the assumptions required for parametric tests (such as normal distribution of data) are not met. Non-parametric tests do not assume a specific distribution.

**Example:**
The Mann-Whitney U test is a non-parametric test that can be used to compare differences between two independent groups when the data does not follow a normal distribution.

### 68. What factors affect the width of a confidence interval?

- **Sample Size:** Larger sample sizes lead to narrower confidence intervals.
- **Confidence Level:** Higher confidence levels result in wider confidence intervals.
- **Variability in the Data:** Greater variability (higher standard deviation) results in wider confidence intervals.

**Example:**
To estimate the average height of students, a larger sample size or lower confidence level (e.g., 90% instead of 95%) will give a narrower confidence interval.

### 69. How does increasing the confidence level affect the width of a confidence interval?

Increasing the confidence level makes the confidence interval wider. This is because a higher confidence level means you want to be more certain that the interval contains the population parameter, so you need a wider interval to account for more variability.

**Example:**
A 95% confidence interval for the average height of students might be [158 cm, 162 cm], while a 99% confidence interval might be [157 cm, 163 cm].

### 70. Can a confidence interval be used to make a definitive statement about a specific individual in the population?

No, a confidence interval provides a range for a population parameter (like the mean or proportion) and does not make definitive statements about specific individuals. It tells us about the overall trend in the population, not individual cases.

**Example:**
If the average height of students is estimated to be between 158 cm and 162 cm with 95% confidence, this does not mean that every individual student's height falls within this range.

### 71. How does sample size influence the width of a confidence interval?

As the sample size increases, the width of the confidence interval decreases. This is because a larger sample provides more information and thus reduces the uncertainty in estimating the population parameter.

**Example:**
If you are estimating the average height of students, a sample size of 100 will give a narrower confidence interval compared to a sample size of 20, assuming the same confidence level.

### 72. What is the relationship between the margin of error and confidence interval?

The margin of error is the amount added and subtracted from the sample mean to create the confidence interval. It represents the range within which we expect the population parameter to lie, given a certain confidence level.

$$ \text{Confidence Interval} = \text{Sample Mean} \pm \text{Margin of Error} $$

**Example:**
If the sample mean height of students is 160 cm with a margin of error of 2 cm at a 95% confidence level, the confidence interval is [158 cm, 162 cm].

### 73. Can two confidence intervals with different widths have the same confidence level?

Yes, two confidence intervals can have the same confidence level but different widths. The width of a confidence interval depends on the sample size, variability in the data, and the chosen confidence level. If the sample sizes or variability are different, the widths of the intervals will be different even if the confidence level is the same.

**Example:**
A 95% confidence interval for a small sample size might be [150 cm, 170 cm], while for a larger sample size, it might be [155 cm, 165 cm].

### 74. What is a Sampling Error and how can it be reduced?

Sampling error is the difference between a sample statistic and the actual population parameter it estimates. It arises because a sample is only a subset of the population.

**How to Reduce Sampling Error:**

- **Increase Sample Size:** Larger samples better represent the population.
- **Random Sampling:** Ensures that every member of the population has an equal chance of being selected, reducing bias.

**Example:**
If the average height of all students is 160 cm, but the sample mean is 158 cm, the 2 cm difference is the sampling error.

### 75. What is a Chi-Square test?

The Chi-Square test is a statistical test used to determine if there is a significant association between categorical variables. It compares the observed frequencies in each category to the frequencies expected if there were no association.

**Example:**
Testing whether there is an association between gender (male, female) and preference for a new product (like, dislike).

### 76. What is a t-test?

A t-test is a statistical test used to compare the means of two groups. It helps determine if the difference between the means is statistically significant.

**Types of t-tests:**

- **One-sample t-test:** Compares the sample mean to a known value.
- **Independent t-test:** Compares means from two independent groups.
- **Paired t-test:** Compares means from the same group at different times.

**Example:**
Comparing the average test scores of two different classes.

### 77. What is the ANOVA test?

ANOVA (Analysis of Variance) is a statistical test used to compare the means of three or more groups. It determines if there are any statistically significant differences between the means of the groups.

**Example:**
Testing whether three different teaching methods lead to different average test scores among students.

### 78. How is hypothesis testing utilised in A/B testing for marketing campaigns?

In A/B testing, hypothesis testing is used to compare the performance of two versions (A and B) of a marketing campaign. The null hypothesis (H0) usually states that there is no difference in performance between the two versions, while the alternative hypothesis (H1) states that there is a difference.

**Steps:**

1. **Formulate Hypotheses:** H0: Conversion rate of A = Conversion rate of B; H1: Conversion rate of A ≠ Conversion rate of B.
2. **Collect Data:** Run the campaigns and collect performance data.
3. **Perform Statistical Test:** Use a t-test or Chi-Square test to compare the results.
4. **Make Decision:** If the p-value is below a certain threshold (e.g., 0.05), reject the null hypothesis and conclude that there is a significant difference.

**Example:**
Comparing the conversion rates of two different email subject lines to see which one performs better.

### 79. What is the difference between one-tailed and two-tailed t-tests?

- **One-tailed t-test:** Tests if the sample mean is significantly greater than or less than the population mean. It has a direction.

  - **Example:** Testing if a new drug increases patient recovery rates.

- **Two-tailed t-test:** Tests if the sample mean is significantly different from the population mean, in either direction. It does not have a specific direction.
  - **Example:** Testing if a new drug has any effect (increase or decrease) on patient recovery rates.

### 80. What is an inlier?

An inlier is a data point that falls within the expected range of values in a dataset. It is the opposite of an outlier, which falls outside the expected range.

**Example:**
In a dataset of student heights, most heights between 150 cm and 180 cm are inliers, while a height of 210 cm might be considered an outlier.
