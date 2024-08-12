# My Project

This project is composed of three separate tasks, each implemented as a standalone Python script. The tasks involve creating a Flask API for accessing historical data, running an algorithm process with Flask, and processing JSON data.

## Task Overview

### Task 1: Historical Data API
This task involves creating a Flask API that provides access to historical data for financial indices such as BANKNIFTY, FINNIFTY, and NIFTY. The API returns data based on user requests and is useful for applications that require financial market data integration.

### Task 2: Algorithm Runner
In this task, a Flask API is developed to control the execution of a simulated algorithm process. The API provides endpoints to start and stop the algorithm, allowing for interactive control over its execution. This can be extended to integrate with more complex algorithmic trading systems or data processing tasks.

### Task 3: JSON Data Processing
This task involves a script that processes JSON data to extract and retain only the most recent entries based on timestamps. The script is designed to handle data from the NIFTY options chain, filtering for the latest date's data for each relevant entry.

## Usage Instructions

Each task is implemented as a separate script. You can run them individually based on your needs:

- *Task 1*: Run python task1.py to start the historical data API.
- *Task 2*: Run python task2.py to launch the algorithm runner API.
- *Task 3*: Execute python task3.py to process and filter JSON data.

### Additional Notes

- Ensure that any necessary data files, such as CSV or JSON files required by the scripts, are located in the same directory or adjust the file paths accordingly in the scripts.
- Review the comments within each script for additional guidance on modifying or extending the functionality.

This README provides a comprehensive guide to setting up and running the tasks, ensuring clarity and ease of use for developers and users alike. If you have any questions or need further assistance, feel free to reach out!
