# Intuition Builders

A collection of from-scratch, visual proofs and explainers built while self-studying statistics, ML, and other technical topics, helping us get to our "aha!" moments.

Most explanations of these concepts assume you already have the intuition instructors do. These notebooks work the other direction: build things by hand, simulate the failure cases side by side with the ideal case, and let the shapes become recognizable rather than something you have to consciously reason through every time.

## What's here

| Notebook | What it builds intuition for |
|---|---|
| [`01_sample_variance_proof.ipynb`](01_sample_variance_proof.ipynb) | Why sample variance divides by *n* − 1 instead of *n* (Bessel's correction), worked from scratch rather than taken on faith |
| [`02_regression_diagnostic.ipynb`](02_regression_diagnostic.ipynb) | Reading regression diagnostic plots by sight — currently **in progress**, see below |

## In progress: Regression Diagnostics

This notebook walks through the standard diagnostic plots for a linear model, showing what each looks like when assumptions hold versus when they're violated.

**Done:**
- Residuals vs. Fitted (linearity, constant variance)
- Q-Q Plot (normality)

**Coming:**
- Scale-Location
- Residuals vs. Leverage (Cook's distance)
- Independence: Residuals vs. Order / ACF

I'm building this alongside a companion post series, one plot per week — check back for updates, or follow along on [LinkedIn](https://linkedin.com/in/carlossanta).
