# Basic Notes for **GO** language
* A file should end with **.go**
* like python no semicolon required
* A package is a filename which is converted as bin
* **package main** is needed for executable file
* Below is the sample function declaration
```
func <name> ( <comma separated arguments followed by data type>) <named return types> {
  <function body>
}
```
* A package can be imported using **import "package name"**
* variable is declared with **var** keyword followed by variable names and types separated with commas. 
Default variable values are zero values of corresponding data types 
```
var a int = 0
var b = "Vinod"
var a,b,c = 1,2,3
var a,b,c = "vinod",10,true
```
* **:=** is for short assignment without **var**. Only valid inside a function
```
func (){
  a,b,c := "vinod",10,true
}
```
* Data types additional to C are **float32, float64, complex64, complex123**
* Constants are declared through **const** keyword
# Iteration loops in **GO** language
* **for**, **if**, **switch** loops does not need brackets, but similar to **C** syntax. 
```
  for i := 0; i < 10; i++ {
    a = a + i
  }
```
* no **while**. **for** without **semicolon**,**initialization** and **increment** is **while** in **Go**
* **defer** delayes the function execution until the **return** is called for the calling fucntion
