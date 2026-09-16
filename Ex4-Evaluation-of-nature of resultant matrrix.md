# Ex4 You are given a Java program that performs matrix addition. If Matrix A has all odd numbers and Matrix B has all even numbers of the same dimension, what will be the nature (even/odd/mixed) of the resulting matrix?
## DATE:27/07/2026
### Developed by: JAI HARISH R
### RegisterNumber: 212224040124
## AIM:
To write a java function to evaluate weather the given Matrix A has all odd numbers and Matrix B has all even numbers of the same dimension and find the nature of resultant matrrix.

## Algorithm
1.Read the number of rows (r) and columns (c) from the user.

2.Read all elements of Matrix A (r × c) and store them.

3.Read all elements of Matrix B (r × c) and store them.

4.For each position (i, j), compute C[i][j] = A[i][j] + B[i][j].

5.Display all elements of Matrix C in matrix format. 

## Program:
```java
// Program to ind the nature of resultant matrrix.
// Developed by: JAI HARISH R
// RegisterNumber: 212224040124
import java.util.*;
public class prog{
    public static void main(String [] args){
        Scanner sc=new Scanner(System.in);
        int r=sc.nextInt();
        int c=sc.nextInt();
        
        int [][]A=new int[r][c];
        int [][]B=new int[r][c];
        int [][]C=new int[r][c];
        
        for(int i=0;i<r;i++){
            for(int j=0;j<c;j++){
                A[i][j]=sc.nextInt();
            }
        }
          for(int i=0;i<r;i++){
            for(int j=0;j<c;j++){
                B[i][j]=sc.nextInt();
            }
        }
          for(int i=0;i<r;i++){
            for(int j=0;j<c;j++){
                C[i][j]=A[i][j]+B[i][j];
            }
        }
          for(int i=0;i<r;i++){
            for(int j=0;j<c;j++){
                System.out.print(C[i][j]+" ");
            }
            System.out.println("");
        }      
        
    }
}

```

## Output:

<img width="502" height="753" alt="image" src="https://github.com/user-attachments/assets/ff8a86ef-4c23-4218-af4f-e048b92dc7e1" />


## Result:
Thus, the java program to evaluate weather the given Matrix A has all odd numbers and Matrix B has all even numbers of the same dimension and find the nature of resultant matrrix is implemented successfully.
