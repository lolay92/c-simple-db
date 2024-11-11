# Simple Database Management System in C

A lightweight command-line database system that demonstrates fundamental C programming concepts including file I/O, memory management, and data structures.

## Features

- Create new databases
- Add records with name and email
- Retrieve records by ID
- Delete records
- List all records
- Persistent storage using file I/O

## Technical Details

- Written in C
- Fixed-size records (512 bytes per field)
- Maximum 100 records per database
- Basic error handling
- Memory management with malloc/free
- File operations using fread/fwrite

## Usage

```bash
./database <dbfile> <action> [action params]
