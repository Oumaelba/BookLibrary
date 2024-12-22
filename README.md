# Book Library

This is a frontend application that allows users to search for books and view detailed information using the **Google Books API**. The project is built with **React**, styled using **Tailwind CSS**, and provides a clean, responsive user interface for exploring books.

## Features

- **Search for Books**: Users can search for books by title, author, or keywords.
- **Book Details View**: Clicking on a book will display detailed information such as description, publisher, ISBN, page count, and publication date.
- **Responsive Design**: The app is fully responsive and adapts to mobile, tablet, and desktop screens.
- **Book Covers**: Display book covers with thumbnails from the Google Books API.

## Usage

- Use the search bar to find books by entering the title, author, or keyword.
- Click on a book from the search results to view detailed information such as the description, publisher, ISBN, and more.

## API Integration

The app uses the **Google Books API** to fetch book data. Here are some example API endpoints:

- Search for books by title or keywords:
  ```https://www.googleapis.com/books/v1/volumes?q=harry+potter```
- Search for books by author:
  ```https://www.googleapis.com/books/v1/volumes?q=author:tolkien```

The API returns a list of books that match the query along with book details like the title, authors, publisher, description, and cover images.

## Technologies Used

- **React**: JavaScript library for building the user interface.
- **Tailwind CSS**: Utility-first CSS framework for styling.
- **Google Books API**: API to fetch book data.

## Deployment

This project can be deployed to a hosting platform like **Netlify** or **Vercel**.
