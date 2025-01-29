## Lab 01

- Name:Himani
- Email:himani.3@wright.edu

## Part 1 - GitHub Profile

1. https://github.com/Himanii27

## Part 2 - Research

| Windows       | Linux / Mac | Action                                    |
| ---           | ---         | ---                                       |
| help          | man         | displays help command                     |
| Get-Location  | pwd         | shows the current working directory       |
| Get-ChildItem | ls          | shows the content of the directory        |
| mkdir         | mkdir       | creating a new directory                  |
| Set-Location  | cd          | changes the current directory             |
| New-Item      | touch       | creates a new file                        |
| Move-Item     | mv          | moving file from one directory to other   |
| Copy-Item     | cp          | copy file or directory                    |
| Remove-Item   | rm          | removing or deleting a file/directory     |
| notepad.exe   | vim         | opening editor                            |

## Part 3 - Command Line Navigation

My OS is:
- [x] Windows
- [] Linux
- [] Mac

My Command Line Shell is: PowerShell

### Navigating My OS on the Command Line

1. Create a directory named `DirA`: mkdir DirA
2. Create a directory named `Dir B`: mkdir DirB
3. Go into `DirA`: cd DirA
4. Go into `Dir B` from `DirA`: cd ..    ;
                                cd DirB
5. Return to your user's home directory: cd ~
6. Create a file named `test.txt`: New-Item test.txt
7. Move the file named `test.txt` into `DirA`: Move-Item test.txt DirA\
8. Contents of `test.txt`: 
```
Hello Everyone,
I am Himani
```
9. Make a copy of `test.txt` named `copy.txt` in `DirA`: Copy-Item DirA\test.txt DirA\copy.txt
10. View the contents of `DirA`: Get-ChildItem DirA
11. Make a copy of `test.txt` in `Dir B` named `fodder.txt`: Copy-Item DirA\test.txt DirB\fodder.txt
12. Delete / remove both `fodder.txt` AND `Dir B`: Remove-Item DirB\folder.txt

## Citations
I had a glance at the commands given in this website.
(https://learn.microsoft.com/en-us/powershell/module/microsoft.powershell.management/remove-item?view=powershell-7.5)



