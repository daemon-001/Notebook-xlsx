# Notebook-xlsx

**Notebook-xlsx** is a Python application designed to store text notes in a date-wise organized `.xlsx` file. This application enables users to perform Excel operations without requiring Microsoft Excel or Google Sheets, thanks to the use of Python libraries.

## Features

- **Date-Wise Note Management:** Organize and store your notes with automatic date association.
- **Standalone Excel Operations:** Perform Excel file manipulations without needing external software like MS Excel or Google Sheets.
- **Lightweight and User-Friendly:** Simple and intuitive interface.

## Requirements

This project is built with Python and relies on the following libraries:

- `customtkinter`: For creating user friendly gui.
- `openpyxl`: For creating and modifying Excel files.
- `datetime`: To reading current data and time. 
- `os`: For running some cmd commands.

Make sure you have Python 3.6 or higher installed on your system.

## Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/daemon-001/Notebook-xlsx.git
   ```

2. Navigate to the project directory:
   ```bash
   cd Notebook-xlsx
   ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. Run the application:
   ```bash
   python notebook_xlsx.py
   ```

2. Follow the on-screen instructions to:
   - Add a new note.
   - View existing notes.
   - Edit or delete notes (comming soon).

3. The notes will be stored in an automatically generated `notebook_data.xlsx` file in the `C:\Users\username\Documents\Notebook-xlsx\`.

## File Structure

```plaintext
Notebook-xlsx/
├── __pycache__/          # Cache folder
├── customtkinter/        # Python module
├── openpyxl/             # Python module
├── README.md             # Project documentation
├── datetime.py           # Python module
├── notebook_xlsx.py      # Main application script
├── os.py                 # Python module
└── requirements.txt      # Required dependencies
```

## How It Works

- The application uses the `openpyxl` library to create and manipulate `.xlsx` files programmatically.
- Notes are stored in rows, with each note associated with a date column.
- You can perform standard operations like adding, viewing, updating, and deleting notes, all without relying on external spreadsheet software.


## License

This project is licensed under the MIT License.

## Acknowledgments

- Built with Python and open-source libraries.
- Inspired by the need for lightweight, software-independent note management.

---

Happy note-taking with **Notebook-xlsx**! 🎉

