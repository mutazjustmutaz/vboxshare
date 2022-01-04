The setup is a Windows host and a Linux (Ubuntu in my case) guest installed on a VirtualBox virtual machine. Of course, sharing between the two systems is enabled.

This shell script moves all files and directories from a shared directory called 'shared' to the Linux Home directory, switches their ownership to the current user's group, removes files' execution permissions, and echos all top-level names to the terminal.

The paths for the shared and destination directories are hardcoded; of course, you can easily change them to suit your needs. And if you want more flexibility, it shouldn't be hard to modify the script so that it accepts paths passed to it from the command line.  
 

Note: In the case of nested files, the script doesn't support files with names that contain two or more consecutive spaces. 
