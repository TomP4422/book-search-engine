# Book Search Engine

## Table of Contents
- [Description](#description)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Deployed Application](#deployed-application)
- [Screenshots](#screenshots)
- [License](#license)
- [Contributing](#contributing)
- [Questions](#questions)

---

## Description
The Book Search Engine is a full-stack MERN application that allows users to search for books using the Google Books API and manage their personal book collection. The application leverages GraphQL for API communication, replacing a traditional RESTful architecture, to provide efficient and scalable data handling.

This project demonstrates modern web development practices, including dynamic user authentication, state management, and deployment.

## Features
- **Book Search**: Users can search for books and view details such as title, author, description, and cover image.
- **User Authentication**: Secure login and signup functionality.
- **Save Books**: Logged-in users can save books to their profile.
- **View and Manage Saved Books**: Access and manage a personalized list of saved books.
- **GraphQL API**: Refactored back-end API using Apollo Server.
- **Responsive Design**: Fully functional on all screen sizes.

## Technologies Used
- **Front-End**: React, Apollo Client, TypeScript
- **Back-End**: Node.js, Express.js, Apollo Server, MongoDB Atlas
- **Authentication**: JWT (JSON Web Token)
- **Database**: MongoDB
- **Deployment**: Render and MongoDB Atlas

## Installation
1. Clone the repository:
   ```bash
   git clone [repository URL]
   ```
2. Navigate to the project directory:
   ```bash
   cd book-search-engine
   ```
3. Install dependencies for both the client and server:
   ```bash
   npm install
   cd client && npm install
   ```
4. Create a `.env` file in the root directory and include the following:
   ```env
   MONGODB_URI=<your MongoDB connection string>
   SECRET=<your JWT secret>
   ```
5. Build the client:
   ```bash
   cd client && npm run build
   ```
6. Start the application:
   ```bash
   npm run develop
   ```

## Usage
1. Navigate to the application URL.
2. Use the "Search for Books" feature to find books by keywords.
3. Create an account or log in to save books to your personal profile.
4. View and manage your saved books in the "My Books" section.

## Deployed Application
The application is deployed and can be accessed at: [Deployed URL]

## Screenshots
### Home Page
*(Include screenshot here)*

### Book Search Results
*(Include screenshot here)*

### Saved Books
*(Include screenshot here)*

## License
This project is licensed under the [LICENSE] provided in the repository.

## Contributing
Contributions are welcome! If you'd like to contribute, please fork the repository and submit a pull request.

## Questions
For any questions, please contact:
- [Your Name or GitHub Username](https://github.com/YourUsername)
- Email: [YourEmail@example.com]

