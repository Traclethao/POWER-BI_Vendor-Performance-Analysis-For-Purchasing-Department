# Vendor Performance Analysis For Purchasing Department
Using Power BI to visualize dashboards about the business's purchasing situation. 
## **I. Introduction**

### **1. Situation**

- **AdventureWorks database** of a fictitious bicycle manufacturer - Adventure Works Cycles contains **Manufacturing, Purchasing**. 
- The purchasing department will be responsible for purchasing goods, raw materials, and semi-finished products for production. **Management expects that the goods ordered are sufficient for sales, on time, and at optimal import prices**.
- The dataset includes a **dim table** containing information about product and vendor, including fields of **product** information (ID, name, category, and subcategory) and information related to the **vendor** (ID, name, price, leadtime).

### **2. Business Questions**

- Create an Operation Dashboard for managers that displays vendor order completion rate, on-time delivery rate, vendor leadtime, and total order amount.

### **3. Data Model**

From the company's data dictionary I did data modeling.

![Data model](https://github.com/user-attachments/assets/28ff3b12-6f40-4697-8f0a-afe2bf8582f1) 

## **II. Design Thinking Method**

**Here are the five steps of design thinking:**

### **Step 1 - Empathize**

![Stage 1](https://github.com/user-attachments/assets/c3959d1e-ad52-4d35-80f8-64d5b802e8e9)

### **Step 2 - Define**

![Stage 2](https://github.com/user-attachments/assets/a7b62135-a9ed-4e9a-9bef-04231d98e1d2)

### **Step 3 - Ideate**

![Stage 3](https://github.com/user-attachments/assets/6ffd4240-51d2-4081-8528-5b34d3373f7f)

### **Step 4 - Prototype**

![Stage 4](https://github.com/user-attachments/assets/47106cf4-ee6c-4046-8bf6-5401b40b72d1)

### **Step 5 - Review**

![Stage 5](https://github.com/user-attachments/assets/8904bf3b-4a22-43e0-9ae8-2affdbaf0c0c)

## **III. Visualization & Insights**
### **1. Vendor Performance**

![Spend Vendor](https://github.com/user-attachments/assets/29cb6473-e9aa-489d-bbbb-8bac636e8e37)

Overall, the Vendor Performance Dashboard plays a crucial role in ensuring the efficiency of the supply chain.

1. Evaluate Vendors by order fulfillment rate.
=> At 99%, Dec had the highest %Order_Fulfillment and was 19.12% higher than Jun, which had the lowest %Order_Fulfillment at 83%. 

2. Evaluate Vendors by on-time rate and Average number of days late by month.
=> Most vendors are late. The number of late days is too large, in July it was more than 400 days.

3. Reject rate of each vendor. 
=> Reject rate is not much, acceptable.

### **2. Spend Vendor**

![Spend Vendor](https://github.com/user-attachments/assets/29cb6473-e9aa-489d-bbbb-8bac636e8e37)

The Spend Vendor Dashboard provides insights into spending patterns and identifies areas for cost optimization. By analyzing spending by vendors, managers can identify opportunities to consolidate purchasing, and reduce unnecessary expenses. This helps them to maximize their budget and improve their overall financial performance. 

1. Line chart: Total purchase by month.
   => At $5,696,578, Aug had the highest Total_Purchase and was 5,144.17% higher than Jul, which had the lowest Total_Purchase at $108,627. Aug accounted for 25.69% of Total_Purchase.

2. 100% Stacked bar chart: Total purchase amount and cost type.
   => See what percentage of each vendor's cost is 

3. Treemap: Compare total purchase amount from vendors.
   => From this treemap, we can see the top eleven vendors are the eleven blocks on the left of the treemap. We can also see they account for close to 50% of Total purchase amount.  


## **IV. Recommendations**

- Improve %Ontime: discuss with vendors about delivery time to agree on the time, because most suppliers deliver late. Find out why vendors deliver late, it could be because the lead time is not quite right.

- The company's peak purchasing time is from August to December. August is the most. ⇒ The purchasing department should plan to order a lot during this time to meet the demand.

