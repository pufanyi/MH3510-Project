# MH3510 Project

**As we're approaching graduation, we'd really appreciate it if you gave this project a star if you find it helpful! 🙏**

[Report](https://pufanyi.github.io/MH3510-Project/report/MH3510_Project.pdf) / [Code (html)](https://pufanyi.github.io/MH3510-Project/) / [Code (pdf)](https://pufanyi.github.io/MH3510-Project/index.pdf)

In this study, we investigate factors affecting Annual Average Daily Traffic (AADT) on road section, using a dataset comprising five variables. We demonstrate our overall pipeline in the figure below. After inputting our data, we first observe its distribution. To address the skewness in some of the data, we applied transformations to the data.

After that, we conduct Single Linear Regression (SLR) analysis. We analyze and explain the influence of each variable on the response variable in detail through this approach. In parallel, we also perform Multiple Linear Regression (MLR) analysis to get the more precise model. For variables found to be significant, we proceed to use them for prediction.

![](docs/imgs/intro.png)

Our final model can demonstrates below.

<img src="docs/imgs/model.png" alt="Model" style="display: block; margin: auto; width: 50%;">

And the residual plot of our model is shown below.

![](docs/imgs/residuals.png)
