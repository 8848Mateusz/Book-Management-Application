# Book Management Application
This is a simple Book Management Application built using Spring MVC and a mock service to manage book data in memory. The project demonstrates basic CRUD operations for managing books, including adding, editing, deleting, and viewing book details.

## Features
- List all books: View a list of all available books.
- Add a new book: Add a new book to the collection.
- Edit a book: Update the details of an existing book.
- Delete a book: Remove a book from the collection.
- View book details: View detailed information about a book.
## Technologies Used
- Java 11
- Spring MVC 5.1.9
- JSTL
- Hibernate 5.4.30 (for future database connection, currently using mock data)
- Maven
- Tomcat or any other servlet container
## Project Setup
### Prerequisites
- Java 11 or higher installed
- Maven installed
- MySQL installed (for future database integration)
## Steps to Run the Application
### Run the application:
- You can deploy the generated WAR file to a servlet container like Tomcat.
- Alternatively, you can use an embedded Tomcat server or run the application from your IDE (IntelliJ IDEA or Eclipse).
### Access the application:
- Open your browser and navigate to:
  ```bash
  http://localhost:8080/your-app-context/books/all
  ```
- This will display the list of books managed by the application.
### Database Setup
1. Create a MySQL Database:
   ``` sql
   CREATE DATABASE workshopHibernate;
   ```
2. Configure the database in persistence.xml
   ``` persistence
    name="javax.persistence.jdbc.user" value="root"
    name="javax.persistence.jdbc.password" value="your_password"
   ```
## License
This project is licensed under the MIT License.
