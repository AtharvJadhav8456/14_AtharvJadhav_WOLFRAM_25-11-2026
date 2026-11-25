# Mathematics for AI & Machine Learning — Wolfram Demonstrations Lab Report

## 📌 Overview
This repository/report documents a series of interactive mathematical and statistical experiments performed using **Wolfram Demonstrations** as part of the **2nd-Year B.Tech (Artificial Intelligence & Machine Learning)** curriculum. The objective of these experiments is to build an intuitive, visual understanding of probability distributions, statistical inference, and limit theorems that serve as the mathematical backbone of modern AI/ML algorithms.

---

## 🧪 List of Experiments

### 1. Hypothesis Tests about a Population Mean
* **Wolfram Resource:** `ResourceData["Demonstration: Hypothesis Tests about a Population Mean"]`
* **Objective:** To visually explore statistical hypothesis testing for an unknown population mean using a $t$-distribution with $n - 1$ degrees of freedom.
* **Key Observations:** By varying sample size ($n$), hypothesized mean ($\mu_0$), significance level ($\alpha$), and standard deviation ($\sigma$), we observed how sample variations impact the $t$-test statistic ($t = \frac{\bar{X} - \mu_0}{s / \sqrt{n}}$) and the resulting $p$-value relative to the rejection region.
* **AI/ML Relevance:** Forms the basis for A/B testing, statistical feature selection, and validating whether improvements in model accuracy are statistically significant.

---

### 2. Dice Probabilities
* **Wolfram Resource:** `ResourceData["Demonstration: Dice Probabilities"]`
* **Objective:** To analyze discrete probability distributions and sample spaces for the sum of outcomes when rolling multiple $n$-sided dice.
* **Key Observations:** Adjusting the number of dice and sides demonstrated how the probability distribution transitions from uniform (1 die) to a symmetric, bell-shaped curve as the number of dice increases—providing an early visual intuition of the Central Limit Theorem.
* **AI/ML Relevance:** Essential for understanding discrete sample spaces, stochastic algorithms, probabilistic graphical models, and Monte Carlo simulations.

---

### 3. Normal Approximation to a Binomial Random Variable
* **Wolfram Resource:** `ResourceData["Demonstration: Normal Approximation to a Binomial Random Variable"]`
* **Objective:** To examine how a discrete binomial distribution ($n, p$) converges to a continuous normal distribution with matching mean ($\mu = np$) and variance ($\sigma^2 = np(1-p)$).
* **Key Observations:** Measuring the overlapping area (percentage agreement) confirmed the **Central Limit Theorem**, showing that the normal approximation becomes highly accurate as the number of trials ($n$) increases and $p$ approaches $0.5$.
* **AI/ML Relevance:** Used to simplify large-scale probability computations, estimate confidence intervals for classifier performance, and model noise across large datasets.

---

### 4. Standard Normal Distribution Areas
* **Wolfram Resource:** `ResourceData["Demonstration: Standard Normal Distribution Areas"]`
* **Objective:** To compute cumulative probabilities and tail areas under the standard normal curve ($\mu = 0, \sigma = 1$) using lower and upper $z$-score bounds ($z_1, z_2$).
* **Key Observations:** Using interval and complement controls, we visually verified the **68–95–99.7 empirical rule**, confirming the proportion of data lying within 1, 2, and 3 standard deviations of the mean.
* **AI/ML Relevance:** Directly applied in Z-score feature scaling (standardization), statistical anomaly/outlier detection, and Gaussian Naive Bayes classifiers.

---

## 🛠️ Tools & Environment
* **Platform:** Wolfram Cloud / Wolfram Mathematica (`ResourceData` Demonstrations)
* **Course Level:** 2nd Year B.Tech — Artificial Intelligence & Machine Learning

---

## 🚀 How to Run the Demonstrations
1. Open **Wolfram Mathematica** or **Wolfram Cloud**.
2. Create a new notebook (`.nb`).
3. Evaluate any of the `ResourceData[...]` commands listed under the experiments above (e.g., `ResourceData["Demonstration: Dice Probabilities"]`) using `Shift + Enter` to launch the interactive controls.
