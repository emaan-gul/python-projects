Report: Comprehensive Guide on Python Applications for Bookstore Management, Hotel Data Analysis, and Housing Dataset Processing

Introduction
This report presents a comprehensive guide on utilizing Python for various applications, including bookstore management, hotel data analysis, and housing dataset processing. It encompasses detailed implementations, code explanations, and practical insights to streamline tasks and derive meaningful insights from data.

 1. Bookstore Management

Overview
Efficient bookstore management is crucial for maintaining inventory, tracking sales, categorizing books, managing customer information, and processing orders. This section provides a Python-based solution to simplify these tasks.

Implementation Details
The Python code and functionalities for bookstore management are  implemented in the `assignment_1.ipynb` Jupyter notebook. The main functionalities include:

1. Inventory Management: 
   - Structure: Books are represented as tuples with details like ISBN, title, author, price, and quantity.
   - Storage: Inventory is stored as a list of tuples.
   - Functions: Adding books and updating quantities.

2. Sales Data Tracking: 
   - **Structure**: Sales data is stored in a dictionary with dates as keys.
   - **Functions**: Recording sales and retrieving sales data.

3. Categorization of Books: 
   - **Structure**: Books are categorized into genres using nested lists.
   - **Functions**: Browsing books by category.

4. Customer Information Management: 
   - Structure: Customer information is stored in a nested dictionary.
   - Functions: Accessing and updating customer information.

5. Order Processing: 
   - Functions: Checking book availability, removing duplicates, and identifying common order patterns.

 2. Hotel Data Analysis

 Overview
This section details the process of extracting hotel data from Booking.com and visualizing it using various charts. The implementation is provided in `assignment_2.pdf`.

 Implementation Details
The code in `assignment_2.pdf` demonstrates the following steps:

1. Web Scraping:
   - Using `requests` and `BeautifulSoup` to extract hotel information such as name, address, rating, price, and reviews from Booking.com.
   
2. Data Storage:
   - Saving the extracted data into a CSV file.

3. Data Visualization:
   - Bar Chart: Comparing hotel ratings.
   - Pie Chart: Showing the distribution of hotel types.
   - Line Graph: Showing the trend of hotel prices over different locations.

3. Housing Dataset Processing and Text Tokenization

Overview
This section describes the process of handling a housing dataset by managing missing values, checking for duplicates, converting text data into numeric format, and performing text tokenization.

Implementation Details
The code in `assignemnt_3` demonstrates the following steps:

1. Dataset Processing:
   - Libraries: Import necessary libraries using `import numpy as np` and `import pandas as pd`.
   - Loading Data: Load the housing dataset using `pd.read_csv()` and create a copy.
   - Handling Missing Values: 
     - Fill missing 'furnishingstatus' with 'Unknown'.
     - Fill missing 'price' values with the median price.
     - Fill missing 'mainroad' values with the mode.
     - Drop rows with other missing values.
   - Removing Duplicates: Check for and drop duplicate rows.
   - Converting Text to Numeric: Replace 'Yes' with 1 and 'No' with 0 using `replace()`.

2. Text Tokenization:
   - Sample Text: "Tokenization is the process of breaking down text into smaller components such as words or sentences. Tokenization helps in preparing text data for further analysis."
   - Tokenizing Text: Split the text into words using `split()`.
   - Counting Word Frequencies: Count the frequency of each word using a dictionary and a loop.
