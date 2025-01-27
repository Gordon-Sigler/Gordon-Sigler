## Lab 01

- Name:Gordon Glandon-Sigler
- Email:glandon-sigler.2@wright.edu

## Part 1 - GitHub Profile

1. [Gordon-Sigler Profile](https://github.com/Gordon-Sigler/Gordon-Sigler)

## Part 2 - Research

| Windows | Linux / Mac | Action |
| ---     | ---         | ---    |
| help    | man         |   Bring up a help guide     |
| Get-Location | pwd    |    Shows where you are currently    |
| Get-ChildItem | ls    |   list the content of the dierctory    |
| mkdir   | mkdir       |   Makes a new directory     |
| Set-Location | cd     |    Allows you to change dierectory    |
| New-Item | touch      |   Used to create new Item like files     |
| Move-Item | mv        |  Used to Move items      |
| Copy-Item | cp        |   Used to copy item     |
| Remove-Item | rm      |    Used to remove items    |
| notepad.exe | vim     |   Open notepad     |

## Part 3 - Command Line Navigation

My OS is:
- [x] Windows
- [] Linux
- [] Mac

My Command Line Shell is: 

### Navigating My OS on the Command Line

1. Create a directory named `DirA`: mkdir DirA
2. Create a directory named `Dir B`: mkdir "Dir B"
3. Go into `DirA`: cd DirA
4. Go into `Dir B` from `DirA`: cd .. cd "Dir B"
5. Return to your user's home directory: cd ~
6. Create a file named `test.txt`:New-Item test.txt
7. Move the file named `test.txt` into `DirA`: mv -path .\test.txt -Destination .\DirA
8. Contents of `test.txt`: notepad.exe test.txt to write in it, then cat test.txt will display content.
```
Alright this isn't bad at all just got to stay with it and practice.
```
9. Make a copy of `test.txt` named `copy.txt` in `DirA`: Copy-Item -Path .\test.txt -Destination .\copy.txt
10. View the contents of `DirA`: ls
11. Make a copy of `test.txt` in `Dir B` named `fodder.txt`: cp -Path .\DirA\test.txt -Destination '.\Dir B\.\fodder.txt'
12. Delete / remove both `fodder.txt` AND `Dir B`: rm '.\Dir B\'

## Citations

To add citations, provide the cite and a summary of what it assisted you with.  If generative AI was used, include which generative AI system was used and what prompt(s) you fed it.
