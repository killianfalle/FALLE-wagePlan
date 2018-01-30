
import javax.swing.JOptionPane;

public class WagePlans {
    public static void main(String[] args) {
        
        Double Sales, WageA, WageB;
        
        Sales = Double.parseDouble(JOptionPane.showInputDialog("Enter the Expected Weekly Sales"));
        //Calculate the Wages for each plan
        
        WageA = (50.00* 40) + (0.05 * Sales);
        
		WageB = Sales * 0.40;

	if (WageA > WageB)
		JOptionPane.showMessageDialog (null, "Wage for Plan A: " + WageA +
											"\n Wage for Plan B : " + WageB +
											"\n Best paying plan: Wage A " );
	else
		
		JOptionPane.showMessageDialog (null, "Wage for Plan A: " + WageA +
											"\n Wage for Plan B : " + WageB +
											"\n Best paying plan: Wage B " );
					
        
    }
}
