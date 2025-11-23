cse_vityarthi-
EasyBook - Console Movie Ticket Booking System
A lightweight, console-based application written in Python for simulating a movie ticket booking system. Users can register, log in, view available shows, book tickets, and manage their reservations.
features 
User Management: Register and Log in with a simple username and password system.

Show Listings: View a list of current movies, dates, times, and available seats.

Ticket Booking: Book multiple tickets for any available show (Price: ₹200 per ticket).

Booking History: See a list of all your current reservations.

Cancellation: Cancel a booking, which automatically returns the seats to the show's capacity.

 How to Run the Project
This project runs directly in your terminal using Python.

Prerequisites
Python 3 installed on your computer.

Steps
Save the Code: Save the provided code into a file named easybook.py.

Open Terminal: Navigate to the directory where you saved the file.

Run the App: Execute the following command by
python easybook.py
Follow the Menu: The application will launch a menu. Start by selecting 1. Register to create an account.

 Example Usage Flow
Main Menu: Select 1. Register and create your account.

Login: Select 2. Login to access the system.

User Menu:

Choose 1. Book Ticket to view the show list.

Enter the Show ID and the number of tickets you want.

Choose 2. My Bookings to confirm your reservation.

Choose 3. Cancel Booking if you need to reverse a reservation.

Exit: Use 4. Logout to return to the main menu, or 3. Exit from the main menu to close the program.

Data Structure Overview
The application uses standard Python dictionaries and lists to store all necessary data while running:

Variable	Type	Purpose
shows	list of dict	Stores movie ID, name, date, time, and seats_left.
users	dict	Stores registered usernames and their passwords.
bookings	dict of list	Stores a list of booking strings for each user.
