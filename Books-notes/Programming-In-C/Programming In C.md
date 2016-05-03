Book Notes of Programming in C

## Chapter 1. Introduction
## Chapter 2. Some Fundamentals
## Chapter 3. Compiling and Running Your First Program
* Declare variables before use
* Case sensitive
* Comments:
```C
  /* comments 
  multi lines*/
  
  // comments line
```
## Chapter 4. Variables, Data Types, and Arithmetic Expressions
* Variable names

    Begin with a letter or underscore(_) and can be followed by and combination of letters(upper or lower case), underscores, or the digits.

* Data Types
  * int,  float,  double,  char  _Bool
  * constant: constant integer, constant string, constant expressions
  
* Int
  * octal: ```050, %o, %#o``` (display with the first 0)
  * hexadecimal: ```0x50. %x, %#x``` (display with the first 0x), ```%X, %#X``` (Upper case displayed)

* Float
  * can omit one of the part before or after the decimal point
  * Scientific notation: ```1.7e4, 2.25E-3```
  * ```%f, %e, %g``` (auto select: ```if exponent < -4 or > 5, %e, %f```)
  * Hexadecimal floating: ```0x0.3p10 (or 0x0.3P10) represents 3/16 x 2^10 = 192```

* Char
  * ```%c```
  * ```'\n'```

* _Bool

* Table 4.1 Basic Data Types


| Type                   | Constant Examples              | printf chars   |
|------------------------|--------------------------------|----------------|
| char                   | a','\n'                        | %c             |
| _Bool                  | 0,1                            | %i,%u          |
| short int              | —                              | %hi,%hx,%ho    |
| unsigned short int     | —                              | %hu,%hx,%ho    |
| int                    | 12,-97,0xFFE0,177              | %i,%x,%o       |
| unsigned int           | 12u,100U,0XFFu                 | %u,%x,%o       |
| long int               | 12L,-2001,0xffffL              | %li,%lx,%lo    |
| unsigned long int      | 12UL,100ul,0xffeeUL            | %lu,%lx,%lo    |
| long long int          | 0xe5e5e5e5LL,500ll             | %lli,%llx,%llo |
| unsigned long long int | 12ull,0xffeeULL                | %llu,%llx,%llo |
| float                  | 12.34f,3.1e-5f,0x1.5p10,0x1P-1 | %f,%e,%g,%a    |
| double                 | 12.34,3.1e-5,0x.1p3            | %f,%e,%g,%a    |
| long double            | 12.341,3.1e-5l                 | %Lf,$Le,%Lg    |
  
## Chapter 5. Programming Looping

* For statement
  * ```for(int i = 0; i < 10; i++)```
  * ```for(int i = 1; i < 10; ++i)```

* While Loop
* Do While Loop
* ```break;``` and ```continute;```

## Chapter 6. Making Decisions

* The ```if``` statement
* The ```switch``` statement
* The condintional operator


