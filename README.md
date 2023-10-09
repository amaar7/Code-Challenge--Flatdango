Flatdango Movie Theater Application
Overview
Flatdango is a web application that allows users to purchase movie tickets from Flatiron Movie Theater. Users can view details about movies, including posters, titles, runtimes, showtimes, and available tickets. The application fetches data from a local server running a JSON DB server.

Project Structure
The project is organized as follows:

index.html: The main HTML file that provides the structure for the web page.
script.js: The JavaScript file that contains the application logic.
styles.css: The CSS file that contains styles for the web page.
db.json: A JSON file acting as the local server's database.
Running the Application
To run the application, follow these steps:

Ensure you have a local server setup to serve the files. You can use tools like http-server or live-server.
Open index.html in a web browser.
Core Functionality
The core functionality of the application includes:

Displaying Movie Details:

When the page loads, details of the first movie are displayed, including the poster, title, runtime, showtime, and available tickets.
Displaying Movie Menu:

A menu of all movies is displayed on the left side of the page.
Each movie item in the menu can be clicked to display its details.
Buying a Ticket:

Users can click the "Buy Ticket" button to simulate buying a ticket.
The number of available tickets decreases on the frontend.
Additional Features
Viewing Movie Details:

Users can click on a movie in the menu to view its details.
This functionality is achieved by making an additional GET request to access the movie's details.
Sold-Out Status:

When a movie is sold out, the "Buy Ticket" button is disabled and the movie item in the menu is marked as sold out.
Project Implementation
The application is implemented in HTML, CSS, and JavaScript. It fetches movie data from a local JSON database and dynamically updates the UI to display movie details and the movie menu.

Future Improvements
In future iterations, the following enhancements could be made:

User Authentication:

Implement user authentication to allow users to sign in and purchase tickets using their accounts.
Persistent Data:

Implement backend functionality to persist data such as purchased tickets and user profiles.
Dynamic Showtimes:

Incorporate real-time showtime updates to reflect the current time and upcoming showtimes.
Integration with Payment Gateway:

Integrate a payment gateway to enable real transactions for ticket purchases.
Credits
This project was created for an assessment as part of the Flatiron School curriculum. The project structure and initial code were provided by Flatiron School. The implementation and additional features were completed by Amar Ahmed.