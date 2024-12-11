![Screenshot (14)](https://github.com/user-attachments/assets/25cbfd2b-1bf0-44ee-9bce-724bf6f7fd79)

# PENNYPAL
## A Banking Management System




## I. Project Overview💡

📍Pennypal is a Python-based banking management system designed to simplify account creation, management, and viewing account details. The system provides a user-friendly graphical interface using the Tkinter library, enabling seamless user interactions. Its core functionalities include:📍
1. Creating new accounts with essential details such as name, account number, balance, address, and contact number.
2. Viewing detailed account information by entering an account number.
3. Managing account data securely using a MySQL database.

- - 
![1_tugtGW5WpXKdpuaPvM2SHg](https://github.com/user-attachments/assets/059e01ee-e41f-4d70-b084-f726e2ac557c)

📍This project contributes to the advancement of Sustainable Development Goal (SDG) 8: Decent Work and Economic Growth, by promoting inclusive financial systems and providing tools to enhance personal financial management.📍

## II. Application of Python Concepts and Libraries📝

1. Tkinter:🔖

- Used to create a responsive and visually appealing graphical user interface (GUI).
- Frames, labels, entry fields, and buttons are employed for interaction.
- Text widgets and message boxes handle multiline text and error alerts

2. MySQL:🔖

- Facilitates secure storage and retrieval of account data.
- Queries for inserting and fetching data are seamlessly integrated with Python using mysql.connector.
- The database schema ensures the data integrity of user information.

3. OOP Principles:🔖

- Classes and methods encapsulate functionalities for modularity and reusability.
- Window-specific logic (e.g., account creation and information display) is implemented in dedicated classes.

4. Error Handling:🔖

- Extensive use of try-except blocks for managing database errors and invalid user inputs.

## III. Integration of SDG 8🔍
![1_tugtGW5WpXKdpuaPvM2SHg](https://github.com/user-attachments/assets/059e01ee-e41f-4d70-b084-f726e2ac557c)

📍SDG 8 emphasizes the need for accessible and efficient financial tools to foster economic productivity. Pennypal directly supports this goal by offering a streamlined, accessible banking system for users. It simplifies account management, reduces financial errors, and empowers individuals to monitor their financial transactions, supporting inclusivity and financial growth📍
## Running the Program🏃🏼‍♂️

1. Required Libraries: Install the necessary Python libraries using pip:
🏷 pip install mysql-connector-python 

2. Database Setup
🏷 Open MySQL shell or GUI client.

🏷 Create a database and accounts table by executing the following script:

 CREATE DATABASE IF NOT EXISTS bank_db;  
USE bank_db;  
CREATE TABLE IF NOT EXISTS accounts (  
    id INT AUTO_INCREMENT PRIMARY KEY,  
    name VARCHAR(255) NOT NULL,  
    account_number VARCHAR(20) UNIQUE NOT NULL,  
    account_money DECIMAL(10, 2) NOT NULL,  
    contact_number VARCHAR(15) NOT NULL,  
    address TEXT NOT NULL  
);  

4. Running the program.
🏷 Clone this repository 

 git clone https://github.com/ElaineRoxas/PENNYPAL/tree/main/Final%20Project%20in%20ACP%20%26%20DBMS.git
cd.PENNYPAL

5. Run the main Python file
- python main.py  

6. Follow the on-screen instructions to create and view account details. 
![Screenshot (15)](https://github.com/user-attachments/assets/239a1a38-f03f-4353-aa77-1a3c46b60b24)

## Created by💅🏼

- Elaine Joy Roxas
- IT-2104

