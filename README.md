# Statistics for Data Science

A comprehensive project exploring fundamental and advanced statistical concepts essential for data science practitioners. This repository contains implementations, analyses, and practical examples of statistical methods used in modern data science workflows.

## 📋 Table of Contents

- [Overview](#overview)
- [Project Structure](#project-structure)
- [Key Topics](#key-topics)
- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)
- [Project Contents](#project-contents)
- [Learning Outcomes](#learning-outcomes)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## 🎯 Overview

This project serves as a comprehensive guide to statistics for data science, covering essential concepts from foundational probability and descriptive statistics to advanced inference techniques and predictive modeling. The repository combines theoretical explanations with practical Python implementations and real-world examples.

**Project Focus:**
- Statistical foundations for data analysis
- Probability theory and distributions
- Hypothesis testing and inference
- Regression analysis and prediction
- Bayesian methods
- Time series analysis
- Practical applications in machine learning

## 📁 Project Structure

```
Data-Science-project-/
├── README.md
├── notebooks/
│   ├── 01_descriptive_statistics.ipynb
│   ├── 02_probability_distributions.ipynb
│   ├── 03_hypothesis_testing.ipynb
│   ├── 04_regression_analysis.ipynb
│   ├── 05_bayesian_methods.ipynb
│   └── 06_time_series_analysis.ipynb
├── src/
│   ├── __init__.py
│   ├── statistical_functions.py
│   ├── visualization_utils.py
│   └── data_processing.py
├── data/
│   ├── raw/
│   ├── processed/
│   └── datasets.md
├── tests/
│   ├── __init__.py
│   └── test_statistical_functions.py
├── requirements.txt
└── .gitignore
```

## 📚 Key Topics

### 1. **Descriptive Statistics**
   - Measures of central tendency (mean, median, mode)
   - Measures of dispersion (variance, standard deviation, IQR)
   - Skewness and kurtosis
   - Data visualization techniques

### 2. **Probability Theory**
   - Basic probability concepts and rules
   - Conditional probability and independence
   - Random variables and probability distributions
   - Law of large numbers and central limit theorem

### 3. **Probability Distributions**
   - Discrete distributions (Binomial, Poisson, Geometric)
   - Continuous distributions (Normal, Exponential, Beta, Gamma)
   - Distribution fitting and selection
   - Q-Q plots and goodness-of-fit tests

### 4. **Hypothesis Testing**
   - Null and alternative hypotheses
   - Type I and Type II errors
   - t-tests, z-tests, and chi-square tests
   - P-values and significance levels
   - Power analysis

### 5. **Regression Analysis**
   - Simple and multiple linear regression
   - Model assumptions and diagnostics
   - Feature selection and regularization
   - Logistic regression for classification

### 6. **Bayesian Methods**
   - Bayes' theorem and Bayesian inference
   - Prior, likelihood, and posterior distributions
   - Bayesian regression
   - MCMC methods

### 7. **Time Series Analysis**
   - Autocorrelation and partial autocorrelation
   - ARIMA models
   - Seasonal decomposition
   - Forecasting techniques

## 🔧 Requirements

- Python 3.8+
- Jupyter Notebook
- NumPy
- Pandas
- SciPy
- Scikit-learn
- Matplotlib
- Seaborn
- Statsmodels

## 📦 Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/hesneyhasin/Data-Science-project-.git
   cd Data-Science-project-
   ```

2. **Create a virtual environment (optional but recommended):**
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install required packages:**
   ```bash
   pip install -r requirements.txt
   ```

## 🚀 Usage

### Running Jupyter Notebooks

```bash
jupyter notebook
```

Navigate to the `notebooks/` directory and open any notebook to explore the topics and examples.

### Using Statistical Functions

```python
from src.statistical_functions import *

# Example: Calculate descriptive statistics
data = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10]
stats = calculate_descriptive_stats(data)
print(stats)
```

### Running Tests

```bash
pytest tests/
```

## 📖 Project Contents

### Notebooks

Each notebook contains:
- **Theoretical explanations** with mathematical formulations
- **Code implementations** with detailed comments
- **Practical examples** with real or simulated datasets
- **Visualizations** to illustrate concepts
- **Exercises** for practice and reinforcement

### Source Code

The `src/` directory contains reusable functions for:
- Statistical computations
- Data visualization
- Data preprocessing and cleaning

### Data

Sample datasets are provided in the `data/` directory:
- Raw datasets for practice
- Processed datasets ready for analysis
- Data documentation in `datasets.md`

## 🎓 Learning Outcomes

After completing this project, you will be able to:

✓ Understand and apply descriptive statistical methods
✓ Work with probability distributions and calculate probabilities
✓ Conduct hypothesis tests and interpret results
✓ Build and evaluate regression models
✓ Apply Bayesian inference to real-world problems
✓ Analyze and forecast time series data
✓ Communicate statistical findings effectively
✓ Implement statistical methods in Python
✓ Make data-driven decisions using statistical evidence

## 🤝 Contributing

Contributions are welcome! To contribute:

1. Fork the repository
2. Create a new branch: `git checkout -b feature/your-feature`
3. Make your changes and commit: `git commit -am 'Add new feature'`
4. Push to the branch: `git push origin feature/your-feature`
5. Submit a pull request

Please ensure your contributions:
- Follow PEP 8 style guidelines
- Include docstrings and comments
- Add relevant tests
- Update documentation as needed

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 📧 Contact

**Author:** Hesney Hasin  
**GitHub:** [@hesneyhasin](https://github.com/hesneyhasin)  
**Email:** [Your Email]

For questions, suggestions, or collaborations, feel free to reach out!

---

**Last Updated:** December 18, 2025

### Resources & References

- [StatQuest with Josh Starmer](https://www.youtube.com/c/joshstarmer)
- [Introduction to Statistical Learning (ISLR)](https://www.statlearning.com/)
- [Think Stats](http://greenteapress.com/thinkstats/)
- [SciPy Documentation](https://docs.scipy.org/)
- [Statsmodels Documentation](https://www.statsmodels.org/)

### Related Topics to Explore

- Machine Learning Fundamentals
- Advanced Causal Inference
- Experimental Design
- Bayesian Deep Learning
- Statistical Consulting

**Happy Learning! 📊**
