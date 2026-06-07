# Java Recursive File Explorer

A simple Java program that calculates the size of a folder and shows everything inside it. It uses **recursion** to look inside folders that are hidden inside other folders.

## What It Does
* Shows a visual list of your files and folders.
* Looks deep inside nested folders automatically.
* Calculates the exact total size of the folder in Megabytes (MB).

## How to Run It
1. Download or copy the `FileExplorer.java` file.
2. Open your terminal or command prompt.
3. Compile the code:
   ```bash
   javac FileExplorer.java
   ```
4. Run the program:
   ```bash
   java FileExplorer
   ```
5. Paste any folder path from your computer (like `C:\Users\Name\Documents`) and press Enter!

## Example Output
```text
Enter a directory path: C:\MyFolder

Exploring files...
📁 [MYFOLDER]
  📄 note.txt (1500 bytes)
  📁 [IMAGES]
    📄 photo.png (2500 bytes)

Total Directory Size: 0.00 MB
```
