# 6 - Add UI to the Application

To display and test the content we created for the customer loyalty program, we need to create an SAP Fiori elements UI.


## Add UI 

1. Go to back to the Storyboard and add a UI application. **TODO: FIX SCREENSHOT - PROJECT NAME**

![](./Images/6_Screenshot_1.png)

2. We will start with the user interface for the **Purchases** data entity. 
Set the **Display name** to **Purchases** and the **Description** to **Manage Purchases**, and then click **Next**.

![](./Images/6_Screenshot_2.png)

3. We are using the browser, so we will select **Template-Based Responsive Application** as the UI Application type, and click **Next**.

![](./Images/6_Screenshot_3.png)

4. Select **List Report Page** as the UI application template, and click **Next**. 

![](./Images/6_Screenshot_4.png)

5. Select **Purchases** as the **Main entity**, and click **Finish**. The page will be created now.

![](./Images/6_Screenshot_5.png)

It might take a few moments for the UI to be created because the dependencies need to be installed. 

6. Repeat steps 2 through 5 to create additional UI apps for the **Customers** and the **Redemptions** entities.
**Customer**:
* Display name: **Customers** <br/>
* Description: **Manage Customers**
* UI Application type: **Template-Based Responsive Application** <br/>
* UI Application Template: **List Report Page** <br/>
* Main Entity: **Customers** <br/>
**Redemptions**:
* Display name: **Redemptions** <br/>
* Description: **Manage Redemptions** <br/>
* UI Application type: **Template-Based Responsive Application** <br/>
* UI Application Template: **List Report Page** <br/>
* Main Entity: **Redemptions** <br/>

And that's it! You've created an application.

7. To preview your application, once the files have been generated, go to the upper-right corner, and click ![preview](./Images/6_playgreen.png) (Run and Debug).

![](./Images/6_Screenshot_6.png)

The application's preview is displayed.

![](./Images/6_Screenshot_7.png)

8. Click **Go**.

![](./Images/6_Screenshot_8.png)

The customer information is displayed.

![](./Images/6_Screenshot_9.png)

9. From the dropdown list at the top of the page, select **Home** to go back and preview the other applications.

![](./Images/6_Screenshot_10.png)