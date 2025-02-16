# [Machine Learning] A/B Testing for Customer Conversion Rates on E-commerce Platforms
## **I. INTRODUCTION**

### 1. **A/B TESTING**
- A/B testing, also known as split testing, refers to a randomized experimentation process wherein two or more versions of a variable (web page, page element, etc.) are shown to different segments of website visitors at the same time to determine which version leaves the maximum impact and drives business metrics.
- In A/B testing, A refers to ‘control’ or the original testing variable. Whereas B refers to ‘variation’ or a new version of the original testing variable.

**Reference**

[A/B Testing Guide](https://vwo.com/ab-testing/)

### 2. **USER PROFILE DEFINITION & PROBLEM STATEMENT**

The Ecommerce business offers a group of whitelist customers a special promotion for the membership subscription, currently they show the screen A to customers, and they found that the conversion rate of users buying the subscription is too low. They suggest changing the content on the banner. The suggestion as below:

**Screen A:** show a discounted price of paid package (99K)

**Screen B:** show a discount amount in price (discount 100K)

*Notes: the original price of the subscription package is 199K, and with the promotion, they can buy with 99K*

## **II. DATA DICTIONARY**

**Dataset:** abtesting

| Field | Type of Column | Information |
| --- | --- | --- |
| **customer_id** | Dimension | unique id of each users |
| **group** | Dimension | group1: show screen A, group2: show screen B |
| **is_buy** | Measure | whether that user buy the subscription or not |
