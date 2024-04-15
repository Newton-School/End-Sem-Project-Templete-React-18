# End-Sem Project: Wynk Music Clone



## Project Objective


This project aims to recreate the core features and user interface of the popular music streaming platform, Wynk Music, using HTML, CSS, JavaScript, and React.



## Tech Stack


HTML: Provides the structural foundation of the web application.
CSS: Handles the styling and visual presentation.
JavaScript: Enables dynamic functionality and interactivity.
React: Facilitates component-based UI development and efficient updates.


## Prerequisites


Basic understanding of HTML, CSS, JavaScript, and React.


## Getting Started


Boilerplate Template: Select a suitable React boilerplate template from the provided GitHub links. Clone the repository to your local system.

Dependencies: Install the required packages using npm install.  Ensure to also install react-router-dom@6.22.3 for routing within the application.



## CSS Libraries


Choose between PrimeReact and Tailwind CSS to style your application:

Why Tailwind CSS? Tailwind CSS provides a utility-first approach, allowing for rapid custom design and a polished application look.
Why PrimeReact? PrimeReact offers pre-built React components with a comprehensive design system, aiding in the creation of a cohesive user interface.
Refer to the respective installation guides:

Tailwind CSS Documentation: https://tailwindcss.com/docs
PrimeReact Documentation: https://primereact.org/


## Features and Functionalities


1. Navigation Bar

Fixed: Remains at the top of the screen even when scrolling.
Branding: Displays the Wynk Music logo and brand name.
User Icon: Right-side icon with "Login" text when the user is not logged in.
Login Redirect: Clicking "Login" navigates the user to the /login page.
Logout Functionality: When logged in, the icon remains, but "Login" changes to "Logout." Upon clicking "Logout," the user is logged out, and an alert confirms the action.
2. Sign-up and Log-in Pages

Sign-up Form (/signup)
Fields: Name, email, password.
Validations: All fields required, valid email format, strong password rules (minimum 6 characters, lowercase, uppercase, symbols).
Login Form (/login)
Fields: Email, password.
Validations: All fields required, checks for existing user and matching credentials.
3. Home Page and Featured Music

API Integration (/): Fetch and display song data using the provided API.
Categories: Display eight categories: "Trending Songs," "Top 20 of this Week," "Top 50 of this Month," "Evergreen Melodies," "Happy," "Romantic," "Excited," and "Sad."
Pagination: Implement pagination for each category, allowing users to navigate through additional songs.
Song Component:
Thumbnail image
Title
Artist name(s)
Play/pause button (functional for logged-in users only)


## API Usage


The API endpoint  https://academics.newtonschool.co/api/v1/music/song is crucial.  Utilize query parameters for filtering and pagination:

filter: Retrieve songs by featured or mood categories.
limit: Control the number of songs in each API response.
page: Navigate through API results.




## Additional Notes

Project ID: Your unique project ID is derived from your Playground URL. Include this in API requests.
Authentication: Logged-in users should play songs, others are redirected to login.
UI Design: Refer to provided images.


## Best Practices


Component Structure: Create modular, reusable components.
Project Organization: Maintain a clear file structure.
Naming Conventions: Use meaningful names.
Error Handling: Address potential errors.