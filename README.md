*#Data Science Assignment: eCommerce Transactions Dataset*#

*Overview:*
You are provided with an eCommerce Transactions dataset consisting of three files:
Customers.csv, Products.csv, and Transactions.csv. Your task is to perform
exploratory data analysis (EDA), build predictive models, and derive actionable insights. This
assignment will test your data analysis, machine learning, and business insight generation skills.
Customers.csv:
https://drive.google.com/file/d/1bu_--mo79VdUG9oin4ybfFGRUSXAe-WE/view?usp=sharing
Products.csv :
https://drive.google.com/file/d/1IKuDizVapw-hyktwfpoAoaGtHtTNHfd0/view?usp=sharing
Transactions.csv :
https://drive.google.com/file/d/1saEqdbBB-vuk2hxoAf4TzDEsykdKlzbF/view?usp=sharing

Files Description:
1. Customers.csv
○ CustomerID: Unique identifier for each customer.
○ CustomerName: Name of the customer.
○ Region: Continent where the customer resides.
○ SignupDate: Date when the customer signed up.
2. Products.csv
○ ProductID: Unique identifier for each product.
○ ProductName: Name of the product.
○ Category: Product category.
○ Price: Product price in USD.
3. Transactions.csv
○ TransactionID: Unique identifier for each transaction.
○ CustomerID: ID of the customer who made the transaction.
○ ProductID: ID of the product sold.
○ TransactionDate: Date of the transaction.

○ Quantity: Quantity of the product purchased.
○ TotalValue: Total value of the transaction.
○ Price: Price of the product sold.

**Assignment Tasks:**
*Task 1:* Exploratory Data Analysis (EDA) and Business Insights
![image](https://github.com/user-attachments/assets/f230951b-f5b8-4cc6-914f-950fd85aca53)

![image](https://github.com/user-attachments/assets/8726d9e6-4eca-4c9c-8008-4d886c06df70)

![image](https://github.com/user-attachments/assets/cc8b44d5-d8cc-4bc0-a113-0844bd088c94)

![image](https://github.com/user-attachments/assets/98aacae0-d620-4f1b-84d5-66140f8aa78f)

![image](https://github.com/user-attachments/assets/ba036f86-a1bf-4b73-8bc2-085078922866)


Task 2: Lookalike Model
Build a Lookalike Model that takes a user's information as input and recommends 3 similar
customers based on their profile and transaction history. The model should:

![image](https://github.com/user-attachments/assets/85059f0d-6501-4235-9997-a9af6a2ea943)

![image](https://github.com/user-attachments/assets/94de4352-a70b-4d96-a532-68083c228975)


Task 3: Customer Segmentation / Clustering
Perform customer segmentation using clustering techniques. Use both profile information
(from Customers.csv) and transaction information (from Transactions.csv).
● You have the flexibility to choose any clustering algorithm and any number of clusters in
between(2 and 10)
● Calculate clustering metrics, including the DB Index(Evaluation will be done on this).
● Visualise your clusters using relevant plots.
Deliverables:
● A report on your clustering results, including:
○ The number of clusters formed.
○ DB Index value.
○ Other relevant clustering metrics.
● A Jupyter Notebook/Python script containing your clustering code.
Evaluation Criteria:
● Clustering logic and metrics.
● Visual representation of clusters.
![image](https://github.com/user-attachments/assets/dd30285d-db0f-41ee-8ffc-a7f635bb8a06)
