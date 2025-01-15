<h1 align="center"> 🛡️ Code Obfuscator By Mael Salah </h1>

Welcome to the **Code Obfuscator & Encryptor** project! This Python-based tool is designed to protect your code from reverse engineering and unauthorized access by obfuscating and encrypting it. It leverages libraries like `cryptography`, `zlib`, and `base64` to ensure your code remains secure and obscured.

## ✨ Features

- **🔒 Code Encryption**: Utilizes the `cryptography` library to encrypt your original Python code, making it unreadable without the appropriate decryption key.
- **🕵️‍♂️ Advanced Obfuscation**: Inserts randomized fake classes, functions, and variables to add complexity and make reverse engineering more challenging.
- **🚀 Executable Generation**: Outputs obfuscated Python files that are ready to be executed, maintaining functionality while hiding implementation details.
- **🔧 Dependency Management**: Automatically handles and installs any missing dependencies at runtime, ensuring smooth operation.

## 🛠️ Requirements

To use this tool, ensure you have the following:

- Python 3.6 or later
- Required libraries:
  - `cryptography`
  - `zlib`
  - `base64`
  - `subprocess`

The script will also install additional modules as needed during runtime, such as `requests` and `pycryptodome`.

## 📥 Installation

Follow these steps to get started:

1. **Clone the Repository**:
    ```bash
    git clone https://github.com/mael0salah/PYOBFUSCATOR.git
    cd Obfuscator
    ```

2. **Install Dependencies**:
    ```bash
    pip install cryptography
    ```

   The script will take care of other necessary dependencies during execution.

## 🏗️ Usage

To obfuscate and encrypt a Python file, follow these instructions:

1. **Prepare Your Script**:
   - Place the Python script you want to obfuscate in the `Build/` folder.
   - Rename this script to `temp.py`.

2. **Run the Obfuscator**:
    ```bash
    python Obfuscator.py <output_file_name>
    ```
    - `<output_file_name>`: Specify the desired name for the obfuscated output file (omit the extension).

### Example

For a file named `temp.py`, you would run:

```bash
python Obfuscator.py temp.py
