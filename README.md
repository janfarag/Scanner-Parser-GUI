# Scanner-Parser-GUI

## Overview
This project is a GUI-based parser tool for processing Tiny language code. It provides features such as parsing, syntax tree visualization, error handling, and file saving.

## Features
1. **Parsing Tree Generation**: The application parses Tiny language code entered by the user and generates a syntax tree visualization.![photo_2024-12-11_16-52-49](https://github.com/user-attachments/assets/c4353378-c454-423a-b1b1-2e2607f2cbaa)

2. **Bonus Part - Error Handling**:
   - Displays warnings for empty input or invalid Tiny language code.
   - Notifies users of parsing errors such as invalid statements or errors in the parse tree.
   - ![photo_2024-12-11_16-51-47](https://github.com/user-attachments/assets/ee2d15d8-8094-436a-ab95-ac451e8d3fee)
     ![photo_2024-12-11_16-51-53](https://github.com/user-attachments/assets/0cef5944-05fd-4f5d-816a-24519b4414f7)

3. **Auto Scanner**: Converts the user input into tokens automatically.![photo_2024-12-11_16-52-33](https://github.com/user-attachments/assets/ad58f194-361c-4968-9d2e-b5aed1d8892c)

4. **Undo and Redo**: Includes functionality for undoing and redoing actions in the text editor.
5. **File Saving**: Outputs are saved in a predefined directory. The application allows users to save scanned output as text files.![photo_2024-12-11_16-53-14](https://github.com/user-attachments/assets/b67c4958-cdfb-441e-80dd-c343232312df)

6. **Custom Error Messages**: Provides detailed error messages based on program design.

## Directory Structure
- **Source Code**: Located in `Parser\GUIP`.
- **Saved Outputs**: Saved outputs such as syntax tree PNG files and text files are stored in `GUIP\x64\Release\SavedFiles`.

## Prerequisites
- Microsoft Visual Studio with C++/CLI support.
- .NET Framework (for GUI functionality).
- Graphviz (for syntax tree visualization).

## How to Run
1. Install Graphviz.
   ```
   Parser\GUIP\Graphviz.exe
   ```
2. Navigate to the following path to execute the program:
   ```
   Parser\GUIP\x64\Release\GUIP.exe
   ```

## Saved Outputs
All generated outputs such as scanned text files and syntax tree PNG files are saved in the following path:
```
GUIP\x64\Release\SavedFiles
```

## Additional Notes
- Ensure that all required dependencies are installed and available in the system path.
- If the program fails to find necessary DLL files, install the required Microsoft Visual C++ Redistributable packages.
- Graphviz must be installed and added to the system PATH to generate syntax tree PNG files.

