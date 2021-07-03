		TURBO PASCAL UNITS IN ADA


I Introduction

   GTKAda bindings facilitate graphic programming in Ada.
And also ease translation of Pascal applications into Ada
language.

   For those who want to translate a Pascal language application
from Turbo Pascal, I provide some Ada bindings of Turbo Pascal 7.0 units.

   This package is a very first version of TP7 units in Ada based on GTKAda
bindings.

In the package you will find some test examples.


II How to use this package

   GNAT CE 2021 compiler (with Ada 2005) and XNAdalib-CE-2021 library must be installed before,
see on Blady web site.
   Your Ada program translated from Turbo Pascal (P2Ada is recommended)
must be referenced in main.adb source with TP7.Init subprogram.
   Executable is built and run with following instructions for example:

$ gprbuild -P examples/examples.gpr
$ ./bin/main

  The program is composed of a control window: start and stop execution
of your program with a Debug option, a text window if TP7.CRT is used,
a graphic window if TP7.Graph is used.


III Use and licence

   This library is provide only for test, as it is.
It is not aimed to build any software other than for test.
All parts indicated belong to their copyright holder.
  This library is usable under CeCILL licence,
see Licence_CeCILL_V2-en.txt.

Pascal Pignard,
December 1998, June 1994, October 2002, September-December 2011, January-November 2012,
January 2014, June 2014, December 2015, September 2016, January 2018, juillet 2021.
http://blady.pagesperso-orange.fr

