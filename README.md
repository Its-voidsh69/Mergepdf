# Mergepdf

This is a simple web application that allows you to merge multiple PDF files into a single document.

-----

### Features

  * **Merge PDFs**: Combine multiple PDF files into one.
  * **User-Friendly Interface**: A clean and simple interface for selecting and merging files.
  * **File Uploads**: Supports uploading up to 12 PDF files at a time.
  * **Progress Tracking**: Shows the upload progress.
  * **Download**: Provides a link to download the newly merged PDF.

-----

### Technologies Used

  * **Node.js**: The server-side runtime environment.
  * **Express.js**: A web framework for handling server requests and routing.
  * **EJS**: A templating engine to render dynamic HTML pages.
  * **Multer**: Middleware used for handling multipart/form-data, primarily for file uploads.
  * **PDF-Merge**: A library for programmatically merging PDF files.
  * **HTML, CSS, & JavaScript**: For the front-end user interface.

-----

### Installation and Setup

1.  **Clone the repository:**

    ```bash
    git clone [repository-url]
    cd mergepdf
    ```

2.  **Install dependencies:**

    ```bash
    npm install
    ```

3.  **Create a `.env` file:**
    Create a `.env` file in the root directory and add the following line. You can change the port if you want.

    ```
    PORT=3000
    ```

4.  **Create an `uploads` folder:**
    Create a directory named `uploads` in the project's root folder. This is where the temporary PDF files will be stored.

5.  **Start the application:**

    ```bash
    npm start
    ```

    The application will now be running at `http://localhost:3000`.

-----

### How to Use

1.  Open your web browser and navigate to `http://localhost:3000`.
2.  Click the "Browse File to Upload" area to select the PDF files you want to merge.
3.  Click the "Merge" button.
4.  Once the files are processed, a "Download" button will appear. Click it to download your merged PDF.
