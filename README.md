#  📁 Project Structure Generator

**🛠️ A Python Script to Automatically Generate Project Folder Structures**

##  📌 Overview

This lightweight Python CLI tool allows developers to **automatically generate and visualize project folder structures** with a single command. Simply type `structure` in your terminal to get a clean, Markdown-formatted tree of your current directory — while excluding any files or folders you don't want included.

It’s perfect for documenting repositories, planning architecture, and kickstarting new projects with consistency.

---

## Features

- **One-Command Execution**: Generate folder structure instantly with `structure`.
- **Custom Ignore List**: Skip files or folders you don’t want in the output.
- **Virtual Environment Awareness**: Optionally include/exclude virtual environment folders.
- **Markdown Format**: Outputs a clean, shareable structure for your README or documentation.
- **Easy Setup**: No external libraries or complex dependencies.

---

## Technology Stack

- **Programming Language**: Python 🐍
- **Execution Mode**: Command-Line Interface (CLI)
- **Output Format**: Markdown (`.md`)

---

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Madhur-Prakash/Folder-Structure-Creator.git
   ```
2. Navigate to the project directory:
   ```bash
   cd Folder-Structure-Creator
   ```
3. Add the Folder Path to System Environment Variables:

- Copy the full path of the cloned folder.
- Go to System Properties → Environment Variables → Path → Add New → Paste the path.

4. Restart Your System or Terminal for the changes to apply.

---

## Usage

1. Open any directory in your terminal.

2. Run the command:
   ```bash
   structure
   ```
3. Input Prompts:
- Enter the name of your virtual environment (if any).
- Enter comma-separated file or folder names you wish to exclude.

4. Output:
- A Markdown-style folder structure will be saved in the `current working directory`

---

## Project Structure
```plaintext
folder structure creator/
├── Readme.md       # Project documentation
└── structure.py    # main logic
```
---
## Future Enhancements
- 📝 Auto-generate an entire README.md based on the project structure.
- 🌐 Web-based interface for drag-and-drop structure creation.
- 📊 Integrate analytics for folder usage suggestions in real-time.
---

## 🤝 Contribution Guidelines

Contributions are welcome! To contribute:
1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Commit your changes and submit a pull request.
---

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## Author
**Madhur Prakash**  
[GitHub](https://github.com/Madhur-Prakash) | [Medium](https://medium.com/@madhurprakash2005)

---