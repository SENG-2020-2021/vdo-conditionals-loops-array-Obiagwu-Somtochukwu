import java.util.Scanner;

public class microfinance {
    public static void main(String[] args) {
        Scanner input = new Scanner(System.in);
                int loan;
                int days, debt, amount, loanpaidback, bank, loanpaid, paidamount, amountperday;
                int i=1, x;
                System.out.println("Welcome to World micro finance bank " + "How may I help you");
				System.out.println("Please select an option");
				System.out.println("1.Sum of amount from the previous day");
				System.out.println("2.How many days you have paid based on loan and amount paid");
				System.out.println("3.calculate the amount the debtor paid for but the day was not captured in the above challenge because the amount was not up to the amount payable for day");
				System.out.println("4.Calculate the amount left for you to pay");
				System.out.println("5.Calculate the days you have not completely payed for");
				bank=input.nextInt();
				switch(bank){
					case 1:
                Scanner scanner = new Scanner(System.in);
System.out.println("Please enter amount loaned out to you in Naira(type quit to stop)");
int sum = 0; 
int count = 0;
while (scanner.hasNext()) {
    if (scanner.hasNextInt()) {
        count++;
        sum += scanner.nextInt();
    } else {
        String str = scanner.next();
        if (str.equalsIgnoreCase("quit")) {
            break;
        }
        System.out.printf("The amount '%s' is not an int (quit to stop).%n", str);
    }
}
System.out.printf("The sum of your %d amount loaned is %d.%n", count, sum);
				break;
		case 2:
			System.out.printf("Please enter the amount of loan taken in Naira");
			loan=input.nextInt();
			System.out.printf("How much have you paid in Naira");
			loanpaid=input.nextInt();
				days=(loan - loanpaid) / 365;
				System.out.printf("your loan should be paid off in: " +days);
				System.out.printf("days");
			break;
			case 3:
			System.out.printf("Please enter the amount of loan taken in Naira");
				loan=input.nextInt();
				System.out.printf("How much have you paid today in Naira");
				loanpaid=input.nextInt();
				loanpaidback=loan / 365;
				if(loanpaidback>loanpaid){
				System.out.printf("Your loan paid back for today is incomplete because it was below the intrest rate you ought to pay "+loanpaidback);
				System.out.println("Naira");
				System.out.printf("but you paid "+loanpaid);
				System.out.println("Naira");
			}else{
				System.out.printf("Your loan paid back has been captured and deducted from the loan you collected");
			
			}
			break;
			case 4:
			System.out.printf("Please enter the amount of loan taken in Naira");
			loan=input.nextInt();
			System.out.printf("How much have you paid in Naira");
			loanpaid=input.nextInt();
				debt=(loan - loanpaid);
			System.out.printf("Your remaining debt is: "+debt);
			System.out.printf("Naira");
			break;
			case 5:
			System.out.printf("Please enter the amount of loan taken in Naira");
			loan=input.nextInt();
			System.out.printf("How much have you paid in Naira");
			loanpaid=input.nextInt();
			loanpaidback= loan / 365;
			int incompleteamount= loanpaid % loanpaidback;
   System.out.printf("The incomplete amount not captured " + incompleteamount);	
   System.out.printf("Naira");
				}
				}
				}
        
