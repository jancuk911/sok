# JWT Generator

## Overview

The JWT Generator project automates the process of generating JSON Web Tokens (JWTs) using a Python script and GitHub Actions. This tool simplifies the process of creating temporary email addresses, managing OTPs, and retrieving JWTs for authentication purposes.

## Features

- **Generate Temporary Email**: Creates a temporary email address for use.
- **Request and Confirm OTP**: Sends a request for a One-Time Password (OTP) and confirms it.
- **Create User**: Uses the temporary email to create a user account.
- **Save Account Details**: Stores user account information in `account.txt`.
- **Retrieve JWT**: Obtains a JWT for the user and saves it to `bearer.txt`.
- **Scheduled Execution**: Runs twice a day using GitHub Actions.

## Getting Started

### Prerequisites

- **Python**: Version 3.11
- **Dependencies**: The script requires the `cryptography` package.

### Setup

1. **Clone the Repository**
    ```bash
    git clone https://github.com/fcqx7/anakastro.git
    cd anakastro
    ```

2. **Install Dependencies**
    ```bash
    pip install -r requirements.txt
    ````
### Usage

- **Run the Script Locally**: Execute the script directly to generate JWTs and save the results.
    ```bash
    python generate.py
    ```

## Files

- `generate.py`: The Python script that performs the JWT generation.
- `account.txt`: Stores the user account information.
- `bearer.txt`: Contains the generated JWT.
- `requirements.txt`: Lists the dependencies required to run the script.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## DISCLAIMER

This project is intended for educational purposes and demonstration. Ensure proper handling and security practices for sensitive data in production environments.
