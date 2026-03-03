# Library Management System

A simple Library Management System written in Python. This project automates common library tasks such as managing a book catalog, registering members, tracking borrow/return transactions, and calculating fines for late returns. The project uses a SQL file (`librarymanagement.sql`) to define the database schema and sample data.

## Features

- Add, edit, and remove books from the catalog
- Register and manage library members
- Borrow and return books with due-date tracking
- Automatic fine calculation for late returns
- SQLite-compatible SQL schema in `librarymanagement.sql`

## Repository Structure

- `LibraryManagement.py` — main application script
- `librarymanagement.sql` — database schema and sample data
- `README.md` — this file

## Requirements

- Python 3.8 or newer
- SQLite (included with Python) or another SQL database if modified

If the project uses external packages, add them to `requirements.txt` and install with:

```powershell
python -m pip install -r requirements.txt
```

## Setup

1. Place `librarymanagement.sql` in the project folder.
2. (Optional) Create an SQLite database file from the SQL schema:

```powershell
sqlite3 library.db < librarymanagement.sql
```

3. If a database file is required by the script, make sure the script's database path matches `library.db` or update it in `LibraryManagement.py`.

## Running the Application

Run the main script with:

```powershell
python LibraryManagement.py
```

Follow any on-screen prompts or check the top of `LibraryManagement.py` for command-line options.

## Contributing

1. Fork the repository.
2. Create a branch: `git checkout -b feature/YourFeature`.
3. Commit changes: `git commit -m "Add feature"`.
4. Push and open a pull request.

## License

Add a license (for example, MIT) to the project root if you plan to make this public.



