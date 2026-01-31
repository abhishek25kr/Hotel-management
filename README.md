# Hotel-management
This project is a console-based Hotel Reservation System developed using Java and MySQL with JDBC. It allows hotel staff to manage guest reservations through a simple menu-driven interface. The application connects to a MySQL database to store and retrieve reservation details such as guest information, room number, check-in time, and check-out time.

The system provides core functionalities including retrieving guest information using a guest ID, allocating rooms to new guests, checking current room occupancy, and performing guest checkout by updating the check-out timestamp. All database operations are handled securely using JDBC PreparedStatement to prevent SQL injection and ensure reliable data handling.

The backend database is created in MySQL with a table named reservations, which stores reservation ID, guest ID, guest name, contact number, room number, check-in time, and check-out time. The check-in time is automatically recorded using the current timestamp, while the check-out time is updated during checkout.

To run the project, Java (JDK 8 or above) and MySQL must be installed on the system along with the MySQL Connector/J JDBC driver. After configuring the database credentials in the source code, the program can be compiled and executed from the command line. This project can be further enhanced by adding room availability checks, billing functionality, a graphical user interface, or converting it into a web-based application using Spring Boot.
