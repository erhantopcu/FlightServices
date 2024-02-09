● Data Modeling: The information stored in the database needs to be designed and modelled.
  ○ Any relational (SQL) or NoSQL database can be used as a database.
  ○ Information to be stored:
        -Flights
            ■ ID
            ■ Departure airport
            ■ Arrival airport
            ■ Departure date/time
            ■ Return date/time
            ■ Price
        - Airports
            ■ ID
            ■ City
● CRUD structure must be constructed: CRUD (Create, Read, Update, Delete) is created on a database.
It represents the most commonly performed basic operations.
  ○ Establishing this structure ensures that data is managed consistently and organised. This way, users can create, read, update and delete data as needed.
  ○ Resources to which the CRUD structure will be applied.
        - Flights
        - Airports
● Search API
  ○ A list of flights available for the given origin, destination, departure date and return date.
API endpoint should be made.
  ○ If a return date is not given, it is a one-way flight; if it is, it is a two-way flight.
  ○ One flight information must be given for a one-way flight, and two flight information must be given for a two-way flight.
● Service should be provided outside with REST: Providing service outside with REST architecture. It enables interaction with systems. This makes data exchange easier and more general. It enables integration between systems.
● Java should be used (Spring/Spring Boot etc.)
● Authentication structure must be:
  ○ Authentication structure is used to authenticate and authorize the user. It makes building systems safer. Desired authentication architecture available.
