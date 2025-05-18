# LexVi: An Interactive Lexical Analyzer Tool

LexVi is a Python-based desktop application that provides an interactive environment for lexical analysis of code. It features a modern GUI interface, real-time syntax highlighting, and visualization capabilities for understanding the tokenization process.

## Features

- Modern GUI interface built with PyQt5
- Real-time syntax highlighting
- Interactive tokenization with step-by-step execution
- Visualization of token stream and automata
- Export capabilities (CSV and PDF)
- Error detection and reporting
- Drag-and-drop file support

## Installation

1. Clone the repository:

```bash
git clone https://github.com/yourusername/lexvi.git
cd lexvi
```

2. Create a virtual environment (recommended):

```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. Install dependencies:

```bash
pip install -r requirements.txt
```

## Usage

1. Run the application:

```bash
python main.py
```

2. Enter or paste code into the input area
3. Use the control buttons to:
   - Run: Perform complete tokenization
   - Step-by-Step: Execute tokenization one step at a time
   - Pause: Pause the current execution
   - Export CSV: Save tokens to a CSV file
   - Export PDF: Save tokens to a PDF file

## Project Structure

```
lexvi/
├── lexer/
│   └── core.py          # Core lexer functionality
├── gui/
│   └── main_window.py   # GUI implementation
├── visualizer/
│   └── automata.py      # Visualization components
├── tests/
│   └── test_lexer.py    # Unit tests
├── main.py              # Application entry point
├── requirements.txt     # Dependencies
└── README.md           # Documentation
```

## Testing

Run the test suite using pytest:

```bash
pytest tests/
```

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## Role and Responsibility

- **Member 1**: Lead Developer - Oversees the overall development process, ensures code quality, and manages the project timeline.
- **Member 2**: UI/UX Designer - Designs the user interface and ensures a seamless user experience.
- **Member 3**: Tester - Conducts thorough testing to identify bugs and ensure the application meets the requirements.

## Updated Workflow/Architecture

The project follows an agile development workflow with regular sprints and daily stand-ups. The architecture is modular, allowing for easy integration of new features and scalability.

## Technical Progress

- Implemented core lexer functionality.
- Developed a modern GUI interface using PyQt5.
- Integrated real-time syntax highlighting and tokenization features.
- Added visualization capabilities for token stream and automata.

## Screenshots/Code Snippets

[Add screenshots or code snippets here]

## Role-wise Contributions

- **Member 1**: Implemented core lexer functionality and managed the project timeline.
- **Member 2**: Designed the user interface and improved user experience.
- **Member 3**: Conducted extensive testing and identified critical bugs.
