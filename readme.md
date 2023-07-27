# PySpark Interview Test
Welcome to my PySpark Interview Test! This test aims to evaluate my skills in using PySpark to solve real-world data processing challenges related to flights data. 
There are two questions in this test that I needed to address using PySpark.

# Questions
1. Build a String of Flights (Next Flights based on Aircraft Turn)
Given a dataset containing information about flights, you are required to build a string of flights for each aircraft based on its turn. The "turn" of an aircraft refers to the sequence of flights that an aircraft takes, i.e., the next flights after it lands at an airport.

Input Data:

The input data provided is a CSV format and contains the following columns:

flight_id: Unique identifier for each flight.
aircraft_id: Unique identifier for each aircraft.
origin_airport: The airport where the flight originated.
destination_airport: The airport where the flight landed.

* orig: departure airport data code
* dest: arrival airport data code
* id: flight id
* actl_dep_lcl_tms: actual departure local timestamp	
* actl_arr_lcl_tms: actual arrival local timestamp
* flight_num: fligh number
* flights	acft_regs_cde: aircraft registration code
* airborne_lcl_tms: takeoff time
* landing_lcl_tms: lading time
* next_flight_id: ???

2. I was required to build a PySpark program to analyze flight traffic in a specific airport over a period of 2 hours each 15 minutes. Given the scenario there are 2 ways of solve it: using spark streaming or batch. Because I want to demostrate my spark skills, I decided to go to the batch analysis simulating the time data
