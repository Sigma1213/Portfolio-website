
## React Router Project its hooks

This is a simple React application demonstrating the use of `react-router-dom` for client-side routing. The project includes multiple pages like Home, About, Contact, User, Github, and a 404 Not Found page,outlet is been used for some common layout like header and footer where main section will only move.

## Features

- **Home Page**: The main landing page of the application.
- **About Page**: Information about the placeholder text.
- **Contact Page**: Contact information in input data can be fill but in address is taken from dummy data.
- **User Page**: Dynamically loaded user information based on the user ID in the URL.
- **Github Page**: Fetches and displays information from the Github API.
- **NotFound Page**: A fallback route for any unrecognized URLs.
- **Location Page**: Displays the current location details using `useLocation` hook from `react-router-dom`.




### Routes

- `/`: Home Page
- `/about`: About Page
- `/contact`: Contact Page
- `/user/:userid`: User Page
- `/github`: Github Page (data loaded via a loader function)
- `/location`: My Location Page
- `*`: 404 Not Found Page

## Technologies Used

- **React**: For building the user interface.
- **React Router**: For managing routing within the app.
- **Tailwind CSS**: For styling the application.
- **Github** : For loading github profile image and username in /github route.
