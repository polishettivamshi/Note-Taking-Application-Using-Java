# Note-Taking-Application-Using-Java

**NOTE TAKING APPLICATION**

**1.	Title:** 
Note Taking Application - Java GUI Implementation.

**2.	Description:**
The Note Taking Application is a Java-based graphical user interface (GUI) program that allows users to create, save, and load text notes. The application provides an intuitive interface with menu options for managing notes and folders.

**3.	Key Features:**
Create new notes: Users can start a new note by selecting the "New" option from the File menu. This clears the text area, allowing users to enter fresh content.
Save notes: Users can save their notes to a file by selecting the "Save" option from the File menu. A file chooser dialog is presented to select the desired save location and file name.
Load notes: Users can load previously saved notes by selecting the "Load" option from the File menu. A file chooser dialog is displayed to select the note file, which then populates the text area with the loaded content.
Folder creation: The application allows users to create folders for organizing their notes. The "Create Folder" option in the File menu prompts users to enter a folder name, and a new folder is created in the current directory.

**4	Libraries and Components Used:**
javax.swing: Utilized Swing components to create the GUI, including JFrame, JTextArea, JScrollPane, JMenuBar, JMenu, and JMenuItem.
java.awt: Used the AWT BorderLayout for arranging components within the JFrame.
java.awt.event: Implemented ActionListener to handle user interactions with menu options.
java.io: Utilized BufferedReader, BufferedWriter, FileReader, and FileWriter for reading and writing           text files.
java.nio.file: Used Files, Path, and Paths for folder creation and file operations.

**5.	Code Organization:** 
The code follows a class-based structure. The main class, NoteTakingApplication, extends JFrame to create the application window. It contains methods for handling user actions, such as saving and loading files, creating folders, and managing the GUI components.

**6.	Error Handling:**
7The application includes error handling mechanisms for file operations. In case of errors during file save or load operations, error messages are displayed using JOptionPane to inform the user about the encountered issues.

