# Text Editor
This is a simple text editor application built using Python's Tkinter library. It allows users to open, edit, and save text files with ease.

## Features
* **Open Files:** Open and view text files (.txt) within the editor.
* **Save Files:** Save the current text to a new or existing file.
* **Keyboard Shortcuts:**
    * Ctrl + S: Save the current file.
    * Ctrl + O: Open a file.
      
## Requirements
* Python 3.x
* Tkinter (usually included with Python installations)
  
## Usage
1. Clone or download this repository to your local machine.

2. Ensure you have Python installed on your system.

3. Run the script using Python:
  *python text_editor.py*
   
4. Use the "Open" button to select a text file to view and edit.

5. Use the "Save" button to save your changes to a file.

6. You can also use the keyboard shortcuts for quick access to open and save functionalities.

## Code Overview
### Functions:

* open_file(window, text_edit): Opens a file dialog to select and load a text file into the editor.
* save_file(window, text_edit): Opens a file dialog to save the current content to a file.
* main(): Sets up the Tkinter window, layout, and binds functions to buttons and shortcuts.
  
### Widgets:

* Text: The main text area for editing.
* Button: Buttons for opening and saving files.
* Frame: Container for organizing buttons.
  
## Customization
* Adjust the font size and style by modifying the font parameter in the tk.Text widget.
* Change the default window size by modifying the rowconfigure and columnconfigure settings.
