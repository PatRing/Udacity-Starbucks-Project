## Udacity-Starbucks-Project

# Python Libraries Used

-Python Data Analysis Library
-Numpy
-Matplotlib
-seaborn: Statistical Data Visualization
-os — Miscellaneous operating system interfaces
-scikit-learn: Machine Learning in Python

# References 

https://stackoverflow.com/questions/40245507/python-pandas-selecting-rows-whose-column-value-is-null-none-nan

https://stackoverflow.com/questions/38987/how-to-merge-two-dictionaries-in-a-single-expression

https://www.google.com/search?client=firefox-b-d&ei=WDmZXNLXEInTkgWLpZKYDQ&q=multiple+regression+in+python&oq=multiple+regression+in+python&gs_l=psy-ab.3..0i203l5j0i22i30l5.1853.2595..2782...0.0..0.77.505.7......0....1..gws-wiz.......0i71j35i39j0j0i22i10i30.QNIRBf9QRfA

# How consumers behave on the Starbucks reward app (Udacity Project)

Companies need to gather insights to understand how consumers respond to various types of special reward programs. Based on these insights, companies can effectivley manage these programs and create a value-added for their customers. In this post, I try to outline ways how companies can observe patterns in their consumer data related to such reward programs.

Link to my blog: https://medium.com/@patrick.ring/how-consumers-behave-on-the-starbucks-reward-app-udacity-project-4082575dc3fc


# Background

Based on simulated data of consumer behavior on the Starbucks rewards mobile application, I provide a careful analysis of consumer behavior. This is part of the Udacity Nanodegree Data Science.

# Goals

I try to answer the following three questions. Please keep in mind that all results are obtained from simulated data and do not necessarily apply to the real world.

    What consumers use the Starbucks rewards mobile application? Are there differences between men and women?
    How do different types of consumers behave on this platform?
    How effectively are different reward programs in incentivising purchases?
    
   # Question 1: What consumers use the Starbucks rewards mobile application?

First, I look at the characteristics of consumers using the app. In total, there are ~ 15000 customers registered (40% women). On average, the male customers are 52 years old and therefore younger than the female customers which are, on average, are 58 years old. The income distribution is shown below and reveals that women on this platform, on average, are “richer” and have a more normally distributed income structure.

# Question 2: How do different types of consumers respond to different reward programs?

Next, we look at the behavior of different types of consumers on this platform. In a linear regression model, we study how the total amount spent depends on the following variables: age, gender, income. This analysis reveals that consumers with higher incomes have significantly higher total transactions (not surprising); older people and women, on average, as well.

# Question 3: How effectively are different reward programs in increasing purchases?

When we look at the effectiveness of the different programs, we find that information on new products increase purchases, as well as reward programs. Interestingly, buy-one-get-one-free programs, on average, reduce the amount spent on the mobile app. This is plausible because consumers save money by not having to buy the additional item.

# Improvement section

In future specifications, it may be possible to apply machine learning to predict transactions based on both consumer characteristics and reward programs. This would provide companies a powerful tool for directing their marketing activities. Potential applications may be random forests or neural networks.

# Summary of the results

In this blog, we have identified clusters of consumers using the Starbucks reward app. We have analyzed the characteristics of different consumer clusters and their behavior on the app. Finally, we have studied the effectiveness of different reward programs. The key insight is that informational and reward programs boost transactions, while buy-one-get-one-free programs do not. In fact, they decrease transactions.
