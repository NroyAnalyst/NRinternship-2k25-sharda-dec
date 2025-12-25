Task 7

To create and connect database in python using SQlite there is a inbuilt library known as 'sqlitw3', hence first import sqlite3 library, pandas for showing output in dataframe and matplotlib.pyplot library for charts and graphs.

<img width="889" height="90" alt="image" src="https://github.com/user-attachments/assets/b256b055-13af-4c89-8f42-97b10e51b23b" />

Now, create a database with he name 'sales' usinf sqlite3 and also create table in the database having feature (order_id,product,quantity,price

<img width="882" height="337" alt="image" src="https://github.com/user-attachments/assets/3ef6069c-79b9-46b2-9833-011275ee81a0" />

In next code i put some datas into sales table.

<img width="881" height="360" alt="image" src="https://github.com/user-attachments/assets/a7db9aba-d016-414b-8a8c-42b05ce15e09" />

In this sql query i calculate the sum of total quantity and revenue and group them by product.

<img width="895" height="247" alt="image" src="https://github.com/user-attachments/assets/1d26bd43-64ae-473a-8a0e-d17932f274a3" />

Now, load data which is calculated by above code in pandas dataframe and print dataframe.

<img width="884" height="221" alt="image" src="https://github.com/user-attachments/assets/6472e68a-3225-45b4-bbd5-fb33dbca6d76" />

In next step i create a bar chart using revenue and product.

<img width="894" height="764" alt="image" src="https://github.com/user-attachments/assets/543a8d86-52d7-4e5b-ace8-9c832cb0e185" />

To save this chart i use plt.savefig("sales_cart.png")

<img width="887" height="160" alt="image" src="https://github.com/user-attachments/assets/be52cb49-83bb-4b04-ae8f-3b6d8db3b302" />
