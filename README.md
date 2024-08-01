# EXP-4
## Aim

- To implement and study Bitwise operators in C++ language

## Software required-

You need to have a C++ compiler installed on your system. Common options include:

- [Microsoft Visual C++](https://visualstudio.microsoft.com/vs/features/cplusplus/)

## Theory
In C++, operators are symbols that specify the operations to be performed on operands. C++ provides a rich set of operators to perform various types of operations. These operators can be categorized into several groups:

##### Bitwise Operators
Operators perform bit-level operations on integer types.
Implement a program that demonstrates the use of bitwise operators, such as setting, clearing, and toggling bits.

1.  (&) Bitwise AND
2.  (|) Bitwise OR
3.  (^) Bitwise XOR
4.  (~) Bitwise NOT
5.  (<<) Left shift
6.  (>>) Right shift

## CODE 1 BITWISE OPERATORS
```cpp

//RIDDHI LOKAHNDE
//ENTC B2
//23070123107
//EXP 3 B
#include<iostream>
using namespace std;
int main(){
    int a=5;
    int b=6;
    
    cout << "\nBitwise Operators:" << endl;
    cout << "AND (a & b): " << (a & b) << endl;
    cout << "OR (a | b): " << (a | b) << endl;
    cout << "XOR (a ^ b):" << (a ^ b) << endl;
    cout << "NOT (~a) : " << (~a) << endl;
    cout << "LEFT SHIFT (a << 1):" << (a << 1) << endl;
    cout << "RIGHT SHIFT (a >> 1) : " << (a >> 1) << endl;
    return 0;
}
```
### Output
![image](https://github.com/user-attachments/assets/3f8d5ab2-403b-48e4-98f6-208c5adf140b)

## Conclusion
We learnt the implementation and study of  Bitwise operators in C++ language.
