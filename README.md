# Creating a Dashboard of Seattle Weather with Excel
 For this project I used Excel to make a dashboard for data on Seattle Weather. The dataset looks like this:
 
![Screenshot 2025-04-18 204019](https://github.com/user-attachments/assets/248b3d9c-8e58-44d6-ab42-c57f66418118)

The dataset was downloaded from Kaggle and can be found [here](https://www.kaggle.com/datasets/mahdiehhajian/seattle-weather). Each row of the dataset contains data on one day, with 25552 days in total ranging from 1948 to 2017. I made a couple changes to the original dataset. I added the "month" column so that I could easily create the pivot tables that aggregate the data based on month. I also renamed some of the columns to make their meaning more obvious. 


In order to make the line graphs in the dashboard I needed to aggregate the data through multiple pivot tables. The first one shows how the average temperature in Seattle changes by month:

![Screenshot 2025-04-19 085008](https://github.com/user-attachments/assets/49a6472a-7880-4c4a-b01d-3341db815ac0)


The next pivot table shows how the precipitation varies by month:

![Screenshot 2025-04-19 085021](https://github.com/user-attachments/assets/221b7e07-9d91-48ce-b6f6-047243fc38c0)


The final pivot table shows how the average temperature per year has changed over time:

![Screenshot 2025-04-19 085050](https://github.com/user-attachments/assets/ee8b3d56-c91d-403d-8c27-8a0d644e5c5d)


I then created pivot charts using the pivot tables which completed most of the dashboard.

![Screenshot 2025-04-19 095852](https://github.com/user-attachments/assets/61a61301-72d9-452b-8d77-5582693c0519)


You can see I added a couple of interesting stats in the bottom right corner. Here, the record high temperature and and precipitation as well as record low temperature are displayed. 






