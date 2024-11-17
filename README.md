# Adventure Works Analysis
Using Power BI to visualize dashboards about the business's purchasing situation. 
## **I. Introduction**

### **1. Introduction to Dataset**

- AdventureWorks database of a fictitious bicycle manufacturer - Adventure Works Cycles contains Manufacturing, Purchasing. 
- The purchasing department will be responsible for purchasing goods, raw materials, and semi-finished products for production. Management expects that the goods ordered are sufficient for sales, on time, and at optimal import prices.
- The dataset includes a **dim table** containing information about product and vendor, including fields of **product** information (ID, name, category, and subcategory) and information related to the **vendor** (ID, name, price, leadtime).

### **2. Data Dictionary**

![Data Dictionary](https://github.com/user-attachments/assets/4a8a0ae1-5740-4159-bf2c-fa662abe6950)

### **3. Business Questions**

- Create an Operation Dashboard for managers that displays vendor order completion rate, on-time delivery rate, vendor leadtime, and total order amount.

### **4. Data Model**

![Data model](https://github.com/user-attachments/assets/28ff3b12-6f40-4697-8f0a-afe2bf8582f1) 

## **II. Design Thinking Method**

**Here are the five steps of design thinking:**

### **Step 1 - Empathize**

![Stage 1](https://github.com/user-attachments/assets/7b87c808-96a9-4a68-8101-ece826a35439)

### **Step 2 - Define**

![Stage 2](https://github.com/user-attachments/assets/d4f17f24-d33b-4cb6-ac8c-95b3fcfa4127)

### **Step 3 - Ideate**

![Stage 3](https://github.com/user-attachments/assets/f1b078e2-57c3-42cb-9955-06aabb522564)

### **Step 4 - Prototype**

![Stage 4](https://github.com/user-attachments/assets/56f0ee0b-5714-4965-b2de-7167ac4ab825)

### **Step 5 - Review**

![Stage 5](https://github.com/user-attachments/assets/2bb50d6d-b39d-42b7-be45-2c1c37045f90)

## **III. Visualization**
### **1. Vendor overview**

![Vendor detail](https://github.com/user-attachments/assets/3235fafb-230a-48d1-a767-41732ea2b082)

### **2. Vendor detail**

![Vendor overview](https://github.com/user-attachments/assets/1a01a8a7-14c1-4279-92a3-bbeb4b215923)

## **IV. Insights**

- August accounted for 24.92% of Total_StockedQty.
- Total TotalCost_Product was higher for Salable ($5,246,055) than Not Salable (3,301,786.69).
- Average TotalCost_Product was higher for Salable (582,894.97) than Not Salable (330,178.67).
- At $1,610,965, Superior Bicycles had the highest Total_Purchase and was 90.33% higher than Jackson Authority, which had the lowest Total_Purchase at $846,400.
- Superior Bicycles accounted for 28.86% of Total_Purchase.
- Across all 5 Vendors, Total_Purchase ranged from $846,400 to $1,610,965.

## **V. Recommendations**

- Improve %Ontime: discuss with suppliers about delivery time to agree on the time, because most suppliers deliver late. See the Average Days Late by Subcategory chart to recalculate the leadtim of each product.

- The company's busiest time is from August to December. August is the busiest. ⇒ the purchasing department should plan to order a lot during this time to meet the demand.

