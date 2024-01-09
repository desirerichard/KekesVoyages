# Management rules

## Use Case Diagram:

- Client :
    - Create a user account
    - Book flight, (passengers, locations, dates) : Pay for the reservation, Register your flight, Cancel the reservation and need to be logged.
    - Login
    - Edit user information need to be logged.
    - Delete user account need to be logged.
- Travel Agency :
    - Ask for confirmation
    - Propose flights on the platform include “Retrieve flight list’”
    - Manage customer data as login extended.
    - Retrieve flight list include the company's proposal flights
- Airline Company :
    - Confirm reservation include the confirmation’s demand from the agency.
    - Propose flights to agencies
    - Manage and plan flights : Cancel flights, Edit flights



## Class Diagram:

1. **Flight Management:**
    - A flight can be opened for reservation and closed on the company's order.
    - Flights can be canceled by the airline.
    - Each flight has a departure airport and an arrival airport.
    - Flights have specific departure and arrival dates and times.
    - Flights can include stops at different airports.
2. **Reservation Management:**
    - Customers can reserve one or more flights for different passengers.
    - Each reservation is associated with a single flight and a single passenger.
    - Reservations can be canceled or confirmed.
3. **Stopover Management:**
    - Flights can have layovers, each with a specific arrival and departure time.
4. **Airport and City Management:**
    - Each airport serves one or more cities.
5. **Airline Management:**
    - Different airlines offer various flights.