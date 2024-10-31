import java.util.Scanner;

public class CalculateInvestmentValue {

	public static void main(String[] args) {
		
		// Scanner object
		Scanner input = new Scanner(System.in);
		
		// Ask user for investment amount 
		System.out.println("Enter an Investment amount: ");
		double investmentAmount = input.nextDouble();
		
		// Ask user for annual interest rate 
		System.out.println("Enter the annual interest rate in percentage, ex. 4.25: ");
		double annualInterestRate = input.nextDouble();
		
		// Ask user the number of years for investment 
		System.out.println("Enter the number of years: ");
		double numberOfYears = input.nextDouble();
		
		// Calculate monthly interest rate: Convert into decimal by dividing by 100 (12 months * 100)
		double monthlyInterestRate = annualInterestRate / 1200;
				
		// Calculate future investment value: Use Math.pow(a,b)
		double futureInvestmentValue = investmentAmount * Math.pow((1 + monthlyInterestRate), (numberOfYears * 12));
		
		// Display results: Cast the value to int and use (int)(x * 100 + 0.5) / 100.0 to round up to two decimal places
		System.out.println("The accumulated value is: " + (int)(futureInvestmentValue * 100 + 0.5) / 100.0);

		// Close scanner
		input.close();
	
	}

}
