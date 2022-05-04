# TSUNAMI

The aim of this project is to create a [buffer overflow](https://en.wikipedia.org/wiki/Buffer_overflow) with the [strcpy](https://www.tutorialspoint.com/c_standard_library/c_function_strcpy.htm) function as it is not protected and exploit this to execute a program the memory.

I have inserted a string bigger 4 byte bigger than the buffer into another program to access the return function of the vulnerable program.

Inside the string there is a shellcode that will be executed with the return function of the vulnerable program.

You may know where is the address where the buffer starts and that the address of the return is 4 byte away from the stack variables.

It is developed on a Windows XP VM. Developed on Vagrant.
