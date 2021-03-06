Install
-------

    git clone https://github.com/openfl/openfl-validation
    haxelib dev openfl-validation openfl-validation
    haxelib install munit
    
Testing
-------------

First, change to the openfl-validation directory:

    cd openfl-validation

Next, you can test HTML5 and Flash using munit:

    haxelib run munit test
    
Other targets can be tested using the normal OpenFL test commands:

    openfl test windows
    openfl test windows -neko
    openfl test mac
    openfl test mac -neko
    openfl test linux
    openfl test linux -neko
    openfl test ios
    openfl test ios -simulator
    openfl test android
    openfl test blackberry
    openfl test blackberry -simulator

Contributing
-------------

If you would like to contribute a test, create a fork of the repository, then make a pull request with your addition.

Tests are organized based upon the class, then the method or property which has been tested. This will help us validate across the full API, and when there are problems, will help identify exactly which property or method needs to be improved for the specific target. Remember to remove @Ignore when you finish a test.
