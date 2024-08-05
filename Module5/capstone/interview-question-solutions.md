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
