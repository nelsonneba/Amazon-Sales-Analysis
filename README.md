# Amazon Sales Analysis

## Introduction
The "Amazon Sales Analysis" project is designed to explore and interpret sales data from Amazon using Python. This analysis aims to uncover key sales patterns and trends by leveraging various data manipulation and visualization techniques. To achieve this, the project utilizes powerful Python libraries such as NumPy, Pandas, Matplotlib, and Seaborn for data handling and graphical representation.

## Data Loading and Inspection
The initial phase of the project involves importing sales data from a CSV file using Pandas. The dataset consists of **128,976 entries** across **21 columns**, containing crucial information such as **Order ID, Date, Status, Sales Channel, Quantity, and Amount**. To gain an understanding of the dataset structure, exploratory functions like `head()`, `info()`, and `shape` are employed for an overview of the data.

## Data Cleaning
The dataset undergoes cleaning processes to enhance its usability:
- **Dropping Unrelated or Blank Columns:** 'New' and 'PendingS' are removed.
- **Handling Null Values:** Rows with missing values are either dropped or filled with appropriate data.
- **Adjusting Data Types:** Ensuring consistency, converting columns like 'Date' to `datetime` objects for better analysis.

## Exploratory Data Analysis (EDA)
### 1. Size Analysis
- Count plots reveal that **M-Size is the most popular** among buyers.

### 2. Grouping by Size
- Grouping the data by size confirms that **M-Size products dominate sales**.

### 3. Courier Status and Order Status
- Count plots indicate that the **majority of orders are shipped through couriers**.

### 4. Category Distribution
- A histogram visualizes the distribution of purchases across different product categories, highlighting that **T-shirts are the most frequently bought items**.

### 5. B2B Analysis
- A **pie chart** showcases the distribution of **Business-to-Business (B2B) and retailer buyers**, indicating that **99.3% of buyers are retailers**.

### 6. Fulfilment Analysis
- Another **pie chart** illustrates the **distribution of fulfilment methods**, with **Amazon being the primary fulfilment service**.

### 7. Scatter Plot and State-wise Distribution
- **Scatter plots** explore relationships between **product categories and sizes**.
- **State-wise distribution plots** provide insights into the **geographical concentration of buyers**, with **Maharashtra having the highest number of customers**.

## Conclusion
The **Amazon Sales Analysis** project provides valuable insights into **customer preferences, popular product categories, and geographic distribution**. This information can be leveraged by the business to:
- Make **informed decisions**
- Optimize **inventory management**
- Enhance **customer satisfaction**
