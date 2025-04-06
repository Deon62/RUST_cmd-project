
# 🔍 minigrep

**minigrep** is a tiny command-line tool written in Rust that searches for a string in a file — just like the classic `grep` tool.

This project is inspired by [The Rust Programming Language Book](https://doc.rust-lang.org/book/) (Chapter 12), and is meant to demonstrate 
basic Rust concepts like error handling, file I/O, and command-line arguments.

---

## 🚀 Features

- Search for a keyword in a file
- Prints all matching lines
- Simple, beginner-friendly code structure
- Includes unit tests

---

## 🛠️ Usage

```bash
cargo run -- <query> <file_path>
```

Example:

```bash
cargo run -- rust poem.txt
```

This will search for the word `rust` in the file `poem.txt`.

---

## 🧪 Run Tests

```bash
cargo test
```

---

## 📚 Concepts Practiced

- Working with command-line arguments (`std::env`)
- Reading files with `std::fs`
- Error handling with `Result` and `unwrap_or_else`
- Writing modular, testable Rust code

---

## 📁 Project Structure

- `main.rs`: Entry point, handles CLI and runs the program
- `lib.rs`: Core logic (parsing, searching, testing)

---

## 📦 Future Improvements

- Add case-insensitive search
- Support regex
- Add colored output

---

Feel free to fork, play around, or suggest improvements!
