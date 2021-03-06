Farida T. Yousry - 900171942

Exercise 3

-In order to insert the hello.c module into the kernel, first compile using the Makefile through the command "make", followed by "insmod ./hello.ko"

-In order to pass parameters (number of repitions & the text to be printed use the following command:
insmod ./hello.ko repeat=3 text="Hello World CSCE-3402 :)"

-In order to check that the module has been successfully inserted use the command "lsmod" to view all your kernel modules to check if it has been added

-In order to remove the module from the kernel use the command "rmmod hello"



-side note: to compile more than 1 files into 1 object file in makefile -> 
	newname-objs := file1.o file2.o

* to find text in files in current directory ->  grep -iRl "text.." ./