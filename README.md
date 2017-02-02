class ComputerQuizGame
{
  public static void main(String[] args)
  {
    System.out.println("this is a quiz game to test your knowledge on computer programming.");
    System.out.println("there are 5 levels of difficulty in this quiz");
    System.out.println("IF yoo are able to complete all levels you are a programming master!!!!");
    System.out.println("Would you like to play ??? yes or no");
    String answer = In.getString();
     if (answer.equalsIgnoreCase("yes"));
   {
     System.out.println("Alright letsss goo ");
   }
   else 
   {
     ending(answer);
   }
 
  }
  //trying to end game if user says no
  public static String ending( String answer);
  {
     if(answer.equalsIgnoreCase("no"))
   {
     System.out.println("Please come again if you change your mind!!!");
   }
  }
  public static void int level1question1()
  {
    System.out.println("how many data types are there in java ");
  int ans1 = In.getInt();
  if (ans1= 8)
  {
    System.out.println("you are right!");
  }
   
 }

 public static void int level1question2()
  {
    System.out.println("what would the equation (13/4) give in java");
  int ans2 = In.getInt();
  if (ans2 == 3)
  {
    System.out.println("you are right!");
  }
}
  public static void int level1question3()
  {
    System.out.println("how many reserved words are there in java ");
  int ans3 = In.getInt();
  if (ans3 == 53)
  {
    System.out.println("you are right!");
  }
  }
    public static void int level1question4()
  {
    System.out.println("What would the answer of the equation (19%8 ) in java ");
  int ans4 = In.getInt();
  if (ans4 == 3)
  {
    System.out.println("you are right!");
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
  }
}
  
