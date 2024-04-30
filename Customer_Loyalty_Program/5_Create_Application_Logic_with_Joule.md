# 5 - Create Application Logic with Joule  

We already have created the entities, services, and sample data with Joule. Now we want to create some logic for our app. We would like to calculate the bonus points automatically when a customer makes a purchase. Additionally, we want to provide logic for customers to redeem these bonus points.


## Application Logic

1. Go to **Storyboard**. Click on one of the entities under **Services** and **Open in Graphical Modeler**

![](./Images/5_Screenshot_1.png)


2. Select **Purchases** entity by clicking on the title. Then, click on **Add Logic**

![](./Images/5_Screenshot_2.png)

3. Leave the default value and click on **Add**

![](./Images/5_Screenshot_3.png)

4. Under the **Standard Event** select **Create**. That means this logic will be automatically executed if a new purchase is done.
 Afterwards, go to **Application Logic** under **Open Code Editor**. This will open Joule again to create the logic for us.

![](./Images/5_Screenshot_4.png)

5. Use the following prompt in Joule to create application logic:

```code
Reward points of each purchase will be the one tenth of the purchase value. Each purchase value will be added to the total purchase value of the related customer. Each reward points will be added to the total reward points of the related customer.
```

![](./Images/5_Screenshot_5.png)

Joule should create the logic to:
 - check if the customer exists
 - calculate the rewardPoints from the purchase value
 - update the total purchase value and the total reward points in the customers entity

6. Accept the code created by Joule. 

![](./Images/5_Screenshot_6.png)


> **Note:**
> Joule typically generates different code each time for the same prompt. So if yours differs, it is completely fine as long as it does the same job. If there are no obvious errors, just keep working on the exercise. If you are unsure, you can have Joule try again by clicking **Regenerate**.  

7. Now let's look at the Redemptions. Go back to **service.cds** tab. Select **Redemptions** entity by clicking on the title. Then, click on **Add Logic**.

![](./Images/5_Screenshot_7.png)

8. Click on **Add**

![](./Images/5_Screenshot_8.png)

9. Select **Create**. Then, choose **Application Logic** under **Open Code Editor**.

![](./Images/5_Screenshot_9.png)

10. Use the following Prompt in Joule to create a backend logic:

```code
Deduct the redemption amount from the customer's total reward points and add that to his total redeemed points.
```

![](./Images/5_Screenshot_10.png)

11. Accept the code created by Joule. 

![](./Images/5_Screenshot_11.png)

Have a closer look at the generated code. It even includes some checks on whether the customer has enough points for the redemption.


> **Note:**
> Joule might generate different codes for the same prompt. So, you might have a different code for the logic which is completely fine if it does the same job. You can ignore this and keep working on the exercise. 

## [Next Step: Add UI to the Application](./6_Add_UI_to_Application.md) >
