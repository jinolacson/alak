# 🧪 Alak: A Simple Programming Language in Python

**Alak** is a simple interpreted programming language built in Python for educational and experimental purposes. It features a basic compiler, tokenizer, parser, and interpreter pipeline. Alak was designed to help you understand how programming languages work under the hood.

---

## Project Structure
```bash
alak/
├── compiler.py # Entry point for compiling & running Alak files
├── interpreter.py # Evaluates parsed syntax tree
├── parser.py # Converts tokens into an AST
├── token_types.py # Definitions of token types
├── tokenizer.py # Lexical analyzer (lexer)
└── example.alak # Sample Alak program
```

---

## Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/alak.git
cd alak
```

### Run an Alak Program
```bash
python compiler.py example.alak
```
Make sure you have Python 3 installed.

### Example
Here's what an example .alak file might look like:
```bash
let x = 10;
print x + 5;
```

Output:
```bash
15
```

### How It Works
* Tokenizer (tokenizer.py): Breaks source code into tokens.
* Parser (parser.py): Converts tokens into an abstract syntax tree (AST).
* Interpreter (interpreter.py): Walks through the AST and executes commands.
* Compiler (compiler.py): Orchestrates the entire compilation and execution process.

### Future Improvements
Add support for more complex expressions
Implement control flow (if, while, loops)
Add function definitions
Improve error handling

📜 License
MIT License. Feel free to use and modify.