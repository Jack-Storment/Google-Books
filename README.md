# Google-Books

Google-Books is a MERN (MongoDB, Express.js, React.js, Node.js) stack application that allows users to search for books using the Google Books API, view book details, and save their favorite books to a personal reading list.

## Project Overview

This application provides a user-friendly interface for book enthusiasts to discover and manage their reading lists. Users can search for books, view detailed information about each book, save books to their list, and remove books from their saved collection.

### Key Features

- Search for books using the Google Books API
- View book details including title, author(s), description, image, and link to Google Books
- Save books to a personal reading list
- View all saved books
- Remove books from the saved list

## Technical Stack

- **Frontend**: React.js
- **Backend**: Node.js with Express.js
- **Database**: MongoDB with Mongoose ODM
- **Deployment**: Heroku-ready

## Project Structure

The project follows a typical MERN stack structure:

- `client/`: Contains the React frontend application
- `models/`: Defines the Mongoose schema for the GoogleBooks model
- `routes/`: Contains API routes for book operations
- `scripts/`: Includes database seeding script
- `server.js`: Main server file that sets up the Express application

## Getting Started

1. Clone the repository
2. Install dependencies:
   ```
   npm install
   cd client && npm install
   ```
3. Set up your MongoDB connection (local or Atlas)
4. Run the development server:
   ```
   npm run start:dev
   ```

## API Routes

- GET `/api/books`: Retrieve all saved books
- POST `/api/books`: Save a new book
- DELETE `/api/books/:id`: Remove a book from the saved list


## Deployment

This application is set up for easy deployment to Heroku. Use the following command to deploy:


## Scripts

- `npm run start`: Start the production server
- `npm run start:dev`: Start the development server
- `npm run build`: Build the React client
- `npm run seed`: Seed the database with initial data

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the ISC License.