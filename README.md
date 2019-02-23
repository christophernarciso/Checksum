# Checksum
Implementation of the Checksum learned in CIS-3360 at the University of Central Florida

## Usage
*Command Line Parameters*

1. The first parameter must be the name of the file used for calculating the checksum.
2. The second parameter must be the size, in bits, of the checksum.


Run command javac checksum.java java checksum filename.txt 8


## Output
```
printf("%2d bit checksum is %8lx for all %4d chars\n", checkSumSize, checksum, characterCnt);

Note: that the checksums are masked to print the appropriate sizes such two hex characters for 8 bits,
4 hex characters for the 16 bit checksum, and 8 hex characters for 32 bit checksum.
