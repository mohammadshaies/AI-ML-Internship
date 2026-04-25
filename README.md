# AI-ML-Internship
My AI/ML Engineering internship tasks for Developers Hub.

## Task 1: Exploring and Visualizing a Simple Dataset
* **Task objective:** Learn how to load, inspect, and visualize a dataset to understand data trends and distributions.
* **Dataset used:** The Iris Dataset (loaded via seaborn).
* **Models applied:** None for this specific task (Exploratory Data Analysis only).
* **Key results and findings:**
  * **Scatter Plot:** The scatter plot made it really clear that *setosa* flowers are easy to identify. Their petals are a lot smaller than the other two species, so all their data points clump together in the bottom left corner.
  * **Histograms:** The sepal width data looks like a normal, even bell curve. But for the petal lengths and widths, there's a big empty gap in the middle of the charts. This makes sense because the tiny *setosa* flowers are separated from the rest.
  * **Box Plots:** Using the box plots was a great way to spot outliers. I noticed a few stray dots sitting just outside the whiskers specifically for the `sepal_width` column, which means a couple of those flowers were unusually wide or narrow.

## Task 2: Predict Future Stock Prices (Short-Term)
* **Task objective:** Use historical stock data to predict the next day's closing price.
* **Dataset used:** Real-time Yahoo Finance data (AAPL) retrieved using the `yfinance` library.
* **Models applied:** Linear Regression (using `scikit-learn`).
* **Key results and findings:** The model successfully tracked the general price trends of the stock. However, visualizing the actual vs. predicted prices revealed a slight lag during sudden market shifts, demonstrating the limitations of basic linear regression in highly volatile time-series environments.
