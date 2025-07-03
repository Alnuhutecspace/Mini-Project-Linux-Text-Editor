# Mini-Project-Linux-Text-Editor 

## Linux Text Editors 

A linux text editor is a software application specifically designed for creating, modifying and managing text files on a Linux-based operating system. Text editors play a crucial role in the Linux environment, providing a means for users to interact with and manipulate plain text-based documents.

Linux offers a wide variety of text editors, ranging from simple command-line tools to sophisticated graphical interfaces. Popular choices include Vim, Nano, Emacs, Gedit, and Visual Studio Code (VS Code). Vim and Nano are commonly used for command-line editing, while Gedit and VS Code provide graphical user interfaces. 

## VIM Text Editor 

The vi editor is installed on almost every Unix. Linux will very often install vim (vi improved) which is similar. Every system administrator should know vi(m), because it is an easy tool to solve problems. The vi editor is not intuitive, but once you get to know it, vi becomes a very powerful application. Most Linux distributions will include the vimtutor which is a 45 minute lesson in vi(m). While Vim has a steeper learning curve compared to simpler editors like Nano, its capabilities make it a favourite among tech professionals and anyone working extensively with text files. 

## Working With Vim Editor 

Let get start with vim 

- **Open a new file:** named "exercise.txt" using the command:

![Open New File](./img/01.%20Open%20New%20File.png) 

The command above creates a "exercise.txt" even if it doesn't exist. Then it opens the file up so that we can start writing into it. Its just like opening Notepad file on Windows. 

![Opens](./img/02.%20Opens.png)

- **Enter Insert Mode:** to edit the file.

    - Press 'i' to enter insert mode.

    - Type the following text into file:

- **Moving Around:** Navigate through the text using the arrow keys or h (left), j (down), k (up) and l (right).

![Insert and Navigate](./img/03.%20Insert%20and%20Navigate.png)    

- **Deleting a Character:** Press 'esc' on the keyboard to exit the 'insert mode'. Position the cursor on a character you want to delete and press x. 

![Character Deleted](./img/04.%20Character%20Deleted.png) 

- **Deleting a Line:** To delete an entire line in the file, ensure that you are not in the 'insert mode'. If you are press 'esc' key as above. Then, place the cursor on a line, and press **d** twice on the keyboard to delete the entire line. 

![Line Deleted](./img/05.%20Line%20Deleted.png) 

- **Undoing Changes:** Make a change (add or delete text) in Insert or Normal Mode, then press 'esc' to enter press u to undo the last change. 

![Undoing Changes](./img/06.%20Undoing%20Change.png) 

- **Saving Changes:** After finish writing into the file, press 'esc', then type **:wq** and press Enter. This will save the file. 'w' means **write** and 'q' means **quit** which basically quits the vim mode and returns back to the terminal. 

![Saving Changes](./img/07.Saving%20Changes.png) 

- **Quitting and Saving:** Incase you do not intend to save the file, simply press 'esc' then **:q!** and press Enter to quit without saving changes. 

## Nano Text Editor 

GNU nano is a user-friendly, command-line text editor, primarily used on Unix-like systems. It's known for its simplicity and ease of use, making it a good choice for beginners or for quick edits in a terminal environment. It emulates the Pico text editor and includes features like syntax highlighting, search and replace, and auto-indentation. 
Nano serves as a versatile and lightweight text editor, ideal for performing quick edits, writing scripts, or making configuration changes directly from the command line, its intuitive command set simplifies text manipulation tasks, allowing users to navigate through the files, insert or delete text, and save changes effortlessly. Nano's ease of use extends to its keyboard shortcuts, making it accessible even to those unfamiliar with intricate command sequences. With Nano, users can focus on the content of their text files without distraction of a complex interface, making it a go-to choice for a wide range of users, from beginners to experienced Linux enthusiasts. 

## Working With Nano Editor 

- **Opening a File:** name "nano_project.txt" using the following command: 

![Terminal Command](./img/08.%20Terminal%20Command.png) 

![OPens](./img/09.%20Opens.png)

You will enter Nano editor interface. 

- **Entering and Editing:** Type a few lines of of text into the file. Nano has a simple interface, and you can start typing immediately. 

- **Saving Changes:** Save your changes by pressing 'Ctrl' + 'O'. Nano will prompt you to confirm the filename; press 'Enter' to confirm. 

- **Exiting Nano:** If you wish to exit nano without saving the file, simply press 'Ctrl' + 'X'. If you have unsafe changes. Nano will prompt you to save before exiting. 

![Naming the File](./img/10.%20Naming%20the%20File.png) 

![Editing, Saving, and Saving](./img/11.%20Editing,%20Saving,%20%20and%20Exiting.png)

- **Opening an Existing File:** I Open an empty existing file and write into it and save the content of the file. 

![Existing File](./img/12.%20Exixting%20File.png) 
