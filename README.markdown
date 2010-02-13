C# Intellisense and syntax-highlighting support for NHaml files
===============================================================

Install
=======

Download the .msi intaller file from the Download section, and run it.
It is tested to work with Visual Studio 2008 x64 Professional edition.
It might not work with other editions.

Currently it does not support Visual Studio 2010 or 2005 editions.

Because the component is not signed, you will need to have the Visual Studio
2008 SDK installed for the module to work.

Usage
=====

Intellisense support will only be enabled for all files with .haml extension
inside a Web Project. You will have to have the .haml files inside a Web Project
for the Intellisense to work.

Compilation
===========

To compile you will need to have the Visual Studio 2008 SDK, and it's files in the
path. The current source code assumes you have the VS2008 SDK files in their default
location on a x64 machine.

Known bugs
==========

NHaml Intellisens support is based on the Spark View Engine Intellisense library.
The bugs and limitations found there also apply to the NHaml Intellisense Library.

Links
=====

Visual Studio 2008 SDK: http://www.microsoft.com/downloads/details.aspx?FamilyID=30402623-93ca-479a-867c-04dc45164f5b&displaylang=en
Spark View Engine Intellisense support: http://sparkviewengine.com/usage/intellisense
SztupY's screencast about the installation and usage: http://www.youtube.com/watch?v=8jTZ2zC9eYc
