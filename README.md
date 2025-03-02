# DataManager

## Overview
DataManager is a Python-based application enabling users to interact with various relational databases. It involves information retrieval and database modifications by executing queries. 

## Features
- **User Login:** Authenticate users based on their user ID
- **Search Business:** Filter businesses based on name, city, star rating and display ordered results
- **Search Users:** Find users based on name, review count, and average star rating.
- **Make Friend:** Establish friendships between users and store the relationship in the database.
- **Review Business:** Allow users to submit business reviews and update the business’s rating and review count.

## Installation
### Setup Steps
Ensure you have Python installed along with the following dependencies:
```sh
pip install pymssql pyodbc
```

### Running the Application
```sh
python bmp_viewer.py
```

## Usage
1. Launch the application.
2. Open a BMP image using the file menu.
3. Apply various image processing effects from the menu options.
4. Use sliders to fine-tune effects like Unsharp Masking.
5. Save the processed image if needed.

## Controls
- **Menu Options:** Access various image effects and enhancements.
- **Sliders:** Adjust parameters like amount, radius, and threshold for Unsharp Masking.
- **Apply Button:** Apply real-time changes from the sliders.

## Contributing
Feel free to fork and contribute improvements. Submit a pull request with detailed explanations of your changes.

## License
This project is licensed under the MIT License.
