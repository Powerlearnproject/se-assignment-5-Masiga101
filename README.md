[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/XoLGRbHq)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15442856&assignment_repo_type=AssignmentRepo)

# SE-Assignment-5
Installation and Navigation of Visual Studio Code (VS Code)

## Instructions:
Answer the following questions based on your understanding of the installation and navigation of Visual Studio Code (VS Code). Provide detailed explanations and examples where appropriate.

## Questions:

### 1. Installation of VS Code:
- **Describe the steps to download and install Visual Studio Code on Windows 11 operating system. Include any prerequisites that might be needed.**
  1. Go to the [Visual Studio Code download page](https://code.visualstudio.com/Download).
  2. Select the Windows download option.
  3. Once the installer is downloaded, open the `.exe` file.
  4. Follow the installation prompts:
     - Accept the agreement.
     - Select the destination folder.
     - Choose additional tasks (e.g., creating a desktop icon).
     - Click 'Install'.
  5. Once installation is complete, launch Visual Studio Code.

### 2. First-time Setup:
- **After installing VS Code, what initial configurations and settings should be adjusted for an optimal coding environment? Mention any important settings or extensions.**
  1. **Theme and Appearance:**
     - Go to `File > Preferences > Color Theme` and choose a theme.
  2. **Extensions:**
     - Open the Extensions view by clicking on the Extensions icon in the Activity Bar or pressing `Ctrl+Shift+X`.
     - Install essential extensions such as:
       - `Prettier - Code formatter`
       - `ESLint`
       - `Live Server`
       - `Python` (if applicable)
  3. **Settings:**
     - Go to `File > Preferences > Settings` or press `Ctrl+,`.
     - Adjust settings such as font size, line height, and enabling format on save.

### 3. User Interface Overview:
- **Explain the main components of the VS Code user interface. Identify and describe the purpose of the Activity Bar, Side Bar, Editor Group, and Status Bar.**
  - **Activity Bar:** Located on the far left, it allows you to switch between views and gives access to views like Explorer, Search, Source Control, and Extensions.
  - **Side Bar:** Displays different views and lists depending on the Activity Bar selection, such as file explorer or source control changes.
  - **Editor Group:** The main area where you edit your files. You can open multiple files in tabs and split the editor into multiple panes.
  - **Status Bar:** Located at the bottom, it shows information about the opened project, such as file type, encoding, Git branch, and errors or warnings.

### 4. Command Palette:
- **What is the Command Palette in VS Code, and how can it be accessed? Provide examples of common tasks that can be performed using the Command Palette.**
  - The Command Palette provides quick access to many commands and features. It can be accessed by pressing `Ctrl+Shift+P` or `F1`.
  - Examples of tasks:
    - Opening a file: `Ctrl+P`
    - Running a task: `> Run Task`
    - Formatting the current document: `> Format Document`

### 5. Extensions in VS Code:
- **Discuss the role of extensions in VS Code. How can users find, install, and manage extensions? Provide examples of essential extensions for web development.**
  - Extensions enhance the functionality of VS Code, adding support for languages, debuggers, and tools.
  - Users can find and install extensions from the Extensions view (`Ctrl+Shift+X`). 
  - Examples of essential web development extensions:
    - `Prettier - Code formatter`
    - `ESLint`
    - `Live Server`
    - `Debugger for Chrome`

### 6. Integrated Terminal:
- **Describe how to open and use the integrated terminal in VS Code. What are the advantages of using the integrated terminal compared to an external terminal?**
  - Open the integrated terminal by selecting `View > Terminal` or pressing `Ctrl+``.
  - Advantages:
    - Directly integrated into the IDE, keeping the workflow seamless.
    - Easily access project files and execute commands without switching windows.

### 7. File and Folder Management:
- **Explain how to create, open, and manage files and folders in VS Code. How can users navigate between different files and directories efficiently?**
  - Create a new file or folder by right-clicking in the Explorer view and selecting `New File` or `New Folder`.
  - Open files by dragging them into the editor or using `Ctrl+O`.
  - Navigate between files using `Ctrl+P` to quickly open files by name.

### 8. Settings and Preferences:
- **Where can users find and customize settings in VS Code? Provide examples of how to change the theme, font size, and keybindings.**
  - Access settings via `File > Preferences > Settings` or `Ctrl+,`.
  - Change theme: `File > Preferences > Color Theme`.
  - Change font size: Search for `Editor: Font Size` in settings.
  - Change keybindings: `File > Preferences > Keyboard Shortcuts` or `Ctrl+K Ctrl+S`.

### 9. Debugging in VS Code:
- **Outline the steps to set up and start debugging a simple program in VS Code. What are some key debugging features available in VS Code?**
  1. Open your project folder in VS Code.
  2. Set breakpoints by clicking in the gutter next to the line numbers.
  3. Open the debug view by clicking on the Debug icon in the Activity Bar.
  4. Click on the gear icon to configure the debugger.
  5. Select the appropriate configuration and press `F5` to start debugging.
  - Key features:
    - Breakpoints, watch variables, call stack, and integrated terminal.

### 10. Using Source Control:
- **How can users integrate Git with VS Code for version control? Describe the process of initializing a repository, making commits, and pushing changes to GitHub.**
  1. Open your project folder in VS Code.
  2. Initialize a repository: `View > Source Control` and click on `Initialize Repository`.
  3. Stage changes by clicking the `+` icon next to the files.
  4. Commit changes by writing a commit message and clicking the checkmark icon.
  5. Push changes by opening the terminal and running:
     ```bash
     git remote add origin <repository-url>
     git push -u origin master
     ```

## Submission Guidelines:
- Your answers should be well-structured, concise, and to the point.
- Provide screenshots or step-by-step instructions where applicable.
- Cite any references or sources you use in your answers.
- Submit your completed assignment by 1st July.
