---
num: "lect03"
desc:  "For loops, functions, intro to lab01 "
ready: false
pdfurl: /lectures/CS16_Lecture3.pdf
annotatedpdfurl: /lectures/CS16_Lecture3_ann.pdf
annotatedready: false
lecture_date: 2018-04-09
---


# Code from lecture


# Topics

* Intro to lab01
* For loops are DIFFERENT in C++ than in Python. We'll discuss.
* Simple accumulator
* For loops, applied to a simple accumulator pattern (find sum of a series)
* Basic abstraction in software: functions
* Function declaration, definition, and call
* Formal and actual parameters, return type

## Working with doubles
* Evaluating expressions with mixed numeric types
* Typecasting int to double 
* Formatted output with doubles:

Comment each line of code. What is the output of the code?
```
int i = 10;
double j = 1/static_cast<double>(i);
cout.setf(ios::fixed);
cout.setf(ios::showpoint);
cout.precision(3);
cout<<j<<endl;
```
