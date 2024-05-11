# Probability Theory

## Discrete and Continuous Random Variables, Conditional Probability, Joint Probability Distribution, Multivariate, MAP Criterion, ML Criterion

This concise guide covers key probability concepts relevant to ML exams, including formulas:

**1. Random Variables (RVs):**

- **Concept:** A variable whose value depends on chance (outcome of a random experiment).

**Types:**

  - **Discrete:** Takes a finite or countable number of values (e.g., coin flips, dice rolls).
  - **Continuous:** Can take any value within a specific range (e.g., heights, weights).

**2. Probability Distribution Function (PDF):**

- **Discrete:**
  $$
  P(X = x) = f(x)
  $$
  where:
    - \\(P(X = x)\\) is the probability of RV X taking on value x
    - \\(f(x)\\) is the probability mass function (PMF)
- **Continuous:**
  $$
  P(a ≤ X ≤ b) = ∫_a^b f(x) dx
  $$
  where:
    - \\(P(a ≤ X ≤ b)\\) is the probability of X falling within the range a to b
    - \\(f(x)\\) is the probability density function (PDF)

**3. Conditional Probability:**

- **Concept:** Probability of event B occurring given that event A has already happened.
- **Formula:**
  $$
  P(B | A) = P(A ∩ B) / P(A)
  $$
  where:
    - \\(P(B | A)\\) is the conditional probability of B given A
    - \\(P(A ∩ B)\\) is the joint probability of A and B happening together
    - \\(P(A)\\) is the probability of event A occurring

**4. Joint Probability Distribution (JPD):**

- **Concept:** Describes the probability of multiple RVs occurring simultaneously.
- **Discrete:** A table or formula specifying the probability of each combination of values.
- **Continuous:** A function that takes multiple values as arguments and outputs the joint probability.

**5. Multivariate Distribution:**

- **Concept:** A joint probability distribution for more than two RVs.
- **Example:** Distribution of height and weight of individuals (two RVs).

**6. Maximum A Posteriori (MAP) Criterion:**

- **Concept:** A decision rule in ML that finds the most probable hypothesis (parameter values) given the observed data.
- **Formula:**
  $$
  argmax_θ P(θ | X)
  $$
  where:
    - θ (theta) represents the hypothesis (parameter values)
    - X represents the observed data
    - \\(P(θ | X)\\) is the posterior probability of θ given X, using Bayes' theorem

**7. Maximum Likelihood (ML) Criterion:**

- **Concept:** A method for estimating model parameters by finding the values that maximize the likelihood of observing the training data.
- **Formula:**
  $$
  argmax_θ P(X | θ)
  $$
  where:
    - θ represents the model parameters
    - X represents the observed data
    - \\(P(X | θ)\\) is the likelihood of X given θ

**Remember:**

- These are foundational concepts. Exams may delve deeper into specific probability distributions and their applications in ML algorithms.
- Practice using these formulas and interpreting probabilities in the context of ML problems.


---

### Summary

Sure, here are some concise notes on the requested Machine Learning topics:

**1. Discrete and Continuous Random Variables:**

- A random variable is a variable whose possible values are numerical outcomes of a random phenomenon.
- Discrete random variables can only take specific values (like integers), while continuous random variables can take any value in a given range or interval <sup>[1](https://www.geeksforgeeks.org/random-variable/) [2](https://byjus.com/maths/random-variable/) [3](http://isl.stanford.edu/~abbas/ee178/lect02-2.pdf) [4](https://www.khanacademy.org/math/statistics-probability/random-variables-stats-library/random-variables-discrete/v/discrete-and-continuous-random-variables)</sup>.

**2. Conditional Probability:**

- Conditional probability is the probability of an event given that another event has occurred <sup>[5](https://byjus.com/maths/conditional-probability/) [6](https://www.cuemath.com/data/conditional-probability/) [7](https://www.geeksforgeeks.org/conditional-probability/)</sup>.
- It is represented as P(A|B), which means the probability of event A given that event B has occurred.

**3. Joint Probability Distribution:**

- Joint probability distribution represents a probability distribution for two or more random variables <sup>[8](https://stt.msu.edu/Academics/ClassPages/uploads/US19/351-201/Lecture-08.pdf) [9](https://statisticsbyjim.com/probability/joint-probability/) [10](https://byjus.com/maths/joint-probability/) [11](https://en.wikipedia.org/wiki/Joint_probability_distribution)</sup>.
- It is used to determine the probability that all of several events occur simultaneously.

**4. Multivariate:**

- Multivariate analysis involves observation and analysis of more than one statistical outcome variable at a time <sup>[12](https://careerfoundry.com/en/blog/data-analytics/multivariate-analysis/) [13](https://online.stat.psu.edu/stat505/) [14](https://babar.heprc.uvic.ca/BFROOT/www/Statistics/mva.pdf) [15](https://www.tutorialsduniya.com/notes/multivariate-calculus-notes/) [16](http://www.statslab.cam.ac.uk/~pat/AppMultNotes.pdf)</sup>.
- It provides a method to study the behavior of random variables simultaneously, allowing patterns and relationships to be observed.

**5. Maximum A Posteriori (MAP) Criterion:**

- MAP is a Bayesian-based approach to estimating a distribution and model parameters that best explain an observed dataset <sup>[17](https://machinelearningmastery.com/maximum-a-posteriori-estimation/) [18](https://www.probabilitycourse.com/chapter9/9_1_2_MAP_estimation.php) [19](https://web.stanford.edu/class/archive/cs/cs109/cs109.1216/lectures/22_map.pdf)</sup>.
- It calculates a conditional probability of observing the data given a model weighted by a prior probability or belief about the model.

**6. Maximum Likelihood (ML) Criterion:**

- ML estimation is a method of estimating the parameters of a statistical model given observations.
- The ML estimates are the values of the parameters that maximize the likelihood function, making the observed data most probable.

Remember, these are just brief overviews. For a deeper understanding, you should refer to textbooks or detailed course materials. Good luck with your exam!