# URL Shortener with TinyURL

## Description
This script shortens a given long URL using TinyURL's API. It sends a request to TinyURL's API and retrieves a shortened URL.

## Requirements
- Python 3.x
- `requests` library

## Installation
1. **Clone the repository** (if applicable) or download the script file.

2. **Install the required Python packages**. You can install the `requests` library using pip:

    ```bash
    pip install requests
    ```

## Usage
1. **Insert your long URL**: Replace the placeholder `INSERT YOUR LONG URL HERE` in the script with the URL you want to shorten.

2. **Run the script**:

    ```bash
    python script.py
    ```

   Replace `script.py` with the name of your Python script file if it's different.

3. **Check the output**: The script will print the shortened URL if the request is successful, or an error message if there is an issue.

## Example
If your long URL is `https://www.example.com`, replace `INSERT YOUR LONG URL HERE` with `https://www.example.com`:

```python
long_url = r"https://www.example.com"
