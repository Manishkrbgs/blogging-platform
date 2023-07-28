
## **README-FILE**
# BLOGGING-PLATFORM-API
.> *Welcome to the documentation for the Blogging Platform API. This API serves as the backend for a blogging platform that allows users to create, read, update, and delete blog posts. This README file provides essential information for developers to understand and interact with the API effectively.*

-  ## [**Framework and Language Used :**](#heading-ids) ##
___
- ### Framework : **SpringBoot**
- ### Language : **Java, MySQL**
- ### Others : **Java Persistence API (JPA), Swagger UI, Email**

-  ## [**Prerequisites :**](#heading-ids) ##
*To run this project, ensure that you have the following installed:*
> - Java Development Kit (JDK)
>- MySQL
>- Maven

-  ## [**Getting Started Use :**](#heading-ids) ##

1. Clone this repository to your local machine.
2. Set up your MySQL database and configure the connection details in the `application.properties` file.
3. Build the project using Maven: `mvn clean install`.
4. Run the application: `mvn spring-boot:run`.
5. Access Swagger UI in your browser at: `http://localhost:8080/swagger-ui.html`.

## [**Data Flow**](#heading-ids) ##

- ## [**Endpoints Used:**](#heading-ids) ##
___
- ### 1. **Controller (User, Post, AuthenticationToken):-** ###
> - **User Controller :-**  
> 1. `POST /user/signUp` - *Create a new user blogging account.*
> 2. `POST /user/signIn` - *Authenticate and obtain a token for the blog user and By Hashing Password and Using Email*
> 3. `Update /user/update/details` - *Update blog user Information who have sign in *
> - **Post Controller :-**  
> 1. `POST /blog/post` - *Uploading a post an authoize blog user*
> 2. `POST //blog/AllPosts` - *See all Posts, An autorize blog user*


- ### 2. **DataBase Design:-** ###
> - **Database Used :-**  *SQL/Hibernate Database using*


- ### 3. **Model / Entity(User, Post, AuthenticationToken):-** ###
> - **Annotation Used :-**  *@Data, @NoArgsConstructor, @AllArgsConstructor, @Id, @OneToOne, @Column, @JoinColumn, @Entity, @GeneratedValue, @Enumerated, @NotBlank, @Min, @Max, @ManyToMany, @ManyToOne*

## [**Data Structure used in my Project**](#heading-ids) ##
____
> - **[Used :-](#heading-ids)** *SQL Database --> But Mostly used Java Concept, oops, collection, ENUM*

## [**Security**](#heading-ids) ##
____
*Authentication is implemented using an Authentication Token class. This token is generated upon successful sign-in and must be included in the headers of subsequent requests to authorized endpoints.*

## [**Encryption**](#heading-ids) ##
____
*Authentication is implemented using an Authentication Token class. This token is generated upon successful sign-in and must be included in the headers of subsequent requests to authorized endpoints.*


## [**Project Summary**](#heading-ids) ##
____
> - **[Aim :-](#heading-ids)** *This is basically good project for learning purpose springBoot basics, Mappings, Annotation, API, spring mvc and CRUD Operation, crud Repository inbuilt method, and Custom Finder and Custom Query. In this project i just add Posts, get all psots a particular user,  update User inforamtion lot of things i learned from this project.*

## **[👨‍💻 MANISH](#heading-ids)** ##
___

- Github: [@manish-Github](https://github.com/Manishkrbgs)


🤝 **Contributing**
___
Contributions, Thanks to everyone , contributing with me and know about more myself [visit my profile](https://instagram.com/manish_razzzz?igshid=MzNlNGNkZWQ4Mg==).

**Show Your Support**
___
Give a ⭐if this project helped you!

- ```bash
  BECOME A SOFTWARE DEVELOPER 👩‍💻

<!-- Here something icon -->

📝 **License**
___
Copyright © 2023 [manish kumar](#heading-ids).


___
*This README was generated with* 🧡 *by [readme-md-generator]









# Blogging-Platform
