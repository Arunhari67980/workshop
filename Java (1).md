#### **Java**



* it is developed by James gosling in the year 1991.
* officially released in 1995.
* the latest java version is java25  (released September 2025).
* still widely used java version is java21.
* it is object oriented programing language.
* it is a platform independent language.
* once written run anywhere.
* it is a high-level programing language.
* it is highly used for security purpose.



###### Applications



* mobile application.
* web application.
* desktop application.
* banking application.



###### Types



1. java standard edition.
2. java enterprise edition.



###### 

###### Class



* it is a blueprint or templates of an object.
* the class name should be meaningful and it always start with uppercase and it follows camelCase.
* syntax ( class classname{} ).



###### Object



* an entity which has properties and behaviors created by class.



###### Method

* public static void main(string\[] args){} -> main method.



EG.1



 	public class HelloWorld{

 	public static void main (string\[] args){

 		system.out.print("hello");
}

 	}





###### Output statements



* system.out.print("hello");
* system.out.println("hello");
* system.out.printf("%d is 1st number , %d is 2nd number",10,20);





###### Input statements





* scanner s=new Scanner(System.in)



* import java.util.*;
* int b=s.nextInt();
* float a=s.nextFloat();
* double c=s.nextDouble();
* char a=s.next()charAt(0);
* string s1=s.next();
* string s2=s.nextLine();

##### Data Types

=> Primitive Datatypes - 8 types

    *int(-12000 to +12000)
    *byte(-128 to +127)
    *char(character)
    *float(decimal Values)
    *double(long decimals)
    *boolean(True or False)
    *short(-12000 to +12000)
    *long(Exceeds or more than int and short)

=> Non-Primitive Datatypes 

    *Array
    *Class
    *String
    *Enumurate
    *Interface

=> Variables

    *It is a container which stores the values with the specified data type.

    ->Syntax:

        datatype variablename;
        int a=10; //Initialization and declaration
        int b=20;
        a=20; //changing values of variable

=> Keywords

    *It is a reserved words , So there are 32 keywords .
    *Eg: if,else,in,out,while,int,float,do,break,continue,class,etc.....

=> JDK

    *Java Development Kit.
    
=> JRE 

    *Java Runtime Environment.

=> JVM

    *Java Virtual Machine.(Platform dependent)

+------------------------------------------------------+
|                        JDK                           |
|  +-----------------------------------------------+   |
|  |                     JRE                       |   |
|  |                                               |   |
|  |   +-------------------------------+           |   |
|  |   |              JVM              |           |   |
|  |   |                               |           |   |
|  |   +-------------------------------+           |   |
|  |                                               |   |
|  |   +-------------------------------+           |   |
|  |   |            Libraries          |           |   |
|  |   +-------------------------------+           |   |
|  |                                               |   |
|  +-----------------------------------------------+   |
|                                                      |
|  +-----------------------------------------------+   |
|  |           Development Tools                   |   |
|  |  (javac, jar, javadoc, debugger, etc.)        |   |
|  +-----------------------------------------------+   |
|                                                      |
+------------------------------------------------------+  

=>TypeCasting

    *Converting element from one data type to another.

    *ASCII - American standard code for information interchange.

    Eg: For (0-9) => ASCII => 48 to 57
        For (a-z) => ASCII => 97 to 122
        For (A-Z) => ASCII => 65 to 90
        For (' ',space) => ASCII => 32  

    Eg for Typecasting:

        class Main (
            public static void main(string[] args){
                char a = 'r' ;
                System.out.prinln(int(a))
            }
        ) 

=>Conditional Statement

    * Arithmetic operator { +,-,*,/.%}
    * Relational operator { ==,=,===,<,>,!=,<=,>=,||}

    Eg1:

    import java.util.*;
    public class Main{
        public static void main(String[] args){
            Scanner s=new Scanner(System.in);
            int a =s.nextInt();
            int b =s.nextInt();
            if(a>b) System.out.println(a); //Relational operator used.
            else System.out.println(b);
        }
    }

    Eg2:

    import java.util.*;
    public class Main{
        public static void main(String[] args){
            Scanner s=new Scanner(System.in);
            int n =s.nextInt();
            if(n%2==0) System.out.println("Even"); //Arithmetic Operation Used.
            else System.out.println("Odd");
        }
    }

    Eg3:

    import java.util.*;
    public class Main{
        public static void main(String[] args){
            Scanner s=new Scanner(System.in);
            int n =s.nextInt();
            if(n>0) System.out.println("Positive"); //Arithmetic Operation Used.
            elseif(n<0) System.out.println("Negative"); //elseif Used.
            else System.out.println("Zero")
        }
    }

    Eg 4:

        import java.util.*;
        public class Main{
                public static void main(String[] args){
                Scanner s=new Scanner(System.in);
                int n =s.nextInt();
                if(n%3==0 || n%5==0) System.out.println("Yes"); //Arithmetic Operation Used.
                else System.out.println("No")
        }
    }

    Eg 5:

    import java.util.*;
    public class Main{
        public static void main(String[] args){
            Scanner s=new Scanner(System.in);
            int a =s.nextInt();
            int b =s.nextInt();
            int c =s.nextInt();
            if(a>b && a>c) System.out.println(a +"is greater"); //Relational operator used.
            else if(b>a && b>c) System.out.println(b + "is greater");
            else System.out.println(c+"is greater");
        }
    }

    Eg 6:

    import java.util.*;

    public class Main {
    public static void main(String[] args) {
        Scanner s = new Scanner(System.in);
        System.out.print("Subject1 Mark: ");
        int a = s.nextInt();
        System.out.print("Subject2 Mark: ");
        int b = s.nextInt();
        System.out.print("Subject3 Mark: ");
        int c = s.nextInt();
        System.out.print("Subject4 Mark: ");
        int d = s.nextInt();
        System.out.print("Subject5 Mark: ");
        int e = s.nextInt();
        int average = (a + b + c + d + e) / 5;
        if (average >= 90)
            System.out.println("Grade A");
        else if (average >= 70)
            System.out.println("Grade B");
        else if (average >= 50)
            System.out.println("Grade C");
        else
            System.out.println("Fail");
    }
}


1.Java program for calculating Area of the circle using constant value for pi =3.14 ?

import java.util.*;
    public class Main{
        public static void main(String[] args){
            Scanner s=new Scanner(System.in);
            float r =s.nextFloat();
            float pi = 3.14;
            float area = (pi*r)**2;
            System.out.println("The Area of Circle is %f"+area)
            
        }
    }

2.Calculate the simple intrest by getting principle amount, rate of intrest,and time from the user ?

    import java.util.*;
    public class Main{
        public static void main(String[] args){
            Scanner s=new Scanner(System.in);
            System.out.println("Enter the principle amount:");
            int pamount =s.nextInt();
            System.out.println("Enter the rate of Intrest:");
            int rIntrest = s.nextInt();
            System.out.println("Enter the time in years:");
            int time = s.nextInt();
            float si = (pamount*rIntrest*time)/100;
            System.out.println("Simple Intrest is : "+si);
            
        }
    }


    
3.check the number enter by the user if the number is divisible by 3  print fizz,if a number dividible by 5 print buzz,if the number is divisible by 3 and 5 print fizzbuzz otherwise print the number itself ?

import java.*;

public class Main {
    public static void main(String[] args) {

        Scanner s = new Scanner(System.in);

        System.out.print("Enter a number: ");
        int num = s.nextInt();

        if (num % 3 == 0 && num % 5 == 0) {
            System.out.println("FizzBuzz");
        } 
        else if (num % 3 == 0) {
            System.out.println("Fizz");
        } 
        else if (num % 5 == 0) {
            System.out.println("Buzz");
        } 
        else {
            System.out.println(num);
        }
    }
}

4.leap year?

    
    import java.util.*;
    public class Main{
        public static void main(String[] args){
            Scanner s=new Scanner(System.in);
            int n =s.nextInt();
            if(n%4==0) System.out.println("Leap Year"); //Arithmetic Operation Used.
            else System.out.println("Not a Leap Year");
        }
    }


5.vowel or consanat?

    import java.*;

    public class Main {
    public static void main(String[] args) {

        Scanner s = new Scanner(System.in);

        System.out.print("Enter a character: ");
        char ch = s.next().charAt(0);

        if (ch == 'a' || ch == 'e' || ch == 'i' || ch == 'o' || ch == 'u' ||
            ch == 'A' || ch == 'E' || ch == 'I' || ch == 'O' || ch == 'U') {
            System.out.println("Vowel");
        } 
        else {
            System.out.println("Consonant");
        }
    }
}
                                           
###### Operators

*Arithmetic Operator
*Relational Operator
*Logical Operator
*Bitwise Operator
*Assignment Operator
*Increament/Decreament Operator
*Conditional Operator

Eg:

Class Main {
    public static void main(string[] args){
        boolean b=false;
        if(!b){
            system.out.print("Yes")
        }
    }
}

Class Main{
    public static void main(string[] args)
    {
        system.out.println(5|4);
        system.out.println(5&4);

    }
}


| a | b | a \| b | a & b | a ^ b |
|---|---|-------|-------|-------|
| 0 | 0 |   0   |   0   |   0   |
| 0 | 1 |   1   |   0   |   1   |
| 1 | 0 |   1   |   0   |   1   |
| 1 | 1 |   1   |   1   |   0   |


Eg:

Class Main {
    public static void main(string[] args){
        system.out.println(2<<5);  //64
        system.out.println(8>>2);  //2
    }
}

Formulae:

Left shift : if a<<b then a*(2^b)
Right shift : if a>>b then a/(2^b)

Assignment Operator:

* +=
* -=
* *=
* /=
* == || ===

Increament Operator:

* a++ (post-increament)
* ++b (pre-increament)

=>Pre-Increament:

     * Value is increased first and then the value is assigned.

=>Post-Increament:

     * Value is assigned first then the increament occurs.

Eg:

++a  +  ++a = 15
++a  +  a++ = 14
a++  +  a++ = 13
a++  +  ++a = 14


=>Ternary Operator:

Class Main{
    public static void main(string[] args){
        int a=9, b=5;
        int c=(a<b)?a:b;
        System.out.print(c);
    }
}

=>Syntax:

    conditional operator=>(condition)?statement1:statement2;

=>Commands

    // => Single Line Command.
    /*.....*/ => Multi Line Command.

##### Electricity Example Program:

import java.util.*;

public class Main {
    public static void main(String[] args) {
        Scanner s = new Scanner(System.in);

        double units = s.nextDouble();
        double bill = 0;

        if (units <= 50) {
            bill = units * 1;
        } 
        else if (units <= 150) {
            bill = 50 * 1 + (units - 50) * 2;
        } 
        else if (units <= 250) {
            bill = 50 * 1 + 100 * 2 + (units - 150) * 3;
        } 
        else {
            bill = 50 * 1 + 100 * 2 + 100 * 3 + (units - 250) * 4;
        }

        if (bill > 150) {
            bill = bill + bill * 0.20;
        }

        System.out.println((int)bill);
    }
}


###### Triangle Based Example Program:

import java.util.*;

public class Main {
    public static void main(String[] args) {
      
      Scanner s=new Scanner(System.in);
      int a= s.nextInt();
      int b= s.nextInt();
      int c= s.nextInt();
      if(a+b+c==180 && a>0 && b>0 && c>0){
        System.out.println("VALID");
        if(a==b && b==c){
          System.out.println("EQUILALTERAL");
        }
        else if(a==b || b==c || c==a){
          System.out.println("ISOSCELES");
      }
      else{
        System.out.println("SCALENE");
      }
      }
      else{
        System.out.println("NOT VALID");
      }
      
    }
}

##### For Loop:
 Syntax:

 * for(initialization;condition;increament/decreament){
    .......
    .....
    ...
    .
 }


##### Factorial Example:
import java.util.*;

public class Main {
    public static void main(String[] args) {
        Scanner s = new Scanner(System.in);
        int a = s.nextInt();
        int count = 1;
        for(int i = 1; i <= a; i++){
           count=count*i;
        }
        System.out.println(count);
    }
}


###### Take an integer and print "YES" if the integer is prime and "NO" if it is not.

import java.util.*;

public class Main {
    public static void main(String[] args) {
        Scanner s = new Scanner(System.in);

        int n = s.nextInt();
        boolean Prime = true;

        for(int i = 2; i <= n/2; i++){
            if(n % i == 0){
                Prime = false;
                break;
            }
        }
        if(Prime){
            System.out.println("YES");
        } else {
            System.out.println("NO");
        }
    }
}

##### Take two numbers and find product of all numbers between them that satisfy following condition (inclusive range):
-> Numbers should be even
-> Second last digit of number is 4

import java.util.*;

public class Main {
    public static void main(String[] args) {
       Scanner s = new Scanner(System.in);
        int a = s.nextInt();
        int b = s.nextInt();
        int product=1;
        boolean br=false;
        for(int i=a;i<=b;i++){
          if(i%2==0 && (i/10)%10==4){
            product=product*i;
            br=true;
          }
        }
        if(br){
          System.out.println(product);
        }
        else{
           System.out.println(0);
        }
    }
}



##### Patterns:

* Nested For-loop

* While Loop:
      
        It is a Entry - check loop 

   Syntax:

   While(condition){
    .......
    ......
    ......

   }


Eg:

import java.util.*;
public class Main{
    public static void main(string[] args){
        int i=7;
        do(i<=10){
            System.out.println(i);
            i++;
        }while(i<=10);
    }
    
}


=> Mathod Calling

public class Operations{
public static void add(int a,int b,int c){
System.out.print(a+b+c);
}
public void add1(int a,int b){
System.out.print(a+b+c);
}
public static void main(String[] args){
    Operations obj=new Operations();
    obj.add(1,5,3);
}
}

public class Operations{
    public static int add(int a,int b){
        return a+b;
    }
    public static void main(String[] args){
        System.out.println(add(1,2)); //Static Mathod calling
        int a=add(5,6);
        System.out.print(a);
    }
}

=> Method Overloading:

    * It is Overloaded with same class name and mathod but different parameters.

    Eg: 
    import java.util.*;
    public class Operations{
    public static int add(int a,int b){
        return a+b;
    }
     public static double add(double a,double b){
        return a+b;
    }
     public static int add(int a,int b,int c){
        return a+b+c;
    }
    public static void main(String[] args){
        System.out.println(add(1,2));//Static Mathod calling
        System.out.println(add(1.2,2.3));
        System.out.println(add(1,2,3));
        
    }
}

###### Array

   *Array is the collection of elements of similar data types.


        
import java.util.*;

public class Main {
    public static void main(String[] args) {
      //int arr[]={1,2,3,4,5,7};
      Scanner s=new Scanner(System.in);
      int n=s.nextInt();
      int arr[]=new int[n];
      
      for(int i=0;i<n;i++){
        arr[i]=s.nextInt();
      }
      
      for(int i=0;i<n;i++){
        System.out.print(arr[i]+" ");
      }
      
      
    }
}

#### For Enhanced Loop:

for(int a:arr){
    System.out.print(a+" ");
}


#### Eg1:

import java.util.*;

public class Main {
    public static void main(String[] args) {
        Scanner s = new Scanner(System.in);
        int arr[] = new int[10];
        int sum = 0;
        for(int i = 0; i < 10; i++){
            arr[i] = s.nextInt();  
            sum =sum+arr[i];         
        }
        System.out.println(sum);    
    }
}

#### Eg2:

import java.util.*;

public class Main {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);

        int x = sc.nextInt();   // number to insert
        int n = sc.nextInt();   // size of array

        int[] arr = new int[n];

        for(int i = 0; i < n; i++){
            arr[i] = sc.nextInt();
        }

        int index;

        if(n % 2 == 0)
            index = n / 2;
        else
            index = (n - 1) / 2;

        for(int i = 0; i < index; i++){
            System.out.println(arr[i]);
        }

        System.out.println(x);

        for(int i = index; i < n; i++){
            System.out.println(arr[i]);
        }
    }
}


##### Eg3:

import java.util.*;

public class Main {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);

        int n = sc.nextInt();
        int[] arr = new int[n];

        for(int i = 0; i < n; i++){
            arr[i] = sc.nextInt();
        }

        for(int i = 0; i < n; i++){
            if(i == 2) continue;   // skip second index
            System.out.println(arr[i]);
        }
    }
}