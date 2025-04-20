# Group-5--A3-Project-Web-Look-and-Feel

# BookBridge - Community Book Sharing Platform

BookBridge is a community-driven platform that connects book lovers, allowing them to share, borrow, and discover new books. Our mission is to make literature accessible to everyone while building a community of readers.

This project is a static website prototype that represents the design and structure of our final application. It includes navigation between pages, functional CRUD operation buttons, and interactive data visualizations.

![BookBridge Logo](logo.jpg)

## Features

- **Book Management**: Create, read, update, and delete book entries
- **User-Friendly Interface**: Clean, responsive design that works on all devices
- **Search and Filter**: Easily find books by title, author, or genre
- **Data Visualization**: View statistics and trends about your book collection
- **Access Control**: Different users can have access to different books

## Technology Stack

- **Frontend**: HTML5, CSS3, JavaScript
- **Styling**: Custom CSS with responsive design
- **Data Management**: JavaScript for client-side data handling (can be extended to use a backend)

## Usage

### Home Page
The home page provides an overview of the BookBridge application and quick access to all features.

### Data Visualization
View statistics and trends about your book collection.

### About Us
Learn more about the BookBridge team and mission.

### Create Book
Add new books to your collection by filling out the book details form.

### Read Books
Browse your book collection with search and filter options.

### Update Book
Select a book from the dropdown and update its details.

### Delete Book
Select a book from the dropdown and confirm deletion.

## Project Structure

```
bookbridge/
├── index.html              # Home page
├── data-visualization.html # Data visualization page
├── about.html              # About us page
├── create.html             # Create book page
├── read.html               # Read books page
├── update.html             # Update book page
├── delete.html             # Delete book page
├── css/
│   └── style.css           # Main stylesheet
├── js/
│   └── charts.js           # Charts functionality
│   └── script.js           # JavaScript functionality
└── README.md               # Project documentation
└── logo.jpg                # Website logo
```

## Customization

The color scheme can be customized by modifying the CSS variables in the `:root` selector in `style.css`:

```css
:root {
    --primary-color: #6a4c93;
    --secondary-color: #8a6db1;
    --accent-color: #ff9a8b;
    /* other variables */
}
```

## Future Enhancements

- Backend integration with a database
- User authentication and authorization
- Book cover image upload
- Book lending system
- Reading list and recommendations
- Mobile app version

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## Acknowledgments

- Inspired by library management systems
- Thanks to all contributors and users 


