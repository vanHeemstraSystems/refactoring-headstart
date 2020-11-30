# 100 Bloaters
Bloaters are code, methods and classes that have increased to such gargantuan proportions that they’re hard to work with. Usually these smells don’t crop up right away, rather they accumulate over time as the program evolves (and especially when nobody makes an effort to eradicate them).

## 100 Long Method
A method contains too many lines of code. Generally, any method longer than ten lines should make you start asking questions.

## 200 Large Class
A class contains many fields/methods/lines of code.

## 300 Primitive Obsession
- Use of primitives instead of small objects for simple tasks (such as currency, ranges, special strings for phone numbers, etc.)
- Use of constants for coding information (such as a constant USER_ADMIN_ROLE = 1 for referring to users with administrator rights.)
- Use of string constants as field names for use in data arrays.

## 400 Long Parameter List
More than three or four parameters for a method.

## 500 Data Clumps
Sometimes different parts of the code contain identical groups of variables (such as parameters for connecting to a database). These clumps should be turned into their own classes.
