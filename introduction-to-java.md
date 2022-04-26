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
