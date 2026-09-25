# **File Handling**

File handling refers to the process of performing operations on a file, such as creating, opening, reading, writing and closing it through a programming interface. It involves managing the data flow between the program and the file system on the storage device, ensuring that data is handled safely and efficiently.

**Need for File Handling**

- Store data permanently, even after the program ends.
- Access external files like .txt, .csv, .json, etc.
- Process large files efficiently without using much memory.
- Automate tasks like reading configs or saving outputs.

## **Opening a File**

To open a file, we can use open() function, which requires file-path and mode as arguments.

**Syntax:**

`file = open('filename.txt', 'mode')`

- **filename.txt:** name (or path) of the file to be opened.
- **mode:** mode in which you want to open the file (read, write, append, etc.).

## **Closing a File**

file.close() method closes the file and releases the system resources. If the file was opened in write or append mode, closing ensures that all changes are properly saved.

## **Checking File Properties**

Once the file is open, we can check some of its properties like filename, mode etc.

## **Reading a File**

Reading a file can be achieved by file.read() which reads the entire content of the file. After reading, it’s good practice to close the file to free up system resources.

## **Writing a File**

Writing to a file is done using the mode "w". This creates a new file if it doesn’t exist, or overwrites the existing file if it does. The write() method is used to add content. After writing, make sure to close the file.

## **Using with Statement**

Instead of manually opening and closing the file, you can use the with statement, which automatically handles closing. This reduces the risk of file corruption and resource leakage.

## **Handling Exceptions When Closing a File**

It's important to handle exceptions to ensure that files are closed properly, even if an error occurs during file operations. Here, the finally block ensures the file is closed even if an error occurs.
