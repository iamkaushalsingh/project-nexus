# Simple Restaurant Website Login and Signup Authentication

This project is a streamlined web application designed for restaurant management, featuring essential user authentication capabilities including login and signup functionalities. Below you'll find detailed information on understanding and running the project.

## Project Structure

The project comprises the following files:

1.**index.ejs**: The main page displaying a welcome message and a logout button.
2.**login.ejs**: The login page with a form for email and password input.
3.**signup.ejs**: The signup page with a form for name, email, and password input.
4.**server.j**s: The Node.js server file, handling user authentication, routing, and middleware configurations.

## Usage

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/iamkaushalsingh/project-nexus
   ```

2. Navigate to the project directory:

   ```bash
   cd project-nexus/Project2
   ```

3. Install the required dependencies:

   ```bash
   npm install
   ```

### Running the Application

Run the following command to start the server:

```bash
npm start
```

The application will be accessible at `http://localhost:3000/`.

### Dependencies

- Express: Web application framework for Node.js.
- Bcrypt: Library for hashing passwords.
- Passport: Authentication middleware for Node.js.
- Express Flash: Middleware for flashing messages.
- Express Session: Middleware for session management.
- Method Override: Middleware for HTTP method override.

## Design

The design of the website is simple and user-friendly. It features a background image with a radial gradient, providing a pleasant and welcoming atmosphere. The login and signup pages are designed with a glass-like effect, enhancing the visual appeal.

### References

1. [Bootstrap Documentation](https://getbootstrap.com/docs/5.2/examples/cover/)
2. [Desphixs](https://www.desphixs.com)
3. [Smashing Magazine](https://www.smashingmagazine.com)
4. [MDN Web Docs](https://developer.mozilla.org/)

## Additional Notes

The project utilizes Bootstrap for styling and ensuring responsiveness.
Currently, user data is stored in-memory for demonstration purposes. In a production environment, a database would be necessary for persistent data storage.
Feel free to explore and modify the project according to your needs. For any questions or further assistance, refer to the provided references or contact the project creator.

Enjoy building with this simple yet effective foundation for your restaurant management application!
