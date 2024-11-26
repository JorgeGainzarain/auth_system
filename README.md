# Authentication System

## Description
This project is a simple authentication system built with Node.js, Express, and EJS. It provides user registration, login, and logout functionality. It also includes a template for other categories like settings, with an "Under construction" message for the moment.

## Features
- User registration with full name, username, and password
- User login with username and password
- Session-based authentication
- Logout functionality
- Client-side form validation
- Server-side error handling and display
- Responsive design for both desktop and mobile devices

## Dependencies
- Node.js
- Express
- EJS
- express-session
- dotenv

## Installation
1. Clone the repository.
2. Navigate to the project directory.
3. Install the dependencies using `npm install`.
4. Modify the `.env` file in the root directory and add your `SESSION_SECRET` (a long, unique phrase).
5. Optionally, modify the port in `src/index.js`.

## Usage
1. Start the server with `npm start`.
2. Open your web browser and navigate to `http://localhost:3000`.

## Project Structure
- `src/`: Contains the source code
  - `index.js`: Entry point of the application
  - `routes.js`: Defines the routes for the application
  - `models/`: Contains the model files
    - `AuthService.js`: Handles authentication logic
    - `UserRepository.js`: Manages user data
- `views/`: Contains the EJS templates
  - `login.ejs`: Login page template
  - `register.ejs`: Registration page template
  - `index.ejs`: Home page template
- `public/`: Contains static assets
  - `user.png`: User icon image
  - `construction.png`: Under construction image
- `package.json`: Defines project dependencies and scripts
- `README.md`: Project documentation (this file)

## Contact 
If you want to contact me, you can reach me at `jorgegainzarain@gmail.com`.

## Contributing
This is an individual project for academic purposes. Contributions are not currently accepted.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
