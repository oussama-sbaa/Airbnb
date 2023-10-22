# Project Description

The project is an online stay booking application. It is accessible in three different modes: unauthenticated, user, and host. Each mode allows access to different functionalities.

The unauthenticated mode allows the user to access the application's home page. This page displays a list of all stays along with a search bar. It also provides access to the login form as a traveler or host.

Once authenticated as a user, the user accesses the home page. This page displays a search bar along with a list of all available stays. The user can write a comment relating to a specific stay. They can also add one or more trips to their cart. The cart displays the list of all trips selected by the user. They have the option to delete stays and validate their cart to send reservation requests to the concerned hosts. Finally, the user has access to a page summarizing all the stays they have booked (validated reservations and ongoing requests).

As a host, the user accesses the home page containing a search form and the list of stays. They also have access to a list of stays they exclusively offer. The host can access a list of all ongoing reservation requests which they can validate or cancel. Lastly, the host has access to a schedule summarizing all validated reservations for the stays they offer.

=> The project is developed in JavaFX, and is connected to a MySQL database.

# Installation and Execution

- Clone the project from GitHub
- Import the project into a development environment compatible with JavaFX (for example, IntelliJ IDEA)
- Configure the database connection parameters in the application.properties file
- Run the application by launching the main class Main.java
