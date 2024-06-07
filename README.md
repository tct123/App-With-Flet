# App-With-Flet

## Description
The project was developed with the aim of studying and practicing programming in Python, manipulating MySQL and Flet databases to create graphical interfaces. The idea was to create an application that would allow managing the registration of users, customers, products, sales and controlling stock in a simple and efficient way.

The challenge was to develop a project from start to finish, implementing all the essential functionalities for inventory control, while learning to use the mentioned technologies and applying object-oriented programming concepts to guarantee the organization and scalability of the code.

## Functionalities
- User Authentication: The system has a login screen for authentication of administrator users.
- User Registration: Allows users to be created.
- Customer Control: Allows you to register and edit customer information.
- Product Management: Allows you to register, edit and delete products from stock.
- Sales Record: Allows you to record sales, associating the customers and products involved.
- Inventory Control: Keeps product stock updated based on sales made.

## Technologies Used
-Python
- MySQL
- Flet (graphical interface)

## Screens:

Login:

![Login](Screens/Login.PNG)

Home screen:

![Home Screen](Screens/Home.PNG)

Sales:

![Sales](Screens/Sales.PNG)

Products:

![Products](Screens/Products.PNG)

Customers:

![Customers](Screens/Customers.PNG)

User registration:

![User Registration](Screens/Users.PNG)

## To test:
To run the application, make sure you have Python and MySQL installed on your system. Additionally, it is recommended to create a virtual environment to isolate project dependencies.

1. Clone the repository to your local machine:
 - git clone https://github.com/HelioCard/App-With-Flet.git
 - cd App-With-Flet

2. Install project dependencies:
 - pip install -r requirements.txt

3. Access MySQL. Create your database (schema) and run the script from the "database_scripts" folder to create the tables. There are two options:
 - create_tables - structure_only.sql (only creating tables);
 - create_tables - structure_and_some_data.sql (creating tables and inserting some data for testing)

4. Run the main.py file. Enter any text in the "User" and "Password" fields and click "Login" to open the initial database configuration screen. Enter your connection details and click "Save". The following screens only open on the first run, when there has been no configuration yet:

![Database Configuration](Screens/Config_DB.PNG)

5. Once again, enter any text in the "User" and "Password" fields and click "Login" to open the administrator registration screen. Fill in and click "Register":

![Creation of the First Administrator](Screens/Config_Admin.PNG)

6. Login.


The project was developed for educational purposes and to develop skills in Python, MySQL and Flet. Feel free to explore the code and adapt it to your needs. If you have any questions or suggestions, please contact: helio.card@yahoo.com.br