---
title: "Part 3: Machine Learning Methods for Trading"
description: "Machine learning methods and their application to trading decisions."
weight: 30
---

Note: The content on this page is subject to change before class starts.

{{< collapse summary="Lesson 1: Machine Learning in Trading" openByDefault=true >}}

In this lesson, we will introduce how hedge funds use machine learning and how trading models are tested before being used.

### Topics Covered

- How hedge funds use machine learning
- Trading problems machine learning can address
- Backtesting
- Out-of-sample testing
- Roll-forward cross validation
- Why testing matters in financial modeling

{{< /collapse >}}

{{< collapse summary="Lesson 2: Supervised Learning for Trading Signals" >}}

In this lesson, we will review common supervised learning methods and introduce the trading problem used in the rest of the module.

### Topics Covered

- Linear regression
- KNN regression
- Decision trees and random forests
- Regression and classification
- Parametric and instance-based models
- Limits of regression in finance
- Introduction to reinforcement learning
- Training period and testing period
- Creating trades for the backtester

{{< /collapse >}}

{{< collapse summary="Lesson 3: Regression Models for Trading" >}}

In this lesson, we will introduce regression as a way to predict future stock behavior and connect it to the trading workflow.

### Topics Covered

- Role of regression in trading models
- Fake stock data with embedded patterns
- Training features and target values
- Making predictions with new data
- Learner API structure
- `constructor`
- `addEvidence(X, y)`
- `query(X)`
- Implementing linear regression

{{< /collapse >}}

{{< collapse summary="Lesson 4: Evaluating Learning Algorithms" >}}

In this lesson, we will compare linear regression and KNN and learn how to measure model performance in trading problems.

### Topics Covered

- Linear regression versus KNN
- Extrapolation and local prediction
- Adding new data to a model
- Cross validation
- Roll-forward cross validation
- Recent data versus full history
- Batch learning versus online learning
- Training time versus query time
- RMS error
- Predicted versus actual scatter plots
- Correlation coefficient
- Overfitting

{{< /collapse >}}

{{< collapse summary="Lesson 5: Ensemble Learning for Trading Models" >}}

In this lesson, we will learn how ensemble methods combine multiple learners to improve prediction performance.

### Topics Covered

- What ensemble learners are
- Combining different algorithms
- Bagging
- Boosting
- Decision trees
- Random forests
- Ensemble methods in prediction competitions

{{< /collapse >}}

{{< collapse summary="Lesson 6: Reinforcement Learning" >}}

In this lesson, we will introduce reinforcement learning and explain how it differs from supervised learning.

### Topics Covered

- Reinforcement learning problem setup
- Agent, environment, actions, and rewards
- Model-based learning
- Model-free learning
- Why reinforcement learning fits trading problems

{{< /collapse >}}

{{< collapse summary="Lesson 7: Q-Learning" >}}

In this lesson, we will introduce Q-learning as a model-free reinforcement learning method.

### Topics Covered

- Q-learning intuition
- States, actions, and rewards
- Q-table
- Updating Q-values
- Exploration versus exploitation
- Applying Q-learning to trading decisions

{{< /collapse >}}

{{< collapse summary="Lesson 8: Dyna" >}}

In this lesson, we will learn how Dyna combines real experience with simulated experience to improve learning.

### Topics Covered

- Dyna learning framework
- Real experience
- Simulated experience
- Learning from a model
- Updating the policy faster
- Using Dyna for trading problems

{{< /collapse >}}
