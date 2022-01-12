### Overview

This is a side data analyst & BI project I'm currently doing for a local café shop in my neighborhood. For business privacy concern, the café name is changed to CafeABC, and all the wholesale suppliers are renamed to Produce1, Produce2, Pastry1, Pastry 2, and etc.. 

The goal of this project is to answer the stakeholders' questions, and the aim of this data project is to figure out the relationship, trend and patterns of its products and net sales between December 2020 to October 2021. This will help the stakeholders to make informed decision on which products to phase out, increase, and combined together to make attractive food/drink combo. Hence, we'll only be using product costs and product net sale data from TouchBistro app and internal data of produce purchase history. 

I will also be presenting my findings via both Google sheet and Tableau, the links will be updated here as they become available. 



### Datasets

#### Provided Data
The set of data we collected are from December 2020 to October 2021, total of 11 months. 

* [`cafeABC-sales-by-menu-item-2020-12-01-2021-10-31.csv`](./datasets/cafeABC-sales-by-menu-item-2020-12-01-2021-10-31.csv): Sales Data by Menu Item between DEC2020 and OCT2021
* [`cafeABC_produce_cost_2020-2021.csv`](./datasets/cafeABC_produce_cost_2020-2021.csv): Produce Purchase History & Cost between DEC2020 and OCT2021, with wholesale suppliers renamed to protect business privacy
* [`cafeABC_discount-summary-2020-12-01-2021-10-31.csv`](./datasets/cafeABC_discount-summary-2020-12-01-2021-10-31.csv): Discount Summary of Customer Purchase between DEC2020 and OCT2021



### Present Findings

#### Google Sheet
Google sheet contains pivot tables tabs, and a functional dashboard with metrics
Link:

#### Tableau
Tableau public data visualization 
Link: 



### Summary



### Changelog
12/2021
- Gathered all produce purchase receipts from the shop and manually punched in the info in Google Sheet.

1/7/2022
- Data are cleaned via Google Sheet, and then Python.
- Google Sheet pivot tables are ready to present.

1/9/2022
- Gathered all questions from 3 stakeholders.

1/11/2022
- Currently in the process of getting full customer purchase history in .sql from TouchBistro, because the backend of TouchBistro for admin does not provide such data.
- Currently in the process of building data visualization dashboard in Google Sheet and Tableau.