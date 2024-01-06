# rest-crud-jpa-api-employee_with_SpringDataRest

# Java class details 👈
* This is a regular CRUD project made using REST API.
* This project contains the below classes
   1. Entity class - Employee.java
   2. DAO interface that extends JpaRepository (given by Spring Data JPA) to carry out Database operations.
   3. Annotated repository class as @RepositoryRestResource(path="members") to explicitly change the context-path.

# Database details 👈
* We use the MySql database for this project.
* Database name is employee_directory and table name is employee.
* The name of the primary key field is id
