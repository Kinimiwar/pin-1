# pin
Collection of pin tools


## General information

Unless stated otherwise, all pin tools were created with Visual Studio C++ 2012 Express.

To download & install the corresponding version of Pin, check this link:
https://software.intel.com/en-us/articles/pintool-downloads


## Creating a new Pin project folder for use with Visual Studio

This repository contains a simple python script to create a new Visual Studio project folder, based on the "MyPinTool" example folder.
Copy the script into the source/tools folder inside your pin folder structure.
Run the script from that working folder, and specify the name of the new project.

Example:
```
C:\pin\vc11\source\tools>python createpintool.py MyNewProjectName
[+] Creating new PIN project MyNewProjectName
    - Copying clean project
[+] Updating project files
    - Processing makefile -> makefile
    - Processing makefile.rules -> makefile.rules
    - Processing MyPinTool.cpp -> MyNewProjectName.cpp
    - Processing MyPinTool.vcxproj -> MyNewProjectName.vcxproj
    - Processing MyPinTool.vcxproj.filters -> MyNewProjectName.vcxproj.filters
[+] Done
```


## Notes

Hint: For Visual Studio C++ 2012, you need vc11, not vc12!<br>
Hint2: You may have to disable SAFESEH.
