About QSsh
==========

QSsh provides SSH and SFTP support for Qt applications. The aim of this project 
is to provide a easy way to use these protocols in any Qt application.

This project is based on Qt Creator's libQtcSsh.so. All the credits to
Qt Creator's team!


### Compiling QSsh

Prerequisites:
   * Qt 4.7.4 (May work with older versions)
   * On Windows: MinGW 4.4 or later, Visual Studio 2008 or later
   * On Mac: XCode 2.5 or later, compiling on 10.4 requires setting the
     environment variable QTC_TIGER_COMPAT before running qmake


    $ mkdir $BUILD_DIRECTORY
    $ cd $BUILD_DIRECTORY
    $ qmake $SOURCE_DIRECTORY/qssh.pro
    $ make (or mingw32-make or nmake depending on your platform)


### Examples

Directory examples/SecureUploader/ contains an example on how to upload 
a file using SFTP
