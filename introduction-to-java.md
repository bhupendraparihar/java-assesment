# Introduction to Java

## 1. Print Message


Write a progam to display a message "Welcome to object oriented programming"

Sample Output 1:

Welcome to object oriented programming

### Solution
```java
public class PrintMessage {

    public static void main(String args[]) {
        System.out.println("Welcome to Object Oriented Programming");
    }
}
```



## 2. Print Customer Details


Help Mr.Ben who is a programmer, in developing a registration form on console. Customers will not just input data, but also view the details once he/she finishes the registration. 

### Sample Input 1:

Enter your name:Jany

Enter age:25

Enter gender:Female

Hailing from:Mexico

<br/>

### Sample Output 1:

Welcome, Jany!

Age:25

Gender:Female

City:Mexico

### Source Code
```java
import java.util.Scanner;

public class Customer {
    
    public static void main(String args[]) {
        Scanner scn = new Scanner(System.in);
        String name;
        String age;
        String gender;
        String city;

        System.out.print("Enter your name:");
        name = scn.nextLine();

        System.out.print("Enter age:");
        age = scn.nextLine();

        System.out.print("Enter gender:");
        gender = scn.nextLine();

        System.out.print("Hailing from:");
        city = scn.nextLine();

        System.out.println("Welcome, " + name + "!");
        System.out.println("Age:" + age);
        System.out.println("Gender:" + gender);
        System.out.println("City:" + city);
    }
}
```


## 3. Print Username


Jeffy, who is going to complete the higher education in this year needs to create a simple application which accept the name of a person and welcome them with a message along with their name. She wants to read the data using the class "Scanner". Implement this scenario using Java.

### Sample Input 1: 

Enter the name:

Johson

Sample Output 1:

Welcome Johnson.



### Sample Input 2: 

Enter the name:

Stain Polson

Sample Output 2:

Welcome Stain Polson.

### Source Code
```java

import java.util.Scanner;

public class Username {
    
    public static void main(String args[]) {
        String name;

        Scanner in = new Scanner(System.in);
        System.out.println("Enter the name:");
        name = in.nextLine();

        System.out.println("Welcome " + name + ".");
    }
}

```

## 4. Bill Generation


Tom went to a movie with his friends in a multiplex theatre and during  break time he bought pizzas, puffs and cool drinks. Consider   the following prices : 

Rs.100/pizza

Rs.20/puffs

Rs.10/cooldrink

Generate a bill for What Tom has bought.



### Sample Input 1:

Enter the no of pizzas bought:10

Enter the no of puffs bought:12

Enter the no of cool drinks bought:5

<br />
### Sample Output 1:

Bill Details

No of pizzas:10

No of puffs:12

No of cooldrinks:5

Total price=1290

ENJOY THE SHOW!!!

<br/>

## 5 Spell Check


Ruya’s teacher gave her an assignment to practice the spelling of “RAINBOW”. Ruya’s mother helped her in
doing this by spelling each letter as Ruya wrote it in her notebook. If Ruya writes wrong spelling her mother should say "The spelling is wrong"

### Sample Input 1:
Enter the first letter:R

Enter the second letter:A

Enter the third letter:I

Enter the fourth letter:N

Enter the fifth letter:B

Enter the sixth letter:O

Enter the seventh letter:W

<br/>

### Sample Output 1:

RAINBOW

<br/>

### Sample Input 2:
Enter the first letter:R

Enter the second letter:E

Enter the third letter:I

Enter the fourth letter:N

Enter the fifth letter:B

Enter the sixth letter:O

Enter the seventh letter:W

<br/>

### Sample Output 2:

The spelling is wrong

<br/>

## 6. Highest Placement


SRV college wants to recognize the department which has succeeded in getting the maximum number of placements for this academic year. The departments that have participated in the recruitment drive are CSE,ECE, MECH. Help the college find the department getting maximum placements. Check for all the possible output given in the sample snapshot

Note : If any input is negative, the output should be "Input is Invalid".  If all department has equal number of placements, the output should be "None of the department has got the highest placement".

### Sample Input 1:

Enter the no of students placed in CSE:90

Enter the no of students placed in ECE:45

Enter the no of students placed in MECH:70

### Sample Output 1:
Highest placement 

CSE

<br />

### Sample Input 2:

Enter the no of students placed in CSE:55

Enter the no of students placed in ECE:85

Enter the no of students placed in MECH:85

### Sample Output 2:
Highest placement

ECE

MECH

<br />

### Sample Input 3:
Enter the no of students placed in CSE:0

Enter the no of students placed in ECE:0

Enter the no of students placed in MECH:0

### Sample Output 3:
None of the department has got the highest placement

<br/>

### Sample Input 4:

Enter the no of students placed in CSE:10

Enter the no of students placed in ECE:-50

Enter the no of students placed in MECH:40

### Sample Output 3:
Input is Invalid 

<br/>

## 7. Convert Numbers into Months


Ram is very weak in converting the numbers into months. But his friends often tease him by asking him to do that. To solve his problem a close friend of him, suggested to meet IIT students, who were very good at programming. Help ram to resolve his problem.

Note : 
Range of inputs is 1 to 12.
If the input given is beyond the range display error message as given in the sample output.

### Sample Input 1:
2

### Sample Output 1:
February

<br/>

### Sample Input 2:
15

### Sample Output 2:
No month for the number 15

<br/>

## 8. Find Season


Reaya's teacher has asked her to prepare well for the lesson on seasons. When her teacher tells a month, she needs to say the season corresponding to that month. Write a program to solve the above task.

Spring - March to May,

Summer - June to August,

Autumn - September to November and,

Winter - December to February.

Month should be in the range 1 to 12.  If not the output should be "Invalid month".

<br />

### Sample Input 1:
Enter the month:11

### Sample Output 1:
Season:Autumn

<br />

### Sample Input 2:
Enter the month:13

### Sample Output 2:
Invalid month

<br />

## 9. Lucky Number


William planned to choose a four digit lucky number for his car. His lucky numbers are 3,5 and 7. Help him find the number, whose sum is divisible by  3 or 5 or 7.
Provide a valid car number, Fails to provide a valid input then display that number is not a valid car number. 

Note : The input other than 4 digit positive number[includes negative and 0] is considered as invalid.
Refer the samples, to read and display the data.

### Sample Input 1: 
Enter the car no:1234

### Sample Output 1:
Lucky Number

<br />

### Sample Input 2:

Enter the car no:1214

### Sample Output 2:

Sorry its not my lucky number

<br />

### Sample Input 3:

Enter the car no:14

### Sample Output 3:

14 is not a valid car number


## 9. Pencil Count


Nila uses pencils to write at school and at home. When she was in her 1st standard, her parents bought her one pencil. In her 2nd standard, she needed 5 pencils, and in 3rd standard, she needed 14 pencils and so on. How many pencils does she get from the provided standard?

Note : If the input given is not between 1 to 12  then the output should be "Invalid Standard"

### Sample Input 1:
Enter the standard: 4

### Sample Output 1:
Nila gets 30 pencils


<br />

### Sample Input 2:
Enter the standard: 5

### Sample Output 2:
Nila gets 55 pencils

<br />

### Sample Input 3:
Enter the standard:14

### Sample Output 3:
Invalid Standard

<br />

## 10. Repetition of a Number


Pinky’s mom provides Pinky  with a number  and a key digit.  She wants Pinky to find out how many times that key digit appears in that number.  Help Pinky to do that by writing a program.

 
### Sample Input 1:

Enter the number  16466

Enter the key digit   6

### Sample Output 1:

6 appears 3 times in 16466

<br />

### Sample Input 2:

Enter the number  8458

Enter the key digit   6

### Sample Output 2:

6 appears 0 times in 8458

<br />

## 11. Bonus Points - Bike Race


There is an app for  bike race which provides bonus points for the  player.  In this app the player has to play the race and on completion, the total kilometers travelled by the player is calculated. Based on this distance travelled, the product of digits in the odd position and also product of digits in the even position is calculated.  Whichever is highest, that is the bonus points given to the user.   If the product of odd and even position digits are same, then the player should receive double the product as bonus.

Example : If the distance travelled  is 5632 
Product of digits in odd position = 5 * 3 = 15
Product of digits in even  position = 6 * 2 = 12
As 15 > 12, the bonus points the player gets is 15.
Write a program  to do this operation.

Create a class BikeRace.java with the main method.

Note : Input should be the distance travelled and the output is the bonus points.  If the input is less than zero, the output should be “Invalid Input”.  



### Sample Input 1 :

Enter the distance travelled

8694

### Sample Output 1 :

Your bonus points is 72


<br />

### Sample Input 2 :

Enter the distance travelled

263

### Sample Output 2 :

Your bonus points is 12

## 12. Celcius to Farenheit Conversion
Write a program to convert  Celsius to Farenheit.  Display the result correct to 1 decimal.

Create a class "CelsiusConversion.java" and write the main method.

Hint : 5 * (F – 32) = 9 * C,  F-Farenheit , C- Celsius

 

Sample Input  1 :

80

Sample Output  1 :

176.0

Sample Input  2 :

88

Sample Output  2 :

190.4

## 13. Check for Leap Year


Given a year, check if the year is leap year or not. If yes, the output should be “Leap Year”.  Else output should be “Not a Leap Year”.  The input should be a positive four digit number.  Else,  the output should be “Invalid Year”.

Sample Input  1 :

Enter the Year

2016

Sample Output  1 :

Leap Year



Sample Input  2 :

Enter the Year

2001

Sample Output  2 :

Not a Leap Year

## 14. Factors of a Number


Betsy  teaches her daughter  to find the factors of a given number.  When she provides a number to her daughter, she should tell the factors of that number.  Help her to do this, by writing a program.

Write a class FindFactor.java and write the main method in it.

Note : 

If the input provided is negative, ignore the sign and provide the output. If the input is zero
If the input is zero the output should be “No Factors”.


Sample Input 1 :

54

Sample Output 1 :

1, 2, 3, 6, 9, 18, 27, 54



Sample Input 2 :

-1869

Sample Output 2 :

1, 3, 7, 21, 89, 267, 623, 1869

## 15. Multiplying adjacent numbers
Write a program that prints a sequence of numbers by slightly modifying the Fibonacci series. The series of numbers is created by multiplying adjacent numbers instead of adding them. Prompt the user to enter the starting number and the number of terms.

Also write code to check the following conditions

whether the first number entered by the user is greater than or equal to the second number. If so display "Invalid Input", else get the number of terms.

Out of three inputs check whether each input value is greater than 0. 

If first input value entered is less or equal to 0 then display "Invalid Input" else get the 2nd input value. 

If second input value entered is less or equal to 0 then display "Invalid Input" else get the 3rd input value. 

If third input value entered is less or equal to 0 then display "Invalid Input" else print the required terms. 

Sample Input

Enter the first number:

2

Enter the second number:

3

Enter the number of terms:

4

Sample output

2, 3, 6, 18, 108, 1944


## 16. Count at the Cow barn
Tom was standing outside a cow barn. A group of men were appointed to take care of the cattle. All Tom could see was ‘m’ heads and ‘n’ feet. Write a program to display the number of cows and the number of men found.

Input consists of the heads as the first input and feet as the second input. If sum of number of cows and number of men is not equal to heads, then display “Invalid Input”.

Sample Input 1

3

10

Sample Output 1

Number of Cows: 2

Number of Men: 1

Sample Input 2

10

44

Sample Output 2

Invalid Input

## 17. Pair of Two digits
Write a program that accepts a pair of two digit numbers which satisfies the following condition.

The product of the numbers should be the same, when both the numbers are reversed and multiplied.

If products were same,then print "Yes" else print "No". Note: Assume both the inputs are 2-Digit values.

Hint: [13*62=31*26]

Sample Input:

13

62

Sample output:

Yes

## 18. Prime numbers ending with one
Write a program that prints a series of prime numbers that end with 1.

Prompt the user for the first number (n1) and the last number(n2) in the series. 

Print all possible prime numbers that ends with one from n1 to n2.

If n2 itself is prime, stop the series.  Else print the nearest prime number that ends with one,  next to n2.


Sample input:

Enter the first number

10

Enter the last number

100

Sample output:

11,31,41,61,71,101

## 19. currency calculator
Write a program to convert dollars into Indian money.

The currency calculator is capable of converting only USA, Canada, Singapore and Hong Kong dollars to INR.

Prompt the user to enter the Currency code and the amount to be converted. Display the result as given in the sample output.

Note the currency code and exchange rate for the countries

{Canada –CAD, 52.08} , {Hong Kong – HKD, 8.86}, {Singapore – SGD, 51.29} {USA – USD, 69.55}

Store these values as double and after calculation, print the values to two decimal places. Use System.out.printf to print correct to 2 decimal places.

Sample input 1

Enter the currency code

HKD

Enter the amount

3400

Sample output 1

Hong Kong dollar 3400 equals to 30124.00 Indian Rupee

Sample input 2

AED

Sample output 2

Currency code not found

## 20. Sum and Product
Lisa is hosting a party, during which she has planned for surprise gifts for her guests.

The guests while entering the hall should pick two slips of paper upon which numbers are written.

At the end of the party the guests should bring their slip of papers to Lisa. The Lucky ones are those who received numbers that satisfy the following condition.

The sum of the two numbers is the reverse of the product of the two numbers.

For example, If a guest has got X and Y as the two numbers, he will be a winner only if

X+ Y= AB; Then X * Y =BA.

Note : Both X and Y should be greater than 0. Otherwise print "Invalid Input"

Write a program to help Lisa find out the lucky winner. The program should accept two numbers, check the logic and display the message as shown in the sample output.


Sample input 1

24

3

Sample output 1

You are Lucky! Here Is your Gift.

Sample input 2

46

2

Sample output 2

Better Luck Next Time

Sample input 3

0

Sample output 3

Invalid Input

Sample input 4

89

0

Sample output 4

Invalid Input

## 21. Find Profit or Loss
Sam started a new business with an investment of Rs.1, 00,000. During the first year the he got a profit of x%, whereas in the second year he lost a certain amount(say Rs. Y). Help him to find out the profit/loss (in terms of initial investment) in percentage at the end of the second year.

Sample input 1:

Enter the profit percentage

20

Enter the amount lost in Rs.

50000

Sample output 1:

After two years he gets a loss of 30%.

Explanation :

investment = 100000

profit = 20% of 100000 = 20000

Loss=50000

If loss > profit, there is a loss

If loss < profit, there is a profit

If loss = profit, no gain no loss

Here loss > profit So loss

To calculate  loss% -  

loss amount = loss - profit = 30000

Loss % =( loss amount  / investment)    * 100             

That is 30000 * 100 / 100000 = 30%

Sample input 2:

Enter the profit percentage

20

Enter the amount lost in Rs.

20000

Sample output 2:

After two years he gets no loss or no gain.

## 22. Siblings Fund Raising
Harry, James, Leo and Sara are siblings and their mother has asked them to sell cake boxes for a fund raising event. She told them that there is a surprise gift for the ones who sell the maximum number of boxes. There can be more than one maximum.

Write a program to display the names of all the siblings who receive gifts by selling the maximum number of boxes. If all the four sold the same number then display, “All get the same gifts."

Sample input 1:

Enter the number of boxes sold by Sara

14

Enter the number of boxes sold by Harry

14

Enter the number of boxes sold by Leo

14

Enter the number of boxes sold by James

10

Sample output 1:

Sara, Harry and Leo receive the gifts.

Sample input 2:

Enter the number of boxes sold by Sara

14

Enter the number of boxes sold by Harry

14

Enter the number of boxes sold by Leo

14

Enter the number of boxes sold by James

20

Sample output 2:

James receives the gifts.

## 23. Numerology number
Harry has developed a new interest in learning numerology, so starts paying attention to the numbers that comes up as he goes about his daily routines.

Write a program to help him. The program should get the input from the user and display the individual digits separated by a single space. Assume input is less than 1000000000. For example, the number 7654 should be displayed as 7 6 5 4

Also display the sum of the digits, the numerology number(Multi-digit numbers are added and reduced to a single digit), number total number of odd numbers and total number of even numbers.

For example if the given number is 7654 then,

The Numbers are :    7    6    5    4    

Sum of digits : 22 (7+6+5+4)

Numerology number : 4 ((7+6+5+4 =22 => 2+2) sum of digits is again added and reduced to a single digit).

Number of odd numbers: 2

Number of even numbers: 2

Sample input:

Enter the number

86347

Sample output:

The Numbers are :    8    6    3    4    7

Sum of digits : 28

Numerology number: 1

Number of odd numbers: 2

Number of even numbers: 3

## 24. Decimal to Fraction
Bobby is in her 2nd grade and has just started to learn about fractions. Whenever  she comes across a decimal number she is curious to know the equivalent fraction for that number. Help her to convert a decimal number into a fraction. Write a program that accepts a decimal number and prints the fraction equivalent in the simplified/reduced form.

Sample input1

12.5

Sample output 1(Improper Fraction- where the numerator is greater than denominator)

Fraction: 25/2

Sample input 2

0.625

Sample output 2(Proper Fraction- where the numerator is lesser than denominator)

Fraction: 5/8

Sample input 3

3

Sample output 3

Input a decimal number

## 25. Grade Points
At Raffle’s Academy, students are given grade points to a maximum of 5 during their final exam. The grade points are mapped to Letter grades as follows.
<table>
    <tr>
        <td>Letter Grade</td>
        <td>Grade points</td>
    </tr>
    <tr>
        <td>0</td>
        <td>5</td>
    </tr>
    <tr>
        <td>A</td>
        <td>>= 4.5 and < 5.0</td>
    </tr>
    <tr>
        <td>B</td>
        <td>>= 4.0 and < 4.5</td>
    </tr>
    <tr>
        <td>C</td>
        <td>>=3.0 and  < 4.0 </td>
    </tr>
    <tr>
        <td>D</td>
        <td>>=2.0 and < 3.0</td>
    </tr>
    <tr>
        <td>E</td>
        <td>>=1.0 and < 2.0</td>
    </tr>
    <tr>
        <td>F</td>
        <td>>=0.0 and < 1.0 </td>
    </tr>
</table>

Write a program to that get’s an input between 0 and 5 and outputs the grade of the student.



Sample input:

Enter the grade point: 4.5

Sample output:

Grade: A



Sample input:

Enter the grade point: 3.4

Sample output:

Grade: C



Sample input:

1.2

Sample output:

Grade: E

## 26. KN Agencies Sales Orders
KN Agencies are dealers for a popular brand of Electric Kettle and Induction Stove. The selling price of the Electric Kettle and Induction Stove differs based on the number of units ordered and product chosen (either Electric Kettle or Induction Stove), as shown below .

<table>
    <tr>
        <td>
            Electric Kettle 
        </td>
    </tr>
    <tr>
        <td>No. of units</td>
        <td>Price/Unit (Rs) </td>
    </tr>
    <tr>
        <td>1 - 10 </td>
        <td>950</td>
    </tr>
    <tr>
        <td>11 - 20 </td>
        <td>900</td>
    </tr>
    <tr>
        <td>21 and above </td>
        <td>850</td>
    </tr>
</table>

<table>
    <tr>
        <td>
            Induction Stove
        </td>
    </tr>
    <tr>
        <td>No. of units</td>
        <td>Price/Unit (Rs) </td>
    </tr>
    <tr>
        <td>1 - 15 </td>
        <td>1100</td>
    </tr>
    <tr>
        <td>16 - 25 </td>
        <td>1000</td>
    </tr>
    <tr>
        <td>26 and above </td>
        <td>975</td>
    </tr>
</table>

Design a program to get input from the user( If Electric Kettle enter ‘E’ and if Induction Stove enter ‘I’, and the number of units. ) and display the total amount that has to be paid.

Hint : Assume that input provided will be either 'E' or 'I' alone.  No need to do any validation for the input provided.


Sample input

Enter 'E' for Electric Kettle and 'I' for Induction Stove( No other character will be accepted)

E


Enter the number of units ordered

12



Sample Output

Total amount to be paid is Rs.10800
