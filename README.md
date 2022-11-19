package javamaster;
import java.util.Scanner;
public class programm1 {
    public static void main(String[] args) {
        int ans=0;
        Scanner in=new Scanner(System.in);
        while(true) {
            System.out.println("Enter two numbers");
            int num1 = in.nextInt();
            int num2 = in.nextInt();
            System.out.println("enter the operator");
            char op=in.next().charAt(0);
            if(op=='+' || op=='-' || op=='*' || op=='/' || op=='%' ){
                if(op=='+'){
                    ans=num1+num2;
                }
                if(op=='-'){
                    ans=num1-num2;
                }
                if (op == '*') {
                    ans=num1*num2;

                }
                if(op=='/'){
                    ans=num1+num2;
                }
                if(op=='%'){
                    ans=num1+num2;
                }

            }
            System.out.println("answer:"+ans);
        }

    }

}
