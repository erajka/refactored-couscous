# X-Team 67 Style Guide

We want our code to be very readable and consistent

## Naming conventions

 using camel case for variables, classes and uppercase for final variables, using variable names that show what they are representing instead of just a random letter.

 * Camelcase for variables and methods `int numOfStudents`, `public String toString()`
 * Camelcaps for classes `SomeClass`
 * Uppercase with underscores for final/const variables `final int TABLE_SIZE`
 * Descriptive variable names, no "magic numbers"
 * Space before and after "=": `int x = 0`
 * Parameters in camelcase `method(int aParam, String aSecondParam)`
 * Four spaces = tab
 * Upper case connected by underscores for constants `public static final int INT_X = 10`


## Spacing and examples

We use javadoc for all public and private methods and constructors.
```
/**
 * A method that does stuff
 * @param name of the thing
 * @return some stuff
 */
 ```

We will use in-line comments on fields by putting "// " below the line.
```
String name;
// The name of the thing
```


Opening bracket will be with the header(declaration) and the closing bracket will be on its own line for loops/if statements/ switch..
```
newClass() {
    if () {

     } else {

     }
}
```


Switch formatting:
```
switch(x) {
	case(1):
		...
		break;
}
```
For loops:

```
for (int i = 0; i < x; i++) {

}
```

Method spacing:
```
/**
 * Method returns something
 * @return 0
 */
public static int method() {
	return 0;
}

/**
 * Method Two returns something else
 * @return 1
 */
public static int methodTwo() {
	return 1;
}
```
