# Introductory Assignments
Link to this assignment can be found on [Selfie Github Repository](https://github.com/cksystemsteaching/selfie/blob/master/assignments/introductory-assignments.md)

This assignment is done by Nadir Fejzic, Matrikelnummer: 11910236


### Exercise 1 - Decimal System and Scientific notation

**1. Write the number 1337 in scientific notation**

| 4-digit sequence |         1          |         3          |         3          |         7          | value |
| :--------------- | :----------------: | :----------------: | :----------------: | :----------------: | :---: |
| Notation         | 1 * 10<sup>3</sup> | 3 * 10<sup>2</sup> | 3 * 10<sup>1</sup> | 7 * 10<sup>0</sup> |       |
| Representation   |        1000        |        300         |         30         |         7          | 1337  |

**2. Write the number 267938 in scientific notation**

| 6-digit sequence |         2          |         6          |         7          |         9          |         3          |         8          | value  |
| :--------------- | :----------------: | :----------------: | :----------------: | :----------------: | :----------------: | :----------------: | :----: |
| Notation         | 2 * 10<sup>5</sup> | 6 * 10<sup>4</sup> | 7 * 10<sup>3</sup> | 9 * 10<sup>2</sup> | 3 * 10<sup>1</sup> | 8 * 10<sup>0</sup> |        |
| Representation   |       200000       |       60000        |        7000        |        900         |         30         |         8          | 267938 |

## Binary Numbers and conversion between Decimal and Binary number system

**Note:** 
- The right-most bit is also called **L**east **S**ignificant **B**it (LSB). Changing this bit has the least effect on the resulting value.  
- Conversely, the left-most bit is also called **M**ost **S**ignificant **B**it (MSB). Changing this bit has the largest effect on the resulting value. 

|      MSB      |               |               |               |               |               |               |      LSB      |
| :-----------: | :-----------: | :-----------: | :-----------: | :-----------: | :-----------: | :-----------: | :-----------: |
| 2<sup>7</sup> | 2<sup>6</sup> | 2<sup>5</sup> | 2<sup>4</sup> | 2<sup>3</sup> | 2<sup>2</sup> | 2<sup>1</sup> | 2<sup>0</sup> |
|      128      |      64       |      32       |      16       |       8       |       4       |       2       |       1       |

### Exercises 2:
1. What is a binary number?
    - Binary number is a number represented in base 2, in which there are only two possible values for a digit: 0 and 1. The sequence of 0's and 1's represent the powers of 2 which, when added together, represent the final value. 0 means that this power of 2 is not present, 1 means it is present. The right-most digit represents the 0th power (2<sup>0</sup>).
  
2. What is the value of the 5-digit sequence 10101?
    - The value is: 1 * 2<sup>4</sup> + 0 * 2<sup>3</sup> + 1 * 2<sup>2</sup> + 0 * 2<sup>1</sup> + 1 * 2<sup>0</sup> = 16 + 0 + 4 + 0 + 1 = 21.

3. What is the value of the 8-digit sequence 10110110?
    - The value is: 1 * 2<sup>7</sup> + 0 * 2<sup>6</sup> + 1 * 2<sup>5</sup> + 1 * 2<sup>4</sup> + 0 * 2<sup>3</sup> + 1 * 2<sup>2</sup> + 1 * 2<sup>1</sup> + 0 * 2<sup>0</sup> = 128 + 0 + 32 + 16 + 0 + 4 + 2 + 0 = 128 + 54 = 182.

## MSB & LSB 
MSB is the bit on the far left and represents the greatest value.
The Least Significant Bit is the right-most bit and it shows if a number is even or odd. If the LSB is 1 the number is odd, otherwise it's even.

### Exercises 3:
1. Is the value 101010 even or odd?
    - LSB is 0, so this number is even. The number is: 42.
2. Is the value 111 even or odd?
    - The LSB is 1, so the number is odd. The number is: 7.
3. Is the value 11101 even or odd?
    - The LSB is 1, number is odd. The number is: 29.
4. Is the value 111110 even or odd?
    - The LSB is 0, number is even. The number is: 62.


## Byte
Byte is a unit of digital information in computing and most commonly consists of 8 bits.

### Exercises 4:
1. What is the smallest number representable by an (unsigned) byte?
    - The smallest number is 0 represented by byte 0b00000000.

2. What is the largest number representable by an (unsigned) byte?
    - The largest number is 0b11111111 = 128 + 64 + 32 + 16 + 8 + 4 + 2 + 1 = 255.

## ASCII
ASCII is used to map characters to 7 bit wide integers and vice versa. 
Reference: [ASCII Table](https://github.com/cksystemsteaching/selfie/blob/master/assignments/ascii-table.md)

### Exercises 5:
1. How many different characters can be represented in ASCII?
    - ASCII uses 7 bits, there are also 2<sup>7</sup> = 128 many characters in ASCII.

2. What is the decimal representation of your first name?
    - My first name is Nadir, in ASCII: Nadir = 78 97 100 105 114
  
3. What is the ASCII representation of the decimal numbers 115, 101, 108, 102, 105, 101?
    | Decimal | ASCII |
    | :-----: | :---: |
    |   115   |   s   |
    |   101   |   e   |
    |   108   |   l   |
    |   102   |   f   |
    |   105   |   i   |
    |   101   |   e   |

## Octal number system
Octal notation is popular in computer science because it is represented in blocks of three bits. Each digit of an octal number is represented by 3 bits.  
Conversion from decimal to octal can be done by first converting to binary, then grouping the binary representation into groups of three bits, and converting the three bits to their octal digits.

### Exercises 6:
1. What is the octal representation of the decimal value 16?
   - 16 = 0b00010000 = 0b 010 000 = 0o20
2. What is the octal representation of the binary number 0b100100?
   - 0b 100 100 = 0o 4 4 = 0o44
3. What is the decimal representation of the octal value 173?
   - 0o173 = 1 * 8<sup>2</sup> + 7 * 8<sup>1</sup> + 3 * 8<sup>0</sup> = 64 + 56 + 3 = 123.

## Nibble
A **nibble** is a block of four bits. One nibble corresponds to precisely one hexadecimal digit.
**Hexadecimal** representation is popular in computer science because it is represented in blocks of four bits, each digit can have values from 0 (0000) to 15 (1111).  
When we write hexadecimal numbers we use prefix **0x** to emphasize it.  
Conversion from binary to hexadecimal is similar to conversion from binary to octal.

### Exercises 7:
1. Convert the binary number 0b1100100100011111 into the hexadecimal representation.
    - 0b1100100100011111 = 0b 1100 1001 0001 1111 = 0x C 9 1 F = 0xC91F
2. Convert the hexadecimal number 64B1D into the binary representation.
    - 0x 6 4 B 1 D = 0b 0110 0100 1011 0001 1101 = 0b01100100101100011101

## Computation
Computation is essentialy a sequence of state transitions. Computer stores a large but finite amount of bits in memory and registers at any given time. 
**State** of a digital logic circuit or a computer program is a technical term for all the stored information, at a given instant in time, to which the circuit or program has access. It's current inputs and it's state entirely determine it's output at any time.  
Software (and therefore machine code) specifies for each state what is the next state. Some bits are being changed, and others determine that change.

## State space

With N-many bits we can distinguish 2<sup>N</sup> many states.

### Exercises 8:
1. How many states can we distinguish with 1 byte?
    - 1 byte has 8 bits, therefore we can distinguish 2<sup>8</sup> = 256 many states.
2. How many states can we distinguish with 64 bits?
    - With 64 bits we can distinguish 2<sup>64</sup> many states. (A whole lot of 'em).

## Software
Software instructs a computer what to do in a computation. Thus computation defines the meaning of software.

## Binary Number Names & Prefixes

| Number of Binary Digits (bits) | Common Name |
| :----------------------------: | :---------: |
|               1                |     Bit     |
|               4                |   Nibble    |
|               8                |    Byte     |
|               16               |    Word     |
|               32               | Double Word |
|               64               |  Quad Word  |

### Binary - base 2
The computer industry has historically used the units kilo-, mega-, gigabyte and corresponding symbols KB, MB, GB etc. in at least two slightly different measurement systems: binary (base 2) and decimal (base 10) system.

**Binary base 2 system**
| Prefix | Symbol | Scientific Notation |
| :----- | :----: | :-----------------: |
| kibi-  |   Ki   |   2<sup>10</sup>    |
| mebi-  |   Mi   |   2<sup>20</sup>    |
| gibi-  |   Gi   |   2<sup>30</sup>    |
| tebi-  |   Ti   |   2<sup>40</sup>    |
| pebi-  |   Pi   |   2<sup>50</sup>    |
| exbi-  |   Ei   |   2<sup>60</sup>    |

| Value          | Scientific Notation |    Result    | Symbol |
| :------------- | :-----------------: | :----------: | :----: |
| 1024 bytes     |   2<sup>10</sup>    | = 1 kibibyte |  KiB   |
| 1024 kibibytes |   2<sup>20</sup>    | = 1 mebibyte |  MiB   |
| 1024 mebibytes |   2<sup>30</sup>    | = 1 gigibyte |  GiB   |
| 1024 gigibytes |   2<sup>40</sup>    | = 1 tebibyte |  TiB   |

**Decimal base 10 system**
Multipliers kilo, mega, giga, etc. are used in a manner consistent with their meaning in the [Internation System Of Units (SI)](https://en.wikipedia.org/wiki/International_System_of_Units), namely as powers of 10 (1000);

| Prefix | Symbol | Scientific Notation |
| :----- | :----: | :-----------------: |
| kilo-  |   k    |   10<sup>3</sup>    |
| mega-  |   M    |   10<sup>6</sup>    |
| giga-  |   G    |   10<sup>9</sup>    |
| tera-  |   T    |   10<sup>12</sup>   |
| peta-  |   P    |   10<sup>15</sup>   |
| exa-   |   E    |   10<sup>18</sup>   |


| Value          | Scientific Notation | Result       | Symbol |
| :------------- | :-----------------: | :----------- | :----: |
| 1000 bytes     |   10<sup>3</sup>    | = 1 kilobyte |   KB   |
| 1000 kilobytes |   10<sup>6</sup>    | = 1 megabyte |   MB   |
| 1000 megabytes |   10<sup>9</sup>    | = 1 gigabyte |   GB   |
| 1000 gigabytes |   10<sup>12</sup>   | = 1 terabyte |   TB   |

### Exercises 9:
1. How many different states can a digital computer with 4GB of memory have?
    - 4GB is 4 * 10<sup>9</sup> bytes, which is further 4 * 10<sup>9</sup> * 8 many bits.
    - Therefore 4GB = 4 * 1 000 000 000 * 8 = 32 000 000 000 many bits, and such a computer can have   
      2<sup>32 000 000 000</sup> many states.
2. How many different states can a digital computer with 80GB of storage have.
    - 80GB = 80 * 8 * 10<sup>9</sup> bits = 640 000 000 000 bits. Such a computer can have 2<sup>640 000 000 000</sup> many states.

## Architecture
### Binary vs Decimal

Computers encode all information in binary, since they also use binary representation at the hardware level. 0's and 1's are represented by voltage level. Since this is the case, it is possible to have as few states as possible, because physical fluctuations could affect voltage levels. It is harder to compensate for these fluctuations if we have many states. One would also have to increase the generally possible voltage (hence increasing the voltage range) to be able to detect different voltage levels (many states), and this would increase power consumption.  
Also, if we use more states we also need more memory, and hardware-level logic becomes increasingly difficult with more states.