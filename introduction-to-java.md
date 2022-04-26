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

