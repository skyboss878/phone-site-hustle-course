**[VIDEO INTRO - Clean, technical music. Graphics showing a simple command line interface, text flowing, and file structures. You look clear and instructive.]**

Welcome back, Phone Site Hustlers! We've talked about your phone as a powerhouse and the essential apps. Now, let's demystify one of the most powerful tools in your arsenal, especially for organization: **the terminal emulator.**

For Android users, this is typically **Termux**. For iOS, while a full terminal is restricted, you'll still interact with file systems in a similar conceptual way through file management apps and cloud services. This lesson will focus on core concepts and practical commands that empower you to manage your course files and future project files directly from your phone.

Don't be intimidated! We're only covering the essentials you need for our course and your hustle.

---

### **Why the Terminal?**

* **Direct Control:** The quickest way to create, move, or delete files and folders.
* **Efficiency:** Faster than tapping through menus for file management.
* **Understanding Structure:** Helps you grasp how your files are organized, which is key for web projects.

---

### **Key Terminal Commands You'll Use**

Let's break down the essential commands. **Practice these as you learn them!**

1.  **`pwd` (Print Working Directory)**
    * **What it does:** Shows you your current location (directory/folder) in the file system.
    * **When to use:** Whenever you're lost or unsure where you are.
    * **Example:**
        ```bash
        pwd
        # Output: /data/data/com.termux/files/home
        ```
    * **Action:** Type `pwd` and see your current directory.

2.  **`ls` (List)**
    * **What it does:** Lists the contents (files and folders) of the current directory.
    * **When to use:** To see what's in a folder.
    * **Example:**
        ```bash
        ls
        # Output: phone-site-hustle-course  Scratchpad
        ```
    * **Action:** Type `ls` to see what's in your current directory.
    * **Useful variations:**
        * `ls -l`: Lists with more details (permissions, size, date).
        * `ls -a`: Shows all files, including hidden ones.

3.  **`cd` (Change Directory)**
    * **What it does:** Moves you into a different directory.
    * **When to use:** To navigate between your project folders.
    * **Examples:**
        * **Go into a folder:**
            ```bash
            cd phone-site-hustle-course
            # Your prompt might change to ~/phone-site-hustle-course $
            ```
        * **Go up one level:**
            ```bash
            cd ..
            ```
        * **Go to your home directory (anywhere):**
            ```bash
            cd ~
            # Or just 'cd' by itself
            ```
        * **Go to a specific path (absolute path):**
            ```bash
            cd /data/data/com.termux/files/home/phone-site-hustle-course/CourseContent/Module01_MobileStudio
            ```
    * **Action:** Practice moving into and out of your `phone-site-hustle-course` directory.

4.  **`mkdir` (Make Directory)**
    * **What it does:** Creates a new empty directory (folder).
    * **When to use:** To organize your course content or client projects.
    * **Example:**
        ```bash
        mkdir NewClientProject
        ```
    * **Useful variations:**
        * `mkdir -p path/to/new/directory`: Creates parent directories if they don't exist. This is what we used for your module structures!
            ```bash
            mkdir -p CourseContent/Module01_MobileStudio/Lessons
            ```
    * **Action:** Create a temporary test folder: `mkdir mytestfolder`.

5.  **`rm` (Remove)**
    * **What it does:** Deletes files.
    * **When to use:** To clean up old files. **Be careful! This is permanent!**
    * **Example:**
        ```bash
        rm unwanted_file.txt
        ```
    * **Useful variations:**
        * `rm -r directoryname`: Deletes a directory and its contents recursively. **Use with extreme caution!**
            ```bash
            rm -r mytestfolder # Deletes the folder and anything inside it
            ```
    * **Action:** Delete the test folder you just created: `rm -r mytestfolder`.

6.  **`mv` (Move)**
    * **What it does:** Moves a file or directory from one location to another. Also used to rename!
    * **When to use:** Organizing files, renaming module folders.
    * **Examples:**
        * **Rename a file:**
            ```bash
            mv oldname.txt newname.txt
            ```
        * **Rename a directory:**
            ```bash
            mv OldModuleName NewModuleName
            ```
        * **Move a file to a different directory:**
            ```bash
            mv myfile.txt NewFolder/myfile.txt
            # Or if you're already in NewFolder: mv ../myfile.txt .
            ```
    * **Action:** Don't practice this with your actual course files yet, but understand its function.

7.  **`nano` (Text Editor)**
    * **What it does:** Opens a simple text editor directly in the terminal to create or edit files.
    * **When to use:** Editing lesson files, quick code tweaks.
    * **Example:**
        ```bash
        nano myfirstfile.txt
        ```
    * **Action:** We've used this extensively. Remember `Ctrl+O` to Save, `Enter`, `Ctrl+X` to Exit.

---

### **Putting It All Together: Your File Structure**

Remember your course's structure:

