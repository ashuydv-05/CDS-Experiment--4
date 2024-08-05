# CDS-Experiment--4
## Aim:To study and implement C++ bitwise operators.

## Theory:
In C++, bitwise operators let you work with individual bits inside an integer. They are essential for jobs that call for optimisation and low-level data processing.

AND (&): If the matching bits of the operands are both 1, then every bit in the result is 1. If not, it is 0.

As an illustration, 5 & 3 yields 1 (binary: 0101 & 0011 = 0001).
OR (|): If at least one of the matching bits of the operands is 1, then every bit in the result is 1.

As an illustration, 5 | 3 yields 7 (binary: 0101 | 0011 = 0111).
XOR (^): If the matching bits of the operands disagree, then every bit in the result is 1.

As an illustration, 5 ^ 3 yields 6 (binary: 0101 ^ 0011 = 0110).
NOT (~): converts 1 into 0 and 0 by inverting every bit of the operand.
Left Shift (\\): Adds zeros to the right while shifting bits to the left.

As an illustration, 5 << 1 equals 10. (binary: 0101 << 1 = 1010).
Right Shift (>>): Moves elements to the right while removing elements from the right.

For instance, 5 >> 1 yields 2 (binary: 0101 >> 1 = 0010).
These operators are essential for effective computing, especially in graphics, encryption, and systems programming.

## Code:
```
//Ashu Yadav
//23070123154
//bitwise_operator
#include<iostream>
using namespace std;
int main() {
    int a,b,a1,a2,a3,a4,a5,a6;

    cout<<"Enter the value for A"<<endl;
    cin>>a;
    cout<<"Enter the value for B"<<endl;
    cin>>b;
    a1=a&b;    //------BITWISE OPERATOR
    a2=a|b;    //------BITWISE OPERATOR
    a3=a^b;    //------BITWISE OPERATOR
    a4=~b;     //------BITWISE OPERATOR
    a5=a<<2;   //------BITWISE OPERATOR
    a6=a>>2;   //------BITWISE OPERATOR

    cout<<"AND of the entered value is "<<a1<<endl<<endl;
    cout<<"OR of the entered value is "<<a2<<endl<<endl;
    cout<<"XOR of the entered value is "<<a3<<endl<<endl;
    cout<<"NOT of B is "<<a4<<endl<<endl;
    cout<<"LEFT SHIFT of A by 2 is "<<a5<<endl<<endl;
    cout<<"RIGHT SHIFT of A by 2 is "<<a6<<endl<<endl;

    return 0;
}
```
## OUTPUT:
![exp4](https://github.com/ashuydv-05/CDS-Experiment--4/blob/main/Screenshot%202024-07-30%20161308.png)
## Conclusion:
Bitwise operators in C++ provide powerful tools for manipulating individual bits of data. They are used in a variety of low-level programming tasks and can greatly optimize certain types of operations. Understanding and implementing these operators is crucial for efficient and effective programming in system-level applications and performance-critical code. This experiment provided an in-depth understanding of how bitwise operators work and their practical applications.



