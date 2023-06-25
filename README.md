# final-Capstone

# Inventory OOP project
___

This project was created as an introduction to working with classes and works with the .txt file 'inventory.txt",
The python file and the text file both work together to simulate a business operating in numerous different countries
with a database of different types of shoes, using the program the user is able to display and call upon different 
types of information such as searching for a specific shoe type, view all, viewing the values of each item
and even updating the database using the re_stock function to ammend the quantities of shoes listed in the txt file.

# Installation section
___

To install this program, download both the inventory.py and inventory.txt files and proceed to drag and drop them
into the same folder, once you have done this you can run the .py file using any code editor. press f5 to run the
program and once you are presented with the menu, first select option 1 to read from the text file. This will
intialise the database and then you can proceed to work with the file. Make sure python is installed on your computer
if you are using VScode install Python and Pylance extensions.

# Using inventory.py
___

# Read shoes data
___

![image2](https://user-images.githubusercontent.com/112674211/211157926-ec049538-1b19-442e-84c7-b9f42cb2a647.png)

This function opens the file, inventory.txt, and reads the data, it then creates an object with this data, and appends the object into a list. Each line in the text file represents a different object ( or product).
___

# Capture shoes
___

![image3](https://user-images.githubusercontent.com/112674211/211157927-91ac5bdc-8655-4790-8820-2071d860a27c.png)

This function allows the user to input data to create a new object that can be appended to the shoes list.

![image4](https://user-images.githubusercontent.com/112674211/211157930-365ed9c8-5afe-477a-99d2-cf87a9f0e980.png)
___

# View all
___

![image5](https://user-images.githubusercontent.com/112674211/211157934-d620b9b4-b794-4b03-be80-01216868b9cb.png)

This function iterates over the shoes list and prints out the the information in an easy to read manner.
___

# Re stock
___

This function finds the product object with the lowest quantity of stock. Which is the product in need of a restock. The program asks the user if they want to update the quantity of items. This function updates the information stored on the .txt file.
___

# Search shoe
___

Prints data of the specified object the user inputs into the terminal.
___

# Total value of stock
___

Calaculates and displays the total value of all stock currently on the system.

