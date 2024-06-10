# bookstoor
This project is a simple web application built using Flask that allows users to manage a list of books. Users can add new books by providing the title and author, and they can also delete books from the list. This project is a great starting point for anyone looking to learn Flask and basic web development concepts.
# Book List App

A simple web application to manage a list of books. Built with Flask.

## Introduction

This project is a simple web application built using Flask that allows users to manage a list of books. Users can add new books by providing the title and author, and they can also delete books from the list. This project is a great starting point for anyone looking to learn Flask and basic web development concepts.

## Setup

1. Clone the repository:

    ```bash
    git clone <your-repository-url>
    cd book-list-app
    ```

2. Create a virtual environment:

    ```bash
    python -m venv myprojectenv
    source myprojectenv/bin/activate  # On Linux/Mac
    myprojectenv\Scripts\activate  # On Windows
    ```

3. Install the requirements:

    ```bash
    pip install Flask
    ```

4. Run the application:

    ```bash
    python app.py
    ```

5. Open your web browser and go to `http://127.0.0.1:5000/`.

## Usage

- **Add a new book**: Enter the title and author in the form and click "Add Book".
- **Delete a book**: Click the "Delete" link next to the book you want to remove.

## Code Explanation

The project consists of a single file `app.py` which contains the following:

- **Imports and Initialization**: The Flask framework is imported and the application is initialized.
- **Global Variable**: A list `books` is defined to store the book information.
- **Routes**:
  - **`/` Route**: Renders the main page with a list of books and a form to add new books.
  - **`/add` Route**: Handles the form submission for adding new books.
  - **`/delete/<int:book_id>` Route**: Handles the deletion of a book by its index in the list.
- **Main Block**: Runs the Flask application in debug mode.

## Contributing

Feel free to fork the repository and submit pull requests. For major changes, please open an issue first to discuss what you would like to change.

## License

This project is licensed under the MIT License.
