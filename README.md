# Program to Login to a Server

This Python program logs into a server using provided credentials and handles different login scenarios. It uses the `requests`, `lxml`, and `xml.etree.ElementTree` libraries. Follow the steps below to set up and run the program.

## Prerequisites

Before running the program, ensure you have the following libraries installed:
- `requests`
- `lxml`

You can install them using pip:

```bash
pip install requests lxml
```
## Usage

1. Open the Python file `login_script.py` in a text editor.
2. Fill in your login credentials:
   - Update `username` and `password` with your primary login credentials.
   - Update `username1` and `password1` with your secondary login credentials.
3. Save the file.

## Running the Program

To run the program, simply execute the Python script using your preferred Python interpreter:

```bash
python login_script.py
```
OR
```bash
python3 login_script.py
```

## Creating an Executable

To create an executable from the Python script, you can use tools like PyInstaller. PyInstaller bundles the Python script and its dependencies into a standalone executable.

### Install PyInstaller

```bash
pip install pyinstaller
```
```bash
pyinstaller --onefile login_script.py
```
This will create an executable file in the dist directory.

```bash
./dist/login_script
```

Note:
Before creating the executable, make sure you have entered your correct login credentials in the Python script.
