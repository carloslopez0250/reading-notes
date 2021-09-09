## **Terminal Set Up**


 ## **Terminal Uses**
     -  Find Files
     -  Change Directories
     -  Move and Copy Files
     -  Open Files
     -  Make New Files/Folders and **MUCH MORE!**

## **Terminal Commands (cheat sheet)**
     - pwd - present working directory
     - cd - change directory ( .. goes back. Just the name of the folder in that directory will take you into it cd myFolder
     - ls - list all files in current directory
     - mkdir - make a new directory
     - touch myFile.txt - Create a new file named myFile.txt
     - mv (location and name of file) (new location and file name) - move file from one location to another
     - cp (location and name of file) (new location and file name) - copy file from one location to another
     - clear - clears your console screen
     - less myText.txt - outputs the text from the file onto the console (thanks Marni!)
     - cd .. move back one directory
     - mv myfile.txt ..\myFolder move the myfile.txt to the folder named myFolder in the parent directory  
     
     
 ##  **Command Line Reading**
     - Prompts (user@bash)
     - Command (ls)
     - The output from running the command
     - Prompt again (user@bash)
     - Shell Bash (This is a part of the operating system that defines how the terminal will behave and looks after running (or executing) commands for you.)     
     
     
 ##  **Navigation**
     - Where are we (PWD - Print Work Directory)
     - Whats our current location (ls - list)
          - cd (Current Directory)
          - -l (Long List)
     - Paths
          - Relative (Relative paths specify a location (file or directory) in relation to where we currently are in the system. They will not begin with a slash.)
          
          - Absolute (Absolute paths specify a location (file or directory) in relation to the root directory. You can identify them easily as they always begin with a forward slash ( / ))      
      
          - More on Paths ~ (tilde) - This is a shortcut for your home directory. eg, if your home directory is /home/ryan then you could refer to the directory Documents with the path /home/ryan/Documents or ~/Documents
                          . (dot) - This is a reference to your current directory. eg in the example above we referred to Documents on line 4 with a relative path. It could also be written as ./Documents (Normally this extra bit is not required but in later sections we will see where it comes in handy).
                          .. (dotdot)- This is a reference to the parent directory. You can use this several times in a path to keep going up the hierarchy. eg if you were in the path /home/ryan you could run the command ls ../../ and this would do a listing of the root directory.      
      
      
  ## **More About Files**
     - file (obtain information about what type of file a file or directory is.)
     - ls -a (List the contents of a directory, including hidden files.)    
     - Everything is a file under Linux (Even directories.)
     - Linux is an extensionless system (Files can have any extension they like or none at all.)
     - Linux is case sensitive (Beware of silly typos.)
     
 ## **VS Code Set Up**    
     - Initall Download
     - Extensions for ease of use
     
     
 ## **Text Editors**
     - Preinstalled Text Editors (What's already installed on your computer when you buy it.)
            - On a Mac it's Text Edit
            - On a Windows it's Notepad
            - On Linux each distribution will have it's own text editor
            
     - Third Party Options
            - NotePad ++ (For Windows only)
            - Text Wrangler (For Macs only. Retired in 2017, R.I.P)
            - Bare Bones (Sames as Text Wrangler, but not free)
            - Visual Studio Code (Free Text Editor for EVERYONE! Has Emmet shorthand for HTML and CSS built in. YAY!)
            - Atom (Same as Visual Studio Code. Brought to you by the folks at GitHub. 
            - Brackets (Same as Atom, but only has HTML,CSS, and JavaScript.
            - Sublime Text (Premium software, with all the bells and whistles, for $70.
            
            
     - IDE
            - An IDE (Integrated Development Environment) is really a suite of different software all coming together. An IDE is a text editor, a file manager, a compiler, and a debugger all in one software package. (e.g Microsoft Outlook)
            
     - Things to consider during Text Editor Selection
            - Code Completion/Emmet (Time Saving)
            - Syntax Highlighting (This makes it so much easier when you’re looking for an error and you can’t find it. As well as making your text easier to read.)          
            - A varitey of themes to reduce fatigue. (easier on the eyes)
            - A good selection of extensions for your code flow. (Add functionality as you need it)
            
            
   ## **Thesis** - Go through Several of them and see which one works for you the best.
