# Predicting-Catalog-Demand

## The Business Problem
You recently started working for a company that manufactures and sells high-end home goods. Last year the company sent out its first print catalog, and is preparing to send out this year's catalog in the coming months. The company has 250 new customers from their mailing list that they want to send the catalog to.

Your manager has been asked to determine how much profit the company can expect from sending a catalog to these customers. You, the business analyst, are assigned to help your manager run the numbers. While fairly knowledgeable about data analysis, your manager is not very familiar with predictive models.

You’ve been asked to predict the expected profit from these 250 new customers. Management does not want to send the catalog out to these new customers unless the expected profit contribution exceeds $10,000.

## Details
* The costs of printing and distributing is $6.50 per catalog.
* The average gross margin (price - cost) on all products sold through the catalog is 50%.
* Make sure to multiply your revenue by the gross margin first before you subtract out the $6.50 cost when calculating your profit.

**Step 1: Business and Data Understanding**

**Step 2: Analysis, Modeling, and Validation**

Build a linear regression model, then use it to predict sales for the 250 customers. <br>

Once we have our linear regression equation, we should use our linear regression equation to predict sales for the individual people in our mailing list.

**Step 3: Writeup**

Once we have our predicted or expected profit, write a brief report with the recommendation to whether the company should send the catalog or not.

**Hint:** We want to calculate the expected revenue from these 250 people in order to get expected profit. This means we need to multiply the probability that a person will buy our catalog as well. For example, if a customer were to buy from us, we predict this customer will buy $450 worth of products. At a 30% chance that this person will actually buy from us, we can expect revenue to be $450 x 30% = $135.

## Data
* *p1-customers.xlsx* - This dataset includes the following information on about 2,300 customers. Important: You should build your model on this dataset and not p1-mailinglist.xlsx.

* *p1-mailinglist.xlsx* - This dataset is the 250 customers that you need to predict sales. This is the list of customers that the company would send a catalog to. Use this dataset to estimate how much revenue the company can expect if they send out the catalog. It includes all of the fields from P1_Customers.xlsx except for Responded_to_Last_Catalog so this variable cannot be used in the linear regression model since it could not be applied to the mailing list data set. It also includes two additional variables.

* *Score_No:* The probability that the customer WILL NOT respond to the catalog and not make a purchase.
* *Score_Yes:* The probability that the customer WILL respond to the catalog and make a purchase.

