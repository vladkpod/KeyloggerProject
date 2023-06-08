# Keylogger

This is a Python keylogger project that records keystrokes and saves them to a text file. It uses the `pynput` library to capture keyboard events.

## Prerequisites

To run this keylogger, you need to have the following:

- Python 3.x installed on your system
- The `pynput` library installed. You can install it using the following command:

  ```shell
  pip install pynput
  ```

## Usage

1. Clone the repository or download the source code files.
2. Open a terminal or command prompt and navigate to the project directory.
3. Run the following command to start the keylogger:

   ```shell
   python keylogger.py
   ```

4. The keylogger will start running and listening for keyboard events.
5. All the captured keystrokes will be saved to a file named `keyfile.txt` in the same directory as the `keylogger.py` file.

**Note:** Please be aware that keyloggers can be used for malicious purposes. Make sure you have appropriate permissions and legal rights before using this tool. It is your responsibility to use it ethically and in compliance with the law.

## Limitations

- This keylogger currently supports only the capturing of printable characters. Non-printable keys (such as function keys, arrow keys, etc.) will not be recorded.
- The keylogger does not encrypt or obfuscate the captured keystrokes. Exercise caution when handling the generated log file to ensure the security and privacy of the recorded data.

## Contributing

Contributions to this project are welcome. If you find any issues or want to add new features, feel free to open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE). Feel free to modify and distribute the code as per the terms of the license.
