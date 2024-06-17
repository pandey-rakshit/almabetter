# Module 5 - Applied Statistics

## Capstone -- End Course Summative Assignment

**Problem Statement: Write the Solutions to the Top 50 Interview Questions and Explain any 5 Questions in a Video**

### **1. What is a vector in mathematics?**

#### **Vector**

---

A vector is a quantity that has both magnitude and direction, often represented as an arrow in a coordinate plane. Mathematically, a vector in n-dimensional space is represented as:

$$ \vec{v} = \langle v_1, v_2, \ldots, v_n \rangle $$

where $ v_1, v_2, \ldots, v_n $ are the components of the vector.

In the context of data science and machine learning, vectors are crucial in various ways:

1. **Data Representation**:

   - Vectors represent data points in feature space, which is essential for machine learning algorithms. For instance, each data point in a dataset can be represented as a vector of features.

2. **Distance Calculation**:

   - Calculating distances between vectors (or data points) is critical for clustering, classification, and nearest neighbor algorithms. For example, in K-means clustering, similar data points are grouped by minimizing the distance between them.

3. **Vector Operations**:

   - Operations such as addition, subtraction, and scalar multiplication are used extensively in optimization algorithms like gradient descent. In neural networks, for example, adjusting weights involves performing these vector operations.

4. **Dimensionality Reduction**:

   - Techniques like Principal Component Analysis (PCA) use vectors to reduce the dimensionality of data while retaining its essential features. This is particularly useful for visualizing high-dimensional data in 2D or 3D.

5. **Feature Engineering**:
   - Vectors are also used in feature engineering to create new features by combining existing ones. In text analysis, for example, feature vectors can be created from word frequencies or embeddings to improve model performance.

In conclusion, vectors are versatile tools for representing and manipulating data in various dimensions. Understanding vectors and their operations is crucial for effectively implementing and optimizing machine learning algorithms, which in turn enhances model accuracy, efficiency, and interpretability.

---

### **2. How is a vector different from a scalar?**

Scalars and vectors are fundamental concepts in mathematics and data science, and they differ in several key ways.

**Scalar**:

- A scalar is a quantity that is fully described by a single value, which represents its magnitude, without any direction.

- Examples of scalars include temperature, mass, speed, and time.

- Scalars are represented by simple numerical values.

  - For instance, temperature: 25°C, mass: 70 kg, speed: 60 km/h.

**Vector**:

- A vector, on the other hand, is a quantity that has both magnitude and direction.

- Examples of vectors include velocity, force, displacement, and acceleration.

- Vectors are often represented as an ordered list of numbers indicating their components in different dimensions.

> **For example:**
>
> **_velocity:_** $\vec{v} = \langle 30 \text{ km/h}, \text{ east} \rangle$
>
> **_force:_** $\vec{F} = \langle 10 \text{ N}, 45 \text{ degrees} \rangle$
>
> **_displacement:_** $\vec{d} = \langle 5 \text{ m}, \text{ north} \rangle$.

**Mathematical Representation**:

- Scalars are represented by a single number, such as $ s = 5 $.

  - Arithmetic operations on scalars are straightforward, including addition, subtraction, and multiplication.

- Vectors are represented by an ordered list of numbers, such as $\vec{v} = \langle 3, 4 \rangle $ in 2D space or $\vec{w} = \langle 2, -1, 5 \rangle$ in 3D space.

  - Vector operations include addition, subtraction, dot product, cross product (for 3D vectors), and scalar multiplication.

**Examples**:

- **Scalar Example**:

  - Temperature: In New York, the temperature is 30°C.

    - This is a scalar because it only has magnitude (30) and no direction.

- **Vector Example**:

  - Velocity: A car is moving at 60 km/h to the north.

    - This is a vector because it has both magnitude (60 km/h) and direction (north).

**Practical Use in Data Science, Data Analytics, and Machine Learning**:

- **Scalars in Data Science**:

  - Scalars are used to represent individual data points or summary statistics.

  - Example: Average income in a dataset, total sales, mean temperature.

- **Vectors in Data Science**:

  - Vectors represent multi-dimensional data points, which are crucial for machine learning algorithms.

  - Example: Each data point in a feature space for machine learning models.

  - Use Case: In a dataset of houses, a house can be represented as a vector of features like $\langle \text{number of bedrooms}, \text{square footage}, \text{age} \rangle $.

**Conclusion**:

- Scalars provide simple, single-value representations of quantities, which are easy to understand and manipulate.

- Vectors offer a more detailed representation, incorporating both magnitude and direction, essential for modeling complex phenomena in physics, engineering, and data science.

- In data science and machine learning, vectors are particularly useful for representing feature sets, calculating distances, and performing various operations necessary for training and optimizing models. Understanding the distinction between scalars and vectors enhances the ability to effectively analyze and manipulate data.

---

### **3. What are the different operations that can be performed on vectors?**

### **4. How can vectors be multiplied by a scalar?**

### **5. What is the magnitude of a vector?**

### **6. How can the direction of a vector be determined?**

### **7. What is the difference between a square matrix and a rectangular matrix?**

### **8. What is a basis in linear algebra?**

### **9. What is a linear transformation in linear algebra?**

### **10. What is an eigenvector in linear algebra?**

### **11. What is the gradient in machine learning?**

### **12. What is backpropagation in machine learning?**

### **13. What is the concept of a derivative in calculus?**

### **14. How are partial derivatives used in machine learning?**

### **15. What is probability theory?**

### **16. What are the primary components of probability theory?**

### **17. What is conditional probability, and how is it calculated?**

### **18. What is Bayes theorem, and how is it used?**

### **19. What is a random variable, and how is it different from a regular variable?**

### **20. What is the law of large numbers, and how does it relate to probability theory?**

### **21. What is the central limit theorem, and how is it used?**

### **22. What is the difference between discrete and continuous probability distributions?**

### **23. What are some common measures of central tendency, and how are they calculated?**

### **24. What is the purpose of using percentiles and quartiles in data summarization?**

### **25. How do you detect and treat outliers in a dataset?**

### **26. How do you use the central limit theorem to approximate a discrete probability distribution?**

### **27. How do you test the goodness of fit of a discrete probability distribution?**

### **28. What is a joint probability distribution?**

### **29. How do you calculate the joint probability distribution?**

### **30. What is the difference between a joint probability distribution and a marginal probability distribution?**

### **31. What is the covariance of a joint probability distribution?**

### **32. How do you determine if two random variables are independent based on their joint probability distribution?**

### **33. What is the relationship between the correlation coefficient and the covariance of a joint probability distribution?**

### **34. What is sampling in statistics, and why is it important?**

### **35. What are the different sampling methods commonly used in statistical inference?**

### **36. What is the central limit theorem, and why is it important in statistical inference?**

### **37. What is the difference between parameter estimation and hypothesis testing?**

### **38. What is the p-value in hypothesis testing?**

### **39. What is confidence interval estimation?**

### **40. What are Type I and Type II errors in hypothesis testing?**

### **41. What is the difference between correlation and causation?**

### **42. How is a confidence interval defined in statistics?**

### **43. What does the confidence level represent in a confidence interval?**

### **44. What is hypothesis testing in statistics?**

### **45. What is the purpose of a null hypothesis in hypothesis testing?**

### **46. What is the difference between a one-tailed and a two-tailed test?**

### **47. What is experiment design, and why is it important?**

### **48. What are the key elements to consider when designing an experiment?**

### **49. How can sample size determination affect experiment design?**

### **50. What are some strategies to mitigate potential sources of bias in experiment design?**

### **51. What is the geometric interpretation of the dot product?**

### **52. What is the geometric interpretation of the cross-product?**

### **53. How are optimization algorithms with calculus used in training deep learning models?**

### **54. What are observational and experimental data in statistics?**

### **55. How are confidence tests and hypothesis tests similar? How are they different?**

### **56. What is the left-skewed distribution and the right-skewed distribution?**

### **57. What is Bessel’s correction?**

### **58. What is kurtosis?**

### **59. What is the probability of throwing two fair dice when the sum is 5 and 8?**

### **60. What is the difference between Descriptive and Inferential Statistics?**

### **61. Imagine that Jeremy took part in an examination. The test has a mean score of 160, and it has a standard deviation of 15. If Jeremy’s z-score is 1.20, what would be his score on the test?**

### **62. In an observation, there is a high correlation between the time a person sleeps and the amount of productive work he does. What can be inferred from this?**

### **63. What is the meaning of degrees of freedom (DF) in statistics?**

### **64. If there is a 30 percent probability that you will see a supercar in any 20-minute time interval, what is the proba­bility that you see at least one supercar in the period of an hour (60 minutes)?**

### **65. What is the empirical rule in Statistics?**

### **66. What is the relationship between sample size and power in hypothesis testing?**

### **67. Can you perform hypothesis testing with non-parametric methods?**

### **68. What factors affect the width of a confidence interval?**

### **69. How does increasing the confidence level affect the width of a confidence interval?**

### **70. Can a confidence interval be used to make a definitive statement about a specific individual in the population?**

### **71. How does sample size influence the width of a confidence interval?**

### **72. What is the relationship between the margin of error and confidence interval?**

### **73. Can two confidence intervals with different widths have the same confidence level?**

### **74. What is a Sampling Error and how can it be reduced?**

### **75. What is a Chi-Square test?**

### **76. What is a t-test?**

### **77. What is the ANOVA test?**

### **78. How is hypothesis testing utilised in A/B testing for marketing campaigns?**

### **79. What is the difference between one-tailed and two tailed t-tests?**

### **80. What is an inlier?**
