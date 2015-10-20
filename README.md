# Homework
//Created by:  Vicky Wang
//Created on: Oct 20, 2015
//Created for: ICS3U
//Assignment Name: Unit 2 Lesson 5 Practice 3
//This program asks the user for address

import java.util.Scanner;
public class Address {

    public static void main(String[] args) {
    //set variables
    String StreetNumber,StreetName,City,Province,Country,PostalCode;
    Scanner user_input=new Scanner(System.in);
    System.out.println("Street Number?");
    StreetNumber=user_input.nextLine();
    System.out.println("Street name?");
    StreetName=user_input.nextLine();
    System.out.println("City?");
    City=user_input.nextLine();
    System.out.println("Province?");
    Province=user_input.nextLine();
    System.out.println("Country?");
    Country=user_input.nextLine();
    System.out.println("Postal code?");
    PostalCode=user_input.nextLine();
    //print user inputs e,g. 711 White Street, Oakville, Ontario, Canada. L1S 3J4
    System.out.println(StreetNumber+" "+StreetName+", "+City+", "+Province+", "+Country+". "+PostalCode);
 
    }
    
}
