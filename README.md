# Quadratic Functions Viewer

A simple, elegant web application to explore and copy various quadratic functions. This tool is designed for educators, students, or developers who need a quick source of quadratic equations for testing or practice.

## Features

- **Random Generation**: Quickly cycle through a large collection of quadratic equations.
- **Math Rendering**: Beautifully rendered equations using KaTeX for a professional look.
- **One-Click Copy**: Easily copy the raw equation string to your clipboard for use in other applications.
- **Responsive Design**: A clean, modern interface that works on both desktop and mobile devices.
- **Dynamic Loading**: Fetches equations directly from a JSONL data source.

## Project Structure

- `index.html`: The core application built with Vue 3, providing the interactive UI and logic. It fetches data from `quad_func_list.jsonl`.
- `quad_func_list.jsonl`: The primary data source containing the list of functions in JSON Lines format.
- `data.js`: (Deprecated) Previously used as a JavaScript data source.

## Built With AI

This project was developed with the assistance of:

- **Aider**: The AI pair programming tool for the terminal.
- **Gemini 3 Flash**: The large language model used to generate the code and documentation.

---
*Happy Mathing!*
