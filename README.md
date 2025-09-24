Parallel Requester
Overview
This project provides a simple yet powerful tool for testing server performance under stress. The "Parallel Requester" is a Python script that sends multiple identical HTTP requests to a specified server endpoint simultaneously, allowing you to observe how the server behaves and responds to concurrent traffic. This is an excellent tool for load testing, identifying race conditions, and evaluating server stability.

Features
Parallelism: The script uses a ThreadPoolExecutor to send up to 100 concurrent requests at a time.

Identical Requests: All requests use the same URL, headers, and payload, ensuring a consistent load for testing.

Detailed Summary: The script provides a summary of the test run, including the number of successful and failed requests, and the average, fastest, and slowest response times.

Error Handling: The script includes try-except blocks to handle exceptions and report on failed requests.

How to Use
Prerequisites
You need to have Python and the requests library installed.

Install Python: If you don't have it, you can download it from the official  Python website.

Install the requests library: You can install it using pip:

pip install requests

Installation
Save the Python script as Parallel_Request_Attacker.py.

Running the Requester
The script is pre-configured to send requests to a specific URL with a defined payload and cookies. To use it, you just need to run the script directly.

python Parallel_Request_Attacker.py

The script will execute and print a summary of the results to your console.

Potential Applications
Load Testing: Determine the maximum number of concurrent requests your server can handle before performance degrades.

Race Condition Detection: Identify subtle bugs that only appear when multiple requests are processed at the same time.

API Performance Benchmarking: Compare the response times of different API endpoints under load.

Server Stability Testing: Check for crashes or unexpected behavior under heavy traffic.

Contributing
We welcome contributions! Please feel free to open an issue or submit a pull request with improvements or new features
