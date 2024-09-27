Java Data Type

Data types are of 2 types primitive type and reference type.
Primitive types include byte, short, int, long, char (which holds one character), float, double (float and double holds decimal type), Boolean( holds true or false). the reason we have different types of primitive types is because it can hold a wide range of data. For integer type we have byte, short, int, long. Each of the integer types carry different values. Byte holds a size of 1 byte of memory and the range of byte is from -128 to +127. 1 byte is having 8 bits. Short has a memory size of 2 bytes ranging its values from -32768 to +32767.
int have memory size 4 bytes ranging from values =2^31 to +2^31-1. Long has memory size of 8 bytes and ranging values from -2^63 to +2^63-1.
char has memory size of 2 bytes and holds character ranging from 0 to 65535. Float has  of size 4 bytes and can have value ranging from +-3.40282347E+38F. double can have memory size of 8 bytes and can have values ranging from +-1.79769313486231570E+308. Booleans holds true or false.

Reference types include class , array, string.



package com.bini.babu;

public class DataTypes {
    byte a = -50;
    short b = 150;
    int c = 10000;
    long d = 100000;
    float e = 1.23F;
    double f = 1234.56789;
    char h = 'A';
    byte g = 20;
    
    int result = a+g; //adding two bytes hence result should be declared as an integer

}



char should be initialized in single quotes. Float should be holding F at end.
int result = a+g; //adding two bytes and the result of adding 2 bytes should be integer hence result should be declared as an integer

