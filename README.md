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

![Vendor Performance](https://github.com/user-attachments/assets/8101e0f4-9d45-411e-a51a-b56936d993f5)



### **2. Spend Vendor**

![Spend Vendor](https://github.com/user-attachments/assets/0154923c-8ab6-4dbc-84cd-49a09b232f97)


## **IV. Recommendations**

- Improve %Ontime: discuss with suppliers about delivery time to agree on the time, because most suppliers deliver late. See the Average Days Late by Subcategory chart to recalculate the leadtim of each product.

- The company's busiest time is from August to December. August is the busiest. ⇒ the purchasing department should plan to order a lot during this time to meet the demand.

