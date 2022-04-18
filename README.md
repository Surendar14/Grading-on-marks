# Grading-on-marks

## Aim:
  To write a C# program to display the comment based on Grade obtained.

## Algorithm:

## Program:

#Developed by: Surendar S
#reg.no:212220230051

  using System;
  using System.Collections.Generic;
  using System.Linq;
  using System.Text; 
  public   class exercise19
     {
         static void Main(string[] args)
      {
      string notes;
      char grd;
      Console.Write("Input the grade :");
      grd = Convert.ToChar(Console.ReadLine().ToUpper());
      switch(grd)
      {
      case 'E':
          notes= " Excellent";
          break;
      case 'V':
         notes= " Very Good";
          break;
      case 'G':
          notes= " Good ";
          break;
      case 'A':
          notes= " Average";
          break;
      case 'F':
          notes= " Fails";
          break;
      default :
          notes= "Invalid Grade Found.";
          break;
      }
      Console.Write("You have chosen  : {0}\n", notes);
  } 
  }


## Output:
![Screenshot (52)](https://user-images.githubusercontent.com/75235759/163829029-4e4342cd-599f-42e6-a17f-f8cdeffb1e8b.png)


## Result:
C# program to display the comment based on Grade obtained was executed successfully.
