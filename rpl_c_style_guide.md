Rocket Propulsion Laboratory C Style Guide
==========================================

All C code written for RPL purposes should follow the guidelines outlined
in this document.

File extensions
---------------

*  All C source files should have the file extension .c
   Similarly, all C header files should have the file extension .h

        Good: foo.c, foo_header.h

        Bad: foo

*  All executable files should have the file extension .o, and 
   should not be the default name(a.out) 

        Good: foo.o

        Bad: foo

These guidelines are in place to make the types of files clear at a glance

Headers and Comments
--------------------

*  All files should have a file header, containing at least:
   +   Name of the file
   +   Date the file was last modified
   +   Author(s) of the file
   +   Team that the file is associated with
   +   Short description of the file
        /* 
	 * Filename: example.c
	 * Last Modified: April 30, 2017
	 * Author: Patrick Liu
	 * Team: Launchy McLaunchface/Avionics
	 * Description: Example of a file header for a C source file
	 */

* 
  
