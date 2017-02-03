class ComputerQuizGame3
{
  public static void main(String[] args)
  {
    System.out.println("what is your name ");
    String name = In.getString();
    System.out.print("Ok " + name + "," );
    System.out.println(" this is a quiz game to test your knowledge on computer programming.");
    System.out.println("there are 2 levels of difficulty in this quiz");
    System.out.println("IF yoo are able to complete all levels you are a programming master!!!!");
    System.out.println("would you like to play the game?");
   String answer = In.getString();
     if (answer.equalsIgnoreCase("yes"));
   {
     System.out.println("Alright letsss goo ");
     int level1question1(int[] points);
     // creating an array to store points
     //int points[] = new int[30];
    //   int sum = 0;
    // for(int count = 0; count<=points.length; count++)
   //  { 
   //    sum+=points[count];
   //  }
   }
   if(answer.equalsIgnoreCase("no"));
   {
     System.out.println("please come back if you changed your mind");
   }
  }
  
  // a new method
   public static void level1question1(int[] points)
  {
    System.out.println("how many data types are there in java ");
  int ans1 = In.getInt();
  if (ans1== 8)
  {
    System.out.println("you are right!");
    System.out.println("you just got 10 points");
    //storing points in an arry
//  points[0] = 10;
  }
  else if(ans1 != 8)
  {
    System.out.println("sorry your answer is wrong"+ "the right answer is 8");
  }
   
 }
}
