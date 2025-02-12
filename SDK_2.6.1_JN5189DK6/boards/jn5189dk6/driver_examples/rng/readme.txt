Overview
========
The RNG project is a simple demonstration program of the SDK RNG driver.
This application is showing in the serial port random number generator examples. 

Toolchain supported
===================
- IAR embedded Workbench  8.40.2
- MCUXpresso  11.2.0

Hardware requirements
=====================
- Mini USB cable
- OM15076-3 Carrier Board
- JN518x Module plugged on the Carrier Board
- Personal Computer

Board settings
==============
No special settings are required.

Prepare the Demo
================
1.  Connect a mini USB cable between the PC host and the USB port (J15) on the board.
2.  Open a serial terminal with the following settings:
    - 115200 baud rate
    - 8 data bits
    - No parity
    - One stop bit
    - No flow control
3.  Download the program to the target board.
4.  Either press the reset button on your board or launch the debugger in your IDE to begin running the demo.

Running the demo
================
The following lines are printed to the serial terminal when the demo program is executed.
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
RNG Examples
Update once example: 0xebf4b62e
No. of bytes Read: 0x1
Byte: 0x0 Random data: 0x44
No. of bytes Read: 0x2
Byte: 0x0 Random data: 0x20
Byte: 0x1 Random data: 0x9a
No. of bytes Read: 0x3
Byte: 0x0 Random data: 0x89
Byte: 0x1 Random data: 0x28
Byte: 0x2 Random data: 0x1e
No. of bytes Read: 0x4
Byte: 0x0 Random data: 0x29
Byte: 0x1 Random data: 0x35
Byte: 0x2 Random data: 0x45
Byte: 0x3 Random data: 0xd3
No. of bytes Read: 0x5
Byte: 0x0 Random data: 0x7d
Byte: 0x1 Random data: 0x22
Byte: 0x2 Random data: 0xd0
Byte: 0x3 Random data: 0x75
Byte: 0x4 Random data: 0x65
No. of bytes Read: 0x6
Byte: 0x0 Random data: 0xb7
Byte: 0x1 Random data: 0x7
Byte: 0x2 Random data: 0x9f
Byte: 0x3 Random data: 0x9d
Byte: 0x4 Random data: 0x99
Byte: 0x5 Random data: 0x3
No. of bytes Read: 0x7
Byte: 0x0 Random data: 0xd9
Byte: 0x1 Random data: 0x6
Byte: 0x2 Random data: 0xb4
Byte: 0x3 Random data: 0x69
Byte: 0x4 Random data: 0x24
Byte: 0x5 Random data: 0xb8
Byte: 0x6 Random data: 0xc5
No. of bytes Read: 0x8
Byte: 0x0 Random data: 0xb0
Byte: 0x1 Random data: 0x85
Byte: 0x2 Random data: 0xeb
Byte: 0x3 Random data: 0xc8
Byte: 0x4 Random data: 0x89
Byte: 0x5 Random data: 0xcb
Byte: 0x6 Random data: 0xad
Byte: 0x7 Random data: 0x5c
No. of bytes Read: 0x9
Byte: 0x0 Random data: 0x2b
Byte: 0x1 Random data: 0xe0
Byte: 0x2 Random data: 0x13
Byte: 0x3 Random data: 0x5b
Byte: 0x4 Random data: 0xe4
Byte: 0x5 Random data: 0x9
Byte: 0x6 Random data: 0xea
Byte: 0x7 Random data: 0x66
Byte: 0x8 Random data: 0x23
No. of bytes Read: 0xa
Byte: 0x0 Random data: 0x3c
Byte: 0x1 Random data: 0x9b
Byte: 0x2 Random data: 0x30
Byte: 0x3 Random data: 0xaa
Byte: 0x4 Random data: 0xaa
Byte: 0x5 Random data: 0x86
Byte: 0x6 Random data: 0x68
Byte: 0x7 Random data: 0xc
Byte: 0x8 Random data: 0x1a
Byte: 0x9 Random data: 0xbf
No. of bytes Read: 0xb
Byte: 0x0 Random data: 0x53
Byte: 0x1 Random data: 0x1a
Byte: 0x2 Random data: 0xd3
Byte: 0x3 Random data: 0xa
Byte: 0x4 Random data: 0x40
Byte: 0x5 Random data: 0x18
Byte: 0x6 Random data: 0x6c
Byte: 0x7 Random data: 0x8b
Byte: 0x8 Random data: 0x7e
Byte: 0x9 Random data: 0x20
Byte: 0xa Random data: 0x49
No. of bytes Read: 0xc
Byte: 0x0 Random data: 0x58
Byte: 0x1 Random data: 0x66
Byte: 0x2 Random data: 0x3f
Byte: 0x3 Random data: 0x23
Byte: 0x4 Random data: 0x11
Byte: 0x5 Random data: 0xad
Byte: 0x6 Random data: 0x7f
Byte: 0x7 Random data: 0x7b
Byte: 0x8 Random data: 0xc1
Byte: 0x9 Random data: 0xd4
Byte: 0xa Random data: 0xdf
Byte: 0xb Random data: 0xdd
No. of bytes Read: 0xd
Byte: 0x0 Random data: 0x13
Byte: 0x1 Random data: 0x64
Byte: 0x2 Random data: 0x50
Byte: 0x3 Random data: 0xc9
Byte: 0x4 Random data: 0x69
Byte: 0x5 Random data: 0x76
Byte: 0x6 Random data: 0xf4
Byte: 0x7 Random data: 0x69
Byte: 0x8 Random data: 0x1d
Byte: 0x9 Random data: 0x7b
Byte: 0xa Random data: 0xb9
Byte: 0xb Random data: 0x75
Byte: 0xc Random data: 0x10
No. of bytes Read: 0xe
Byte: 0x0 Random data: 0x1a
Byte: 0x1 Random data: 0x12
Byte: 0x2 Random data: 0x78
Byte: 0x3 Random data: 0xec
Byte: 0x4 Random data: 0x57
Byte: 0x5 Random data: 0x58
Byte: 0x6 Random data: 0x72
Byte: 0x7 Random data: 0x30
Byte: 0x8 Random data: 0xf4
Byte: 0x9 Random data: 0xde
Byte: 0xa Random data: 0x81
Byte: 0xb Random data: 0x97
Byte: 0xc Random data: 0x17
Byte: 0xd Random data: 0x51
No. of bytes Read: 0xf
Byte: 0x0 Random data: 0x38
Byte: 0x1 Random data: 0xd
Byte: 0x2 Random data: 0xc1
Byte: 0x3 Random data: 0x9d
Byte: 0x4 Random data: 0xd3
Byte: 0x5 Random data: 0x77
Byte: 0x6 Random data: 0x48
Byte: 0x7 Random data: 0x30
Byte: 0x8 Random data: 0x9f
Byte: 0x9 Random data: 0x1b
Byte: 0xa Random data: 0x6d
Byte: 0xb Random data: 0x52
Byte: 0xc Random data: 0x55
Byte: 0xd Random data: 0x1a
Byte: 0xe Random data: 0x8b
No. of bytes Read: 0x10
Byte: 0x0 Random data: 0x60
Byte: 0x1 Random data: 0x1d
Byte: 0x2 Random data: 0x50
Byte: 0x3 Random data: 0xe8
Byte: 0x4 Random data: 0x5a
Byte: 0x5 Random data: 0x19
Byte: 0x6 Random data: 0x44
Byte: 0x7 Random data: 0xee
Byte: 0x8 Random data: 0x93
Byte: 0x9 Random data: 0x4a
Byte: 0xa Random data: 0xc3
Byte: 0xb Random data: 0x63
Byte: 0xc Random data: 0xf9
Byte: 0xd Random data: 0x62
Byte: 0xe Random data: 0x5a
Byte: 0xf Random data: 0x78
Free running example: 0xe036662f
Free running example: 0xbf066dc
Free running example: 0x281e6648
Free running example: 0x58b2481c
Free running example: 0x7da17e04
Free running example: 0xa0eafb9c
Free running example: 0x39a31cb3
Free running example: 0xc59fc566
Free running example: 0x5454d952
Free running example: 0x73ec2b1d
Free running example: 0x226c6ae9
Free running example: 0x31d3ade5
Free running example: 0x7f5357d0
Free running example: 0x442dbb65
Free running example: 0xe2b11e1b
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Customization options
=====================

