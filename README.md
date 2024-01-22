 <h1 align="center"><i>First year even semester neopat solution's of Java</i></h1>

 <h2 align="center"> Day 1 - Java Fundamentals: </h2>
 
 <h1 align="center"> Class Exercises Lab (5 Qn's) </h1>
 
 ### 1.Ramu and Somu are going on a picnic...,
```java
import java.util.Scanner;
public class Main {
    public static void main(String[] args){
        Scanner sc=new Scanner(System.in);
        int m = sc.nextInt();
        int n = sc.nextInt();
        int m1 = sc.nextInt();
        int n1 = sc.nextInt();
        int x = sc.nextInt();
        int y = sc.nextInt();
        int a = (m+(m+m1)) - x;
        int b = (n+(n+n1)) - y;
        System.out.print(a+" "+b);
    }
}
```

</br>

### 2.Seetha was shocked after seeing her electricity bill for May month...,
```java
// You are using Java
import java.util.Scanner;
class Main {
    public static void main(String[] args){
        Scanner sc=new Scanner(System.in);
        int a=sc.nextInt();
        double b=0;
        if(a<=100){
            b=0;
        }
        else if(a<=200){
            b=(a-100)*1.5;
        }
        else if(a<=500){
            b= 100*2 + (a-200)*3; 
        }
        else{
            b = 100*3.5 + 300*4.6 + (a-500)*6.6;
        }
        System.out.print(b);
    }
}
```

</br>

### 3.After explaining the concept of prime numbers, Seetha explained about prime factors to her students..,
```java
// You are using Java
import java.util.*;
import java.lang.Math;
public class Main {
    public static void main(String[] args){
        Scanner sc=new Scanner(System.in);
        int a = sc.nextInt();
        while(a%2==0){
            System.out.print(2+" ");
            a = a/2;
        }
        for(int i=3; i<Math.sqrt(a); i = i+2){
            while(a%i == 0){
                System.out.print(i+" ");
                a = a/i;
            }
        }
        if(a>2){
            System.out.print(a+" ");
        }
    }
}
```
</br>

### 4.Seetha, a maths teacher explained Matrix addition, subtraction and multiplication in her class..,
```java
// You are using Java
import java.util.*;
public class Main {
    public static void main(String[] args){ 
        
        Scanner sc=new Scanner(System.in);
        int n = sc.nextInt();
        int c[][] = new int[n][n];
        int arr1[][] = new int[n][n];
        for(int i=0; i<n; i++){
            for(int j=0; j<n; j++){
                arr1[i][j] = sc.nextInt();
            }
        } 
        
        int arr2[][] = new int[n][n];
        for(int i=0; i<n; i++){
            for(int j=0; j<n; j++){
                arr2[i][j] = sc.nextInt();
            }
        }
        
        for(int i=0; i<n; i++){
            for(int j=0; j<n; j++){
                c[i][j] = 0;
                for(int k=0; k<n; k++){
                    c[i][j] += arr1[i][k] * arr2[k][j];
                }
                System.out.print(c[i][j]+" ");
            }
            System.out.println();
        }
        
    }
}
```
</br>

### 5.An ice-cream vendor sells his ice-creams in cone(radius r and height h) and ball(radius r) shaped containers..,
- leave the header and footer part as it is.
```java
// You are using Java
class Icecream {
    
public static void Quantity (int r, int h){
    System.out.printf("%.2f",0.33 * 3.14 * (r * r * h));
}
    
public static void Quantity (int r){
    System.out.printf("%.2f",(1.33) * 3.14 * (r * r *r));
} 
}
```

</br>

<h1 align="center">Practice at home lab (10 qn's) </h1> 

### 1. Write a Multiply function for two integers and use overload the function..,
```java
// You are using Java
public int Multiply(int a, int b){
    return a*b;
}
public int Multiply(int c, int d, int e){
    return c*d*e;
}
```

</br>

### 2. Ajju has a Carom board and TT table (Table Tennis)..,
```java

```

</br>

### 3. Write a program to move all the special characters to the end of the string..,
```java

```

</br>

### 4. Overriding is another concept that every application developer should know..,
```java

```

</br>

### 5. Create a multilevel inheritance based on the image given below..,
```java

```

</br>

### 6. Write a Java program to create a class named "Birds" that contains a constructor that prints "Birds : "..,
```java

```

</br>

### 7. Write a program to illustrate dynamic polymorphism, create two classes Vehicle and Motorbike..,
```java

```

</br>

### 8. Function Overloading. Write a program to implement function overloading..,
```java

```

</br>

### 9. You are in an Online shopping portal.It has two types of members, Basic and Premium..,
```java

```

</br>

### 10. Write a Java program to demonstrate method overriding and dynamic method dispatch..,
```java

```

</br>
