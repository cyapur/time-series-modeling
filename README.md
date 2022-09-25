# Objective of this notebook

The objective of this notebook is to try to show how I think when I develop a ML model, this attempt will be done through a simple and complete approach to time-series problem with linear regression and Fourier series. For this, I will draw some dimensions this notebook will/won't cover:

- I will do an applied (and fictional) business case for this project. However, for this I will need to do some assumptions explained later.
- We will compare typical time-series baseline models (last observation, historical mean, and historical median) vs multivariate linear regression (with deterministic processes)
- This notebook won't cover tree-based models as the final increase in performance obtained are sufficient for a business case application. However, in the future, I will do a purely-technical approach comparing the models in this project with tree-based models + trend (as tree-based models don't extrapolate), and LSTM.
That said, let's start!

You are more than welcome to give a feedback about the approach of this problem.
