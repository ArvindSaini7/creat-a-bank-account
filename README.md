package bank;
import java.util.*;
public class creat_a_bank_account {
	public static void main(String[]args) {

		
		
	}}
		class main{
			password b=new password();
			public void get_main() {
	Scanner sc=new Scanner(System.in);
	int a;
	System.out.println(" Main Menu");
	System.out.println();
	System.out.println("1.Create a Account ");
	System.out.println("2.Deposit Amount ");
	System.out.println("3.withdraw Amount");
	System.out.println("4. Balance");
	System.out.println("5. All Account Holder List");
	System.out.println("6. Close An Account ");
	System.out.println("7. Modify An Account");
	System.out.println("8. Exit");
	System.out.println();
	System.out.print("Select Your Option  :");
	
	switch(a=sc.nextInt()){
	case 1:
	    b.Create_a_Account();
	    b.create_password();
	    b.get_main();
	    break;
	  case 2:
	    System.out.println("Tuesday");
	    break;
	  case 3:
	    System.out.println("Wednesday");
	    break;
	  case 4:
	    System.out.println("Thursday");
	    break;
	  case 5:
	    System.out.println("Friday");
	    break;
	  case 6:
	    System.out.println("Saturday");
	    break;
	  case 7:
	    System.out.println("Sunday");
	    break;
	}
	
		
	}
	
	
}




class Account extends main{
	Scanner sc=new Scanner(System.in);
	public void Create_a_Account(){
		System.out.print("enter your name:");
		String name=sc.nextLine();
		System.out.print("enter your father name :");
		String fname=sc.nextLine();
		
	}
}

class password extends Account{
	Scanner sc=new Scanner(System.in);
	public void create_password(){
		System.out.println("create a password");
		System.out.println("type is  - ");
		System.out.print("@arvind321");
		System.out.println("Enter your password   - ");
		int password=sc.nextInt();
		
	}
}
