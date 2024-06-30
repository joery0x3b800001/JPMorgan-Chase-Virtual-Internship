## Introduction

Welcome to the JP Morgan Chase & Co. Experience Technology Program! This module provides you with an opportunity to engage with real-world technology challenges faced by JP Morgan Chase & Co. You'll dive into practical tasks that simulate the work environment within their tech team.

## Module 1 Task Overview

In this module, your task involves interfacing with a stock price data feed and setting up your system to analyze the data effectively.

**Objective:** Process the data feed of stock A and stock B’s prices to enable analysis and decision-making regarding when trading for the stocks should occur.

1. **Clone the Repository:** Begin by cloning this repository to start the task.
   
2. **Implement Functions:** Adjust the `getRatio`, `getDataPoint`, and `main` functions as specified in the task requirements.
   
3. **Bonus Challenge:** Pass all unit tests provided and consider adding more to cover edge cases for comprehensive testing.
   
4. **Submission:** Upload a git patch file as your submission for this task.

## Set up / Installation

To set up the server and client application on your local machine, refer to the [setup instructions](https://insidesherpa.s3.amazonaws.com/vinternships/companyassets/Sj7temL583QAYpHXD/setup_devenv_m1_v6.pdf).

**Note:** This module uses Python 3. For the Python 2.7 version, visit [this repository](https://github.com/insidesherpa/JPMC-tech-task-1).

## How to Run

1. **Start the Server:**
   ```bash
   python server3.py
   ```
   This command creates a random market data file called 'test.csv' in your working directory if it doesn't already exist.

2. **Resolve Dependencies:**
   If you encounter an issue with `datautil.parser`, run:
   ```bash
   pip install -r requirements.txt
   ```

   If you don't have pip installed, refer to [pip installation guide](https://pip.pypa.io/en/stable/installing/).

3. **Start the Example Client:**
   ```bash
   python client3.py
   ```

4. **Unit Test the Example Client:**
   ```bash
   python client_test.py
   ```

## Using curl to Request from the Server

To query the server using curl, use the following command format:

```bash
    $ curl 'http://localhost:8080/query?id=1'
    {"id": "1", "top_ask": {"price": 129.18, "size": 70}, "timestamp": "2016-08-06 12:32:11.821574", "top_bid": {"price": 128.79, "size": 61}}
```
This command fetches data from the server at the specified endpoint.

## Fixing Code to Meet Objectives

For detailed instructions on making the necessary changes to achieve the module objectives, refer to the [making changes guide](https://insidesherpa.s3.amazonaws.com/vinternships/companyassets/Sj7temL583QAYpHXD/making_changes_m1_v4a.pdf).

To tackle the bonus task, review the instructions in the [client test guide](https://insidesherpa.s3.amazonaws.com/vinternships/companyassets/Sj7temL583QAYpHXD/client_test_m1_v1a.pdf).

## How to Submit Your Work

Your submission requires a patch file. Follow the steps in the [create patch file guide](https://insidesherpa.s3.amazonaws.com/vinternships/companyassets/Sj7temL583QAYpHXD/create_patch_file_v3a.pdf) to create and submit your patch file via the [JPM Module 1 Page](https://www.insidesherpa.com/modules/R5iK7HMxJGBgaSbvk/gtAhtcvke9AFCzqME).