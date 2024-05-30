# Book Store Documentation: Installation and Usage

## Installation

To install and run the Book Store application, follow these steps:

1. **Prerequisites**:
   - Ensure you have Python installed on your system. You can download it from [python.org](https://www.python.org/downloads/).
   - Install Tkinter (Python's standard GUI library) if it's not already included in your Python installation. Tkinter comes bundled with most Python installations, but if you need to install it, you can usually do so through your operating system's package manager (e.g., `pip install tk` on Ubuntu or `conda install tk` on Windows with Anaconda).

2. **Clone the Repository**:
   - Go to the [Book Store GitHub repository] and click the green "Code" button.
   - Copy the URL provided for the repository.
   - Open a terminal or command prompt, navigate to the directory where you want to clone the repository, and run the following command, replacing `<repository-url>` with the copied URL:
     ```
     git clone <repository-url>
     ```

3. **Navigate to the Project Directory**:
   - After cloning the repository, navigate to the project directory using the `cd` command:
     ```
     cd book-store
     ```

4. **Install Dependencies**:
   - Install the required dependencies by running the following command:
     ```
     pip install -r requirements.txt
     ```

## Usage

To use the Book Store application, follow these steps:

1. **Run the Application**:
   - Execute the following command in the terminal or command prompt to run the application:
     ```
     python main.py
     ```

2. **Application Interface**:
   - The Book Store application will open in a new window with a graphical user interface (GUI).
   - The main window contains buttons for adding, editing, and deleting books, as well as a search functionality to search for books by title, author, or ISBN.
   - The inventory management section displays the current inventory and allows you to view all books stored in the database.

3. **Add, Edit, and Delete Books**:
   - To add a new book, click the "Add Book" button and fill in the necessary details in the pop-up window.
   - To edit an existing book, select the book from the inventory and click the "Edit Book" button. Fill in the updated details in the pop-up window.
   - To delete a book, select the book from the inventory and click the "Delete Book" button. Confirm the deletion in the prompt that appears.

4. **Search Books**:
   - To search for books by title, author, or ISBN, enter the search term in the "Search" input field and click the "Search" button. The results will be displayed in the inventory section.

5. **Inventory Management**:
   - View the current inventory and all books stored by scrolling through the inventory section or using the pagination controls.

By following these steps, you can install and use the Book Store application to manage your book store's inventory 

# Book Store README

## Introduction

The Book Store is a desktop-based application designed to manage a book store's inventory. It is built using Python and Tkinter library for the graphical user interface (GUI), with SQLite as the database management system.

## Application Features

- Add, edit, and delete books: Users can add new books, edit existing ones, and delete books that are in the inventory.
- Search books: Users can search for books by title, author, or ISBN.
- Inventory management: Users can view the current inventory and view all books stored.

## Project Breakdown

### Day 1: Project set up

- Create Github organization and repository, and clone said repository.
- Define the features and functionalities of the book store app.
- Decide and research on the technology stack I will use for frontend, backend, and database.

### Day 2: Frontend (GUI)

- Set up and installation of Python project and necessary tools such as Tkinter library and SQLite.
- Design the GUI, including layout and appearance of the application.

### Day 3: Database Setup

- Set up SQLite database and create the necessary tables for storing book information.
- Integrate the database with the GUI to allow for data input, retrieval, and manipulation.

### Day 4: Application Functionality

- Implement the functionality to add, edit, and delete books.
- Implement the functionality to search for books by title, author, or ISBN.
- Implement inventory management features, allowing users to view the current inventory and all stored books.

### Day 5: Testing and Debugging

- Test the application to ensure all features are working as expected.
- Debug and fix any issues that arise during testing.

### Day 6: Deployment

- Package the application for distribution.
- Create documentation for users on how to install and use the application.

### Day 7: Review and Future Enhancements

- Review the project and identify areas for improvement.
- Discuss potential future enhancements to the application. 
