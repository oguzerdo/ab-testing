# AB - Testing

![Project](/images/project.png)

# Business Problem

Facebook recently introduced a new bidding type, `average bidding`, as an alternative to the existing bidding type called `maximum bidding`

One of our clients decided to test this new feature and wants to run an A/B test to see if `average bidding` brings more conversions than `maximum bidding`.

The A/B test has been running for 1 month and Our client is now asking you to analyze the results of this A/B test.

The key success metric for our client is `Purchase`.
Therefore, for statistical testing, the focus should be on the `Purchase` metric.

You should answer the following questions in your presentation:

1. How would you define the hypothesis of this A/B test?
2. Can we conclude statistically significant results?
3. Which statistical test did you use, and why ?
4. Based on your answer to Question 2, what would be your recommendation to client?

---

# Dataset Info

**Total Features:** 4

**Total Row:** 40

| Feature | Definition |
| --- | --- |
| impression | Number of ad views |
| click | Number of clicks on the displayed ad |
| purchase | Number of products purchased after clicked ads |
| earning | Earnings from purchased products |

---

# Requirements

```python
matplotlib==3.5.2
numpy==1.21.5
pandas==1.4.3
scipy==1.7.3
statsmodels==0.13.2
```

---

# **Files**

[ab-testing.ipynb](https://github.com/oguzerdo/ab-testing/blob/main/ab-testing.ipynb) - AB Test Project with proportion Z test.

---

# Author

[Oğuz Erdoğan](http://www.oguzerdogan.com)