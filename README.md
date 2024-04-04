# IDE-less-AVR 
## Flyandance Advanced 8-bit AVR compile and Upload batch Program Universal

IDEs are for dummies, and Atmel studio is really a bloatware. Instead of creating an alternative that probably would turn into bloatware, a no-string-attached, a no-IDE, an ideless approach has been invented.

![E](https://github.com/flyandancexo/IDE-less-AVR/assets/66555404/2b98a76a-bec1-4dd8-854f-30ace98787b6)

The core of a compiler is the toolchain that turns source code into machine code. ZFDxAVR_ideless is a powerful script program that scans the whole project folder and sub-folders for valid source code, compiles them and then the final executable can either be run after or not. Two versions are provided: 1, for writing normal application 2, for writing bootloader code

![ZFDxAVR_ideless_2 0](https://github.com/flyandancexo/IDElessAVR/assets/66555404/ed9e68d8-c9b3-4804-a941-0166a898be85)

+ Alternative to IDE or more precisely to makefile
+ One click automation script with a lot of commented options
+ The root project folder name is the name of the new program
+ Scan root working folder and Compile all .c .cpp .s .o files
+ Super fast, simple and it just works
+ Auto-upload via AVRdude
   
## C/C++ GNU GCC
C/C++ is a simple yet extremely complicated programming language; Compiling a simple program is simple, but for advanced exploitation, you really need to dig in and hack the fout of the compiler. This script lets you type in more different stage compilation options, and there are literally thousands of options, and GNU compiler manual is 1k+ pages long, therefore this is absolutely not for dummies or for someone whom doesn't want to learn and be less dumber every day. 

## Notepad++
Notepad++ is pretty good. It has a Run menu that enables you to run the script directly using a keyboard shortcut, giving it an IDE like experience yet still being extremely light weight, fast and powerful.

## External libraries
Most libraries come with a header(.h) file and a static library (.a) file. The paths for these files can be linked to the script by entering the path and the name of the library under variables **IncludePath** and **LinkOptions**; For dynamic library, it should be resided on a system path, or a new system path should be created for it using **path**. Other compiling option can be entered on **CompileOptions**. Using -Wp,<options>, -Wa,<options> or -Wl,<options> to pass additional option for different stages. 

To support the creation of more quality code, do donate whatever amount that you are comfortable with.

[![paypal](https://www.paypalobjects.com/en_US/i/btn/btn_donateCC_LG.gif)](https://paypal.me/flyandance?country.x=US&locale.x=en_US)
