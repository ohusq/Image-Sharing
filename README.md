# Image Sharing

This is a simple image sharing application built with Node.js and Express. Users can upload screenshots and get a shareable link.

## Features

- Upload screenshots
- Get a shareable link for the uploaded screenshot

## Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/ohusq/image-sharing.git
    ```
2. Navigate to the project directory:
    ```sh
    cd image-sharing
    ```
3. Install the dependencies:
    ```sh
    npm install
    ```

## Usage

1. Start the server:
    ```sh
    npm start
    ```
2. Open your browser and navigate to `http://localhost:3000`.

## Project Structure

- `server.js`: The main server file that handles file uploads and serves static files.
- `public/index.html`: The frontend HTML file for uploading screenshots.
- `uploads/`: Directory where uploaded files are stored.

## Dependencies

- [Express](https://expressjs.com/): Fast, unopinionated, minimalist web framework for Node.js.
- [Multer](https://github.com/expressjs/multer): Middleware for handling `multipart/form-data`, which is primarily used for uploading files.

## License

This project is licensed under the MIT License