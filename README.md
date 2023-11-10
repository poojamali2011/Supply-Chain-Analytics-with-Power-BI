# Supply-Chain-Analytics-with-Power-BI
This analysis is performed on the dataset provided by codebasics as part of their data analytics resume challenge. The task was to generate insights to solve a supply chain issue for an FMCG manufacturer which is operational in three cities Surat, Ahmedabad, and Vadodra.

A few key customers did not extend the annual contract due to service issues and management wants to fix this.

Three measures ‘on-time delivery (OT) %’, ‘In-full delivery (IF) %’, and ‘OnTime in full (OTIF) %’ of the customer orders are measured against the target service level set for these customers. An order is On Time only when all the line items inside the order are delivered on time. An order is In Full only when all the line items inside the order are delivered In Full. Similarly, an order is On Time and In Full when all the line items inside the order are delivered In Full and ON Time.

There are two more measures ‘Line Fill Rate (LIFR)’ and ‘Volume Fill Rate(VOFR)’. Line Fill Rate measures how many lines they shipped out of the total lines ordered. Volume fill rate measures the total quantity they are able to ship for a customer per order or for a given period of time.

Line fill rate= Number of lines where order is filled/ Total number of lines
Volume fill rate = volume shipped complete / total ordered volume


**Dataset**

Before going into the analysis, let's look at all the tables used in this project. The six tables used in this project are:

dim_customers: This table contains all the information about customers

dim_date: Contains the dates at daily, monthly levels, and week numbers of the year

dim_products: Contains all the information about the products

dim_order_lines: Contains information about orders and each item inside the orders.

dim_orders_aggregate: Contains information about OnTime, InFull and OnTime In full information aggregated at the order level per customer

dim_targets_orders: This table contains all target data at the customer level
