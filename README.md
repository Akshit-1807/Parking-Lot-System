# Parking-Lot-System
This is a parking lot application implemented in Python using Flask. The application provides functionalities for generating parking lot tickets based on vehicle information and available parking spots.
# Features
Generate parking lot tickets for vehicles
Assign parking spots to vehicles based on vehicle type and availability
Store vehicle, gate, and ticket information in repositories
Use a spot assignment strategy to determine the parking spot for a vehicle
Exception handling for invalid gates and no available spots
# Usage
To generate a parking ticket, send a POST request to the following endpoint:

POST /ticket

The request should include the following parameters:
gate_id: ID of the gate for ticket generation
vehicle_type: Type of the vehicle (e.g., car, motorcycle)
vehicle_number: Number of the vehicle
The response will include the generated ticket details.
