# 📚 SmartLib – Smart Library Management System

SmartLib is a web-based library management project designed to make book discovery and library activities easier through a simple, user-friendly interface.

## ✨ Features

- 🏠 **Dashboard** – Access the main library features.
- 📖 **Explore Books** – Browse and discover books.
- 📚 **My Shelf** – Access your personal book collection.
- 🗓️ **Reservations** – Manage book reservations.
- 📷 **Smartboard Book Scanner** – Upload a book cover or capture it using a camera to identify books.
- 🔎 **Book Recognition** – Uses Optical Character Recognition (OCR) to extract text from book covers.
- 🌐 **Online Book Search** – Searches for matching books using the Open Library API.
- 👤 **Profile** – Access the user profile.
- 🌙 **Dark Theme** – A modern interface with charcoal backgrounds, lime-green accents, and gold highlights.

## 🛠️ Technologies Used

- HTML5
- CSS3
- JavaScript
- Tesseract.js – OCR text recognition
- Open Library API – Online book search
- Browser MediaDevices API – Camera access
- GitHub Pages – Website hosting

## 📷 Smartboard Book Scanner

The Smartboard scanner helps users identify books from their covers.

### How it works

1. Open the Smartboard page.
2. Allow camera permission or upload a book-cover image.
3. Capture the image if using the camera.
4. Run text recognition to extract readable text.
5. Review the extracted text and matching book results.
6. Open the available book-search links to explore more information.

**Note:** Camera access generally requires HTTPS or localhost. If the camera is unavailable, use the image-upload option.

## 🚀 How to Run the Project

1. Download or clone this repository.
2. Open the project folder.
3. Open `index.html` in a browser, or run the website using a local development server.
4. Navigate to the Smartboard page to test the scanner.

For camera functionality, use a secure HTTPS website or localhost and grant camera permission.

## 🌐 Deployment

This project can be hosted using GitHub Pages.

1. Push the project files to a GitHub repository.
2. Open the repository's **Settings**.
3. Select **Pages**.
4. Choose the appropriate branch and root folder.
5. Save the settings and open the published website.

## 📁 Project Structure

```text
SmartLib/
├── index.html
├── explore.html
├── shelf.html
├── reservations.html
├── smartboard.html
├── profile.html
└── README.md
```

*The filenames shown above are examples; update them to match the actual files in your repository.*

## 🎯 Project Objective

The objective of SmartLib is to provide a convenient digital library interface with book discovery, personal book organization, reservation features, and a smart book-cover scanning experience.

## 🔮 Future Enhancements

- Improve book-cover recognition accuracy.
- Add user authentication and secure data storage.
- Connect book reservations to a database.
- Save scanned books to the user's shelf.
- Add advanced filters for searching books.

## 👨‍💻 Author

**Chandu A**

BCA – Computer Applications

## 📄 License

This project is intended for educational and learning purposes.
