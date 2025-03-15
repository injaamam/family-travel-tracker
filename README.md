# Family Travel Tracker

## Overview
Family Travel Tracker is a Node.js application designed to help families keep track of their travels, destinations, and itineraries.

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/injaamam/family-travel-tracker.git
    cd family-travel-tracker
    ```

2. Install dependencies:
    ```bash
    npm install
    ```

## Database Initialization

4. Create a postgreSQL database (e.g., named `world`) and run the queries from `queries.sql`. This will create the necessary database for the program:

    Example connection details for your database (used in `index.js`):
    ```env
    user=postgres
    host=localhost
    database=world
    password=ck675511
    port=5432
    ```

## Start the Application

5. Start the application:
    ```bash
    node index.js
    ```

## Usage
- Open your browser and navigate to `http://localhost:5000`
- Start adding and managing your travels

## Contributing
Contributions are welcome! Please fork the repository and submit a pull request.
