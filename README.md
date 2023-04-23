# Restaurant_Api

this Api work is to take input of restaurant vlaues like , restaurantName , id , adress , staffSize , speciality , menu and with it it will make a restaurant data.

## Frameworks and Language Used

The following frameworks and languages were used in the development of this project:

- Java
- Spring Boot

## Data Flow

The following functions were used in this project:

1. Controller - This component is responsible for handling the incoming requests and processing them.
2. Services - This component provides business logic to the application.
3. Repository - This component interacts with the database.
4. Module - This component is responsible for the design of the schema.

## Data Structure

The following data structures were used in this project:

- ArrayList

## brief description of each of the components in the context of the code:

### Controller
The controller is responsible for handling incoming requests and returning appropriate responses. In the code, it have a RestaurantController which handles requests related to the user entity. It has methods such as getAllRestaurant,addRestaurant,getRestaurantId,deleteRestaurantById and updateRestaurantSpecialtyById. These methods use the UserService to perform CRUD (create, read, update, delete) operations on the user data.

### Service
The service layer contains the business logic of the project. It acts as an intermediary between the controller and the repository. In the code, it have a RestaurantrService which contains methods such as getAllRestaurant,addRestaurant,getRestaurantBasedOnId,removeRestaurantById and updateRestaurantSpecialtyById. These methods perform validation on the input data and delegate database operations to the UserRepository.

### Repository
In the code, it have a RestaurantRepository. This interface provides basic CRUD operations such as RestaurantDao,getRestaurantFromDataSource,save,remove and update.

### Module
In the code, i have created a module named Restaurant which contains the User entity class. This class represents the data model of the user and contains properties such as  restaurantName,id,adress,staffSize,speciality and menu.

Overall, these components work together to create a layered architecture for your project, which separates concerns and promotes modularity and maintainability.

## Project Summary

The aim of this project is to create a system that can take input data and use it to create a project. The system is built using Java and Spring Boot.The data flow is handled by the Controller, Services, and Repository components, with the Database Design being responsible for the schema. The project also makes use of arrayslists to store and manipulate data.
