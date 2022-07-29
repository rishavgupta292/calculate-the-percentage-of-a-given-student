# calculate-the-percentage-of-a-given-student

package com.student;

import java.util.Scanner;

public class Calculate_the_percentage {
    public static void main(String[] args){

        Scanner scan = new Scanner(System.in);
        System.out.println("Enter your Physics marks : ");
        int Physics = scan.nextInt();
        System.out.println("Enter your Chemistry marks : ");
        int Chemistry = scan.nextInt();
        System.out.println("Enter your Mathematics marks : ");
        int Mathematics = scan.nextInt();
        System.out.println("Enter your Computer Science marks : ");
        int Computer = scan.nextInt();

        float percentage = ((Physics + Chemistry + Mathematics + Computer)/500.0f)*100;

        System.out.println("Percentage : ");
        System.out.println(percentage);

    }
}
