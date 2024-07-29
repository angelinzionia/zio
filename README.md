
import java.util.*;
class ArrayOfObject
{
public static void main(String[] args)
{
    //create array of employee object
    Employee[]obj = new Employee[3];
    //create & initialize actual employee objects using constructor
    obj[0]=new Employee("Robert",1996,"64C-WallsStreet");
    obj[1]=new Employee("Sam",2000,"68D-WallsStreet");
    obj[2]=new Employee("John",1999,"26B-WallsStreet");
    //display the employee object data
    System.out.println("Name\t"+"Year of Joining\t"+"Address");
    obj[0].showData();
    obj[1].showData();
    obj[2].showData();
}   
}

