# COMP3111 Lab 1: Introduction to Git & GitHub

This Maven project contains the Java examples supplied with the Lab 1 worksheet.
It uses JDK 21 and includes JUnit Jupiter 5.11.0 as a test dependency for later labs.

## Program

- `myLibrary.java` implements recursive integer power and factorial functions.
- `mainApp1.java` prints the results for base 2 and exponent / factorial input 11.

The supplied examples assume positive inputs. They use Java `int`, so sufficiently
large results overflow; zero and negative inputs are outside the supplied examples.

## Expected output

```text
Welcome to Scientific Calculator!
Program started ...
2 to power 11 = 2048
11! = 39916800
Program ..Ended ...
```

## Run in IntelliJ IDEA

1. Open `Comp3111LEx` as a Maven project and select JDK 21 as the project SDK.
2. Reload the Maven project to resolve the JUnit dependency.
3. Open `mainApp1.java` and run its `main` method.

The compiled `.class` files are tracked for this lab, as requested by the worksheet.
