import java.io.*;
import java.util.*;
import java.text.*;
import java.math.*;
import java.util.regex.*;

public class Solution {

    public static void main(String[] args) {
        Scanner obj=new Scanner(System.in);
        int n=obj.nextInt();
        int[] marks=new int[n];
        int total=0;
        if(n>7){
            System.out.println("Invalid");
        }
        else{
        for(int i=0;i<n;i++){
            marks[i]=obj.nextInt();
            total +=marks[i];
        }
        float per=total/(float)n;
        if(per>=90.0){
            System.out.println("A+");
        }
        else if(per>=70.0&&per<=89.0){
            System.out.println("A");
        }
        else if(per>=60.0&&per<=69.0){
            System.out.println("B");
        }
        else if(per>=50.0&&per<=59.0){
            System.out.println("C");
        }
        else if(per<40.0){
            System.out.println("D");
        }
    }
}
}
