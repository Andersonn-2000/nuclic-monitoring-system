# Nuclic Monitoring System

This project is a Telegram bot focused on monitoring the stock of the group's cabinet in the faculty.

## Setting up the Python Environment

To set up the Python environment, follow these steps:

1. Create a virtual environment using `venv`:
    ```sh
    python -m venv venv
    ```

2. Activate the virtual environment:
    - On Windows:
        ```sh
        .\venv\Scripts\activate
        ```
    - On macOS and Linux:
        ```sh
        source venv/bin/activate
        ```

3. Install the required libraries using `requirements.txt`:
    ```sh
    pip install -r requirements.txt
    ```

## Requirements

Make sure to have a `requirements.txt` file with the necessary libraries. Here is an example:

```txt
python-telegram-bot==13.7
requests==2.25.1