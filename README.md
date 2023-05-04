# Cinema-Management-System
This is a simple cinema management system that serves as a database for managing different aspects of a cinema, such as movies, theaters, shows, and tickets. It includes the following main entities:

  Admin: This entity represents the person who controls the system at the ticket window. They have access to book tickets for customers.
  Shows: This entity represents the show ID, start and end time for a specific movie.
  Theater: This entity represents the theater ID and the theater name.
  Movie: This entity represents the available shows that have the movie ID and movie name.
  Seats: This entity represents the seat ID that belongs to the theater.
  Ticket: This entity represents the whole data on the ticket, including the ticket ID, the date the ticket was booked, the seat number, the ticket price, which admin reserves the ticket, the chosen show, and the theater where the movie will be presented.
  Ticket_location: This entity describes the location of the theater place in the hall, along with the ticket ID and which admin has booked the ticket.

The project has the following relationships:

  An admin can book more than one ticket.
  A theater can have more than one ticket.
  A show can have more than one ticket.
  A theater has many seats.
  A show can have more than one movie.

# Project Structure
The project includes the following files:

  ERD.png: This file contains the entity-relationship diagram (ERD) for the cinema management system, which shows the relationships between the entities.
  schema.sql: This file contains the SQL code for creating the tables and relationships in the database.
  queries.sql: This file contains SQL queries for inserting, updating, and retrieving data from the tables.

# How to Use
To use this cinema management system, you will need to have a MySQL database installed and configured. Once you have the database set up, you can use the schema.sql file to create the necessary tables and relationships. You can then use the queries.sql file to insert, update, and retrieve data from the tables.

The entity-relationship diagram (ERD) in the ERD.png file can help you understand the relationships between the entities in the database.
