# Just-Messing-Around

import java.util.*;



class Tester{
Scanner kb = new Scanner(System.in);

  boolean tester;
  System.out.println("If you can respond, type \"yes\"");
  String maybe = kb.nextLine();
  if (maybe.equals("yes")){
    tester = true;
  }
  
  if (tester){
    System.out.println("HOORAY");
  }
}
