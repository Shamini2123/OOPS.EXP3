# OOPS.EXP3

import java.util.Scanner;



public class uniquechar {

	    public static void main(String[] args) {

	    Scanner scanner = new Scanner(System.in);

	       

	        System.out.print("Enter a word : ");

	        String input = scanner.nextLine();



	     

	        boolean isPerfect = true;



	        for (int i = 0; i < input.length(); i++) {

	            char ch = input.charAt(i);



	            for (int j = i + 1; j < input.length(); j++) {

	                if (ch == input.charAt(j)) {

	                    isPerfect = false;

	                    break;

	                }

	            }



	        }



	   

	        if (isPerfect) {

	            System.out.println("PERFECT");

	        } else {

	            System.out.println("NOT PERFECT");

	        }



	        scanner.close();

	    }

	}
