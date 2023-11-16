
import java.util.Random; 
import javax.swing.JOptionPane; 
void setup() 
{ 
 Random r = new Random(); 
 Random a = new Random(); 
 
 int d1 =0 ; 
 int d2 = 0; 
 int distance; 
 distance = 0 ; 
 int roll = 0; 
while (distance != 2) 
{ 
 
 JOptionPane.showMessageDialog(frame, "Roll Dice?"); 
 
 
 d1 = r.nextInt(6); 
 
 d2 = a.nextInt(6); 
 
 d1 = d1 + 1 ; // so it doesn't roll a 0 
 d2 = d2 + 1 ; 
 
 distance = d1 + d2 ; 
 
 System.out.println ("Roll "+ (roll) ); 
 System.out.println ("Dice 1 -> "+ (d1) ); 
 System.out.println ("Dice 2 -> "+ (d2) ); 
 System.out.println ("You rolled "+ (distance) ); 
 
 d1 = 0; 
 d2 = 0; 
 roll = roll + 1 ; 
} 
if (distance == 2) 
{ 
 System.out.println ("SNAKE EYES!" ); 
} 
}
