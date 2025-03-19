# YouTube Video Listing Application

This project is a web application that fetches and displays a list of YouTube videos based on a search query. It utilizes a public API to retrieve video data and dynamically displays the results on the page.

## Features

- **Dynamic Video Fetching:** Loads a set of videos on page load from a public API endpoint.
- **Search Functionality:** Enables users to search for videos by title using a live search bar.
- **Responsive Design:** Optimized layout that adapts to different screen sizes.
- **Themed Styling:** Utilizes a modern black, blue, and red theme with a fancy handwritten font for a unique look.
- **Interactive UI:** Hover effects and transitions for an enhanced user experience.

## Technologies Used

- **HTML5:** Provides the basic structure.
- **CSS3:** Used for styling, effects, and responsive layout.
- **JavaScript (ES6):** Handles API calls, DOM manipulation, and search filtering.
- **Google Fonts:** Incorporates the "Caveat" font for a distinctive style.
- **External API:** Fetches video data from a public YouTube-related API endpoint.

## How It Was Built

1. **Project Structure:**
   - `index.html`: Main HTML file that structures the layout of the application.
   - `style.css`: Contains the styling rules for the application including the themed colors (black, blue, and red) along with responsive design adjustments.
   - `script.js`: Implements fetching video data from the API, searching, filtering, and dynamically displaying video elements.

2. **Styling & Theme:**
   - The application uses a gradient background (black to blue), with red accents to highlight text and interactive elements.
   - A custom font ("Caveat") is imported via Google Fonts, enhancing the visual appeal.
   - CSS transitions and hover effects are used to provide a modern, interactive feel.

3. **Functionality:**
   - **Video Fetching:** On page load, the app makes an asynchronous API call to fetch video data, which is then stored in an array for further manipulation.
   - **Display Videos:** The fetched videos are rendered as cards in a responsive grid layout.
   - **Live Search:** An input field allows users to filter videos by title. As the user types, the display updates to reflect the search results.
   - **User Interaction:** Buttons and search fields have smooth visual transitions and effects that enhance usability and aesthetic appeal.

4. **Responsive Design:**
   - Media queries are used to ensure that the layout and components are responsive on various devices, including tablets and mobile phones.

## Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, Edge, etc.)
- Internet connection (to access external API and Google Fonts)

### Installation

1. Clone or download the project repository to your local machine.
2. Open the project folder in Visual Studio Code (or your preferred IDE).

### Running the Application

1. Open the `index.html` file in the browser.
2. The application loads automatically, fetching and displaying the latest YouTube videos.
3. Use the search bar to filter videos by title.

## Future Enhancements

- **Pagination:** Add pagination controls to handle large sets of video data.
- **Additional Filters:** Implement more advanced filtering options such as video duration or channel.
- **Improved Error Handling:** Enhance user notifications for API errors or connectivity issues.

## Credits

Developed as part of the Assignment 2 project for Masterji. Special thanks to the public API provider for making video data accessible.

---

Feel free to customize this documentation as needed.