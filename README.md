# database
//THIS IS JAVA...
/*
 * To change this license header, choose License Headers in Project Properties.
 * To change this template file, choose Tools | Templates
 * and open the template in the editor.
 */
package rank;
import java.util.Scanner;
/**
 *
 * @author Kamili Nascar
 */
public class Rank {

   /**
    * @param args the command line arguments
    */
   public static void main(String[] args) {
      Scanner input=new Scanner(System.in);
      System.out.println("enter marks of following subjects");
      double subj = 0;
      double avg;
      for(int i=0;i<10;i++){
         
         System.out.printf("subject%d =",i+1,+subj);
         subj=input.nextDouble();
         ++subj;
       
      }
     avg=subj/10;
     System.out.printf("The average ="+subj);
     
   
   //System.out.printf("average rank ="+rank.);
      }
   public static int rank(int avg){
     switch(avg)
     {
        case 1:
             System.out.println("A");
             break;
             case 2:
                System.out.println("A");
                break;
                case 3:
                   System.out.println("A");
                   break;
                default:System.out.println("below");
     } 
     return avg;
   }
}
