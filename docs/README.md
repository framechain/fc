# Paillier-NIZK library

## 1. Build

Enter the source directory, and then execute the following command.

+ mkdir build
+ cd build
+ cmake ../
+ make

The default version is release version, if need to build debug version, replace the command at the step 3 with the following command.

+ cmake ../ -DCMAKE_BUILD_TYPE=Debug

If everything is working right, 4 output files will be generated, as following.

+ libmiracl.a (in build/miracl)
+ libnizk.a (in build/nizk)
+ nizk-inter (in build/inter)
+ nizk-test (in build/test)

## 2. Test

Enter the test directory, and then execute the following command into the interactive mode.

+ ./nizk-test

## 3. Command line interaction

Enter the inter directory, and then execute the following command into the interactive mode.

+ ./nizk-inter

