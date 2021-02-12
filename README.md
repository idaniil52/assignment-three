# assignment-three
import java.util.Scanner;
public class hw3{

    public static void main(String[] args) {
        Scanner in =new Scanner(System.in);
        System.out.println("Give me a number.");
        int x=in.nextInt();
        if(x<0){
            System.out.println(x+" is a negative number");
        }
        else{
              System.out.println(x+" is a positve number");
        }
    }
}

import java.util.Scanner;
public class hw3pt2{
    public static void main(String[] args) {
        Scanner in =new Scanner(System.in);
        int x,y,z;
        System.out.println(" Give me 3 numbers");
        System.out.print("First Number ");
        x=in.nextInt();
        System.out.print("Second Number ");
        y=in.nextInt();
        System.out.print("Third Number ");
        z=in.nextInt();
        if( x >= y && x >= z){
          System.out.println(x+" is the largest Number");
        }
        else if (y >= x && y >= z){
            System.out.println(y+" is the largest Number");
        }
        else{
            System.out.println(z+" is the largest Number");
        }
    }
}

import java.util.Scanner;
public class hw3pt3{
    public static void main(String[] args) {
        Scanner in =new Scanner(System.in);
        int x;
        System.out.println(" Pick a nunber 1 to 7");
        x=in.nextInt();
        System.out.println(getDayName(x));
    }
    public static String getDayName(int x) {
        String dayName = "";
        switch (x) {
            case 1: dayName = "Monday"; break;
            case 2: dayName = "Tuesday"; break;
            case 3: dayName = "Wednesday"; break;
            case 4: dayName = "Thursday"; break;
            case 5: dayName = "Friday"; break;
            case 6: dayName = "Saturday"; break;
            case 7: dayName = "Sunday"; break;
            default:dayName = "Invalid day range";
        }

        return dayName;
    }
} 
