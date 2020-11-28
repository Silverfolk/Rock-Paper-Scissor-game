# Rock-Paper-Scissor-game
package com.company;
import java.util.Scanner;
import java.util.Random;
public class cwd_rock_paper_scssor {
    public static void main(String[] args) {
        System.out.println("Instructions-->0 for Rock");
        System.out.println("1  for Scissor");
        System.out.println("2 for Paper");
        Scanner sc=new Scanner(System.in);
        System.out.println("Choose 0,1 or 2 ");

        int a =sc.nextInt();
        Random ran=new Random();
        int b=ran.nextInt(2);
        System.out.println("Value Entered by computer="+b);
        if(a==b){
            System.out.println("Match is tie");
        }
        else if (a==0 && b==1){
            System.out.println("Computer is Winner");
        }
        else if (a==1 && b==0){
            System.out.println("You Win");
        }
        else if(a==0 && b==2){
            System.out.println("YOu Win");
        }
        else if(a==2 && b==0){
            System.out.println("Computer wins");
        }
        else if(a==1 &&b==2){
            System.out.println("Computer Wins");
        }
        else if(a==2 && b==1){
            System.out.println("You win");
        }



    }
}

