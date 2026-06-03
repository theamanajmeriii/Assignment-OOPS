# ASSIGNMENT-QUESTIONS-FOR-COLLEGE-SUB-OOPS
JAVA ASSIGNMENT 

ASSIGNMENT-1

1. WRITE A JAVA PROGRAM TO CHANGE TEMPERATURE FROM CELCIUS TO FAHRENHEIT AND VICE VERSA.

import java.util.Scanner; 
public class p1 { 
    public static void main(String[] args) { 
        Scanner sc=new Scanner(System.in); 
        System.out.println("enter the value in celcius:"); 
        int celcius= sc.nextInt(); 
        int farenhite=((9*celcius)/5)+32; 
        System.out.println("the value in farenhite is:"+farenhite); 
    } 
} 


output: 
enter the value in celcius: 
30 
the value in farenhite is:86 

2. WRITE A JAVA PROGRAM TO CHCEK IF A NUMBER IS POSITIVE OR NEGATIVE.
   
package com.company; 
import java.util.Scanner; 
public class p2 { 
    public static void main(String[] args) { 
        Scanner sc=new Scanner(System.in); 
        System.out.println("enter a number"); 
        int a= sc.nextInt(); 
        if(a>=0){ 
            System.out.println("the number is positive "); 
        } 
        else { 
            System.out.println("the number is negative"); 
        } 
    } 
} 


output 
enter a number 
45
the number is positive  
enter a number -45 
the number is negative 

3. WRITE A JAVA PROGRAM TO FIND MAXIMUM OF THREE NUMBERS.


import java.util.Scanner; 
public class p3 { 
    public static void main(String[] args) { 
        Scanner sc=new Scanner(System.in); 
        System.out.println("enter three number:"); 
        int a= sc.nextInt(); 
        int b= sc.nextInt(); 
        int c= sc.nextInt(); 
        if(a>b&&a>c){ 
            System.out.println("a is greater"); 
        } 
        else if(b>a&&b>c){ 
            System.out.println("b is greater"); 
        } 
        else{ 
            System.out.println("c is greater"); 
        } 
    } 
} 


output 
enter three number: 
4 5 2 
b is greater

4. WRTE A PROGRAM TO SWAP TWO NUMBERS.

import java.util.Scanner; 
public class p4 { 
    public static void main(String[] args) { 
        Scanner sc=new Scanner(System.in); 
        int num1= sc.nextInt(); 
        int num2= sc.nextInt(); 
        swap(num1,num2); 
    } 
    private static boolean swap(int num1, int num2) { 
        int temp =num1; 
        num1=num2; 
        num2=temp; 
        System.out.println(swap(4,5)); 
        return false; 
    } 
}

output
Enter the first number: 4
Enter the second number: 5
After swapping: 
First number: 5
Second number: 4

5. WRITE A JAVA PROGRAM TO CONVET MILES TO KILOMETRES.
import java.util.Scanner; 
public class p5 { 
    public static void main(String[] args) { 
        Scanner sc=new Scanner(System.in); 
        System.out.println("enter the value of km"); 
        int km= sc.nextInt(); 
        double miles=0.612*km; 
        System.out.println("the value in miles is:"); 
        System.out.println(miles); 
    } 


output
enter the value of km 
3 
the value in miles is: 
1.8359999999999999

6. WRITE A JAVA PROGRAM TO CHCEK WHETHER A YEAR IS LEAP YEAR OR NOT.

import java.util.Scanner; 
public class p6 { 
    public static void main(String[] args) { 
        Scanner sc=new Scanner(System.in); 
        System.out.println("enter the year:"); 
        int year= sc.nextInt(); 
        if(year%4==0||year%400==0){ 
            System.out.println("it is a leap year"); 
        } 
        else if(year%100==0){ 
            System.out.println("it is not a leap year"); 
        } 
        else { 
            System.out.println("it is not a leap year"); 
        } 
    } 
} 


output: 
enter the year: 
1342 
it is not a leap year

7. WRITE A JAVA PROGRAM FOR FOLLOWING GRADING SYSTEM. NOTE:
Percentage>=90%  : Grade A   
Percentage>=80% : Grade B  
Percentage>=70% : Grade C   
Percentage>=60% : Grade D   
Percentage>=40% : Grade E  
Percentage<40% : Grade F

import java.util.Scanner; 
public class p7 { 
    public static void main(String[] args) { 
        Scanner sc=new Scanner(System.in); 
        System.out.println("enter the percentage"); 
        int percent=sc.nextInt(); 
        if(percent>=90) 
            System.out.println("Grade A"); 
        else if(percent>=80) 
            System.out.println("Grade B"); 
        else if(percent>=70) 
            System.out.println("Grade C"); 
        else if(percent>=60) 
            System.out.println("Grade D"); 
        else if(percent>=40)  
                            System.out.println("Grade E"); 
        else 
            System.out.println("Grade F"); 
    } 
} 


output: 
enter the percentage 
45 
Grade E


8. Write a Java program to check whether a number is divisible by a 
number given by user.

import javax.swing.*; 
import java.util.Scanner; 
 
public class p8 { 
    public static void main(String[] args) { 
        Scanner sc=new Scanner(System.in); 
        System.out.println("enter a number"); 
        int a=sc.nextInt(); 
        //to check  whether a given number is divisble by given number or not 
        if(a%a==0){ 
            System.out.println("the nmumber is divisible"); 
        } 
        else if(a%a!=0){ 
            System.out.println("the number is not divisible "); 
        } 
        else { 
            System.out.println("the number is not divisible"); 
        } 
    } 
} 


output: 
enter a number 
34 
the nmumber is divisible by34

9. Write a Java program to calculate factorial of 12.  
//create a factorial 12 
public class p9 { 
    public static void main(String[] args) { 
        int i, fact=1; 
        int number=12; 
        for(i=1;i<=number;i++){ 
            fact=fact*i; 
        } 
        System.out.println("factorial of"+number+ "is"  +fact); 
    } 


output: 
factorial of12is479001600 
 
10. Write a Java program for Fibonacci series.

ublic class p11 { 
    public static void main(String[] args) { 
        int n1=0,n2=1,n3,i,count=10; 
        System.out.print(n1+" "+n2);//printing 0 and 1 
 
        for(i=2;i<count;++i)//loop starts from 2 because 0 and 1 are already printed 
        { 
            n3=n1+n2; 
            System.out.print(" "+n3); 
            n1=n2; 
            n2=n3; 
        } 
 
    } 
}


output: 
0 1 1 2 3 5 8 13 21 34

    
 
 
11. Write a Java program to reverse a number.

    
public class p19 { 
    public static void main(String[] args) { 
        int num = 1234567, reversed = 0; 
        for(;num != 0; num /= 10) { 
            int digit = num % 10; 
            reversed = reversed * 10 + digit; 
        } 
        System.out.println("Reversed Number: " + reversed); 
    } 
} 


output: 
Reversed Number: 7654321 
 
12. Admission to a professional course is subject to the following 
conditions:  
(a) marks in Mathematics >= 60  
(b) marks in Physics >=50  
(c) marks in Chemistry >=40  
(d) Total in all 3 subjects >=200  
(Or) Total in Maths & Physics>=150 Given the marks in the 3 subjects of 
n (user input)  
students, write a program to process the applications to list the eligible 
candidates.


import javax.swing.*; 
import java.util.Scanner; 
public class p12 { 
    public static void main(String[] args) { 
        Scanner sc = new Scanner(System.in); 
        System.out.println("enter the marks oof three subjects:"); 
        int phy = sc.nextInt(); 
        int mat = sc.nextInt(); 
        int chem = sc.nextInt(); 
        int t = phy + mat + chem; 
        int pm = phy + mat; 
        if (phy >= 70 && chem >= 60 && mat >= 70 
                && (t >= 225 || pm >= 150)) ; 
        System.out.println("eligible"); 
        else{ 
            System.out.println("not eligible"); 
 
        } 
    } 
} 
output:

13. Write a Java program to calculate the sum of natural numbers up to 
a certain range.  
public class p13 { 
    public static void main(String[] args) { 
        int n = 100; 
        int sum=0; 
        for(int i=0;i<n;i++) { 
            sum += i; 
        } 
            System.out.println("sum is "+sum); 
        } 
} 
output: 
sum is 4950

14. Write a Java program to print all multiple of 10 between a given 
interval.  
public class p14 { 
    public static void main(String[] args) { 
        int n=10; 
        for(int i=1;i<11;i++){ 
            System.out.println(10*i); 
        } 
    } 
} 
output: 
10 
20 
30 
40 
50 
60 
70 
80 
90
100


15. Write a Java program to generate multiplication table. 
import java.util.Scanner; 
public class p15 { 
    public static void main(String[] args) { 
        Scanner sc=new Scanner(System.in); 
        System.out.println("enter a number"); 
        int n= sc.nextInt(); 
        for (int i=0;i<11;i++){ 
            System.out.println(i*n); 
        } 
    } 
} 
output: 
enter a number 4 
0 4 
8 
12  16  20  24  28  32  36  40

16. Write a Java program to find HCF of two Numbers.  
 
public class p16 { 
    public static void main(String[] args) { 
        int num1 = 24, num2 = 36, hcf=0; 
        for (int i = 1; i <= num1 || i <= num2; i++) 
        { 
            if (num1 % i == 0 && num2 % i == 0) 
                hcf = i; 
        } 
        System.out.println("The HCF: "+ hcf); 
    } 
} 
output: 
The HCF: 12 

public class p17 { 
    public static void main(String[] args) { 
        // Numbers 
        int a = 15, b = 25; 
 
        // Checking for the largest 
        // Number between them 
        int ans = (a > b) ? a : b; 
 
        // Checking for a smallest number that 
        // can de divided by both numbers 
        while (true) { 
            if (ans % a == 0 && ans % b == 0) 
                break; 
            ans++; 
        } 
 
        // Printing the Result 
        System.out.println("LCM of " + a + " and " + b 
                + " : " + ans); 
    } 
} 
output: 
LCM of 15 and 25 : 75

17. Write a Java program to find LCM of two Numbers.  
public class p17 { 
    public static void main(String[] args) { 
        // Numbers 
        int a = 15, b = 25; 
 
        // Checking for the largest 
        // Number between them 
        int ans = (a > b) ? a : b; 
 
        // Checking for a smallest number that 
        // can de divided by both numbers 
        while (true) { 
            if (ans % a == 0 && ans % b == 0) 
                break; 
            ans++; 
        } 
 
        // Printing the Result 
        System.out.println("LCM of " + a + " and " + b 
                + " : " + ans); 
    } 
} 
output: 
LCM of 15 and 25 : 75

18. Write a Java program to count the number of digits of an integer 
public class p18 { 
    public static void main(String[] args) { 
        int count = 0, num = 20000; 
        while (num != 0) { 
            // num = num/10 
            num /= 10; 
            ++count; 
        } 
        System.out.println("Number of digits: " + count); 
    } 
} 
output: 
Number of digits: 5 

19. Write a Java program to check whether a number is palindrome or 
not.  
import java.util.Scanner; 
public class p19 { 
    public static void main(String args[]){ 
        Scanner sc=new Scanner(System.in); 
        System.out.print("Input a number: "); 
        int n = sc.nextInt(); 
        int sum = 0, r; 
        int temp = n; 
        while(n>0) 
        { 
            r = n % 10; 
            sum = (sum*10)+r; 
            n = n/10; 
        } 
        if(temp==sum) 
            System.out.println("It is a Palindrome number."); 
        else 
            System.out.println("Not a palindrome"); 
    } 
} 
output: 
Input a number: 12321 
It is a Palindrome number.

20. Write a Java program to check whether a number is prime or not.  
import java.util.Scanner; 
public class p20 { 
    public static void main(String[] args) { 
        Scanner sc=new Scanner(System.in); 
        System.out.println("enter a number:"); 
        int a=sc.nextInt(); 
        if (a==0||a==1){ 
            return; 
        } 
        for (int i=2;i<a/2;++i){ 
            if(a%i==0){ 
                System.out.println("not a prime number"); 
            } 
            else{ 
                System.out.println("prime number"); 
            } 
        } 
    } 
} 
output: 
enter a number: 
7 
prime number

21. Write a Java program to convert a Binary Number to Decimal and 
Decimal to Binary.  
public class p21 { 
    public static void main(String[] args) { 
        //declare variable to store decimal number,quotient and array 
        int quot,i=1,j; 
        int [] arr=new int[100]; 
        //create a scanner input class 
        Scanner sc=new Scanner(System.in); 
        System.out.println("enter a decimal number:"); 
        int dec_num= sc.nextInt(); 
        //initialize the quotient , 
        quot=dec_num; 
        // Convert the decimal number to binary and store binary digits 
        while (quot != 0) { 
            arr[i++] = quot % 2; 
            quot = quot / 2; 
        } 
 
        // Display the binary representation of the decimal number 
        System.out.print("Binary number is: "); 
        for (j = i - 1; j > 0; j--) { 
            System.out.print(arr[j]); 
        } 
        System.out.print("\n"); 
    } 
} 
output: 
enter a decimal number: 
23 
Binary number is: 10111

22. Write a Java program to find median of a set of numbers.  
mport java.util.Arrays; 
public class p22 { 
    public static void main(String[] args) { 
        // Define and initialize an array of integers 
        int[] nums = {10, 2, 38, 22, 38, 23}; 
        // Display the original array 
        System.out.println("Original array: " + Arrays.toString(nums)); 
        // Calculate and display the median of the array 
        System.out.println("Median of the said array of integers: " + getMedian(nums)); 
        // Define and initialize another array of integers 
        int[] nums1 = {10, 2, 38, 23, 38, 23, 21}; 
        // Display the original array 
        System.out.println("\nOriginal array: " + Arrays.toString(nums1)); 
        // Calculate and display the median of the second array 
        System.out.println("Median of the said array of integers: " + getMedian(nums1)); 
    } 
    public static int getMedian(int[] array) { 
        // Check if the length of the array is even 
        if (array.length % 2 == 0) { 
            // Calculate the median for even-sized arrays 
            int mid = array.length / 2; 
            return (array[mid] + array[mid - 1]) / 2; 
        } 
        // Calculate the median for odd-sized arrays 
        return array[array.length / 2]; 
    } 
} 
output: 
Original array: [10, 2, 38, 22, 38, 23] 
Median of the said array of integers: 30 
Original array: [10, 2, 38, 23, 38, 23, 21] 
Median of the said array of integers: 23

23. Write Java programs for the patterns given bellow:  
(a) 1      
      2 3 4  
      5 6 7 8 9  
(b)      1  
         2 1 2  
      3 2 1 2 3  
   4 3 2 1 2 3 4 
public class p23 { 
    public static void main(String[] args) { 
        int a = 1; 
        for (int i = 1; i <= 4; i++) { 
            for (int j = 1; j <= i; j++) { 
                System.out.print(a++ + "\t"); 
            } 
            System.out.println(); 
        } 
    } 
} 
output: 
1 
2     3    4 
5     6     7     8     9

24. Write a Java program to calculate Sum & Average of an integer 
array.

package com.company; 
//import util.java.s 
import java.util.Scanner; 
public class p24 { 
    public static void main(String[] args) { 
        int n, sum = 0; 
        float average; 
        Scanner sc = new Scanner(System.in); 
        System.out.print("Enter no. of elements you want in array:"); 
        n = sc.nextInt(); 
        int a[] = new int[n]; 
        System.out.println("Enter all the elements:"); 
        for(int i = 0; i < n ; i++) 
        { 
            a[i] = sc.nextInt(); 
            sum = sum + a[i]; 
        } 
        System.out.println("Sum:"+sum); 
        average = (float)sum / n; 
        System.out.println("Average:"+average); 
    } 
} 

output: 
Enter no. of elements you want in array:5 
Enter all the elements: 
23 12 56 45 33 
Sum:169 
Average:33.8


25. Write a Java program to implement stack using array.
    
 public class p25 {private int maxSize; 
    private Object[] stackArray; 
    private int top; 
 
    public p25(int size) { 
        maxSize = size; 
        stackArray = new Object[maxSize]; 
        top = -1; 
    } 
 
    public void push(Object value) { 
        if (isFull()) { 
            System.out.println("Stack is full. Cannot push element."); 
            return; 
        } 
        top++; 
        stackArray[top] = value; 
    } 
 
    public Object pop() { 
        if (isEmpty()) { 
            System.out.println("Stack is empty. Cannot pop element."); 
            return -1; 
        } 
        int oldTop = top; 
        top--; 
        stackArray[oldTop] = null; 
        return stackArray[oldTop]; 
    } 
 
    public Object peek() { 
        if (isEmpty()) { 
            System.out.println("Stack is empty. Cannot peek element."); 
            return -1; 
        } 
        return stackArray[top]; 
    } 
 
    public boolean isEmpty() { 
        return (top == -1); 
    } 
 
    public boolean isFull() { 
        return (top == maxSize - 1); 
    } 
 
    @Override 
    public String toString() { 
        return "Stack: " + Arrays.toString(stackArray); 
    } 
} 

26. Write a Java program to implement Queue using array.

class Queue {
    private int[] arr; // Array to store the elements
    private int front; // Front of the queue
    private int rear;  // Rear of the queue
    private int capacity; // Maximum capacity of the queue
    private int size;  // Current size of the queue

    // Constructor to initialize the queue
    public Queue(int capacity) {
        this.capacity = capacity;
        arr = new int[capacity];
        front = 0;
        rear = -1;
        size = 0;
    }

    // Method to add an element to the queue
    public void enqueue(int element) {
        if (isFull()) {
            System.out.println("Queue is full. Cannot enqueue " + element);
            return;
        }
        rear = (rear + 1) % capacity; // Wrap around if rear exceeds capacity
        arr[rear] = element;
        size++;
        System.out.println("Enqueued: " + element);
    }

    // Method to remove an element from the queue
    public int dequeue() {
        if (isEmpty()) {
            System.out.println("Queue is empty. Cannot dequeue.");
            return -1; // Return a sentinel value for an empty queue
        }
        int element = arr[front];
        front = (front + 1) % capacity; // Wrap around if front exceeds capacity
        size--;
        System.out.println("Dequeued: " + element);
        return element;
    }

    // Method to check if the queue is empty
    public boolean isEmpty() {
        return size == 0;
    }

    // Method to check if the queue is full
    public boolean isFull() {
        return size == capacity;
    }

    // Method to display the queue
    public void display() {
        if (isEmpty()) {
            System.out.println("Queue is empty.");
            return;
        }
        System.out.print("Queue: ");
        for (int i = 0; i < size; i++) {
            System.out.print(arr[(front + i) % capacity] + " ");
        }
        System.out.println();
    }

    // Main method to test the Queue implementation
    public static void main(String[] args) {
        Queue queue = new Queue(5); // Create a queue with capacity 5

        queue.enqueue(10);
        queue.enqueue(20);
        queue.enqueue(30);
        queue.enqueue(40);
        queue.enqueue(50);

        queue.display();

        queue.dequeue();
        queue.dequeue();

        queue.display();

        queue.enqueue(60);
        queue.enqueue(70);

        queue.display();
    }
}

output:
Enqueued: 10
Enqueued: 20
Enqueued: 30
Enqueued: 40
Enqueued: 50
Queue: 10 20 30 40 50
Dequeued: 10
Dequeued: 20
Queue: 30 40 50
Enqueued: 60
Enqueued: 70
Queue: 30 40 50 60 70


27. Write a Java program to enter n elements in an array and find 
smallest number among them.  
public class p27 { 
    public static void main(String[] args) 
    { 
        // Either we can initialize array elements or can 
        // get input from user. Always it is best to get 
        // input from user and form the array 
        int[] initializedArray 
                = new int[] { 25, 110, 74, 75, 5 }; 
        System.out.println("Given array "); 
        for (int i = 0; i < initializedArray.length; i++) { 
            System.out.println(initializedArray[i]); 
        } 
        // Initialize minValue with first element of array. 
        int minValue = initializedArray[0]; 
        // Loop through the array 
        for (int i = 0; i < initializedArray.length; i++) { 
            // Compare elements of array with minValue and 
            // if condition true, make minValue to that 
            // element 
            if (initializedArray[i] < minValue) 
                minValue = initializedArray[i]; 
        } 
        System.out.println("Smallest element present in given array: " + minValue); 
    } 
} 


output: 
Given array  
25   110  74  75  5 
Smallest element present in given array: 5

28. Write Java program to find the sum of all odd numbers in a array.   
import java.util.Scanner; 
public class p28 { 
    static Scanner sc=new Scanner(System.in); 
    public static void main(String[] args){ 
        int Size, i, OddSum = 0; 
        sc = new Scanner(System.in); 
        System.out.print(" Please Enter Number of elements in an array : "); 
        Size = sc.nextInt(); 
        int [] a = new int[Size]; 
        System.out.print(" Please Enter " + Size + " elements of an Array  : "); 
        for (i = 0; i < Size; i++) 
        { 
            a[i] = sc.nextInt(); 
        } 
        for(i = 0; i < Size; i++) 
        { 
            if(a[i] % 2 != 0) 
            { 
                OddSum = OddSum + a[i]; 
            } 
        } 
        System.out.println("\n The Sum of Odd Numbers in this Array = " + OddSum); 
    } 
} 


output: 
Please Enter Number of elements in an array : 5 
 Please Enter 5 elements of an Array  : 12 34 23 67 45 
The Sum of Odd Numbers in this Array = 135

29. Write a Java program to find duplicate elements in a 1D array and 
find their frequency of occurrence.  
mport java.util.Arrays; 
public class p29 { 
    //main method 
    public static void main(String[] args) { 
        //Declare and initialize the array elements 
        int[] array = { 2, 3, 5, 4, 3, 1, 3, 2, 1, }; 
        //sorting an array 
        Arrays.sort(array); 
        //declaring the variables 
        int i,j,frequency; 
        System.out.println("These elements are repeated along with its frequency-"); 
        //loop for logic implementation 
        for(i=0; i<array.length; i++){ 
            frequency = 1; 
            for(j=i+1; j<array.length; j++){ 
                if(array[j] == array[i]){ 
                    frequency++; 
                } else { 
                    break; 
                } 
            } 
            i=j-1; 
            if(frequency > 1){ 
 
                //printing the output 
                System.out.println(array[i] + " --> " + frequency); 
            } 
        } 
    } 
 
}


output: 
These elements are repeated along with its frequency- 
1 --> 2 
2 --> 2 
3 --> 3

30. Write a Java program to print every alternate number of a given 
array  
public class p30 { 
    public static void main( String args[] ) { 
        //initialize array 
        int[] arr = {11, 12, 13, 14, 15}; 
        //array length 
        int n = arr.length; 
        // loop through the array and increment by 2 
        for(int i=0; i<n; i = i+2){ 
            //print element 
            System.out.println(arr[i]); 
        } 
    } 
} 


output: 
11 
13 
15 

31. Write a Java program to show 0-arguments constructor.  
public class p31 { 
    int i; 
    // constructor with no parameter 
    private p31() { 
        i = 5; 
        System.out.println("Constructor is called"); 
    } 
    public static void main(String[] args) { 
        // calling the constructor without any parameter 
        p31 obj = new p31(); 
        System.out.println("Value of i: " + obj.i); 
    } 
} 


output: 
Constructor is called 
Value of i: 5

32. Write a Java program to show parameterized constructor.  
import java.util.Scanner; 
public class p32{ 
    public static class Edureka{ 
        String studentName; 
        int studentAge; 
        //constructor 
        Edureka(String name, int age){ 
            studentName = name; 
            studentAge = age; 
        } 
        void display(){ 
            System.out.println(studentName+ " "+studentAge); 
        } 
        public static void main(String args[]) 
        { 
            Edureka myObj = new Edureka("Manan" , 19); 
            myObj.display(); 
        } 
    } 
 
} 


output: 
Manan 19

33. Write a class, Commission, which has an instance variable, sales; an 
appropriate constructor; and a method, commission() that returns the 
commission.Now write a demo class to test the Commission class by 
reading a sale from the user, using it to create a Commission object 
after validating that the value is not negative. Finally, call the 
commission() method to get and print the commission. If the sales are 
negative, your demo should print the message “Invalid Input”.  
mport java.util.Scanner; 
 
public class p29{ 
        public static class Commission 
        { 
            String name; 
            int emp_no; 
            int sal; 
            double comm; 
            void input() { 
                Scanner sc=new Scanner(System.in); 
                System.out.print("Enter employee name: "); 
                name = sc.nextLine(); 
                System.out.print("Enter employee number: "); 
                emp_no = sc.nextInt(); 
                System.out.print("Enter monthly sales value: "); 
                sal = sc.nextInt(); 
            } 
            void compute() { 
                if (sal <= 50000) { 
                    comm = 5.0 / 100.0 * sal; 
                } 
                else if (sal <= 80000) { 
                    comm = 8.0 / 100.0 * sal; 
                } 
                else if (sal <= 100000) { 
                    comm = 10.0 / 100.0 * sal; 
                } 
                else if(sal<0){ 
                    System.out.println("invalid output"); 
                } 
                else { 
                    comm = 12.0 / 100.0 * sal; 
                } 
            } 
            void display() { 
                System.out.println("Employee name: " + name); 
                System.out.println("Employee Number: " + emp_no); 
                System.out.println("Monthly Sales: " + sal); 
                System.out.println("Commission: " + comm); 
            } 
            public void main(String args[]) { 
                com.company.p33.Commission obj = new com.company.p33.Commission(); 
                obj.input(); 
                obj.compute(); 
                obj.display(); 
            } 
        } 
} 
output:

ASSIGNMENT-2

1. Given are two one-dimensional arrays A & B, which are sorted in ascending order.
Write a Java program to merge them into single sorted array C that contains every item from arrays A & B, in ascending order.  
public class assign { 
    public static void main(String[] args) { 
        int[] A = {1, 3, 5, 7};         int[] B = {2, 4, 6, 8}; 
        int[] C = new int[A.length + B.length];         int i = 0, j = 0, k = 0; 
        while (i < A.length && j < B.length) { 
            if (A[i] < B[j]) {                 C[k++] = A[i++]; 
            } else { 
                C[k++] = B[j++]; 
            } 
        } 
        while (i < A.length) { 
            C[k++] = A[i++]; 
        } 
        while (j < B.length) { 
            C[k++] = B[j++]; 
        } 
        System.out.println("Merged Array: " + args.toString()); 
    } 
} output: 
Merged Array: {1,2,3,4,5,6,7,8}

2. Write a Java program to show 0-arguments constructor.  
class sample{     sample(){ 
        System.out.println("this is a zero argument constructor"); 
    } 
} 
public class assign {  
    public static void main(String[] args) {        sample obj=new sample(); 
    } 
} 
output: 
this is a zero argument constructor


3. Write a Java program to show parameterized constructor.  
class sample{     int num;     sample(int num){        this.num=num; 
        System.out.println("Number: " + num); 
    } 
} 
public class assign { 
    public static void main(String[] args) {        sample obj=new sample(5); 
    } 
} output: 
Number: 5 

4. Write a Java program to show constructor overloading.  
class sample{     int num;     sample(){ 
        System.out.println("this is a default constructor "); 
    } 
    sample(int num){        this.num=num; 
        System.out.println("Number: " + num); 
    } 
} 
public class assign {     public static void main(String[] args) {         sample obj1=new sample(); 
       sample obj2=new sample(5); 
    } 
} output: this is a default constructor  
Number: 5 

5. Write a Java program to implement the concept of inheritance.  
class Animal {     void makeSound() { 
        System.out.println("Animal makes a sound"); 
    } 
} 
class Dog extends Animal {     void makeSound() { 
        System.out.println("Dog barks"); 
    } 
    public static void main(String[] args) { 
        Dog dog = new Dog(); 
        dog.makeSound(); 
    } 
} output: 
Dog barks
String: Hello

6. Write a Java program to show method overloading.  
class Display {     void show(int num) { 
        System.out.println("Integer: " + num); 
    } 
 
    void show(String text) { 
        System.out.println("String: " + text); 
    } 
 
    public static void main(String[] args) {         Display obj = new Display();         obj.show(10); 
        obj.show("Hello"); 
    } 
} output: 
Integer: 10 


7. Write a Java program to show method overriding.  
class Animal {     void sound() { 
        System.out.println("Animal makes a sound"); 
    } 
} 
class Dog extends Animal { 
    @Override     void sound() { 
        System.out.println("Dog barks"); 
    } 
    public static void main(String[] args) {         Animal animal = new Dog(); 
        animal.sound();  // Method overriding in action 
    } 
} output: 
Dog barks  


8. Write a Java program to show method hiding.  
class Parent {     static void display() { 
        System.out.println("Parent's static method"); 
    } 
} class Child extends Parent {     static void display() { 
        System.out.println("Child's static method"); 
    } 
    public static void main(String[] args) {         Parent.display();  // Static method hiding 
        Child.display();   // Static method hiding 
    } 
} output: 
Parent's static method 
Child's static method 


9. Create a general class ThreeDObject and derive the classes Box, Cube, Cylinder and Cone from it.
 The class ThreeDObject has methods wholeSurfaceArea ( ) and volume ().
 Override these two methods in each of the derived classes to calculate the volume and whole surface area of each type of three-dimensional objects.
 he dimensions of the objects are to be taken from the users and passed through the respective constructors of each derived class. Write a main method to test these classes.


class ThreeDObject {     double volume() {return 0;} 
    double surfaceArea() {return 0; 
    }} 
class Box extends ThreeDObject {     double length, width, height; 
    Box(double length, double width, double height) {         this.length = length;         this.width = width;         this.height = height; 
    } 
    @Override 
    double volume() {return length * width * height;} 
    @Override 
    double surfaceArea() {return 2 * (length * width + width * height + height * length);} 
} 
class Cube extends Box {     Cube(double side) {         super(side, side, side); 
    } 
} 
class Cylinder extends ThreeDObject {     double radius, height; 
    Cylinder(double radius, double height) { 
        this.radius = radius;         this.height = height; 
    } 
    @Override 
    double volume() {return Math.PI * radius * radius * height;} 
    @Override 
    double surfaceArea() {return 2 * Math.PI * radius * (radius + height);} 
} 
class Cone extends ThreeDObject {     double radius, height; Cone(double radius, double height) {         this.radius = radius;         this.height = height; 
    } 
    @Override 
    double volume() {return (1.0 / 3) * Math.PI * radius * radius * height;} 
    @Override 
    double surfaceArea() {return Math.PI * radius * (radius + Math.sqrt(radius * radius + height * height));} 
} 
public class assign {     public static void main(String[] args) {         Scanner sc = new Scanner(System.in); 
        System.out.print("Enter Box dimensions (length width height): "); 
        Box box = new Box(sc.nextDouble(), sc.nextDouble(), sc.nextDouble()); 
        System.out.println("Box Volume: " + box.volume()); 
        System.out.println("Box Surface Area: " + box.surfaceArea()); 
        System.out.print("Enter Cube side: "); 
        Cube cube = new Cube(sc.nextDouble()); 
        System.out.println("Cube Volume: " + cube.volume()); 
        System.out.println("Cube Surface Area: " + cube.surfaceArea()); 
        System.out.print("Enter Cylinder radius and height: "); 
        Cylinder cylinder = new Cylinder(sc.nextDouble(), sc.nextDouble()); 
        System.out.println("Cylinder Volume: " + cylinder.volume()); 
        System.out.println("Cylinder Surface Area: " + cylinder.surfaceArea()); 
        System.out.print("Enter Cone radius and height: "); 
        Cone cone = new Cone(sc.nextDouble(), sc.nextDouble()); 
        System.out.println("Cone Volume: " + cone.volume()); 
        System.out.println("Cone Surface Area: " + cone.surfaceArea()); 
    } 
} 

output: 
Enter Box dimensions (length width height): 12 22 33 
Box Volume: 8712.0 
Box Surface Area: 2772.0 
Enter Cube side: 23 
Cube Volume: 12167.0 
Cube Surface Area: 3174.0 
Enter Cylinder radius and height: 5 23 
Cylinder Volume: 1806.4157758141312 
Cylinder Surface Area: 879.645943005142 
Enter Cone radius and height: 5 54 
Cone Volume: 1413.7166941154069 
Cone Surface Area: 930.3981752176131 


10. Write a program to create a class named Vehicle having protected instance variables regnNumber, speed, color, ownerName and a method showData ( ) to show “This is a vehicle class”. Inherit the Vehicle class into subclasses named Bus and Car having individual private instance variables routeNumber in Bus and manufacturerName in Car and both of them having showData ( ) method showing all details of Bus and Car respectively with content of the super class’s showData ( ) method.

 
class Vehicle { 
    protected String regnNumber, color, ownerName;     protected int speed; 
    Vehicle(String regnNumber, String color, String ownerName, int speed) {         this.regnNumber = regnNumber;         this.color = color;         this.ownerName = ownerName; 
        this.speed = speed; 
    } 
    void showData() {System.out.println("This is a vehicle class");} 
} class Bus extends Vehicle {     private String routeNumber; 
    Bus(String regnNumber, String color, String ownerName, int speed, String routeNumber) {         super(regnNumber, color, ownerName, speed);         this.routeNumber = routeNumber; 
    } 
    @Override     void showData() {         super.showData(); 
        System.out.println("Bus Details: " + regnNumber + ", " + color + ", " + ownerName + ", " + speed + " km/h, Route: " + routeNumber); 
    } 
} 
 
class Car extends Vehicle { 
private String manufacturerName; 
    Car(String regnNumber, String color, String ownerName, int speed, String manufacturerName) {         super(regnNumber, color, ownerName, speed);         this.manufacturerName = manufacturerName; 
    } 
    @Override     void showData() {         super.showData(); 
        System.out.println("Car Details: " + regnNumber + ", " + color + ", " + ownerName + ", " + speed + " km/h, Manufacturer: " + manufacturerName); 
    } 
} 
public class assign { 
    public static void main(String[] args) { 
        Bus bus = new Bus("KA01-1234", "Red", "John", 60, "101");         bus.showData(); 
        Car car = new Car("KA05-6789", "Blue", "Alice", 120, "Toyota");         car.showData(); 
    } 
}

output: 
This is a vehicle class 
Bus Details: KA01-1234, Red, John, 60 km/h, Route: 101 
This is a vehicle class 
Car Details: KA05-6789, Blue, Alice, 120 km/h, Manufacturer: Toyota 


11. Write a Java program which creates a base class Num and contains an integer number along with a method shownum() which displays the number. Now create a derived class HexNum which inherits Num and overrides shownum() which displays the hexadecimal value and octal value of the number. Demonstrate the working of the classes.


class Num {     int number; 
    Num(int number) {this.number = number;} 
    void shownum() {System.out.println("Number: " + number);} 
} 
class HexNum extends Num {     HexNum(int number) {         super(number); 
    } 
    @Override     void shownum() { 
        System.out.println("Hexadecimal: " + Integer.toHexString(number));         System.out.println("Octal: " + Integer.toOctalString(number)); 
    } 
    public static void main(String[] args) {         Num num = new Num(42); 
        num.shownum(); 
        HexNum hexNum = new HexNum(42); 
        hexNum.shownum(); 
    } 
} 

output: 
Number: 42 
Hexadecimal: 2a 
Octal: 52 

12. Create a base class Distance which stores the distance between two locations in miles and a method travelTime(). The method prints the time taken to cover the distance when the speed is 60 miles per hour. Now in a derived class DistanceMKS, override travelTime()so that it prints the time assuming the distance is in kilometers and the speed is 100 km per second. Demonstrate the working of the classes.  
class Distance {     double miles; 
    Distance(double miles) {this.miles = miles;}     void travelTime() { 
        // Default speed is 60 miles per hour 
        double time = miles / 60.0; 
        System.out.println("Time to travel " + miles + " miles at 60 mph: " + time + " hours"); 
    } 
} 
class DistanceMKS extends Distance {     DistanceMKS(double kilometers) { 
        super(kilometers / 1.609); // Convert kilometers to miles 
    } 
@Override 
    void travelTime() { 
        // Override assuming speed is 100 km/s 
        double time = miles * 1.609 / 100.0; // Convert miles to kilometers for MKS 
        System.out.println("Time to travel " + miles * 1.609 + " kilometers at 100 km/s: " + time + " seconds"); 
    } 
    public static void main(String[] args) {         Distance dist = new Distance(120); 
        dist.travelTime(); 
        DistanceMKS distMKS = new DistanceMKS(120); 
        distMKS.travelTime(); 
    } 
} 

output: 
Time to travel 120.0 miles at 60 mph: 2.0 hours 
Time to travel 120.0 kilometers at 100 km/s: 1.2 seconds 


13. Write a Java program to explain “multilevel inheritance.”  
class Animal { 
    void eat() {System.out.println("Animal eats food.");} 
} 
class Dog extends Animal { 
    void bark() {System.out.println("Dog barks.");} 
} 
class Puppy extends Dog { 
    void play() {System.out.println("Puppy plays.");} 
    public static void main(String[] args) {         Puppy p = new Puppy(); 
        p.eat(); 
        p.bark();  
        p.play();  
    } 
} 

output: 
Animal eats food. 
Dog barks. 
Puppy plays. 

14. Write a program to define a class Employee to accept emp_id, emp _name, basic_salary from the user and display the gross_salary.  
class Employee {     int emp_id;     String emp_name;     double basic_salary; 
    Employee(int emp_id, String emp_name, double basic_salary) {         this.emp_id = emp_id;         this.emp_name = emp_name; 
        this.basic_salary = basic_salary; 
    } 
    void calculateGrossSalary() { 
        double gross_salary = basic_salary + (0.2 * basic_salary) + (0.1 * basic_salary); // Example for HRA and DA         System.out.println("Gross Salary of " + emp_name + " is: " + gross_salary); 
    } 
    public static void main(String[] args) {         Scanner sc = new Scanner(System.in);         System.out.print("Enter employee ID: ");         int emp_id = sc.nextInt();         sc.nextLine();  // Consume newline character 
        System.out.print("Enter employee name: "); 
        String emp_name = sc.nextLine();         System.out.print("Enter basic salary: ");         double basic_salary = sc.nextDouble(); 
        Employee emp = new Employee(emp_id, emp_name, basic_salary);         emp.calculateGrossSalary(); 
    } 
} output: 
Enter employee ID: 12 
Enter employee name: Vrushali 
Enter basic salary: 234543.8 
Gross Salary of Vrushali is: 304906.94  
15. Write a program to demonstrate use of 'this' keyword.  
class person{     String name; 
    person(String name){this.name=name;} 
    void display(){System.out.println("name:"+this.name);} 
} 
public class p1 {     public static void main(String[] args) { 
        person p=new person("John");         p.display(); 
    } 
} 

output: name:John 


 
16. Write a program to demonstrate use of 'static' keyword.  
class Counter { 
    static int count = 0;      Counter() {count++;}     static void displayCount() { 
        System.out.println("Count: " + count); 
    } 
    public static void main(String[] args) {         new Counter();         new Counter();         Counter.displayCount(); 
    } 
} 
public class p1 { 
    public static void main(String[] args) {         new Counter();         new Counter();         Counter.displayCount(); 
    } 
} 

output: 
Count: 2 

17. Write program, which finds the sum of numbers formed by consecutive digits.  
Input : 2415  
output : 24+41+15=80.  
public class p1 { 
    public static void main(String[] args) {         int num = 2415; 
        String numStr = String.valueOf(num);         int sum = 0; 
        for (int i = 0; i < numStr.length() - 1; i++) { 
            int number = Integer.parseInt(numStr.substring(i, i + 2));             sum += number; 
        } 
        System.out.println("Sum: " + sum); 
    } 
}

output: 
Sum: 80 
 
18. Create three interfaces, each with two methods. Inherit a new interface from the three, adding a new method. Create a class by implementing the new interface and also inheriting from a concrete class. Now write four methods, each of which takes one of the four interfaces as an argument. In main ( ), create an object of your class and pass it to each of the methods.  
interface Interface1 {     void method1();     void method2(); 
} 
interface Interface2 {     void method3();     void method4(); 
} interface Interface3 {     void method5();     void method6(); 
} 
interface NewInterface extends Interface1, Interface2, Interface3 {     void method7(); 
} 
class ConcreteClass { 
    void commonMethod() { 
        System.out.println("This is a common method."); 
    } 
} 
class ImplementingClass extends ConcreteClass implements NewInterface { 
    @Override 
    public void method1() {System.out.println("Method1 from Interface1");} 
    @Override 
    public void method2() {System.out.println("Method2 from Interface1");} 
    @Override 
    public void method3() {System.out.println("Method3 from Interface2");} 
    @Override 
    public void method4() {System.out.println("Method4 from Interface2");} 
    @Override 
    public void method5() {System.out.println("Method5 from Interface3");} 
    @Override 
    public void method6() {System.out.println("Method6 from Interface3");} 
    @Override 
    public void method7() {System.out.println("Method7 from NewInterface");}     public static void main(String[] args) { 
        ImplementingClass obj = new ImplementingClass();         obj.method1();         obj.method7(); 
        obj.commonMethod(); 
    } 
} 

output: 
Method1 from Interface1 
Method7 from NewInterface 
This is a common method. 
 
19. Write a Java program to show the use of all keywords for exception handling. 
public class p1 { 
    public static void main(String[] args) {         try { 
            int[] arr = new int[2];             arr[5] = 10; 
        } catch (ArrayIndexOutOfBoundsException e) {             System.out.println("Array Index Out of Bounds");             throw e; // Rethrow exception 
        } finally {System.out.println("Finally block executed");}         try { 
            int result = 10 / 0;} 
        catch (ArithmeticException e) { 
            System.out.println("Arithmetic Error"); 
        } catch (Exception e) { 
            System.out.println("General Exception"); 
        } finally { 
            System.out.println("Finally block for second exception"); 
        } 
    } } 
 
20. Write a Java program using try and catch to generate NegativeArrayIndex Exception and Arithmetic Exception. 
public class p1 { 
    public static void main(String[] args) {         try { 
            int[] arr = new int[5]; 
            arr[-1] = 10; // NegativeArrayIndexException         } catch (ArrayIndexOutOfBoundsException e) { 
            System.out.println("Negative index accessed."); 
        }         try { 
            int result = 10 / 0; // ArithmeticException 
        } catch (ArithmeticException e) { 
            System.out.println("Cannot divide by zero."); 
        } 
    } 
}

output: 
Negative index accessed. 
Cannot divide by zero. 
  
21. Write a program that outputs the name of the capital of the country entered at the command line. The program should throw a “NoMatchFoundException” when it fails to print the capital of the country entered at the command line. 
class NoMatchFoundException extends Exception {     public NoMatchFoundException(String message) {         super(message); 
    } 
} 
public class CountryCapital { 
    public static void main(String[] args) { 
        Map<String, String> capitals = new HashMap<>(); 
        capitals.put("India", "New Delhi");         capitals.put("USA", "Washington DC"); 
        capitals.put("France", "Paris");         try { 
            if (args.length == 0) { 
                System.out.println("Please enter a country.");                 return; 
            } 
            String country = args[0]; 
            String capital = capitals.get(country);             if (capital == null) { 
                throw new NoMatchFoundException("No capital found for the country: " + country); 
            } 
            System.out.println("Capital of " + country + " is " + capital); 
        } catch (NoMatchFoundException e) { 
            System.out.println(e.getMessage()); 
        } 
    } } 
  
22. Write a java program to create an custom Exception that would handle at least 2 kind of Arithmetic Exceptions while calculating a given equation 
class InvalidEquationException extends Exception {     public InvalidEquationException(String message) {         super(message); 
    } 
} 
public class p1 { 
    public static void main(String[] args) {         try { 
            int result = calculateEquation(10, 0);  // Division by zero 
            System.out.println("Result: " + result); 
        } catch (InvalidEquationException e) { 
            System.out.println("Error: " + e.getMessage()); 
        }         try { 
            int result = calculateEquation(10, 2); 
            System.out.println("Result: " + result);  // Valid operation 
        } catch (InvalidEquationException e) { 
            System.out.println("Error: " + e.getMessage()); 
        } 
    } 
    static int calculateEquation(int num1, int num2) throws InvalidEquationException {         if (num2 == 0) { 
            throw new InvalidEquationException("Cannot divide by zero."); 
        } 
        return num1 / num2; 
    } 
}

output: 
Error: Cannot divide by zero. 
Result: 5 
 
23. Create two user-defined exceptions named “TooHot” and “TooCold” to check the temperature (in Celsius) given by the user passed through the command line is too hot or too cold.  
If temperature > 35, throw exception “TooHot”.  
If temperature <5, throw exception “TooCold”.  
Otherwise, print “Normal” and convert it to Farenheit. 
class TooHotException extends Exception {     public TooHotException(String message) { 
        super(message); 
    } 
} 
class TooColdException extends Exception {     public TooColdException(String message) {         super(message); 
    } 
} 
public class p1 { 
    public static void main(String[] args) { 
        if (args.length == 0) { 
            System.out.println("Please provide the temperature in Celsius.");             return; 
        } 
        double temperature = Double.parseDouble(args[0]);         try { 
            checkTemperature(temperature); 
        } catch (TooHotException | TooColdException e) { 
            System.out.println(e.getMessage()); 
        } 
    } 
    static void checkTemperature(double temperature) throws TooHotException, TooColdException {         if (temperature > 35) { 
            throw new TooHotException("Temperature is too hot: " + temperature + "°C"); 
        } else if (temperature < 5) { 
            throw new TooColdException("Temperature is too cold: " + temperature + "°C"); 
        } else { 
            System.out.println("Normal temperature: " + temperature + "°C");             double fahrenheit = (temperature * 9/5) + 32; 
            System.out.println("Temperature in Fahrenheit: " + fahrenheit + "°F"); 
        } 
    } } 
  
24. Consider an Employee recruitment system that prints the candidate name based on the age criteria. The name and age of the candidate are taken as Input.Create two user-defined exceptions named “TooOlder” and “TooYounger”  
If age>45, throw exception “TooOlder”.  
If age<20, throw exception “TooYounger”.  
Otherwise, print “Eligible” and print the name of the candidate.  
import java.util.Scanner; class TooOlderException extends Exception {     public TooOlderException(String message) {         super(message); 
    } 
} 
class TooYoungerException extends Exception {     public TooYoungerException(String message) {         super(message); 
    } 
} 
public class p1 {     public static void main(String[] args) {         Scanner sc = new Scanner(System.in); 
        System.out.print("Enter candidate name: "); 
        String name = sc.nextLine(); 
        System.out.print("Enter candidate age: "); 
        int age = sc.nextInt(); 
        try { 
            checkEligibility(name, age); 
        } catch (TooOlderException | TooYoungerException e) { 
            System.out.println(e.getMessage()); 
        } 
    } 
    static void checkEligibility(String name, int age) throws TooOlderException, TooYoungerException {         if (age > 45) { 
            throw new TooOlderException("Age too high. Candidate " + name + " is too old for the job."); 
        } else if (age < 20) { 
            throw new TooYoungerException("Age too low. Candidate " + name + " is too young for the job."); 
        } else { 
            System.out.println("Candidate " + name + " is eligible."); 
        } 
    } 
}

output: 
Enter candidate name: john 
Enter candidate age: 86 
Age too high. Candidate john is too old for the job. 
 
25. Write a program to raise a user defined exception if username is less than 6 characters and password does not match. 
import java.util.Scanner; class InvalidUsernameException extends Exception {     public InvalidUsernameException(String message) {         super(message); 
    } 
} 
class InvalidPasswordException extends Exception {     public InvalidPasswordException(String message) {         super(message); 
    } 
} 
public class p1 {     public static void main(String[] args) {         Scanner sc = new Scanner(System.in); 
        System.out.print("Enter username: "); 
        String username = sc.nextLine(); 
        System.out.print("Enter password: ");         String password = sc.nextLine();         try { 
            validateCredentials(username, password); 
        } catch (InvalidUsernameException | InvalidPasswordException e) { 
            System.out.println(e.getMessage()); 
        } 
    } 
    static void validateCredentials(String username, String password) throws InvalidUsernameException, InvalidPasswordException {         if (username.length() < 6) { 
            throw new InvalidUsernameException("Username must be at least 6 characters long."); 
        } 
        if (!password.equals("admin123")) { 
            throw new InvalidPasswordException("Password does not match."); 
        } 
        System.out.println("Login successful!"); 
    } 
}

output: 
Enter username: john 
Enter password: admin123 
Username must be at least 6 characters long. 
  
26. Write a program to input name and age of a person and throw a user-defined exception, if the entered age is negative 
import java.util.Scanner; 
class NegativeAgeException extends Exception { 
    public NegativeAgeException(String message) { 
        super(message); 
    } 
}public class p1 {     public static void main(String[] args) {         Scanner sc = new Scanner(System.in); 
        System.out.print("Enter name: "); 
        String name = sc.nextLine();         System.out.print("Enter age: ");         int age = sc.nextInt();         try { 
            validateAge(age); 
        } catch (NegativeAgeException e) { 
            System.out.println(e.getMessage()); 
        } 
    } 
    static void validateAge(int age) throws NegativeAgeException {         if (age < 0) { 
            throw new NegativeAgeException("Age cannot be negative."); 
        }System.out.println("Age entered: " + age); 
    } 
}

output: 
Enter name: meera 
Enter age: 45 
Age entered: 45 
 

