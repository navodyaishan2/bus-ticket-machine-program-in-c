# bus-ticket-machine-program-in-c
This is a program that simulates a “Ticket Machine”. In this program, you are expected to simulate a ticket machine program (using C language) that is capable of generating a ticket for a given journey. 
The ticket shall print the following information with suitable formatting.
•	Journey starting station
•	Destination
•	Journey distance
•	Number of passengers
•	Fare (for a passenger) and 
•	Total fare
In addition to the above, the ticket shall print appropriate headings. 
The fare (for a passenger) is calculated by the following formula.

Fare = initial fare + ( distance – 1 ) * 2 

The following table depicts the distance between station 1 and any given station. Note that the initial fare, which is charged for the First Kilo meter is Rs. 7.00.  

Starting station	Stopping station	Distance (Km)
1                     	2	              2
1	                      3             	5
1	                      4	              9
1                     	5	              15
 
 
Important hint: 

You may plan to develop this program into several stages. For example, in stage 0, use top-down modular decomposition and/or step-wise refinement discussed during lectures for the design along with flaw charts and pseudocode to explain the algorithms. You may also design the appropriate data structures (arrays, records, array of records, etc.) to hold data that are required for the program.

Stage 1 could be the menu design/development that prompts the conductor to perform a task. For example, a menu containing options to;

•	Issue a ticket
•	Search for distance
•	Calculate fare
•	Total money collected between a ticket number range and etc. Could be designed.
