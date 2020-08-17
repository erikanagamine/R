# R

Some notations from my studies about R - Programming Language

Sites:
  - https://www.r-project.org
  - https://www.rstudio.com

Packages: http://cran.r-project.org/web/packages

R is case sensitive.

- Interpreter (symbol):
```
> 
```

- Adding value to variable:
```
<-
```
- Comment:
```
#
```
Indicates a incompleted command:
```
+
```
- Print a variable:
```
variableName

or 

print(variable)
```

- list existing variables:
```
ls()

Ps. if no variable was found, it will apper: character(0)

```

- remove exisiting variables:
```
rm(variable)

rm(list=ls())
```

- Asking for help: ?
```
?ls
?matrix
```
- Verify type of variable:
```
is.numberic()
is.integer()
is.complex()
is.logical()
is.character()
```

# Types

- Number: Real number
It's a number, but it has a double precision:
```
1 
```
Constant numbers: Infinity: Inf
Indefined number: Not a Number: NaN

- Integer: Integer number
To specify an Integer value, type L
```
1L
```
- Complex: Complex number
- Boolean: Logical number
- character: string

PS. to know what type variable is: class(variable) or class(string)


