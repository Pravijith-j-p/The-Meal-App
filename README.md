Meal Explorer Web App
Overview
This web application allows users to explore and search for meals, view detailed information about specific meals, and manage a list of favorite meals.

Features
Local Storage Initialization:

The application checks if there is a favorites list in the local storage. If not, it initializes an empty list.
API Fetching Function:

Asynchronous function for fetching meals from an external API based on a given URL and search value.
Displaying Meal List:

Function to display a list of meals based on user input. It dynamically generates HTML for each meal card.
Displaying Meal Details:

Asynchronous function to show detailed information about a specific meal. It fetches meal details based on the provided meal ID and updates the displayed content.
Displaying Favorites Meal List:

Function to display a list of favorite meals. It retrieves the favorites from local storage, fetches meal details, and generates HTML for display.
Adding/Removing from Favorites:

Function to add or remove a meal from the favorites list. It updates the local storage and refreshes the displayed favorites list.
Usage
Open the index.html file in a web browser.

Use the search bar to input meal names and view the corresponding list of meals.

Click on "More Details" to view detailed information about a specific meal.

Click the heart icon to add or remove a meal from the favorites list.

Setup
No additional setup is required. The application uses local storage for storing favorites and fetches meal data from an external API.

Technologies Used
JavaScript
HTML
CSS
