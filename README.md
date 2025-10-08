# CarRental-GUI

A simple car rental management application with a graphical user interface (GUI) built using **Python**, **Tkinter**, and **MySQL**.

## Features

- User-friendly GUI for car rental operations
- Add, update, and delete car and customer records
- Manage bookings and returns
- Store and retrieve data from a MySQL database

## Technologies Used

- **Python**: Main programming language
- **Tkinter**: For creating the desktop GUI
- **MySQL**: Backend database for storing all rental, customer, and car information

## Prerequisites

- Python 3.x
- MySQL server
- The following Python libraries:
  - `tkinter` (comes with standard Python installations)
  - `mysql-connector-python` (install via `pip install mysql-connector-python`)

## Setup Instructions

1. **Clone the Repository**
    ```bash
    git clone https://github.com/Dharaniswarreddy/CarRental-GUI.git
    cd CarRental-GUI
    ```

2. **Install Dependencies**
    ```bash
    pip install mysql-connector-python
    ```

3. **Configure MySQL Database**
    - Make sure your MySQL server is running.
    - Create a new database for the car rental system.
    - Update the database connection details in the Python code (host, user, password, database name).
    - Run the provided SQL scripts (if any) to create the required tables.

4. **Run the Application**
    ```bash
    python main.py
    ```
    (Replace `main.py` with the actual entry-point file if different.)

## Usage

- Use the GUI to add, update, or delete cars and customers.
- Book or return cars using the booking interface.
- All actions are reflected in real-time in the MySQL database.

<img width="994" height="666" alt="image" src="https://github.com/user-attachments/assets/6c823480-742a-402d-ae89-32f5629f5896" />


## License

This project is licensed under the MIT License.

---

**Note:**  
If you encounter any issues or have suggestions, feel free to open an issue or submit a pull request.
