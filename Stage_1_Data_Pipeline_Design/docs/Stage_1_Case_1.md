# Case 1: Data Pipeline Design

## Scenario

There are **3 locations** involved:

- **Location 1**: IT Operations Center and Database Processing
- **Location 2**: Data and Analytics Operations Center
- **Location 3**: Business Operations Center

### Description

A new client has just signed a contract. We will process their information, and they have tasked us with performing the entire analytics process to provide valuable business insights.

Due to process restrictions, the analytics team cannot directly access **Location 1**. For each client, a data pipeline is defined to replicate their information to **Location 2**. For this client, the process must be a **batch process** that runs in the early morning hours every day.

- **17 tables** are defined for processing:
  - **1 transactional table** that records **800,000 to 1 million records** daily
  - **16 other tables** that record no more than **1,000 daily records**

### Task

You have just joined the company as the engineer responsible for designing and implementing a **data pipeline** to automate the **ETL and/or ELT** process, allowing the analytics team to perform their tasks (data exploration, identifying insights, data modeling, dashboard generation, decision support, etc.).

### Specific Requirements:

1. **Data Transfer:**

   - The data is located in **Location 1** and must be transferred to **Location 2** for the analytics team to use.

2. **API Restrictions:**

   - The **Location 1 team** has only enabled a **URL (API)** with a single method and structure. You can only modify the table name (`Table`), date (`DD/MM/YYYY`), and time (`HH/MM/SSSS`). Each API call can retrieve a maximum of **5,000 records**.

3. **Data Security:**

   - The data transferred to **Location 2** must be **secured** to avoid corruption.

4. **Analytics Team Workflow:**

   - The analytics team works from their terminals (laptops) and can access the data in **Location 2** by either:
     - Downloading all or part of the data
     - Building scripts (e.g., in Python) and uploading them to the infrastructure at **Location 2** after local testing.

5. **Tools for Data Visualization:**
   - The analytics team can use **Tableau**, **PowerBI**, a **native cloud tool**, or develop a **web platform** to visualize the data (dashboards).

---

## Solution

### 1. Data Pipeline Architecture (Reference)

- Design a graphical representation of the **data pipeline architecture** for the analytics team to perform their tasks.

### Considerations:

1. Assume you are working with a cloud environment (preferably **AWS**).
2. Specify your assumptions.

---

## Questions

1. **What type of file would you use in the Data Pipeline process? Why?**
2. **Would you use a database?**  
   a. If your answer is **No**, why?  
   b. If your answer is **Yes**, indicate which one: **SQL** or **NoSQL**. Why?
3. **What dashboard tool would you suggest to the Analytics team? Why?**
