# Keeper-App-Official

# Notes App (With Functional Components)

This is a React-based Notes application that allows users to create, display, and delete notes. The app is structured with reusable functional components, including a `Header`, `Footer`, `Note`, and `CreateArea` components, making the application modular and easy to maintain.

## Features

- Create new notes with a title and content.
- View a list of notes.
- Delete notes.
- Use of `useState` for managing the state in a functional way.

## Project Structure

- **`App.jsx`**: The main component that holds the state and manages the functionality for adding and deleting notes. It integrates all other components.
- **`Header.jsx`**: A functional component for displaying the header of the app.
- **`Footer.jsx`**: A functional component for displaying the footer of the app.
- **`Note.jsx`**: A functional component for displaying individual notes.
- **`CreateArea.jsx`**: A functional component for creating new notes, with input fields for title and content.

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/jbolan12/Keeper-App-Official.git
    ```

2. Navigate to the project directory:
    ```bash
    cd notes-app
    ```

3. Install the dependencies:
    ```bash
    npm install
    ```

## Usage

To run the application locally:

1. Start the development server:
    ```bash
    npm start
    ```

2. Open your browser and visit [http://localhost:3000](http://localhost:3000) to view the app.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
