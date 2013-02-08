SCHIZOID
===============

Building skz
------------------------

For building skz you must cd to the working directory.
Make sure you have your device tree sources, located on

    cd device/-manufacturer-/-device-

Now you can run the build script:

    . skz/build.sh -device-


You can also use a second parameter for syncing sources before building

    . skz/build.sh -device- true


There are also a few parameters that you can use together with the previous:

* threads: Allows you to choose a number of threads for syncing operation
* clean: Removes intermediates and output files

The usage is the same
    
    . skz/build.sh -device- -parameters- true


Parameters will be considered false unless you set them to true

This will make a signed zip located on out/target/product/-device-.


