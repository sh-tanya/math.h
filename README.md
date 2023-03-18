# math.h
 Project by 21School

 It's my version of math.h library in the C programming language. This library implements basic mathematical operations:

| No. | Function | Description |
| --- | -------- | ----------- |
| 1 | `int abs(int x)` | computes absolute value of an integer value |
| 2 | `long double acos(double x)` | computes arc cosine |
| 3 | `long double asin(double x)` | computes arc sine |
| 4 | `long double atan(double x)` | computes arc tangent |
| 5 | `long double ceil(double x)` | returns the nearest integer not less than the given value |
| 6 | `long double cos(double x)` | computes cosine |
| 7 | `long double exp(double x)` | returns e raised to the given power |
| 8 | `long double fabs(double x)` | computes absolute value of a floating-point value |
| 9 | `long double floor(double x)` | returns the nearest integer not greater than the given value |
| 10 | `long double fmod(double x, double y)` | remainder of the floating-point division operation |
| 11 | `long double log(double x)` | computes natural logarithm |
| 12 | `long double pow(double base, double exp)` | raises a number to the given power |
| 13 | `long double sin(double x)` | computes sine |
| 14 | `long double sqrt(double x)` | computes square root |
| 15 | `long double tan(double x)` | computes tangent |  

According to my task:
- The library is developed in C language of C11 standard using gcc compiler
- Code is checked following the Google style
- Prefix s21_ before each function is used
- Full coverage of library functions code with unit-tests with the Check library is provided
- Makefile for building the library and tests (with the targets all, clean, test, s21_math.a, gcov_report) is provided
- The gcov_report target should generate a gcov report in the form of an html page
- The total verifiable accuracy is 16 significant digits




