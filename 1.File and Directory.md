## Linux directory and file creation

## 📂 Directory Creation
mkdir – Create a Directory
Creates a new directory.
```
mkdir mydir
```
➡️ Creates a directory named mydir.

Creates more than one directory at a time.
```
mkdir dir1 dir2 dir3
```
Create Parent Directories (-p)

Creates parent directories if they do not exist.
```
mkdir -p project/src/main
```
➡️ Creates project, src, and main directories together.


Set Permissions While Creating Directory
Creates a directory with specific permissions.
```
mkdir -m 755 secure_dir
```

## 📄 File Creation
## touch – Create an Empty File

Creates an empty file or updates timestamp if file exists.
```
touch file.txt
```
🔹 Create Multiple Files

Creates multiple files at once.
```
touch file1.txt file2.txt file3.txt
```
🔹 Create File Using Redirection

Creates a file and adds content.
```
echo "Hello Linux" > hello.txt
```
🔹 Append Content to a File

Adds content without overwriting.
```
echo "Welcome to Linux" >> hello.txt
```
🔹 Create File Using cat

Creates a file and allows typing content.
```
cat > notes.txt
```

(Press CTRL + D to save)

 Verify File and Directory Creation
🔹 List Files and Directories
```
ls
```
🔹 Long Listing Format

```
ls -l
```
🔹 Show Hidden Files
```
ls -a
```
 Remove Created Files and Directories (Optional)
🔹 Remove File
```
rm file.txt
```
🔹 Remove Empty Directory
```
rmdir mydir
```
🔹 Remove Directory with Content
```
rm -r project
```
