dart-svn Subversion binding for dart.
========

# Download


# Documentation

## Prepare

### Windows

You'll need:

  * Dart SDK
  * dart.lib, the Dart native API library. You can obtain this from dart-sdk.
  * Visual C++ 2008. The [free version](http://msdn.microsoft.com/en-us/express/future/bb421473) works fine.

Edit build.bat to point to the Dart SDK and the svn-dev folder.

    C:\Program Files (x86)\Microsoft Visual Studio 9.0\VC\vcvarsall.bat
    $BLD = ./build.bat

### OS X and Linux
    $BLD = ./build.sh

## Building the library
    $BLD install
    $BLD

## Generating the documentation

    $BLD doc

## Running tests

    $BLD test

# Legal stuff
    Please read LICENSE