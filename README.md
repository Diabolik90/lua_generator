Copyright 2022 DBK
Author: Davide P. Fragnito <davidepie90@gmail.com>
genie.lua Generator

This program generates compilers to create and/or delete a solution in Visual Studio.

Set the :
  - solution name (which will be the same as the .exe file it will generate),
  - project name,
  - the x32 or x64 platform,
  - the version used by Visual Studio (2019 or 2017)
  - The SDK version (if unknown, open a project in Visual Studio, right click on the solution, retarget solution)


Add the Headers and libraries you want to use in the project
(must not necessarily be in the same folder)

Select the folder where you want to create the project

There is the possibility to generate an automatic main.cc file

Once everything is set up we can create files
