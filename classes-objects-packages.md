## 1. Call Details
For the postpaid customers, the airvoice mobile shop maintains the calls made by the customer in the file in the given format below:

Callid:callednumber:noofminutes

Example: 123:9874561230:2.5

The shop wants to extract the information from the file and populate them in to the Call object. Develop a java application to do the above task.

Consider the class given below:

![CallClass](images/CallClass.png)

                

In the Call class include the given attributes and methods with the access specifiers as specified in the class diagram.

The getter methods are used to retrieve the value.

The parseData method takes the string as argument, the string value will be (123:9874561230:2.5). This method should extract the callid, called number and number of minutes from the string and set the callId, calledNumber and noOfMinutes.

In the Main class, create an object for the Call class; Get the details as shown in the sample input and invoke the parseData method.  Display the details as shown in the sample output using the getters method.

Note: The attribute/method/class name should be specified correctly as given in the class diagram.

Sample Input:

Enter the call details:

102:6547891230:2.15

 Sample output:

  Call id:102

  Called number:6547891230

  Duration:2.15
  
Source Code:
```java
// Filename: Call.java
public class Call {
  private int callId;
  private long calledNumber;
  private float duration:
  
  public Call() {}
  
  public void parseData(String str) {
    String arr[] = str.split(":");
    this.callId = Integer.parseInt(arr[0]);
    this.calledNumber = Long.parseLong(arr[1]);
    this.duration = Float.parseFloat(arr[2]);
  }
  
  public int getCallId() {
    return this.callId;
  }
  
  public long getCalledNumber() {
    return this.calledNumber;
  }
  
  public float getDuration() {
    return this.duration;
  }
}

// Filename: Main.java
import java.util.Scanner;

public class Main {
  public static void main(String args[]) {
    String input;
    Scanner scn = new Scanner(System.in);

    System.out.println("Enter the call details:");
    input = scn.nextLine();

    Call call = new Call();

    call.parseData(input);

    System.out.println("Call id:" + call.getCallId());
    System.out.println("Called number:" + call.getCalledNumber());
    System.out.println("Duration:" + call.getDuration());
  }
}
```
