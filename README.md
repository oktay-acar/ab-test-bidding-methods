# Comparison of Conversion of Bidding Methods with A/B Test

**Business Problem**

**Facebook** recently introduced a new bidding type, **'average bidding'**, as an alternative to the existing **'maximumbidding'** type of bidding.

One of our customers website decided to test this new feature and wants to do an **A/B test to see if average bidding brings more conversions than maximum bidding**.

A/B testing has been going on for 1 month and website now expects you to analyze the results of this A/B test. The ultimate measure of success for the website is **'Purchase'**. Therefore, the focus should be on the **'Purchase'** metric for statistical testing.

**Dataset Story**

In this dataset, which includes the website information of a company, there is information such as the number of advertisements that users see and click, as well as earnings information from here. There are two separate data sets, the Control and Test group. These datasets are in separate sheets of the **ab_testing.xlsx** excel. **Maximum Bidding** was applied to the control group and **Average Bidding** was applied to the test group.

**Variables**
- **impression:** Number of ad views
- **Click:** Number of clicks on the displayed ad
- **Purchase:** The number of products purchased after the ads clicked
- **Earning:** Earnings after purchased products

---

## Requirements
~~~python
pandas==1.5.1
scipy==1.11.4
~~~

---

## Author
[Oktay Acar](https://github.com/oktay-acar)