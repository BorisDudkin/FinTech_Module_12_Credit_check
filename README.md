# Credit Check

### Credit Check attempts to predict the credit quality of the loans comprising a loan portfolio by applying machine learning models to the loan related data.<br/>The application takes us through the complete model selection process: data analysis, model selection, model application and the predictions evealuation.<br/> Finally, a summary report is generated to describe each of those steps in details and provide recommendations for the ultimate model selection.

---

![creit](Images/credit.png)

---

## Table of contents

1. [Technologies](#technologies)
2. [Installation Guide](#installation-guide)
3. [Usage](#usage)
4. [Contributors](#contributors)
5. [License](#license)

---

## Technologies

`Python 3.9`

`Jupyter lab`

_Prerequisites_

1. `Pandas` is a Python package that provides fast, flexible, and expressive data structures designed to make working with large sets of data easy and intuitive.

   - [pandas](https://github.com/pandas-dev/pandas) - for the documentation, installation guide and dependencies.

2. `Scikit-learn` is a simple and efficient tools for predictive data analysis. It is built on NumPy, SciPy, and matplotlib.

   - [scikit-learn ](https://scikit-learn.org/stable/) - for information on the library, its features and installation instructions.<br/>

---

## Installation Guide

Jupyter lab is a preferred software to work with Risk Return Analysis application.<br/> Jupyter lab is a part of the **[anaconda](https://www.anaconda.com/)** distribution package and therefore it is recommended to download **anaconda** first.<br/> Once dowloaded, run the following command in your terminal to lauch Jupyter lab:

```python
jupyter lab
```

Before using the application first install the following dependencies by using your terminal:

To install pandas run:

```python
#  PuPi
pip install pandas
```

```python
# or conda
conda install pandas
```

To install scikit library, in Terminal run:

```python
# PuPi
pip install -U scikit-learn
```

Confirm the installation of the scikit library by running the following commands in Terminal type:

```python
 conda list hvplot
```

## Usage

> Application summary<br/>

To effectively utilize Credit Check application please use the credit_risk_resampling.ipynb jupyter notebook in conjunction with the Report.md document that contains the Loans Credit Quality Prediction Report. The Report begins with the purpose of the analysis presented in the notebook and continues with the description of each step taken to arrive at the final model recommendation, namely:

- Purpose of the analysis;
- Assessment of the available client data and identification of the goal of the machine learning model;
- Model selection criteria;
- Stages of the machine learning process;
- Evaluation comparison of the two models being assessed;
- Summary, containing conclusion and recommendations.

> Getting started<br/>

- To use Credit Check first clone the repository to your PC.<br/>
- Open `Jupyter lab` as per the instructions in the [Installation Guide](#installation-guide) to run the application.<br/>

---

## Contributors

Contact Details:

Boris Dudkin:

- [Email](boris.dudkin@gmail.com)
- [LinkedIn](www.linkedin.com/in/Boris-Dudkin)

---

## License

MIT

---
