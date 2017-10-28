# Valet-Database

This is a small project that I worked on for a final project in my Databse Theory class. I got to choose, design, and create my own database that would satisfy the job that I created. I chose to make a Valet database because I had spent a summer working there and knew everything to create this database and hopefully create it better than the one they used.



Database Application Description

    -- Every valet parking needs employees,  customers, vehicles, keys,  the parking spot number, hotel room, and possible damage

    -- Every time a customer has an employee park their vehicle, that interaction needs to be logged along with what time the employee was given the car and when the customer got their car back

    -- All vehicles that enter the system need to have their model, color, and license plate number recorded

    -- A customer can have more than one vehicle cared for by a valet

    -- A vehicle can be associated with more than one customer

    --A employee must check to see if the vehicle had any preexisting damage once it is first checked in

    --Every car has a key and the key has an Id that identifies it to a car


This database is for a hotel Valet. It must keep track of the customer, and the car that they check into valet. The customer is given an Id that links them to their keys which are linked to their car. In addition we want to keep track of the hotel room that the customer is in. We must know where the car is parked. Each spot is designated with a number that allows the employee to know where the car is parked. The first time a car is logged a damage check must be done and it should be recorded with the employee that did the check. In addition, the make, model, color and license plate number of the car should be logged. Each time the car is parked and pulled, it should track the employee that pulled or parked the car. A car is logged to a hotel room so it may have multiple people to one car. 
