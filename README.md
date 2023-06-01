# Food Order App

Food Order App is a web application built with React that allows users to browse and order delicious meals online. It provides a user-friendly interface for selecting meals and managing the cart. The application utilizes React's powerful components and hooks, along with the Context API for state management.

---

## Features

- Browse a variety of meals available for ordering.
- View detailed information about each meal, including name, description, and price.
- Add meals to the cart with a specified quantity.
- Remove meals from the cart or update their quantity.
- View the total amount and number of items in the cart.
- Place an order by submitting the cart items.

---

## Technologies Used

- **HTML**: The standard markup language for creating web pages.
- **CSS**: A stylesheet language used for describing the look and formatting of a document written in HTML.
- **JavaScript**: A programming language that enables interactivity in web browsers.
- **React**: A JavaScript library for building user interfaces.
- **Vite**: A fast development server and build tool for modern web development.
- **Prettier**: A code formatter that enforces a consistent code style.
- **Git**: A version control system for tracking changes in source code during software development.


---
## Folder Structure

The project folder structure is organized as follows:

- `src`: Contains the source code files
  - `components`: Contains reusable components used throughout the application
    - `Layout`: Renders the application header with a logo and navigation.
    - `Meals`: Displays a single meal item with its name, description, and price.
    - `Cart`: Displays the current cart items and allows users to remove or update quantities.
    - `UI`: General UI components that can be used for any applocation.
  - `assets`: Contains static assets like images
  - `store`: Contains the CartContext and related functionality for managing the cart state
    - `CartProvider`: Provides the cart state and actions to the application using the `CartContext.Provider`.
    - `cart-context.js`: Defines the structure of the cart context and initializes the initial state.
  - `App.js`: The main component that serves as the entry point for the application
  - `index.js`: Renders the `App` component and mounts it to the DOM
---

## Installation

To run the Food Order App application locally, follow these steps:

1. Clone the repository:

   ```
   git clone https://github.com/AhmedHamdi0/react-meals.git
   ```

2. Change to the project directory:

   ```
   cd Food Order App
   ```

3. Install the dependencies:

   ```
   npm install
   ```

4. Start the development server:

   ```
   npm start
   ```

5. Open your browser and visit `http://localhost:3000` to access the application.

---

## Scripts

The following scripts are available for running and building the ReactMeals project:

- `npm run dev`: Starts the development server.
- `npm run build`: Builds the project for production.
- `npm run preview`: Locally previews the built project.


---
## Contributing

Contributions to Food Order App are welcome and encouraged! If you find any bugs, issues, or have suggestions for improvements, please create an issue or submit a pull request.

To contribute to the project, follow these steps:

1. Fork the repository.
2. Create a new branch for your feature/bug fix.
3. Make the necessary changes and commit them.
4. Push the changes to your fork.
5. Submit a pull request to the main repository.

---

## Acknowledgments

- This project was created as part of a React course.
- The design inspiration for the project comes from various food delivery applications.

---
## Future Work

- Adding HTTP & Forms: Integrating APIs for fetching meal data and creating forms for user input.
- Building a Multipage SPA with React Router: Expanding the project to include multiple pages using React Router.
- Adding Authentication: Implementing user authentication features such as login, registration, and protected routes.
- Animating React Apps: Enhancing the user interface with animations using CSS transitions and popular animation libraries.
- Testing React Apps: Performing comprehensive testing with unit tests, integration tests, and end-to-end tests.

These additions will further improve the functionality, user experience, and stability of the application. Users can look forward to these upcoming updates and enhancements as the project progresses.

---

Thank you for using Food Order App! We hope you enjoy using the application.