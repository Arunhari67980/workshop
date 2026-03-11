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