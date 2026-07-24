import javax.swing.JOptionPane;

public class randomguess 
{
    public static void main(String[] args) // must be lowercase "main" and "String"
    {
        // First popup
        JOptionPane.showMessageDialog(null, "guess a number from 1 to 10");

        // Generate random number 1-10
        int randomNumber = 1 + (int)(Math.random() * 10);

        // Second popup with the number
        JOptionPane.showMessageDialog(null, "The number is " + randomNumber);

        System.exit(0);
    }
}
