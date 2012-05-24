This is a sample repository setup for a set of tools that use the statgen library.
It is a starting point you can use for creating your own repository that holds multiple programs.

Update Makefile, replacing any occurrances of SAMPLE_PROGRAM/S(s)ampleProgram with your program names.
Update EXE and add your own cpp/h files to the appropriate lines of the Makefiles.

--------------------------------------------------------------------------------
To use git to clone the required statgen library:
  make cloneLib
Next, to build libStatGen and this program:
  make
To install:
  make install INSTALLDIR=pathToInstall
