---
title: If
---

# If

The if statement executes different blocks of code based on conditions.

```
if (condition) {
	// Do something when `condition` is true
}
else {
	// Do something when `condition` is false
}
```

When `condition` is true, code inside the `if` section executes, otherwise `else` executes. Sometimes you would need to add a second condition. For readability, you should use a `else if` rather than nesting `if` statements.

```
if (condition) {
	// Do something if `condition` is true
}
else if (anotherCondition) {
	// Do something if `anotherCondition` is ture
}
else {
	// Do something if `condition` AND `anotherCondition` is false
}
```

Note that the `else` and `else if` sections are not required, while `if` is mandatory.


## Example
```
#include <stdio.h>

int main () {

   // Local variable definition
   int a = 10;

   // Check the boolean condition
   if(a < 5) {
      // If condition is true then print the following
      printf("a is less than 5!\n" );
   }
   else {
      // If condition is false then print the following
      printf("a is not less than 5!\n" );
   }

   printf("Value of a is : %d\n", a);

   return 0;
}
```

## Output
```
-> a is not less than 5!
-> Value of a is : 100
```

## ----------------------------------------------
Some times when we need to check more than one conditions, at that time we can check those conditions using if statement..
here is the example given which uses "&&" to add another condition in if statment,which stands for "AND" ..
## Example 2:-------------------------
#include<stdio.h>


int main()
{
int a=10;
 //used to clear the screeen.
if(a>0 && a<20){
 printf("Value is less than 20");
 }
 else
  {
   printf("Value is greater than 20");
   }
  

return 0;
}
----------------------------------------------
