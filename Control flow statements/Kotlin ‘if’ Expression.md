# Kotlin ‘if’ Expression

- In Kotlin, **if** is an expression which returns a value. It is used to control the flow of the program structure.


#### Syntax:

```
if(condition){
 
//code statement
 
}
```

#### Example:

```
fun main(args: Array<String>) {
val num1 = 5
val num2 = 10

val result = if (num1 > num2) {
"$num1 is greater than $num2"
} 
else{
"$num1 is smaller than $num2"
}

println(result)
}

Output is: 5 is smaller than 10

```

###### Note:
- You can remove the curly braces of if-else body if the expression has only one statement.
