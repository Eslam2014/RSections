---
title: "Lab 1: Introduction to R"
output: html_notebook
---


> #### Objects

* Objects should have names
* Object Types: vector, matrix … etc.
* Object Attributes
    + mode: numeric, character, boolean
    + length: number of elements in object
* Object Values
    + assign a value
    + create a blank object

> #### Naming Convention 

* must start with a letter (A-Z or a-z)
* can contain letters, digits (0-9), and/or periods “.” ex: Var1.1
* case-sensitive
    + mydata different from MyData
* do not use underscore “_”

> #### Assignment 

**<-** used to indicate assignment


```r
x <- 1
y <- 3
z <- 4
x*y*z
```

```
## [1] 12
```

**Note:** Type determined automatically when variable is created with **"<-"** operator

> #### Built-In Functions

* actions can be performed on objects using functions
* have arguments and options
* provide a result
* parentheses () are used to specify that a function is being called

> Example Functions


```r
rep(1,10)
```

```
##  [1] 1 1 1 1 1 1 1 1 1 1
```


```r
seq(2,6)
```

```
## [1] 2 3 4 5 6
```


```r
x <- c(2,0,0,4)
```


```r
x * 4 
```

```
## [1]  8  0  0 16
```


```r
sqrt(x)
```

```
## [1] 1.414214 0.000000 0.000000 2.000000
```
