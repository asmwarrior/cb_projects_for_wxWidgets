cb_projects_for_wxWidgets
=========================

2022-09-17 added by asmwarrior:

This git repo is a fork from [stahta01/cb_projects_for_wxWidgets](https://github.com/stahta01/cb_projects_for_wxWidgets)
It currently support building wx samples(wxWidgets 3.2.1) by using msys2's prebuild wx library (wxWidgets 3.2) under Code::Blocks IDE.


A tool named `wx-config-msys2.exe` is needed(you can put it in PATH environment) to generate compiler option and linker option, see here for more details.
[wx-config-msys2](https://github.com/eranif/wx-config-msys2).

For discussion, you can see here: [codeblocks cbp projects for wx samples](https://forums.codeblocks.org/index.php/topic,25105.0.html).

stahta01's old readme content
==========================
Code::Blocks projects for building wxWidgets sample code

The file wx-config.exe needs to be in the exe search path.
To build it compile the CB project in folder wx-config-win.

The way these CB Projects are setup requires
that these windows env. variables be set
WXWIN to the base folder of the wxWidgets source code.
 This base folder should contain an include folder under it.
WXCFG to the relative path that contains the build.cfg
 Example: gcc_dll\mswu
