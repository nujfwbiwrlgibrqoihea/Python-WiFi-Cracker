# Python-WiFi-Cracker

This Python script generates combinations of characters to use as passwords and connects to a specified Wi-Fi network using the generated passwords. It utilizes the `itertools` module to generate combinations and the `os` module to execute system commands for adding Wi-Fi profiles and connecting to networks.

## Requirements

- Python 3.x
- Windows OS (due to the use of `netsh` command for Wi-Fi operations)

## Usage

1. Clone or download this repository to your local machine.

2. Open a terminal or command prompt and navigate to the directory containing the script.

3. Run the script by executing the following command:

    ```bash
    python main.py
    ```

4. Follow the on-screen prompts:
   
   - Enter the name of the Wi-Fi network you want to connect to.
   - The script will then generate passwords and attempt to connect to the specified Wi-Fi network using each generated password.

## Notes

- The script generates passwords by combining alphanumeric characters of length 9. You can adjust the length of the passwords by modifying the `range` value in the `generate_combinations` function.

- The generated passwords are saved to a file named `combinations.txt` in the same directory as the script.

- This script is designed for Windows OS as it uses the `netsh` command for Wi-Fi operations. It may not work on other operating systems.

## License

This project is licensed under the Apache License 2.0. See the [LICENSE](LICENSE) file for details.
