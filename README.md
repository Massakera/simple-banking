# Simple banking API

This project is a simple banking API built with FastAPI. It supports operations such as creating accounts, depositing to and withdrawing from accounts, transferring funds between accounts, and checking account balances.

## Getting Started

These instructions will guide you through setting up and running the project locally on your machine for development and testing purposes.

Prerequisites:
- Python 3.10+
- pip

## Setup and Installation

### Clone the Repository

First, clone the repository to your local machine:

```bash
git clone https://github.com/Massakera/simple-banking.git
cd src
```

### Create a Virtual Environment

Run the following command in the root directory of the project to create a virtual environment:

```bash
python3 -m venv venv
```

This command creates a directory named venv in your project directory, containing the virtual environment.

## Activate the Virtual Environment

Before you install the dependencies and run the project, you need to activate the virtual environment:

```bash
source venv/bin/activate
```

After activation, your command line should indicate that the virtual environment is active by showing its name.

### Install Dependencies

With the virtual environment activated, install the project dependencies using pip:

```bash
pip install -r requirements.txt
```

This command installs all the necessary Python packages defined in requirements.txt.

### Running the Application

```bash
uvicorn app.main:app --reload
```

## Testing

To run the automated tests for this project, execute:

```bash
pytest
```

## API Endpoints

List the available API endpoints and their functionalities, for example:

- POST /event: Create an account or deposit/withdraw/transfer money.
- GET /balance?account_id=<account_id>: Get the balance of the specified account.

For detailed API documentation, visit http://localhost:8000/docs after starting the application, which provides Swagger UI documentation generated by FastAPI.
