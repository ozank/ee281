# Introduction
An **electrical network** is an interconnection of electrical elements.

![](http://upload.wikimedia.org/wikipedia/commons/2/2a/Electric_circuit_RCL.jpg)

## A General View

What we are trying to do in this course is to:

### 1-Take a **real-world problem**

(e.g. what is the voltage at some point in a PCB)
![](https://c2.staticflickr.com/4/3639/3403005971_6bdcbb8ac5_z.jpg)

### 2-Simplify and represent it as a model
(e.g. electric schematic)

![](http://upload.wikimedia.org/wikipedia/commons/2/2a/Electric_circuit_RCL.jpg)

### 3-Represent the model mathematically.
$$
      \begin{array}{ccl}
        a_{11}x_1 & + a_{12}x_2 + \cdots + & a_{1n}x = 0 \\
        \;\vdots &  &\quad\vdots \\
        a_{m1}x_1 &+ a_{m2}x_2 + \cdots +& a_{mn}x_n = 0
      \end{array}
$$

### 4-Solve for the unknown

# Not Limited to Electric Circuits

Although, we will focus just on the analysis of the electrical circuits (or electrical networks) in this course, the same analysis techniques can be applied to many areas and they are  fundamental for many engineering problems, so please don't assume you will not use them even if you don't deal with electric circuits.

Some applications:

## Thermal Problems
A Thruster
![](http://upload.wikimedia.org/wikipedia/commons/3/3a/SpaceX_engine_test_fire.jpg)
Converted into a thermal network:
![](http://www.ecosimpro.com/images/lib_thermal_schematic.png)

## Mechanical Problems
Motion of a magnetic levitation train
![](http://upload.wikimedia.org/wikipedia/commons/d/d0/Shanghai_Transrapid_002.jpg)

Converted into a mechanical model:
![](https://raw.githubusercontent.com/ozank/ee281/master/images/train_circuit.png)

## Remember the Big Picture:
![](https://raw.githubusercontent.com/ozank/ee281/master/images/problem_modelling.png)
