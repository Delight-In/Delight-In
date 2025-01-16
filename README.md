# 👋 Hi, I'm Priyanka

Welcome to my GitHub profile! I'm a passionate Data Scientist and AI enthusiast, constantly exploring the exciting world of data, machine learning, and artificial intelligence. Through this repository, I aim to share my projects, experiments, and learning journey.

## 👀 My Interests

- Physics
- Data Science
- Artificial Intelligence (AI)
- Machine Learning (ML)
- Deep Learning (DL)
- Computer Vision (CV)
- Natural Language Processing (NLP)
- Data Visualization
- Big Data & Cloud Technologies

## 🔧 Technologies & Tools

- **Languages**: Python, SQL, R
- **Libraries & Frameworks**:
  - Data Science: **Pandas**, **Numpy**, **SciPy**
  - Machine Learning: **Scikit-Learn**, **XGBoost**, **LightGBM**
  - Deep Learning: **TensorFlow**, **Keras**, **PyTorch**
  - Computer Vision: **OpenCV**, **YOLO**, **TensorFlow Object Detection API**
  - NLP: **SpaCy**, **Transformers**, **NLTK**
- **Data Visualization**: **Matplotlib**, **Seaborn**, **Plotly**
- **Version Control**: **Git**, **GitHub**
- **Cloud**: **AWS**, **Google Cloud Platform (GCP)**
- **Databases**: **MySQL**, **MongoDB**

## 🌱 Currently Learning
- Advanced Agorithms
- Reinforcement Learning
- Cloud computing for AI

## 📫 How to Reach Me
Feel free to connect with me on [LinkedIn](your-linkedin-url) or [Email](your-email-address). I’m open to discussions, collaborations, and feedback!


The Poisson equation is expressed as:

$$
\nabla^2 \phi(\mathbf{r}) = f(\mathbf{r})
$$

In electrostatics, the Poisson equation is:

$$
\nabla^2 \phi(\mathbf{r}) = -\frac{\rho(\mathbf{r})}{\epsilon_0}
$$


## Mathematics

### 1. **Counting (Permutation and Combination)**

- **Permutation (P(n, k))**: 
  - Formula: \( P(n, k) = \frac{n!}{(n - k)!} \)
  - Explanation: The number of ways to arrange \(k\) items out of \(n\) distinct items in a specific order.

- **Combination (C(n, k))**:
  - Formula: \( C(n, k) = \frac{n!}{k!(n - k)!} \)
  - Explanation: The number of ways to select \(k\) items from \(n\) distinct items without regard to order.

---

### 2. **Probability Axioms**

- **Axiom 1**: \( P(S) = 1 \), where \(S\) is the sample space.
- **Axiom 2**: For any event \(A\), \( P(A) \geq 0 \).
- **Axiom 3**: For mutually exclusive events \( A \) and \( B \), \( P(A \cup B) = P(A) + P(B) \).

---

### 3. **Sample Space and Events**

- **Sample Space (S)**: The set of all possible outcomes in a probability experiment.
  - Example: For a coin toss, \( S = \{H, T\} \).
  
- **Event (A)**: A subset of the sample space.
  - Example: Event A could be "getting heads" \( A = \{H\} \).

---

### 4. **Independent Events**

- **Definition**: Two events \(A\) and \(B\) are independent if the occurrence of one does not affect the probability of the other.
  - Formula: \( P(A \cap B) = P(A) \cdot P(B) \)

---

### 5. **Mutually Exclusive Events**

- **Definition**: Two events are mutually exclusive if they cannot occur at the same time.
  - Formula: \( P(A \cap B) = 0 \)

---

### 6. **Marginal, Conditional, and Joint Probability**

- **Marginal Probability**: The probability of a single event, ignoring the other events.
  - Formula: \( P(A) = \sum_{B} P(A \cap B) \)

- **Conditional Probability**: The probability of event \(A\) given that \(B\) has occurred.
  - Formula: \( P(A|B) = \frac{P(A \cap B)}{P(B)} \)

- **Joint Probability**: The probability of two events occurring simultaneously.
  - Formula: \( P(A \cap B) \)

---

### 7. **Bayes' Theorem**

- **Formula**: 
  \[
  P(A|B) = \frac{P(B|A) P(A)}{P(B)}
  \]
  - Explanation: It allows you to update the probability of an event based on new evidence.

---

### 8. **Conditional Expectation and Variance**

- **Conditional Expectation**: The expected value of \(X\) given event \(A\).
  - Formula: \( E[X|A] = \sum x \cdot P(X=x|A) \)

- **Conditional Variance**: The variance of \(X\) given event \(A\).
  - Formula: \( \text{Var}(X|A) = E[X^2|A] - (E[X|A])^2 \)

---

### 9. **Mean, Median, Mode, and Standard Deviation**

- **Mean (Expected Value)**:
  - Formula: \( E[X] = \sum x \cdot P(x) \)

- **Median**: The middle value in a sorted list of data points.
  
- **Mode**: The value that appears most frequently in a data set.

- **Standard Deviation (SD)**:
  - Formula: \( \sigma = \sqrt{\text{Var}(X)} \)

---

### 10. **Correlation and Covariance**

- **Covariance**: Measures the relationship between two variables.
  - Formula: \( \text{Cov}(X, Y) = E[(X - E[X])(Y - E[Y])] \)

- **Correlation**: Standardized measure of covariance.
  - Formula: \( \rho = \frac{\text{Cov}(X, Y)}{\sigma_X \sigma_Y} \)

---

### 11. **Random Variables**

- **Random Variable**: A variable whose value is determined by the outcome of a random experiment.

---

### 12. **Discrete Random Variables and Probability Mass Function**

- **Discrete Random Variable**: A variable that can take on a finite number of values.
- **Probability Mass Function (PMF)**: Describes the probability of each outcome of a discrete random variable.
  - Formula: \( P(X = x) \)

---

### 13. **Common Distributions**

- **Uniform Distribution (Discrete)**:
  - PMF: \( P(X = x) = \frac{1}{n} \), where \( n \) is the number of possible outcomes.

- **Bernoulli Distribution**:
  - PMF: \( P(X = 1) = p, \quad P(X = 0) = 1 - p \)

- **Binomial Distribution**:
  - PMF: \( P(X = k) = \binom{n}{k} p^k (1 - p)^{n - k} \)

- **Poisson Distribution**:
  - PMF: \( P(X = k) = \frac{\lambda^k e^{-\lambda}}{k!} \)

- **Exponential Distribution**:
  - PDF: \( f(x) = \lambda e^{-\lambda x}, \quad x \geq 0 \)

- **Normal Distribution**:
  - PDF: \( f(x) = \frac{1}{\sqrt{2\pi \sigma^2}} e^{-\frac{(x - \mu)^2}{2\sigma^2}} \)

- **Standard Normal Distribution**: A normal distribution with mean \(0\) and variance \(1\).
  
- **t-Distribution**: A family of distributions with different degrees of freedom, used for hypothesis testing when the sample size is small.

- **Chi-squared Distribution**: Distribution of the sum of the squares of \(k\) independent standard normal random variables.

---

### 14. **Cumulative Distribution Function (CDF)**

- **Formula**: \( F(x) = P(X \leq x) \)
- Explanation: The probability that a random variable takes a value less than or equal to \(x\).

---

### 15. **Central Limit Theorem**

- **Statement**: The distribution of the sum (or average) of a large number of independent, identically distributed random variables approaches a normal distribution, regardless of the original distribution.

---

### 16. **Confidence Interval**

- **Formula**: \( \bar{x} \pm Z_{\alpha/2} \frac{\sigma}{\sqrt{n}} \)
- Explanation: An interval estimate of a population parameter based on sample data.

---

### 17. **z-test**

- **Formula**: 
  \[
  z = \frac{\bar{x} - \mu_0}{\sigma / \sqrt{n}}
  \]
- Explanation: A hypothesis test for the population mean when the population variance is known.

---

### 18. **t-test**

- **Formula**: 
  \[
  t = \frac{\bar{x} - \mu_0}{s / \sqrt{n}}
  \]
- Explanation: A hypothesis test for the population mean when the population variance is unknown.

---

### 19. **Chi-squared Test**

- **Formula**: 
  \[
  \chi^2 = \sum \frac{(O_i - E_i)^2}{E_i}
  \]
- Explanation: A test for independence in contingency tables or for goodness of fit.

---

This overview covers many of the fundamental concepts in probability and statistics with their respective formulas and explanations.
