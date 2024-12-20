Food Searching App

A React-based web application that allows users to search for food recipes using an API and displays the results dynamically. The app is styled using modern CSS techniques.

Features

Search for food recipes by name.

Display recipe results dynamically, including images and titles.

Responsive design for an optimal user experience across devices.

Technologies Used

React.js: For building the user interface.

CSS: For styling the application.

Recipe API: For fetching food recipe data.

JavaScript (ES6+): For logic and API integration.

Installation and Setup

Clone the repository:

git clone https://github.com/Vishalkondi/Food-Searching-App.git
cd Food-Searching-App

Install dependencies:
Ensure you have Node.js and npm installed. Run:

npm install

Start the development server:

npm start

The app will be available at http://localhost:3000 in your web browser.

Usage

Enter the name of the food or recipe you want to search for in the input field.

Click the "SEARCH" button to fetch results.

Browse the dynamically displayed results, including images and titles.

Project Structure

Food-Searching-App/
├── public/
│   ├── index.html
├── src/
│   ├── components/
│   │   ├── SearchBar.js
│   │   ├── RecipeCard.js
│   ├── App.js
│   ├── App.css
│   ├── index.js
├── package.json

SearchBar.js: Contains the search input and button.

RecipeCard.js: Displays individual recipe details (title, image).

App.js: Main application logic and API integration.

API Integration

The application fetches data from a Recipe API. Ensure you have an API key if the API requires authentication.

fetch(`https://api.example.com/recipes?query=${searchQuery}`)
  .then(response => response.json())
  .then(data => {
    // Handle fetched data
  });

Deployment

To deploy the app, build the production version:

npm run build

Upload the contents of the build/ directory to your hosting provider.

Screenshots ![Screenshot (29)](https://github.com/user-attachments/assets/ed0f5ec0-3dd0-4bd3-b0e3-15fcd8a4bebd)





Future Enhancements

Add filters for cuisine types, dietary preferences, and more.

Enable saving favorite recipes to a user account.

Implement pagination for large result sets.

License

This project is licensed under the MIT License.

