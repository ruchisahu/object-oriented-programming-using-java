## Chapter 06 - Loop Constructs - Challenges

### From 1 to 10

Print the list of numbers from 1 tot 10 to the console.

```text
1 2 3 4 5 6 7 8 9 10
```

### Even or Uneven

Create a program that prints out the numbers 0 to 10 and states if they are even or uneven. Do the even and uneven check using the modulo operator `%`.

Example output:

```text
0 (even)
1 (uneven)
2 (even)
3 (uneven)
...
10 (even)
```

### Summation

Request multiple numbers from the user and output the sum at the end of the application. Let the user stop inputting numbers by for example entering `0`. Make sure to inform the user how to stop the process of entering numbers.

Example output:

```text
Welcome to the summation application.

Please enter an integral number (0 to stop): 15
Please enter an integral number (0 to stop): 32
Please enter an integral number (0 to stop): -16
Please enter an integral number (0 to stop): 0

The total sum is 31

Thank you for using our application.
```

### Pyramid

Output a pyramid to the console as shown below.

```text
     -
    ---
   -----
  -------
 ---------
-----------
```

### Higher / Lower

Create the higher / lower game. First the application should generate a secret random number (see code below). The user is then requested to enter numbers. After each guess you should output to the user if he/she has to guess higher or lower.

If the secret number is guessed, output a congratulations to the user.

To generate a random number, you can use the code below:

```java
public static void main(String[] args) {
    Random generator = new Random();

    // Generate a random number between 0 (inclusive) and 5000 (exclusive)
    int secret = generator.nextInt(5000);
}
```

You will also need to import the Random library by adding `import java.util.Random;` to the top of your java file.

As an extra you can also output the number of guesses that were needed to guess the number.