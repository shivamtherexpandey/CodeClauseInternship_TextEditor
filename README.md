# CodeClauseInternship_TextEditor

This Python code defines a basic text editor application using the Tkinter library, allowing users to create, open, edit, save, and clear text files. Here's a breakdown of its functionality:

1. **Imports:**
   - It imports the necessary modules, primarily `tkinter` for the graphical user interface (GUI) and `filedialog` for file-related operations.

2. **Class `TextEditor`:**
   - The constructor (`__init__`) initializes the GUI window (`root`) and sets its title as "Text Editor".
   - Creates a text widget using `tk.Text` to display and manipulate text.
   - Calls the method `create_menu()` to generate the menu bar with various options.

3. **Methods:**
   - `create_menu`: Creates a menu bar within the GUI window, containing options for file operations (open, save, exit) and edit operations (clear).
   - `open_file`: Opens a file dialog to select a text file, reads its contents, and displays the text within the text widget. Updates the window title to reflect the opened file.
   - `save_file`: Opens a file dialog to specify a file path for saving the text currently present in the text widget.
   - `clear_text`: Clears all text content from the text widget.

4. **Main Section (`__name__ == "__main__"`):**
   - Creates the Tkinter window (`root`).
   - Instantiates the `TextEditor` class, which sets up the text editor interface within the Tkinter window.
   - Starts the main event loop (`root.mainloop()`) to run the application, enabling user interaction with the GUI elements.

Overall, this code provides a simple text editor interface where users can interactively open, edit, save, and clear text files using a basic Tkinter-based graphical user interface.

![image](https://github.com/shivamtherexpandey/CodeClauseInternship_TextEditor/assets/95215534/e24039b3-c05e-4ad6-8795-5e3e20249e2d)

