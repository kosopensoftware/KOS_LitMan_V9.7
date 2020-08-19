# [KOS]LitMan Version 9.7

Disclaimer:
-----------
The author of the [KOS] Literature Manager program, Kurtis Stanistreet-Welsh, cannot guarantee that the software and the associated documentation are free from error. The author does not accept any responsibility for any loss or damage that may result from the use of this software. Any user that downloads this software accepts that they are solely responsibility for any damage or loss that may result. 

About [KOS] Literature Manager:
-------------------------------
[KOS] Literature Manager is part of the [KOS] System Operations family of software. This program is designed to automate the storage of academic literature in such a way as to allow users to efficiently search and find the stored literature later. The program also allows users to assign notes to publications and these too can be searched for efficiently. Publication data is stored in an organized database and the program automatically creates LaTeX-ready reference lists when you store Bibtex information in the program. The program has a user interface and automates many processes, but further automation and customization are planned for the future.
The ultimate goal for this program is to handle literature management for extensive projects such as literature reviews or academic paper writing.

Installation Instructions:
--------------------------

Installing [KOS] Literature Manager Version 9.7: General Users:
---------------------------------------------------------------
The only program that users will need to ensure they have to run the program without issues is the Microsoft Word.exe program, this is used to make notes and create a backup log for the program. Future updates will aim to allow users to by-pass Word.exe if they do not own it.
After downloading the [KOS]LitManV9.7_User_Installer from kosopensoftware.wordpress.com, simply click on the application. Next, you will need to tell the installer where to put the program files. You want the program to be placed somewhere you can easily access its folders to place publications in them. Once this is done the installer will place all the files in the correct place. Then enter the folder area and click on [KOS]LitManLauncher.exe or if this does not work, enter the ProgramFiles DIR and click on the [KOS]LitMan.exe application (This is the main application EXE). It is then advised to place a shortcut of this [KOS]LitMan.exe and a shortcut to the WaitingRoom DIR on the desktop if the program does not automatically do this for you. This should be everything and the program should run without issues. 


Installing [KOS] Literature Manager Version 9.7: Developers:
------------------------------------------------------------
Users using this route will need to change the shebang lines (#!/example1/example2/python.exe) for all the python scripts if they wish to run them on their systems, they will also have to ensure they have all the necessary extra modules installed. Unless you’re a developer looking to make alterations to the code, the user version is recommended as python is not essential. Alternatively, developers could just use the .exe application provided with the developer installation if they face issues with python.
Users will need to ensure they have the Microsoft Word.exe program to run the program without issues is, this is used to make notes and create a backup log for the program. Future updates will aim to allow users to by-pass Word.exe if they do not own it.
After downloading the [KOS]LitManV9.7_Dev_Installer from kosopensoftware.wordpress.com, simply click on the application. Next, you will need to tell the installer where to put the program files. You want the program to be placed somewhere you can easily access its folders to place publications in them. Once this is done the installer will place all the files in the correct place. Then enter the folder area and click on [KOS]LitManLauncher.exe or if this does not work, enter the ProgramFiles DIR and click on the [KOS]LitMan.exe application (This is the main application EXE). It is then advised to place a shortcut of this [KOS]LitMan.exe and a shortcut to the WaitingRoom DIR on the desktop if the program does not automatically do this for you. This should be everything and the program should run without issues.
To run the python version of the program, the developer will need to ensure that the following python packages are installed:
os | shutil | datetime | subprocess | time | docx | ctypes | sys | re | copy | msvcrt | win32com.client | pythoncom
The Launch.py script is capable of running the program, but the main.py script is the highest priority script for running the program. The setup.py script may also be useful for developers; this script will create a desktop and file area shortcut for the program. If developers have issues with downloading python files or if the full python version does not run, then it may be easier to contact the KOS developer at:
www.kosopensoftware.wordpress.com or email: kosopensoftware@gmail.com kosopensoftware@outlook.com

