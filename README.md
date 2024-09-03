# Metro Ticket Booking System

## Summary

The Metro Ticket Booking System is a comprehensive Java-based application designed to streamline the process of booking metro tickets. It aims to provide a user-friendly interface for users to register, log in, book tickets, and view metro schedules. This system also includes a robust backend powered by a MySQL database, ensuring data integrity and efficient management of user information and booking records.

## Overview

The Metro Ticket Booking System is a Java-based application designed to facilitate the booking of metro tickets. This project includes functionalities such as booking tickets, viewing schedules, and managing user information.

## Features

- User Registration and Login
- Ticket Booking
- Schedule Viewing
- User Information Management
- Database Integration with MySQL

## Prerequisites

- Java Development Kit (JDK) 8 or higher
- Apache NetBeans IDE (or any other preferred Java IDE)
- XAMPP (for MySQL database)

## Getting Started

### Building the Project

1. Open the project in your preferred Java IDE.
2. Build the project to generate the JAR file.

### Build Output Description

When you build a Java application project that has a main class, the IDE automatically copies all of the JAR files on the project's classpath to your project's `dist/lib` folder. The IDE also adds each of the JAR files to the `Class-Path` element in the application's JAR file manifest file (`MANIFEST.MF`).

To run the project from the command line, navigate to the `dist` folder and type the following:

```sh
java -jar "metro_System.jar"
```

To distribute this project, zip up the `dist` folder (including the `lib` folder) and distribute the ZIP file.

### Database Insertion Steps

1. **Install XAMPP**: If not already installed, download and install XAMPP from [https://www.apachefriends.org/index.html](https://www.apachefriends.org/index.html).

2. **Import the Database**:
   - Open XAMPP Control Panel and start the Apache and MySQL modules.
   - Open your web browser and navigate to [http://localhost/phpmyadmin/](http://localhost/phpmyadmin/).
   - Click on the **Import** tab on the top bar of the home page.
   - Browse for the `metros.sql` file from the location where you downloaded or stored it.
   - Ensure the character set is set to `UTF-8` and the format is `SQL`.
   - Click on **Go** at the bottom of the screen.
   - The database will be imported into your XAMPP server.

## Usage

1. **Run the Application**: 
   - Navigate to the `dist` folder and run the JAR file using the command: 
     ```sh
     java -jar "metro_System.jar"
     ```
2. **Access the Application**: 
   - Use the provided user interface to register, login, book tickets, and manage your information.

## Future Scope

The Metro Ticket Booking System has the potential for several future enhancements:
- **Mobile Application Development**: Create mobile versions for Android and iOS to increase accessibility.
- **Payment Integration**: Incorporate online payment gateways for seamless ticket purchasing.
- **Real-time Updates**: Implement real-time schedule updates and notifications.
- **Multi-language Support**: Add support for multiple languages to cater to a broader audience.
- **Enhanced Security**: Strengthen security features to protect user data and transactions.

## Contributing

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes.
4. Commit your changes (`git commit -m 'Add some feature'`).
5. Push to the branch (`git push origin feature-branch`).
6. Open a Pull Request.


## Contact

For any inquiries or support, please contact [Divyanshu Singh] at [singh.divyanshu1121@gmail.com].

---

Thank you for using the Metro Ticket Booking System!
