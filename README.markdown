# Bookstore Database Project

## Overview
This project involves the creation and management of a bookstore database using SQLite in Python. The database tracks authors, books, and sales, with functionality to insert sample data and perform SQL queries using joins to retrieve meaningful insights.

## Features
- **Database Creation**: Sets up tables for Authors, Books, and Sales with appropriate constraints and relationships.
- **Data Insertion**: Inserts sample data into the respective tables with validation for missing values.
- **Query Capabilities**: Executes SQL joins to:
  - Retrieve books and their authors.
  - Calculate total sales per book.
  - Combine book details with sales data.

## Tools and Technologies
- **Language**: Python 3.12.7
- **Database**: SQLite
- **Libraries**: sqlite3 (built-in Python module)
- **Environment**: Jupyter Notebook

## Project Structure
- `Building_a_Bookstore_DB.ipynb`: The main Jupyter Notebook containing the code for database creation, data insertion, and queries.

## Installation
1. Clone the repository:
   ```
   git clone <repository-url>
   ```
2. Navigate to the project directory:
   ```
   cd <repository-directory>
   ```
3. Ensure Python 3.12.7 and Jupyter Notebook are installed:
   ```
   pip install jupyter
   ```
4. Open and run the notebook:
   ```
   jupyter notebook Building_a_Bookstore_DB.ipynb
   ```

## Usage
- Run the notebook cells sequentially to:
  - Create the database and tables.
  - Insert sample data for authors, books, and sales.
  - Execute queries to view results.

## Sample Data
- **Authors**: Includes names like James Clear, J.K. Rowling, Charles Dickens, etc.
- **Books**: Contains titles such as "Atomic Habits", "Harry Potter and the Sorcerer's Stone", with prices and author IDs.
- **Sales**: Records quantities sold and sale dates for each book.

## Results
- Successfully inserted 5 authors, 12 books, and 12 sales records.
- Query results show:
  - Books paired with their authors.
  - Total sales per book (e.g., "Atomic Habits": $79.95).
  - Detailed sales data including price, quantity sold, and date.

## Conclusions
The project demonstrates a functional bookstore database with data integrity checks and effective use of SQL joins for data analysis. The code handles missing values and commits changes to ensure data persistence. This setup can be extended for real-world applications by adding more complex queries or additional tables (e.g., Customers, Orders).

## Future Improvements
- Add error handling for database connection issues.
- Implement data validation for price and quantity ranges.
- Enhance queries with filtering and sorting options.
- Add a user interface for easier data management.

## License
This project is open-source. Feel free to use and modify it as needed.
