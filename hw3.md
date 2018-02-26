<center>

<h1>CSCI 305 Homework 3</h1>

<h3>Due Date: March 9, 2018 @ Beginning of Class</h3>
<br />
<br />

<h4>Name:<u>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</u></h4>

</center>


#### Types
1. Give the ML type corresponding to each of the following sets:

    a. {true, false}
    <br/>
    <br/>
    <br/>
    b. {(true, true), (true, false), (false, true), (false, false)}
    <br/>
    <br/>
    <br/>

2. Suppose there are three variables `X`, `Y`, and `Z` with these types:
   ```
   X: integer that is divisible by 3
   Y: integer that is divisible by 12
   Z: integer
   ```
   For each of the following assignments, knowing nothing about the values of the variables except their types, answer whether a language system can tell before running the program whether the assignment is safe? Why or why not?

     a. `X := Y`
     <br/>
     <br/>
     <br/>
     b. `Z := X`
     <br/>
     <br/>
     <br/>
     <br/>
     c. `X := X + 3`
     <br/>
     <br/>
     <br/>

3. Investigate the following type: *Associative Arrays in Perl*. Describe your findings fully, and don't forget to discuss representation issues and supported operations.
<br/><br/><br/><br/><br/><br/><br/><br/>

#### Polymorphism
1. Consider an unknown language with a left-associative `+` operator that is overloaded to have the following types: `int*real->real`, `int*int->int`, `real*int->real`, and `real*real->real`. Suppose the variable `i` has type `int` and the variable `r` has type `real`. For each `+` operator in each of the following expressions, say which type of `+` is used:

    a. `i + (r + i)`

    <br/>
    <br/>
    <br/>
    <br/>
    <br/>

    b. `i + i + r + (r + i)`
    <br/>
    <br/>
    <br/>
    <br/>
    <br/>

2. Consider an unknown language with integer and real types in which `1 + 2`, `1.0 + 2`, `1 + 2.0`, and `1.0 + 2.0` are all legal expression:

    a. Explain how this could be the result of overloading, using no coercion.
    <br/>
    <br/>
    <br/>
    <br/>
    <br/>
    b. Explain how this could result from subtype polymorphism, with no overloading or coercion.
    <br/>
    <br/>
    <br/>
    <br/>
    <br/>
