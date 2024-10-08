
# License Management System

This project is designed to manage software licenses, providing both client-side validation and server-side administration. Below is a guide to setting up and running the project.

## Features
- Client-side license validation.
- Server-side management for license generation and administration.
- User-friendly interface via templates.

## Installation

### Prerequisites
- Python 3.x
- Flask (for server-side operations)
- Any additional dependencies as listed in the `requirements.txt` (if available).

### Steps to Set Up

1. **Clone the Repository**
   Clone the repository to your local machine using the following command:
   ```bash
   git clone https://github.com/AmithYallati/-license-management-system.git
   ```

2. **Install Dependencies**
   Navigate to the project directory and install the required dependencies.
   ```bash
   cd -license-management-system
   pip install -r requirements.txt
   ```

3. **Run the Client-Side Validator**
   The `client_side_validator.py` script handles the validation of licenses on the client side. To run it:
   ```bash
   python client_side_validator.py
   ```

4. **Set Up the Server**
   The server-side logic is found in the `server_side` folder. To start the server:
   ```bash
   cd server_side
   python app.py
   ```

   This will start the Flask server for license management.

5. **Admin Access**
   Administrative functions are managed in `admin.py`. You can execute it to handle license generation:
   ```bash
   python admin.py
   ```

6. **Access the Interface**
   Open your browser and navigate to `http://localhost:5000` to access the License Management System interface.

