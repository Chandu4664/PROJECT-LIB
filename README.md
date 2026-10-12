# SmartLib — Modern Library Front-End

## Included pages
- `index.html` — welcome / demo sign-in
- `dashboard.html` — overview and Reading Consistency tracker
- `books.html` — book catalogue
- `smartboard.html` — camera/upload scanner with automatic OCR and book search
- `mybooks.html` — reading list
- `reservation.html` — reservations demo
- `Profile.html` — profile page

## Run the website
1. Extract the ZIP into a folder.
2. Open the folder in Visual Studio Code (recommended).
3. Install the VS Code extension **Live Server**, if it is not installed.
4. Right-click `index.html` and choose **Open with Live Server**.
5. Sign in using any valid-looking email and a password of at least 3 characters; this is a front-end demo only.
6. Open **Smartboard scan**, allow camera permission, and capture a book cover—or upload a photo. Recognition starts automatically.

## Camera troubleshooting
- Use Chrome or Edge.
- Camera access normally requires `https://` or `http://localhost`; opening the HTML as `file://` may block the camera.
- Click the site controls/lock icon beside the address bar → Camera → Allow, then reload.
- Close other apps using the camera. If the camera is unavailable, upload an image instead.

## Book recognition notes
The scanner uses Tesseract.js OCR to read visible text and matches it against the SmartLib sample catalogue, then optionally searches Open Library for online suggestions. It is not a trained visual-AI model and cannot guarantee a correct match for every cover. It needs an internet connection to load OCR and search online. Review the suggestions before relying on them.

## Reading consistency
The dashboard includes a daily reading log, weekly minutes, a 10-minute daily goal, and a streak counter. Data is stored in your browser's `localStorage` on that device/browser; it is not synced to other devices or accounts. Log your actual reading time to track consistency.

## Demo limitations
This is a front-end project. Sign-in, reservations, book lists, and reading logs are browser-side demo features, not connected to a secure backend or library database. Google Fonts, book cover images, Tesseract.js, and Open Library suggestions may require internet access.
