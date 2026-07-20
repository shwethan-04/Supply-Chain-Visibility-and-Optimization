**Milestone 1 – Data Modelling:**

**Supply Chain Visibility & Optimization**

This milestone focuses on building a strong data foundation for the Supply Chain Visibility & Optimization project by importing, cleaning, transforming, and modelling the supply chain dataset using Microsoft Power BI.

**Objective:**

- Import the supply chain dataset into Power BI.
- Clean and transform data using Power Query Editor.
- Handle missing values and duplicate records.
- Correct data types and organize required columns.
- Create Fact and Dimension tables.
- Design a Star Schema data model.
- Establish appropriate table relationships.
- Prepare the data model for further supply chain analytics.

**Dataset Source:**

Dataset: DataCo Smart Supply Chain Dataset
Source: Kaggle

The dataset contains information related to customers, products, orders, shipping, departments, categories, and geographical locations.

**Data Cleaning & Transformation:**

The following operations were performed using Power Query Editor:

- Removed unnecessary columns and duplicate records.
- Selected relevant columns for analysis.
- Created Fact and Dimension tables.
- Created unique identifiers using Index Columns.
- Merged tables using Left Outer Joins.
- Created a Date Dimension using DAX.
- Created calculated date columns for Year, Month, Quarter, Week, and Day.

**Data Model Overview:**

A structured data model was created consisting of:

- "Fact_table"
- "Dim_Customer"
- "Dim_Product"
- "Dim_Category"
- "Dim_Shipping"
- "Dim_Location"
- "Dim_Department"
- "Dim_Date"

Appropriate One-to-Many relationships were established between the Fact and Dimension tables to support efficient business analysis.

**Tools Used:**

- Microsoft Power BI Desktop
- Power Query Editor
- DAX
- GitHub

**Project Structure:**

Milestone1/
├── SupplyChain_Milestone1.pbix
├── data/
│   └── SupplyChain.csv
├── screenshots/
│   └── Data_model.png
└── README.md

**Outcome:**

Successfully completed data preprocessing and developed a structured data model that provides a strong foundation for upcoming inventory, delivery, supplier, and transportation analytics modules.

**Author:**

Anumalla Shwethan Kumar
