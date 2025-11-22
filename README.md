# 📡 Text to Morse Code Converter

A simple yet effective command-line utility written in Python that translates standard text into International Morse Code.

## 📝 Project Overview

This lightweight script serves as a handy tool for educational purposes or hobbyist projects. It maps alphanumeric characters and common punctuation marks to their Morse code equivalents using a standard dictionary look-up. It runs entirely in the terminal and requires no external libraries.

## 🚀 Features

- **Standard Conversion**: Accurately converts letters (A-Z), numbers (0-9), and common punctuation (.,?/-()) into Morse sequences.
- **Zero Dependencies**: Built using pure Python, requiring no `pip install` of third-party packages.
- **Extensible**: The dictionary-based mapping structure makes it incredibly easy to add support for new symbols or languages.
- **Clean Output**: Separates letters with spaces and words with forward slashes (`/`) for readability.

## 💻 Installation & Usage

### Prerequisites
- Python 3.x

### Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/DavitEgoian/Text-to-Morse-Code-Converter.git
   cd Text-to-Morse-Code-Converter
   ```

2. **Run the application**
   Pass your text string directly as an argument:
   ```bash
   python "text to morse application.py" "Hello, World!"
   ```

   *Note: Ensure you wrap your input text in quotes if it contains spaces.*

### Example Output
Input:
`"Hello, World!"`

Output:
`.... . .-.. .-.. --- --..-- / .-- --- .-. .-.. -.. -.-.--`

## 📂 Project Structure

```text
Text-to-Morse-Code-Converter/
└── text to morse application.py  # The main script containing the dictionary and logic
```

## ⚙️ Customization

- **Adding Symbols**: Open the python file and add new key-value pairs to the `morse_code_dict` dictionary (e.g., `{'@': '.--.-.'}`).
- **Output Formatting**: Modify the print statements to change how the Morse code is displayed (e.g., changing the word separator from `/` to `|`).

## 🔠 Supported Characters

| Character | Morse Code | Character | Morse Code |
|-----------|------------|-----------|------------|
| A-Z       | `.-` ...   | 0-9       | `-----`... |
| , (comma) | `--..--`   | . (period)| `.-.-.-`   |
| ?         | `..--..`   | /         | `-..-.`    |
| -         | `-....-`   | ( )       | `-.--.`    |

## 📄 License

This project is open source and available for personal and educational use.
