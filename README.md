package bank;
import java.util.*;
public class creat_a_bank_account {
	public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
       

        while (true) {
            System.out.println("1. Create Account");
            System.out.println("2. Deposit");
            System.out.println("3. Withdraw");
            System.out.println("4. Check Balance");
            System.out.println("5. Exit");
            System.out.print("Choose an option: ");
            int choice = scanner.nextInt();
            scanner.nextLine(); // Consume newline
}
	}
	class bankingApp {
	    private String accountNumber;
	    private String accountHolder;
	    private double balance;

	    public void BankAccount(String accountNumber, String accountHolder) {
	        this.accountNumber = accountNumber;
	        this.accountHolder = accountHolder;
	        this.balance = 0.0;
	    }

	    public void deposit(double amount) {
	        if (amount > 0) {
	            balance += amount;
	            System.out.println("Deposited: " + amount);
	        } else {
	            System.out.println("Deposit amount must be positive.");
	        }
	    }

	    public void withdraw(double amount) {
	        if (amount > 0 && amount <= balance) {
	            balance -= amount;
	            System.out.println("Withdrew: " + amount);
	        } else {
	            System.out.println("Insufficient funds or invalid amount.");
	        }
	    }

}
