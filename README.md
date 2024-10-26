# Automated Text Typing Script

This project is a simple script that uses the `pyautogui` library to automatically type a message and press enter at regular intervals.

## Features

- Automatically types a predefined message.
- Simulates pressing the enter key to send the message.
- Runs continuously with a delay between each message.

## Requirements

- Python 3.x
- `pyautogui` library

## Installation

1. Ensure you have Python 3.x installed. You can download it from [Python.org](https://www.python.org/).
2. Install the required library using pip:

   ```sh
   pip install pyautogui
    ```
## Usage
- Clone this repository or download the script file.
- Run the script:
 ```sh
  python main.py
 ```
- The script will start typing the message "I need you..." and pressing enter every second.

## Code Explanation
```python
import pyautogui
import time

while True:
    time.sleep(1)
    pyautogui.typewrite("I need you...")
    pyautogui.press("enter")

```

This script uses a while loop to run continuously. It waits for one second between each iteration, types the message "I need you...", and then simulates pressing the enter key.

## License
This project is licensed under the MIT License. See the LICENSE file for details.
