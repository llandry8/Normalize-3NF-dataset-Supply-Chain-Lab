ER Diagram and SQL Code for Normalizing Supply Chain Data to 3NF

This lab helped me deeply understand the concept of normalizing data into 3NF. I went through multiple redos of the ER diagram to help me understand the concept to identify and eliminate redundancy (repeated/duplicated data), particularly in the Order, Supplier, and Product attributes. The first one I did, I still couldn't understand the concept but I thought the Order was the duplicated data. I did another diagram which helped me grasp the concept. After I completed that chart, I created SQL code to normalize the supply chain dataset, splitting it into separate tables (Orders, Products, Suppliers) to eliminate duplicate data.

Key Takeaways:

Efficiency: Normalizing the data reduced redundancy, improving database processing speed and storage usage.
Ease of Updates: Information can now be updated in one place without worrying about conflicting data.
Consistency: Data consistency is achieved by storing each piece of information only once, eliminating conflicting copies.

This lab reinforced the importance of database normalization for optimizing data management and the value of closely analyzing the small details. 
