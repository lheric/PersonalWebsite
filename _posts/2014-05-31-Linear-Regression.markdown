---
layout: post
title:  "Linear Regression"
date:   2014-05-31 23:02:56
categories: linear regression machine learning
---

***Model***

$$f(x_i) = \theta_0 + \theta_1 x_i$$

***Cost Function***

$$J = {1 \over 2m} \sum_{i=0}^{m-1}(y_i-f(x_i))^2$$

***Partial Derivative***

$${\partial J \over \partial \theta_0} =  {1 \over m} \sum_{i=0}^{m-1}(f(x_i)-y_i)$$

$${\partial J \over \partial \theta_1} =  {1 \over m} \sum_{i=0}^{m-1}(f(x_i)-y_i)x_i$$

***Gradient Descent***

update the parameters $\theta_0$ and $\theta_1$ by the following formula:

$$\theta_0 = \theta_0 - \alpha {\partial J \over \partial \theta_0}$$

$$\theta_1 = \theta_1 - \alpha {\partial J \over \partial \theta_0}$$

where $\alpha$ is the learning rate
