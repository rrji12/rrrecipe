# Recipe Search and Display Application

This web application allows users to search for recipes based on ingredients or keywords and displays the results in an organized manner. It utilizes an external API to fetch recipe data.

## Usage

1. **Search for Recipes:**
   - Enter ingredients or keywords in the search input field.
   - Click the "Search" button to fetch recipes based on the entered query.
   
2. **View Recipe Details:**
   - The search results will be displayed below the search input field.
   - Each recipe card includes the recipe name, ingredients, and a link to the full recipe.
   - Click on the "View Recipe" link to open the full recipe in a new tab.

## Implementation Details

- **Frontend:** 
  - The user interface is built using HTML, CSS, and JavaScript.
  - HTML file (index.html) contains the structure of the application.
  - CSS file (styles.css) provides styling for the user interface.
  - JavaScript file (script.js) handles user interactions and API requests.

- **API Integration:**
  - The application integrates with a fictional recipe API to fetch recipe data based on user input.
  - API requests are made using JavaScript's fetch API.

- **Functionality:**
  - Users can enter ingredients or keywords in the search input field and fetch recipes accordingly.
  - A loading indicator is displayed while fetching recipe data from the API.
  - Error messages are shown if the API request fails.

## Testing

- **Functionality Testing:**
  - Tested the application by searching for different recipes and verifying the search results.

- **Cross-browser Compatibility:**
  - Tested the application on different web browsers to ensure compatibility.

## How to Run

1. Clone the repository to your local machine.
2. Open the index.html file in a web browser.
3. Enter ingredients or keywords in the search input field and click the "Search" button.
