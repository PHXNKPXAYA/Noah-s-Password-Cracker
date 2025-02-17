# Noah's Password Cracker

Noah's Password Cracker is a Python-based tool designed to perform brute-force attacks to crack passwords using two modes: normal and column-based.

## Features
- **Brute-force password cracking** using all possible character combinations (letters, digits, symbols).
- **Column-based cracking mode** which guesses one character at a time per position.
- **Progress bar support** for tracking attempts and estimated time to crack.
- **Color-coded output** for better visibility of the cracking process.

## Installation
To install the required dependencies, run:

```bash
pip install tqdm colorama
```

## Usage
Run the program using Python:

```bash
python noahscracker.py
```

### Modes
- **Normal Mode**: Tries all possible combinations from length 1 up to the password length.
- **Column Mode**: Cracks one character at a time for each position in the password.

## Code Overview
- `brute_force_crack`: Core logic for the cracking process.
- `format_eta`: Formats the estimated time of arrival.
- `calculate_eta`: Calculates the estimated time based on attempts and time elapsed.
- `main_menu`: Provides a user interface for starting and exiting the cracker.

## Example
```plaintext
--- Password Cracker ---
1. Start Cracking
2. Exit
Choose an option (1/2): 1
Enter a password to crack: password123
Choose mode (normal/column): normal
Attempting to crack the password using normal mode...
```

## Disclaimer
This tool is intended for educational purposes and should only be used on systems you own or have explicit permission to test.

## License
This project is licensed under the MIT License.

