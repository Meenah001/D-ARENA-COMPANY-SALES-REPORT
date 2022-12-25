# SALES-REPORT

---

# INTRODUCTION

The aim of this project was to clean the badly structured data, also to analyze and visualize using simple visuals for easy interpretation of what sales looks like in D’arena company 

---

# DATA CLEANING AND TRANSFORMATION

The data was imported to excel and then loaded to power query for cleaning and transformation. Below shows the steps taken to clean the data;


![3716B6BD-CCC3-4FC5-A281-0C5288B638EB](https://user-images.githubusercontent.com/97677904/209458714-713931b3-1b2a-4157-9e60-a3d7fcc3c4e2.jpeg)

The above picture shows the raw data imported to excel workbook for cleaning

---

![39A78AEE-3C72-4DC1-B9F5-CA66DBFE14AE](https://user-images.githubusercontent.com/97677904/209458782-8f68bf54-5343-44a9-8a51-1690997287ec.jpeg)

Here, the data was converted to table for convenient cleaning

---

![Transpose](https://user-images.githubusercontent.com/97677904/209468184-b4aebd36-8a67-49ac-8b6b-31c4141c0ff2.png)

The data was loaded to power query, It was then transposed. This was done for easy access to promote the column headers

---

![Header not corrected ](https://user-images.githubusercontent.com/97677904/209468256-06faf2c2-66c8-442f-9864-0c86c33f7e0c.png)

The first rows from the previous image were used as column headers, but not all the headers are correct. Therefore, further cleaning is needed

---

![Unpivoted](https://user-images.githubusercontent.com/97677904/209468404-3d93d2db-d47a-41ed-88be-bf821ef18597.png)

In order to get the correct column headers, the 'segment' and 'ship mode' column was selected and the rest of the column were "Unpivoted". This gave us the last two column shown in the above image i.e (the Attribute and Value) column

---

![Renamed column](https://user-images.githubusercontent.com/97677904/209468515-a155426f-87dd-4f8d-a516-7f26c1a28f0c.png)

The last two column shown in the previous image were renamed to "Order ID" and " Total Sales" respectively

---

![Split column](https://user-images.githubusercontent.com/97677904/209468592-4199dbef-ae1e-4289-8308-d9dd85925a73.png)

The initial Order ID was split into three different column. These are "Country", "Year" and "Order ID"

---

![PNG image](https://user-images.githubusercontent.com/97677904/209468652-5d28b8b3-2bc6-4dfd-9e48-8ca2709a21dc.png)

Now, the data is cleaned and set to be analyzed







