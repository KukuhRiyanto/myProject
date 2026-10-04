# Simple Project House Rent Using Python Program 
1.	Creating The Class

    Class is used to create a class, House is the name of class from house rent program. This is a blueprint used to create     objects.
2.	__init__() is contructor of Class House.
3.	self is used to refer to current object (house_no, location, and rent). Self in here used as first parameter constructor of def__init__ and first parameter in the instance method (def display(self)).
4.	def display () is used to display House information about:

    print("House Number :", self.house_no)

  	print("Location :", self.location)

  	print("Monthly Rent : ₹", self.rent)

5.	Using tuple ()
A tuple is a collection of data written using paranthesis ().
Using tuple in house rent program: houses = ( (101, "Rajkot", 10000), (102, "Ahmedabad", 15000), (103, "Mumbai", 25000) ).

6.	print("===== HOUSE RENT SYSTEM =====". This is simple print the heading to display output ===== HOUSE RENT SYSTEM =====.
7.	Using for loop

  	for data in houses:

  	house = House(*data)

    This program is retrieving the entire dataset in the tuple: houses = ( (101, "Rajkot", 10000), (102, "Ahmedabad", 15000),     (103, "Mumbai", 25000) ).
8.  Display object using display ()

    house.display() to call object:

    print("House Number :", self.house_no)

    print("Location :", self.location)

    print("Monthly Rent : ₹", self.rent)

9.	Output program
Then output program, like this:

  <img width="247" height="225" alt="image" src="https://github.com/user-attachments/assets/2935133e-cc33-4764-b190-668802ae0a57" />




