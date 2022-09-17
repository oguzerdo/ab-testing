# AB - Testing ANOVA

![projectii](/images/projectII.png)

# **Business Problem**

A fast food chain is planning to add a new product to its menu.

They are undecided about three possible marketing campaigns to promote this new product.

To determine which promotion has the greatest impact on sales, the new product is promoted in several randomly selected convenience stores.

With these promotions in different locations, the weekly sales of the new product are recorded for the first four weeks.

**Evaluate the results of the A/B test and decide which marketing strategy works best.**

---

# Dataset Info

**Total Features:** 7

**Total Row:** 548

| Feature | Definiton |
| --- | --- |
| MarketID | Unique market id |
| MarketSize | Market Size |
| LocationID | Unique store location |
| AgeOfStore | Age of Store |
| Promotion | Type of promotion tested |
| week | One of the four weeks when promotions are managed |
| SalesInThousands | Sales Amount |

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

[ab-testing.ipynb](https://github.com/oguzerdo/ab-testing/blob/main/ab-testing/ab-testing.ipynb) - AB Test Project with proportion Z test.

[ab-testing-anova.ipynb](https://github.com/oguzerdo/ab-testing/blob/main/ab-testing.ipynb) - AB Test Project with ANOVA

---

# Author

[Oğuz Erdoğan](http://www.oguzerdogan.com)