#!/bin/bash

cat <<EOF > README.md
# User authentication service

This project adheres to the specified requirements for execution, documentation, and style.

## Requirements

- **Editors:** Allowed editors include vi, vim, and emacs.
- **Environment:** All files will be interpreted/compiled on Ubuntu 18.04 LTS using python3 (version 3.7).
- **Line Endings:** All files should end with a new line.
- **File Declaration:** The first line of all files should be exactly \`#!/usr/bin/env python3\`.
- **README:** A README.md file at the root of the project folder is mandatory.
- **Code Style:** The code should adhere to the pycodestyle style (version 2.5).
- **SQLAlchemy:** Version 1.3.x of SQLAlchemy is required.
- **Executable Files:** All files must be executable.
- **File Length:** File length will be tested using \`wc\`.
- **Module Documentation:** All modules should have documentation (\`python3 -c 'print(__import__("my_module").__doc__)'\).
- **Class Documentation:** All classes should have documentation (\`python3 -c 'print(__import__("my_module").MyClass.__doc__)'\).
- **Function Documentation:** All functions (inside and outside a class) should have documentation (\`python3 -c 'print(__import__("my_module").my_function.__doc__)'\` and \`python3 -c 'print(__import__("my_module").MyClass.my_function.__doc__)'\`).
- **Documentation Quality:** A documentation is not a simple word, it’s a real sentence explaining the purpose of the module, class, or method (the length of it will be verified).
- **Type Annotations:** All functions should be type annotated.
- **Flask App Interaction:** The Flask app should only interact with Auth and never with DB directly.
- **Public Methods:** Only public methods of Auth and DB should be used outside these classes.

## Execution

To execute the project, ensure you have the required environment (Ubuntu 18.04 LTS with Python 3.7). Follow these steps:

1. Set up the environment with Python 3.7.
2. Install SQLAlchemy version 1.3.x.
3. Ensure the files are executable using appropriate permissions.
4. Run the Flask app using the designated entry points or methods provided by Auth.

## File Structure

- **/folder_name:** Description of contents in this folder.
  - \`file.py\`: Description of the file.
  - \`another_file.py\`: Description of the file.
- **README.md:** This file, detailing project specifications, setup, and execution instructions.

## Documentation

For detailed documentation of modules, classes, and functions, refer to the docstrings within the codebase. Use commands like \`python3 -c 'print(__import__("my_module").my_function.__doc__)'\` to access function and class descriptions.
EOF

