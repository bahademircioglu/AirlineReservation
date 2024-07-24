# Airline Reservation
This project involves developing an automated reservations system for a small airline. The system is designed to assign seats on each flight of the airline's only plane, which has a maximum capacity of 30 seats. The primary features of the system are as follows:

Features
Title and Menu Display:

The system displays the following title and menu at the beginning:
graphql
Copy code
Flight Seating System
Type 1 for "First Class."
Type 2 for "Economy."
Seat Assignment:

The system asks the 30 potential passengers about their seat choices.
The first-class section consists of seats 1 through 10.
The economy section consists of seats 11 through 30.
If the person enters 1, the system assigns a random seat in the first-class section.
If the person enters 2, the system assigns a seat in the economy section.
The system then prints a boarding pass indicating the person's seat number and whether it's in the first-class or economy section of the plane.
Seating Chart:

A one-dimensional array represents the seating chart of the plane.
All elements of the array are initialized to 0 to indicate that all seats are empty.
As each seat is assigned, the corresponding element of the array is set to 1 to indicate that the seat is no longer available.
The system never assigns a seat that has already been assigned.
Handling Full Sections:

When the first-class section is full, the system asks the person if it's acceptable to be placed in the economy section (and vice versa).
If the person agrees, the appropriate seat assignment is made.
If the person declines, the system prints the message "The next flight leaves in 3 hours."
Input Validation:

If the person enters any value other than 1 or 2, the system prints the message "Sorry, that choice is invalid."
The program does not exit at this point; instead, it keeps running from where it left off.
