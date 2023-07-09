#Description of the Dataset:
Airbnb, Inc. is an American San Francisco-based company operating an online marketplace for short- and long-term homestays and experiences. The company acts as a broker and charges a commission from each booking.
You will be working with their European Booking Dataset. This is a merged dataset of 9 famous cities in Europe:
Amsterdam, Athens, Barcelona, Berlin, Budapest, Lisbon, Paris, Rome, and Vienna.
The original Dataset was messy and lacked describing appropriate information. But, this one was first cleaned. 

#Variables Names and Descriptions are:
City: Name of the City/
Price: Price of Airbnb/
Day: If it is a weekday or weekend/
Room Type: Type or Airbnb - Entire Apt, Private Room, Shared Room/
Share Room: If the Room in Airbnb is shared by anyone/
Private Room: If the Stay has a Private room available/
Person Capacity: The Person Capacity of Airbnb/
Superhost: If the Airbnb host is Superhost or not/
Multiple Rooms: If the Airbnb has multiple rooms (2-4) rooms/
Business: If the Business has more than 4 offers/
Cleaningness Rating: Cleanness Ratings of the Places/
Guest Satisfaction: Guest Satisfaction Score they left/
Bedrooms: Number of Bedrooms in the facility/
City Center (km): Distance to the center of the City from the staying place/
Metro Distance (km): Distance to the Metro Service from the staying place/
Attraction Index: Attraction Index of the Place/
Normalised Attraction Index: Normalised value of the Attraction Index/
Restraurant Index: Restaurant Index of the Place/
Normalised Restraurant Index: Normalised value of the Restaurant Index/

#Task:

Perform exploratory data analysis using Snowflake SQL and tell a story you'd like to tell with this dataset.
Create a Database in Snowflake named "TOURISM"
Create a Schema under that Database named "EUROPE"
Create a Table under that Database and Schema named "AIRBNB" [Be careful with the Field Names and Field Types]
Create an Appropriate File Format to Bulk insert the CSV file (Airbnb Europe Dataset.csv)
Insert the dataset using the created file format [K]
If you see any error, then work on that. You must try until you see no error.
Proof Check: The number of Records should be 41,714
Perform Descriptive Analysis and Frequency Distribution [Build Charts as well in your result if you find the output important enough]
Check if there is any outlier in the "PRICE" Field; If so, then report the observations and then remove the outliers
Apart from the descriptive analysis, try to Explore which Fields/Variables have a Causal Relationship with "Guest Satisfaction".

Build a Simple Dashboard using Snowflake [Keep one or two filters on top; whatever field you find most important ones to look at]
Write a Short Report based on your findings [Report should be written in Microsoft Word File and the Analyses, Charts should be included in the report; Add a Screenshot of your dashboard as well]

######################### Findings #########################
![Screenshot (30)](https://github.com/PervejHosen/SQL-Projects/assets/117522848/7adab94b-f7a8-4168-9598-d15c940d19f3)

![Screenshot (29)](https://github.com/PervejHosen/SQL-Projects/assets/117522848/f2c96361-6318-4aca-81f4-a9adcf93b05e)

![Screenshot (34)](https://github.com/PervejHosen/SQL-Projects/assets/117522848/d24a85fc-3dd0-4ef4-86bf-297ea414c7e2)

![Screenshot (33)](https://github.com/PervejHosen/SQL-Projects/assets/117522848/e29fe6d7-14ce-4638-a90d-133de3e80a1d)

![Screenshot (32)](https://github.com/PervejHosen/SQL-Projects/assets/117522848/b3fe9394-6173-42d0-bb99-76bd8cf8d5c3)
![Screenshot (35)](https://github.com/PervejHosen/SQL-Projects/assets/117522848/5c414aed-d1b9-47f2-af48-6ede3cb0b7c2)
![Screenshot (36)](https://github.com/PervejHosen/SQL-Projects/assets/117522848/290baf4e-fa50-455b-96e5-6b678dae1ad8)
![Screenshot (37)](https://github.com/PervejHosen/SQL-Projects/assets/117522848/2888c7af-1209-4b56-b5b1-818881811e72)
![Screenshot (38)](https://github.com/PervejHosen/SQL-Projects/assets/117522848/1d6c7ccb-1baf-4ef2-9574-b6a4a34763b9)
![Screenshot (39)](https://github.com/PervejHosen/SQL-Projects/assets/117522848/fd51c014-cebb-4d89-92f9-17534ef8fdaa)





![Total Observation By City](https://github.com/PervejHosen/SQL-Projects/assets/117522848/cb7ab295-c973-4cdd-a907-ad5147655670)

![City Wise Min, Max and Avg Of Price (1)](https://github.com/PervejHosen/SQL-Projects/assets/117522848/6f53b0a9-5883-4ab5-8c40-e321dd371ded)

![Screenshot (22)](https://github.com/PervejHosen/SQL-Projects/assets/117522848/734b3147-1d7d-4e35-bd7e-4627338ddd8d)



