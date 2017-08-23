# dgtpi
DGTPi I2C communication with DGT3000

to compile use:
$ make

to compile with debug info use
$ make debug

to compile with lots of debug info use
$ make debug2

the library dgtpicom.so can be used as described in dgtpicom.h


the application dgtpicom can be used in three ways:

To display a message:
$ sudo ./dgtpicom "a message"
you can add a beep and icons/dots:
$ sudo ./dgtpicom "a message" 1 31 15

To run a clock:
$ sudo ./dgtpicom r 0 10 0 0 10 0
you can run Left and Right up and down with L,R,l and r

to turn of and exit on power button (or run some tests in debug):
$ sudo ./dgtpicom
lever will pause, off button wil stop te app


