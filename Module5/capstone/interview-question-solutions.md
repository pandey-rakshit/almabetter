# Module 5 - Applied Statistics

## Capstone -- End Course Summative Assignment

**Problem Statement: Write the Solutions to the Top 50 Interview Questions and Explain any 5 Questions in a Video**

### **1. What is a vector in mathematics?**

**Vector**

A vector is a quantity that has both magnitude and direction, often represented as an arrow in a coordinate plane. Mathematically, a vector in n-dimensional space is represented as:

$$ \vec{v} = \langle v_1, v_2, \ldots, v_n \rangle $$

where $v_1, v_2, \ldots, v_n$ are the components of the vector.

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

- Scalars are represented by a single number, such as $s = 5$.

  - Arithmetic operations on scalars are straightforward, including addition, subtraction, and multiplication.

- Vectors are represented by an ordered list of numbers, such as $\vec{v} = \langle 3, 4 \rangle$ in 2D space or $\vec{w} = \langle 2, -1, 5 \rangle$ in 3D space.

  - Vector operations include addition, subtraction, dot product, cross product (for 3D vectors), and scalar multiplication.
    > A vector in a 2-dimensional space (often called a 2D vector) might look like this:
    >
    > $`\mathbf{v} = \begin{pmatrix} v_1 \\ v_2 \end{pmatrix}`$
    >
    > where $v_1 \text{ and } v_2$ are the components of the vector.

**Practical Use in Data Science, Data Analytics, and Machine Learning**:

- **Scalars in Data Science**:

  - Scalars are used to represent individual data points or summary statistics.

  - Example: Average income in a dataset, total sales, mean temperature.

- **Vectors in Data Science**:

  - Vectors represent multi-dimensional data points, which are crucial for machine learning algorithms.

  - Example: Each data point in a feature space for machine learning models.

  - Use Case: In a dataset of houses, a house can be represented as a vector of features like $\langle \text{number of bedrooms}, \text{square footage}, \text{age} \rangle$.

**Conclusion**:

- Scalars provide simple, single-value representations of quantities, which are easy to understand and manipulate.

- Vectors offer a more detailed representation, incorporating both magnitude and direction, essential for modeling complex phenomena in physics, engineering, and data science.

- In data science and machine learning, vectors are particularly useful for representing feature sets, calculating distances, and performing various operations necessary for training and optimizing models. Understanding the distinction between scalars and vectors enhances the ability to effectively analyze and manipulate data.

---

### **3. What are the different operations that can be performed on vectors?**

In linear algebra, vectors are fundamental mathematical entities that allow us to represent quantities with both magnitude and direction. There are several key operations that can be performed on vectors:

1. **Basic Operations**: Addition, subtraction, and scalar multiplication are fundamental operations that manipulate vectors by combining them or scaling them.

2. **Dot Product**: This operation yields a scalar value and measures the similarity or projection of one vector onto another.

3. **Cross Product**: Only applicable in three dimensions, it results in a vector that is perpendicular to the two original vectors.

4. **Magnitude and Unit Vector**: Magnitude gives the length of a vector, while a unit vector has a magnitude of 1 and indicates direction.

5. **Projection and Decomposition**: Projection determines how much of one vector lies in the direction of another, and decomposition breaks a vector into components along given directions.

6. **Linear Combination and Span**: These concepts involve combining vectors with different scalar weights to cover the vector space as well as possible.

7. **Eigenvalues and Eigenvectors**: These are associated with matrices and help us understand the behavior of transformations.

8. **Norms, Distance, and Angle**: Norms measure the size of vectors, distance measures the separation between them, and angle measures the orientation between them.

9. **Matrix Operations**: Vectors can be transformed using matrices for rotation, scaling, and translation.

Each of these operations plays a crucial role in fields like physics, engineering, and computer science, enabling us to model and analyze various phenomena effectively.

---

**Operations on Vectors: Visual and Conceptual Explanation**

Vectors are mathematical entities that represent quantities with both magnitude and direction. Understanding their operations is crucial across various fields. Here's a structured overview with visual aids for clarity:

1.  **Basic Operations**

- **Addition**: Combines vectors by adding their corresponding components, visually shown as shifting one vector to end at the tip of another.

```math
  \mathbf{u} + \mathbf{v} = \begin{pmatrix} u_1 \\ u_2 \end{pmatrix} + \begin{pmatrix} v_1 \\ v_2 \end{pmatrix} = \begin{pmatrix} u_1 + v_1 \\ u_2 + v_2 \end{pmatrix}
```

- **Subtraction**: Finds the difference between vectors, illustrated as the vector connecting the tips of
  $\mathbf{u}$ and $\mathbf{v}$.

```math
     \mathbf{u} - \mathbf{v} = \begin{pmatrix} u_1 - v_1 \\ u_2 - v_2 \end{pmatrix}
```

- **Scalar Multiplication**: Scales a vector by multiplying each component by a scalar, visually stretching or compressing the vector.

```math

  c \cdot \mathbf{u} = \begin{pmatrix} c \cdot u_1 \\ c \cdot u_2 \end{pmatrix}
```

**Applications in Data Science**:

- **Feature Engineering**: Vectors are used to represent features in datasets, where addition and scalar multiplication can manipulate feature values.

**Dot Product**

- **Definition**: The dot product calculates a scalar by summing the products of corresponding components of two vectors, indicating their similarity and ability to project one onto another.

```math
   \mathbf{u} \cdot \mathbf{v} = u_1 v_1 + u_2 v_2
```

- **Purpose**:

  - **Similarity Measurement**: Essential in data science for measuring similarity between vectors, such as in cosine similarity used in recommendation systems and NLP.
  - **Projection**: Facilitates vector projection, aiding in tasks like dimensionality reduction and solving linear systems.

- **Example**: Suppose

```math
\mathbf{u} = \begin{pmatrix} 2 \\ 3 \end{pmatrix} \text{ and } \mathbf{v} = \begin{pmatrix} 1 \\ 4 \end{pmatrix}
```

```math
\mathbf{u} \cdot \mathbf{v} = (2 \cdot 1) + (3 \cdot 4) = 2 + 12 = 14
```

Thus, $`\mathbf{u} \cdot \mathbf{v} = 14`$ illustrates their alignment in vector space.

3.  **Cross Product**

    - **Definition (3D Only)**: Produces a vector perpendicular to both vectors, shown as a vector orthogonal to the plane formed by $\mathbf{u}$ and $\mathbf{v}$.

```math
   \mathbf{u} \times \mathbf{v} = \begin{pmatrix} u_2 v_3 - u_3 v_2 \\ u_3 v_1 - u_1 v_3 \\ u_1 v_2 - u_2 v_1 \end{pmatrix}$$
```

**Purpose**:

- **Geometric Interpretation**: In data science, the cross product may be used in specific geometric calculations, such as determining orientations or transformations.

4.  **Magnitude and Unit Vector**

    - **Magnitude**: Calculates the length of a vector, visualized as the distance from the origin to the vector's tip.

      $$|\mathbf{u}| = \sqrt{u_1^2 + u_2^2}$$

    - **Unit Vector**: Normalizes a vector to have a magnitude of 1, shown as the direction without changing length.

      $$\hat{\mathbf{u}} = \frac{\mathbf{u}}{|\mathbf{u}|}$$

      **Applications in Data Science**:

      - **Normalization**: Scaling features to a common range using unit vectors is crucial in machine learning preprocessing steps.

5.  **Projection and Decomposition**

    - **Projection**: Finds the component of one vector along another, represented as the shadow of $\mathbf{u}$ on $\mathbf{v}$.

      $$\text{proj}_{\mathbf{v}}\mathbf{u} = \left( \frac{\mathbf{u} \cdot \mathbf{v}}{\mathbf{v} \cdot \mathbf{v}} \right) \mathbf{v}$$

    - **Decomposition**: Splits a vector into components along given directions, shown as parts along and orthogonal to $\mathbf{v}$.

      **Applications in Data Science**:

      - **Dimensionality Reduction**: Techniques like Principal Component Analysis (PCA) use projections to reduce the dimensionality of datasets while preserving information.

6.  **Linear Combination and Span**

    - **Linear Combination**: Combines vectors with scalar weights, illustrating their collective influence.

    $$a_1 \mathbf{u}_1 + a_2 \mathbf{u}_2 + \cdots + a_n \mathbf{u}_n$$

    - **Span**: Encompasses all possible combinations of vectors, demonstrating the space covered.

      **Applications in Data Science**:

      - **Machine Learning Models**: Linear combinations are fundamental in defining models, such as linear regression or neural networks.

---

### **4. How can vectors be multiplied by a scalar?**

Vectors can be multiplied by a scalar by scaling each component of the vector individually with the scalar value. This operation is fundamental in linear algebra and has practical applications in various fields, including physics, engineering, and data science.

1. **Definition and Operation**:

   - Scalar multiplication of a vector $`\mathbf{v} = \begin{pmatrix} v_1 \\ v_2 \end{pmatrix}`$ by a scalar $`c`$ results in a new vector

```math
   c \cdot \mathbf{v} = \begin{pmatrix} c \cdot v_1 \\ c \cdot v_2 \end{pmatrix}
```

- Each component of the vector is multiplied by the scalar, preserving the vector's direction but scaling its magnitude.

3. **Purpose and Applications**:

   - **Scaling and Transformation**: Scalar multiplication is used to scale vectors to adjust their magnitude, which is crucial in applications such as scaling forces in physics or resizing data points in machine learning.

   - **Linear Combinations**: It plays a key role in forming linear combinations of vectors, enabling operations like vector addition and creating spans in vector spaces.

**Example**:

- For instance, scaling a velocity vector in physics or resizing feature vectors in machine learning are practical examples that demonstrate scalar multiplication's utility.

---

### **5. What is the magnitude of a vector?**

The magnitude of a vector represents its length or size in a given space. It is a scalar quantity that quantifies the extent or magnitude of the vector's components.

1. **Definition**:

   - Mathematically, for a vector $`\mathbf{v} = \begin{pmatrix} v_1 \\ v_2 \end{pmatrix}`$, the magnitude $`|\mathbf{v}|`$ is calculated as:

     $$|\mathbf{v}| = \sqrt{v_1^2 + v_2^2}$$

     This formula generalizes to higher dimensions as well (

     $$\sqrt{v_1^2 + v_2^2 + \cdots + v_n^2}$$

     for an $n$-dimensional vector).

2. **Purpose and Interpretation**:

   - The magnitude provides a quantitative measure of the vector's length irrespective of its direction.

   - It is fundamental in determining distances, velocities, accelerations, and other physical quantities in sciences and engineering.

3. **Applications**:

   - **Physics**: In physics, it determines the intensity of forces and fields (e.g., electric fields).

   - **Engineering**: It measures displacements, velocities, and accelerations in structural analysis and dynamics.

   - **Data Science**: In machine learning, it's used to normalize vectors or measure distances between data points (e.g., Euclidean distance).

**Example**:

- For example, in 2D space, the magnitude of a velocity vector $`\mathbf{v} = \begin{pmatrix} 3 \\ 4 \end{pmatrix}`$ would be
  $$|\mathbf{v}| = \sqrt{3^2 + 4^2} = 5$$

---

### **6. How can the direction of a vector be determined?**

Determining the direction of a vector involves understanding its orientation relative to a reference axis or another vector. In mathematical terms, the direction of a vector $`\mathbf{v}`$ is often described by a unit vector $`\hat{\mathbf{v}}`$, which points in the same direction as $`\mathbf{v}`$ but has a magnitude of 1. This unit vector is derived by dividing the vector $`\mathbf{v}`$ by its magnitude $`|\mathbf{v}|`$. Geometrically, the direction can be visualized as the angle the vector makes with a specified axis, typically the positive x-axis in two dimensions. This angle can be calculated using trigonometric functions, providing a quantitative measure of the vector's orientation in space. Understanding vector direction is fundamental in fields such as physics, engineering, and data science, where vectors represent forces, velocities, and dimensions in mathematical models and simulations.

1. **Magnitude of a Vector**:

   - **Definition**: The magnitude (or length) of a vector $`\mathbf{v} = \begin{pmatrix} v_1 \\ v_2 \end{pmatrix}`$ in a 2-dimensional space is calculated using the Euclidean norm:

     $$|\mathbf{v}| = \sqrt{v_1^2 + v_2^2}$$

     - This formula applies to higher dimensions as well, adding squares of components.

   - **Example**:

     - For vector $`\mathbf{v} = \begin{pmatrix} 3 \\ 4 \end{pmatrix}`$:

       $$|\mathbf{v}| = \sqrt{3^2 + 4^2} = \sqrt{9 + 16} = \sqrt{25} = 5$$

       - The magnitude $|\mathbf{v}|$ is 5 units.

2. **Direction of a Vector**:

   - **Unit Vector Approach**:

     - Calculate the unit vector $`\hat{\mathbf{v}}`$ to determine the direction of $`\mathbf{v}`$:

```math
       \hat{\mathbf{v}} = \frac{\mathbf{v}}{|\mathbf{v}|} = \frac{\begin{pmatrix} v_1 \\ v_2 \end{pmatrix}}{\sqrt{v_1^2 + v_2^2}}
```

- The unit vector $\hat{\mathbf{v}}$ has a magnitude of 1 and points in the direction of $\mathbf{v}$.

  - **Example**:

    - Given $`\mathbf{v} = \begin{pmatrix} 3 \\ 4 \end{pmatrix}`$:

```math
         \hat{\mathbf{v}} = \frac{\begin{pmatrix} 3 \\ 4 \end{pmatrix}}{5} = \begin{pmatrix} \frac{3}{5} \\ \\ \frac{4}{5} \end{pmatrix}
```

- This unit vector $`\hat{\mathbf{v}}`$ indicates the direction in which $`\mathbf{v}`$ points.

- **Angle Calculation**:

  - **Cosine of Angle**: Another approach is to calculate the angle $\theta$ that the vector makes with a reference axis (usually the positive x-axis).

```math
       \theta = \cos^{-1}\left(\frac{v_1}{|\mathbf{v}|}\right)
```

- Here, $v_1$ is the x-component of $\mathbf{v}$.

  - **Example**:

    - For $`\mathbf{v} = \begin{pmatrix} 3 \\ 4 \end{pmatrix}`$ :

      $$\theta = \cos^{-1}\left(\frac{3}{5}\right)$$

      - This angle $\theta$ measures the direction of $\mathbf{v}$ relative to the positive x-axis.

3. **Geometric Interpretation**:

   - **Visualization**: In a coordinate system, vectors can be visualized as arrows starting at the origin and pointing to a specific point in space.

   - **Application**: Used in physics for representing forces, velocities, and accelerations; in engineering for forces and directions; and in data science for feature representation.

4. **Practical Applications**:
   - **Navigation**: Vectors are crucial in navigation for representing directions and distances.
   - **Engineering**: They are used to model forces, velocities, and directions of motion.
   - **Data Science**: Vectors represent features and dimensions in machine learning and statistical analysis.

---

### **7. What is the difference between a square matrix and a rectangular matrix?**

The difference between a square matrix and a rectangular matrix:

1. **Square Matrix**:

   - **Dimensions**: A square matrix has an equal number of rows and columns. For example, an $`n \times n`$ matrix where n is a positive integer.
   - **Example**: $`2 \times 2`$, $`3 \times 3`$, etc.
   - **Properties**:
     - Can have an inverse if and only if it is nonsingular (determinant $`\neq`$ 0).
     - Has an identity matrix of the same size.
     - Determinant is defined and provides important information about the matrix.
     - Multiplication is commutative under certain conditions (e.g., scalar multiplication).

2. **Rectangular Matrix**:
   - **Dimensions**: A rectangular matrix has a different number of rows and columns. For example, $`m \times n`$ where $`m \neq n`$.
   - **Example**: $`2 \times 3`$, $`3 \times 2`$, etc.
   - **Properties**:
     - Does not have an inverse in the traditional sense, but can have a pseudoinverse (Moore-Penrose inverse).
     - Does not have an identity matrix in the same sense as a square matrix.
     - Determinant is not defined.
     - Matrix multiplication is not commutative in general.

**Summary:**

- **Square Matrix**: Equal rows and columns, can have an inverse and identity matrix, determinant is defined.
- **Rectangular Matrix**: Different rows and columns, no traditional inverse or identity matrix, determinant is not defined, and multiplication is not commutative.

---

In data science, both square matrices and rectangular matrices play crucial roles in various applications. Here are some specific ways they are used:

**Applications of Square Matrices in Data Science:**

1. **Principal Component Analysis (PCA)**:

   - **Application**: PCA involves computing the eigenvalues and eigenvectors of the covariance matrix (a square matrix) to reduce the dimensionality of data while preserving its variance.

2. **Covariance and Correlation Matrices**:

   - **Application**: These matrices (square) are used to analyze relationships between multiple variables in datasets, such as in feature selection and understanding data dependencies.

3. **Optimization and Machine Learning Models**:

   - **Application**: Many optimization algorithms and machine learning models involve manipulating square matrices, such as in gradient descent for training neural networks or solving convex optimization problems.

4. **Graph Algorithms**:

   - **Application**: Algorithms like PageRank (used in search engine algorithms) involve manipulating adjacency matrices (square matrices) to model and analyze relationships in networks.

5. **Matrix Factorization**:
   - **Application**: Techniques like Singular Value Decomposition (SVD) and Eigenvalue Decomposition (EVD) (based on square matrices) are used for collaborative filtering and recommendation systems in data science.

**Applications of Rectangular Matrices in Data Science:**

1. **Data Representation**:

   - **Application**: Rectangular matrices are fundamental for representing structured data in tables, spreadsheets, databases, and CSV files, which are typical data formats used in data science projects.

2. **Machine Learning Models**:

   - **Application**: In supervised learning, the dataset is typically represented as a rectangular matrix where rows are instances (samples) and columns are features (variables). Algorithms such as linear regression, logistic regression, and decision trees operate on these matrices.

3. **Image and Text Data**:

   - **Application**: Images and text data are often represented as rectangular matrices where rows represent pixels (image data) or words (text data), and columns represent features or attributes.

4. **Dimensionality Reduction**:

   - **Application**: Techniques like Non-negative Matrix Factorization (NMF) and Latent Dirichlet Allocation (LDA) involve factorizing rectangular matrices to discover latent features and reduce dimensionality in data science tasks.

5. **Sparse Matrix Representations**:
   - **Application**: Many real-world datasets are sparse (mostly zero values), and efficient data structures (like compressed sparse row (CSR) format) are used to store and manipulate rectangular matrices in memory and computations.

**Summary:**

- **Square Matrices** are used in advanced mathematical computations, graph algorithms, optimization, and matrix factorization techniques in data science.
- **Rectangular Matrices** are central to data representation, machine learning models, image/text processing, and handling structured datasets in various data science applications.

### **8. What is a basis in linear algebra?**

A basis in linear algebra is a set of vectors that serves as the fundamental building blocks for a vector space. To qualify as a basis, this set of vectors must satisfy two crucial conditions:

1. **Linear Independence**:

   - The vectors in the basis must be linearly independent. This means no vector in the basis can be written as a linear combination of the other vectors. For instance, in a set of basis vectors, the only solution to the equation $`c_1 \mathbf{v}_1 + c_2 \mathbf{v}_2 + \ldots + c_n \mathbf{v}_n = \mathbf{0}`$ is when all the coefficients $`c_1, c_2, \ldots, c_n`$ are zero.

2. **Spanning the Vector Space**:
   - The vectors in the basis must span the vector space. This means any vector in the vector space can be expressed as a linear combination of the basis vectors. In other words, the basis vectors can generate the entire vector space through their linear combinations.

**Example**:

- Consider the vector space $`\mathbb{R}^2`$. A common basis for this space is the set of vectors:

```math
  \mathbf{e}_1 = \begin{pmatrix} 1 \\ 0 \end{pmatrix}, \quad \mathbf{e}_2 = \begin{pmatrix} 0 \\ 1 \end{pmatrix}
```

These vectors are linearly independent and any vector in $`\mathbb{R}^2`$ can be expressed as a linear combination of $`\mathbf{e}_1`$ and $`\mathbf{e}_2`$.

**Practical Explanation**:

- Think of a basis as a minimal set of directions needed to navigate the entire space. In $`\mathbb{R}^2`$, the standard basis vectors $`\mathbf{e}_1`$ and $`\mathbf{e}_2`$ are like the X and Y directions on a map. With just these two directions, you can reach any point on the map by moving a certain distance along $`\mathbf{e}_1`$ and $`\mathbf{e}_2`$.

**Applications in Data Science**:

- In data science, bases are used in dimensionality reduction techniques like Principal Component Analysis (PCA). PCA finds a new basis (the principal components) that maximizes the variance in the data, allowing for a more compact representation.

---

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
