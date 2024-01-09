# Kékés Voyages (UML)

Kékés voyages is a UML project to design the modeling of a simplified flight booking system for a travel agency.


The mission is to design the modeling of an online flight booking platform for a travel agency, using the UML standard. Key features include flight management, reservations, passengers, airports, stopovers, and airlines. Steps in the design process include analysis of client needs, creation of use case diagram, development of class diagram, creation of sequence diagram, refinement of the model with management rules, validation with the client, model documentation, and preparation for development.


## Steps: 



1. **Inventory of business rules:**
    - Identification and documentation of the rules that govern the system, including expected behaviors and applicable constraints.
2. **Creation of use case diagrams:**
    - Definition of the main functionalities of the system and the interactions between the actors (users) and the system.
3. **Development of class diagrams:**
    - Representation of the system entities with their attributes, methods, and associations, integrating the business rules to ensure data coherence and integrity.
4. **Construction of sequence diagrams:**
    - Modeling of the interactions between the system objects during specific scenarios, taking into account the business rules to ensure compliance of the system with client requirements.
5. **Validation of UML models:**
    - Presentation of the developed UML models to the client for validation and adjustments based on the received feedback.
6. **Writing of detailed documentation:**
    - Comprehensive documentation of each element of the UML model, including integrated business rules to guide the future development of the system.
7. **Analysis of client requirements:**
    - Meeting with the client to understand specific requirements for online flight ticket reservation.
    - Identification and documentation of the rules that govern the system, including expected behaviours and applicable constraints.

<br>

---

### Use Case Diagram:

#### Rules:

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

<br>

### Class Diagram:

#### Rules:

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