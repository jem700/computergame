class ComputerQuizGame2
{
  public static void main(String[] args)
  {
    System.out.println("this is a quiz game to test your knowledge on computer programming.");
    System.out.println("there are 5 levels of difficulty in this quiz");
    System.out.println("IF yoo are able to complete all levels you are a programming master!!!!");
    System.out.println("You would like to play the game right??" + " true of false");
    boolean answer = In.getBoolean();
     if (answer == true);
   {
     System.out.println("Alright letsss goo ");
     // creating an array to store points
     int points[] = new int[30]
       int sum = 0;
     for(int count = 0; count<=points.length; count++)
     { 
       sum+=points[count];
     }
     level1question1();
     level1question2();
     level1question3();
     level1question4();
     level1question5();
   }
   else 
   {
     System.out.println("Ok. please come back if you change your mind");
   }
 
  }
 
  public static void int level1question1(int[] points)
  {
    System.out.println("how many data types are there in java ");
  int ans1 = In.getInt();
  if (ans1= 8)
  {
    System.out.println("you are right!");
    System.out.println("you just got 10 points");
    //storing points in an arry
  points[0] = 10;
  }
  else 
  {
    System.out.println("sorry your answer is wrong");
  }
   
 }

 public static void int level1question2()
  {
    System.out.println("what would the equation (13/4) give in java");
  int ans2 = In.getInt();
  if (ans2 == 3)
  {
    System.out.println("you are right!");
    points[1] = 10;
  }
  else 
  {
    System.out.println("sorry your answer is wrong");
  }
}
  public static void int level1question3()
  {
    System.out.println("how many reserved words are there in java ");
  int ans3 = In.getInt();
  if (ans3 == 53)
  {
    System.out.println("you are right!");
    points[2] = 10;
  }
  else 
  {
    System.out.println("sorry your answer is wrong");
  }
  }
    public static void int level1question4()
  {
    System.out.println("What would the answer of the equation (19%8 ) in java ");
  int ans4 = In.getInt();
  if (ans4 == 3)
  {
    System.out.println("you are right!");
    points[3] = 10;
  }
  else 
  {
    System.out.println("sorry your answer is wrong");
  }
  }
      public static void int level1question5()
  {
  //  System.out.println("What would the answer of the equation (5/0) in java ");
 // int ans5 = In.getInt();
 // if (ans5= 8)
 // {
 //   System.out.println("you are right!");
  }
  
  System.out.println("you just finished a level would you like to continue unto the next level?");
  String answer2 = In.getString();
  if( answer2.equalsIgnoreCase(("yes"));
  {
System.out.println("moving on to level 2 !!");
points[5] = 10;
 } 
     else 
  {
    System.out.println("sorry your answer is wrong");
  }
 public static void String level2question1();
  {
    System.out.println("what shape would you use if youwant to ask a question on a flow chart? rectangle or diamond");
  String ans6 = In.getString();
  if (ans6.equalsIgnoreCase(("diamond"));
  {
    System.out.println("you are right!");
    points[6] = 10;
  }
      else 
  {
    System.out.println("sorry your answer is wrong");
  }
  }
   public static void String level2question2();
  {
    System.out.println("what shape would you use if youwant to ask a question on a flow chart? rectangle or diamond");
  String ans6 = In.getString();
  if (ans6.equalsIgnoreCase(("diamond"));
  {
    System.out.println("you are right!");
    points[7] = 10;
  }
      else 
  {
    System.out.println("sorry your answer is wrong");
  }
  }
