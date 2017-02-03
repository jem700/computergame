class ComputerQuizGame2
{
  public static void main(String[] args)
  {
    System.out.println("this is a quiz game to test your knowledge on computer programming.");
    System.out.println("there are 5 levels of difficulty in this quiz");
    System.out.println("IF yoo are able to complete all levels you are a programming master!!!!");
    System.out.println("You would like to play the game right??" + " true of false");
   String answer = In.getString();
     if (answer.equalsIgnoreCase("yes"));
   {
     System.out.println("Alright letsss goo ");
     // creating an array to store points
     int points[] = new int[30];
       int sum = 0;
     for(int count = 0; count<=points.length; count++)
     { 
       sum+=points[count];
     }
int a = level1question1(int[] points);
int b = level1question2(int[] points);
int c = level1question3(int[] points);
int d = level1question4(int[] points);
int e = level1question4(int[] points);
     //after all questions in level 1
       System.out.println("you just finished a level would you like to continue unto the next level?");
  String answer2 = In.getString();
  if( answer2.equalsIgnoreCase(("yes")))
  {
System.out.println("moving on to level 2 !!");
  }
   
   else if(answer2.equalsIgnoreCase(("no")))
   {
     System.out.println("Ok. please come back if you change your mind");
   }
 
  }
  }
 
  public static void level1question1(int[] points)
  {
    System.out.println("how many data types are there in java ");
  int ans1 = In.getInt();
  if (ans1== 8)
  {
    System.out.println("you are right!");
    System.out.println("you just got 10 points");
    //soring points in an arry
  points[0] = 10;
  }
  else if(ans1 != 8)
  {
    System.out.println("sorry your answer is wrong"+ "the right answer is 8");
  }
   
 }

 public void level1question2(int[] points)
  {
    System.out.println("what would the equation (13/4) give in java");
  int ans2 = In.getInt();
  if (ans2 == 3)
  {
    System.out.println("you are right!");
    points[1] = 10;
  }
  else if (ans2 !=3)
  {
    System.out.println("sorry your answer is wrong"+ "the right answer is 3");
  }
}
  public void  level1question3(int[] points)
  {
    System.out.println("how many reserved words are there in java ");
  int ans3 = In.getInt();
  if (ans3 == 53)
  {
    System.out.println("you are right!");
    points[2] = 10;
  }
  else if( ans3 != 53)
  {
    System.out.println("sorry your answer is wrong"+ "the right answer is 53");
  }
  }
    public void level1question4(int[] points)
  {
    System.out.println("What would the answer of the equation (19%8 ) in java ");
  int ans4 = In.getInt();
  if (ans4 == 3)
  {
    System.out.println("you are right!");
    points[3] = 10;
  }
  else if(ans4 != 3)
  {
    System.out.println("sorry your answer is wrong" + "the right answer is 3");
  }
 
   //   public static void level1question5()
 // {
  //  System.out.println("What would the answer of the equation (5/0) in java ");
 // int ans5 = In.getInt();
 // if (ans5= 8)
 // {
 //   System.out.println("you are right!");
  //}
  
  System.out.println("you just finished a level would you like to continue unto the next level?");
  String answer2 = In.getString();
  if( answer2.equalsIgnoreCase(("yes")));
  {
System.out.println("moving on to level 2 !!");
  }

     }
}
  
