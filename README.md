# World Capital Quiz

This is a simple web application built with the PERN stack (PostgreSQL, Express, Ejs, Node.js). It serves as a quiz game where users are asked to identify the capitals of different countries.

## Setup

1. Clone the repository to your local machine.
2. Navigate to the project directory.
3. Install dependencies using `npm install`.
4. Ensure you have PostgreSQL installed and running on your machine.
5. Create a PostgreSQL database named `worlds`.
6. Import the provided SQL dump file into the `worlds` database to populate it with quiz data.
7. Open the `index.js` file and update the PostgreSQL connection settings with your database credentials.
8. Run the server using `npm start`.
9. Access the application in your web browser at `http://localhost:3000`.

## Dependencies

- Express: Web framework for Node.js.
- Body-parser: Middleware to parse incoming request bodies.
- pg: PostgreSQL client for Node.js.

## Project Structure

- `index.js`: Main server file that handles routing and database interactions.
- `public`: Directory for static files like CSS and client-side JavaScript.
- `views`: Directory for EJS templates.

## Usage

- Navigate to `http://localhost:3000` in your web browser.
- You will be presented with a question asking for the capital of a random country.
- Enter your answer in the provided input field and submit.
- The application will inform you if your answer is correct or not.
- Your total score will be displayed at the top of the page.

## Contributing

Contributions are welcome! If you have any suggestions, improvements, or bug fixes, feel free to open an issue or submit a pull request.
