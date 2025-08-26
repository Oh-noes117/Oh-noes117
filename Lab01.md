## Lab 01

- Name: William Brinkman
- Email: brinkman.48@wright.edu

## Part 1 - GitHub Profile

1. https://github.com/Oh-noes117

## Part 2 - Research

| Windows | Linux / Mac | Action |
| ---     | ---         | ---    |
| help    | man         |Lists Possible commands |
| Get-Location | pwd    |Dispalys the current Path        |
| Get-ChildItem | ls    |Displays all the folders and files in the current path        |
| mkdir   | mkdir       |Create a new Directory (Folder)        |
| Set-Location | cd     |Change the current Path (Directory)        |
| New-Item | touch      |Create a new File        |
| Move-Item | mv        |Move a File to a new Location       |
| Copy-Item | cp        |Copy a File to a new Location        |
| Remove-Item | rm      |Delete a file        |
| notepad.exe | vim     |Execute Notepad.exe        |

## Part 3 - Command Line Navigation

My OS is:
- [x] Windows
- [] Linux
- [] Mac

My Command Line Shell is: Windows PowerShell, but trying out WSL.

### Navigating My OS on the Command Line

1. Full / absolute path to your user's home directory: **Get-Location**
2. Create a directory named `DirA`: **mkdir DirA**
3. Create a directory named `Dir B`: **mkdir "Dir B"**
4. Go into `DirA`: **cd DirA**
5. Go into `Dir B` from `DirA`: **cd "..\Dir B"**
6. Return to your user's home directory: **cd ..**
7. Create a file named `test.txt`: **New-Item test.txt**
8. Move the file named `test.txt` into `DirA`: **Move-Item test.txt DirA**
9. Contents of `test.txt`: **notepad test.txt**
```
**Hello World!**
```
10. Make a copy of `test.txt` named `copy.txt` in `DirA`: **copy test.txt copy.txt**
11. View the contents of `DirA`: **ls**
12. Make a copy of `test.txt` in `Dir B` named `fodder.txt`: **copy test.txt "C:\Users\Will\Dir B\fodder.txt"**
13. Delete / remove both `fodder.txt` AND `Dir B`: **rm fodder.txt**, **cd ..**, **rm "Dir B"**

## Citations

-Used Google for the correct syntax needed to make a Directory with a space in it.  
