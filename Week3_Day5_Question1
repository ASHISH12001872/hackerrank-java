import java.io.*;
import java.util.*;
import java.text.*;
import java.math.*;
import java.util.regex.*;

public class Solution {

    public static void main(String[] args) {
        /* Enter your code here. Read input from STDIN. Print output to STDOUT. Your class should be named Solution. */
        
        Scanner st=new Scanner(System.in);
        float present_amount=st.nextFloat();
        //System.out.println(p_amount);
        int s=st.nextInt();
        DecimalFormat d=new  DecimalFormat("0.00");
        d.setRoundingMode(RoundingMode.FLOOR);
        switch(s)
        {
                case 1:
                   float withdraw_amount=st.nextFloat();
                  if (withdraw_amount<=present_amount)
                  {
                     float total=present_amount-withdraw_amount;
                      total+=0.01;
                     System.out.println((d.format(total)));   
                  }
                else
                    System.out.println("Error"); 
                break;
                
            case 2:
                float d_amount=st.nextFloat();
                float total=present_amount+d_amount;
                
                System.out.println((d.format(total)));
                break;
                
            case 3:
                System.out.println(present_amount);
                
            default:
               System.out.println("Error");
}
    }
}
