Lucas Boyd             0795339
CIS 2750              Assignment Four

***************
Program summary:
***************
This assignment implements a batch install script called install_dialogc. Once run an command line installer is made and the user is guided through a build and install process for the program.
at the end of the installation the user is prompted to run the program.

*************
compiling the program
*************
Go to directory where install_dialogc is located.
type ./install_dialogc (flags)

Full install:
both flags or no flags.

Build:
--build

Install:
--install

*************
running the program
*************
make run at apppropriate directory.

Short cuts:

File:
open - ctrl+O
New - ctrl+N
Save - ctrl+S
SaveAs - alt+S
Quit - ctrl+Q

Compile:
Compile - ctrl+B
Compile&Run - ctrl+R

Config:
Java-Compiler - alt+B
Compile Options - alt+C
Java Run-Time - ctrl+J
Run-Time Options - alt+R
Working Directory - ctrl+D
Compiler Mode - ctrl+M

Help:
help - ctrl+H
about - ctrl+A

*********
known limitations
*********
The program does not build the lib and bin directories. it does not get rid of source files at the end of installation. does install files to proper directory.
install files are always in the directory of the bash file.
need to use make run to run program.
does not get source from .bashrc file.

**********
Example config file.
**********
title = "compiled_exampl";    #name of app.
fields = {
          "Name",
          "Student_ID",
          "A1",
          "A2",
          "A3",
          "A4",
          "Average",
         }; #field names
# button names
buttons = { "Add", "Update", "Delete", "Query");
#!#

Name = "string";
Student_ID = "integer";
A1 = "integer";
A2 = "integer";
A3 = "integer";
A4 = "integer";

# actionListener classes for buttons
Add = "AddListener";
Update = "UpdateListener";
Delete = "DeleteListener";
Query = "QueryListener";

