# Inuse - Locked File Inspector

# inuse.exe
Inuse is a 32-bit console mode program for Windows. Its purpose is to reveal whether one or more processes have opened handles on a certain file, blocking access. Optionally, the program also allows you to close the handle and/or the owener's process.
To read a guide about its usage, just run it without parameters or with the –h option.

# test.exe
To test Inuse functionality you can use the test.exe program, included in this repository. Test.exe is another 32-bit console mode program for Windows. Once run inside a window opened with the Window command line shell, cmd.exe, the program will create a file and open it exclusively, showing on-screen instructions and inserting the path of the opened file into the Windows clipboard, in such a way as to facilitate the passage of the parameter to Inuse, consisting of the complete path of the file.
